# CLI-TaskManager

A simple command-line tool written in Go to manage daily tasks. This tool allows you to add, list, mark as done, and remove tasks, all from your terminal. Tasks are saved to a JSON file, so your list persists between sessions.

Features:
1. Add Task: Add a new task with the -add flag.
2. List Tasks: List all tasks with the -list flag.
3. Mark Task as Done: Mark a task as completed with the -done flag followed by the task ID.
4. Remove Task: Remove a task with the -remove flag followed by the task ID.
5. Save and Load: Tasks are automatically saved to and loaded from a tasks.json file.
