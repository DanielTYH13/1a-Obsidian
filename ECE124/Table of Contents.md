
Due today or overdue:
```dataviewjs
// 1. Setup
const tag = "#ECE124";
const exclude = "ECE124 Note";
const today = dv.date("today");

// 2. Fetch and Filter
const pages = dv.pages(tag)
		.where(p => 
		    p.file.name != exclude && 
		    p["sr-due"] && 
		    p["sr-due"] <= today // Everything due today or in the past
		)
    .sort(p => p["sr-due"], "asc");

// 3. Render
let counter = 1;
dv.list(pages.map(p => `${counter++}. ${p.file.link}`));
```
___
 *Sorted by order or sr-due*:
```dataviewjs
// 1. Define your tag and the note to exclude
const tag = "#ECE124";
const exclude = "ECE124 Note";

// 2. Fetch, filter, and sort the data
const pages = dv.pages(tag)
    .where(p => p.file.name != exclude)
    .sort(p => p["sr-due"], "asc");

// 3. Create the numbered list
let counter = 1;
dv.list(pages.map(p => `${counter++}. ${p.file.link}`));
```