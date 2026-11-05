# What Is This?
AMWAP stands for **A**s **M**any **W**ins **A**s **P**ossible. It is a means of showing progress and triumph in a way that encourages, especially when progressing through involved and challenging creative projects. 

Capture the least possible completed tasks "wins" and celebrate them in order to make sure that you are both accurately capturing progress as well as creating a clear value proposition for the progress that you are making.

```dataview
LIST CleanText
FROM "02_Active_Projects"
FLATTEN file.tasks AS t
WHERE t.completed AND contains(t.text, "#win")
FLATTEN replace(t.text, "#win", "") AS CleanText
```
# How It Operates

* You type an achievement next to the `- [ ] #win` bullet inside any active project note.
* When you check the box to complete that task, the Dataview plugin detects the `#win` tag and the checked status.
* The `AMWAP Master Log` automatically pulls that specific line and displays it under a heading bearing the project's name.
* This creates a centralized, read-only dashboard of all your project wins without requiring you to copy and paste text between files.
* If you uncheck or delete the win in the original project file, it instantly disappears from the master log.
