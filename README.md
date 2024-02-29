# hamstr

## Idea
Collaborative document editing. A local first application where you can edit many different kinds of files (think Obsidian, LibreOffice). Additionally you can privately store your files in the cloud and collaborate with other users without revealing your data to any middlemen.

## Platforms
Linux, macOS and Windows

## Features
- Store and edit documents locally.
- Login to the app using your nostr identity (nsec and nostr connect).
- Optionally sync your files to a cloud server. Encrypted by default.
- Make your cloud stored files public and copyable.
- Give view-only access to other nostr users without making the file viewable to the file server.
- Give edit access to other nostr users without making the file viewable to the file server.
- Collaboratively edit documents without having to rely on the file server, just via events transmited by relays.
- Install plugins to the app to edit different types of documents that are not supported by default.

## Plan
Intially make it work with plain notes (.txt files) with a simple text editing box. Then allow editing markdown documents (.md files) with a markdown editor, and slowly add support for these documents:
- Word processing (.odt/.docx)
- Spreadsheets (.ods/.xlsx)
- Presentations (.odp/.pptx)
- Graphics (.odg/.vsdx)
- Design (.penpot/.zip with svg and json)

## Tech Stack
Probably Svelte with Tauri for the desktop app. Other things will be decided as I continue building this project.

## Footnote
This is a near impossible project for someone with my skillset and patience leve. I will make it happen even if I have to smoke meth to focus.
