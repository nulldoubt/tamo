# TaMo Aufgabenplanner

## What even is this?
It's a simple todo app I wrote for a school assignment.

## What tech stack did you use?
Mainly jQuery and Fomantic UI

## What are tasks?
Tasks are the central entity of our data model. Each task has an index, a title, a creation data, and an optional "done" date. Newly added tasks are FIFO and first appear in the pending section; when marked as done the task will then be moved into the archive.

Archived tasks are neither editable nor delete-able; unarchive them to enable these actions.

## Did you use AI for this?
Yes.

## How do I run it?
Open your shell, clone the repo, cd into "tamo-main" and let your favorite web server serve the it.

## I don't have a webserver, what should I do?
Go to https://qaws.dev, install qaws using the one-line installer command, go back to your shell and type "qaws --serve ./tamo-main" and enjoy the HTML locally on port 80.

## Is this actually usable?
Not really. The data isn't stored and lives entirely in the current browser session, one refresh is all it takes to empty your task list. It's just a school project to "practice" vanilla JS, please don't use it.

## License?
No. It's free; free as in "freedom", use it for whatever you want and never contact me, I do not take responsibility for whatever you do with this repository.