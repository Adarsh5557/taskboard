# TaskBoard

just a simple project haaaahhaaa

> No AI. No blockchain. No microservices. No 47 dependencies. Just one HTML file and a lot of unfinished tasks.

A simple taskboard that runs entirely in your browser. One HTML file, no install, no backend, no dependencies.

## Features

- Add, edit, and delete tasks
- Each task has a title, notes, date, time, category, and priority
- Categories: Schedule, Study, Research, Personal
- Attach a photo from your camera or gallery (resized and compressed automatically)
- Tabs to filter: Today, Upcoming, All, each category, and Done
- Quick stats at the top: due today, overdue, and done
- Overdue tasks get a red date tag, high and medium priority tasks get a marker
- Light and dark mode follow your system setting
- Works on phone and desktop
- Export all your tasks to a JSON file

## How to use

1. Clone or download the repo:
   ```
   git clone https://github.com/Adarsh5557/taskboard.git
   ```
2. Open `index.html` in any modern browser (just double-click it).
3. Tap the **+** button to add a task. Fill in whatever you need, only the title is required.
4. Tap the circle on the left of a task to mark it done. Tap it again to undo.
5. Use the pencil icon to edit a task and the **x** to delete it.
6. Tap a photo on a task to view it full screen. Tap anywhere to close it.
7. Hit **Export** at the top to download your tasks as `tasks.json`.

The Today tab shows everything not done that is due today or earlier, so overdue tasks stay visible until you finish them. Tasks with no date only show up under All and their category tab.

On the first run you'll see a few sample tasks. Delete them whenever.

## Where is my data stored

Tasks are saved in your browser's localStorage, so they stay on your device and nothing is sent anywhere. A few things to know:

- Data is tied to the browser and device you use. Another browser or phone will have its own empty board.
- Clearing site data for the page will wipe your tasks, so export now and then.
- Photos take up space. If storage fills up, you'll get a warning, so delete some photos or export.
- Export is one way for now. There is no import yet.

## FAQ (nobody asked, but still)

**Is this the next Notion?**
No. Notion has a team. This has a localStorage.

**Does it sync across my devices?**
No. Your laptop and your phone don't talk to each other. They are not friends.

**Will it make me productive?**
It will make you feel productive for about 10 seconds every time you tick a task. That's the whole product.

**Why is there no import button?**
Because I got tired. Export works though, so you can at least leave with your data.

**Why only one HTML file?**
Because I like my projects like I like my deadlines: with no structure and at the last minute.

## Files

- `index.html`: the whole app (HTML, CSS, and JS)
- `README.md`: this file
