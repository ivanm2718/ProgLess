✅ Task 1: Save tasks to localStorage
Ensure tasks are preserved even after refreshing or closing the browser.
Save the task list to localStorage whenever a task is added, deleted, updated, or marked complete/incomplete.
When the app loads, check if there are tasks in localStorage and load them instead of the default ones.


✅ Task 2: Sort tasks alphabetically (A–Z and Z–A)
Add a button that lets the user toggle between ascending and descending sort order.
Add a new variable to store the sort order ("asc" or "desc").
In the filteredTasks computed property, sort the tasks alphabetically based on the current sort order.


✅ Task 3: Add a due date for each task
Allow users to specify a deadline for every task.
When adding a new task, include a date input for the due date.
Display the due date next to each task in the task list.
The due date should also be editable when updating a task.


✅ Task 4: Show task progress
Display a summary at the top: for example, “2 out of 5 tasks completed”.
Count how many tasks are marked as completed.
Show a progress message or bar at the top of the app.