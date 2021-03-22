# fs_part0

Word Diagram for SPA workflow.

Creating a diagram workflow for a single page application.

User Submits a newnote -> The command fetches the form element from the page and registers it to an event handler

The event handler creates a new note and adds it to the notes list ---> The data is sent with an HTTP POST request

The data type is JSON and is sent as a JSON string.