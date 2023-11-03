(more details to be included later)
## Idea
- Self-therapy website 
---
## Details
- Create a self-therapy website that helps you think.
- The website will NOT ask you specifics about your problem, rather it will simply pose generic questions to the user, in hopes of invoking the user's own thought process. If the question displayed on the screen is not helping, there will be a button to move on to the next / previous question.
- The website will also be capable of creating a to-do list if required, that will help the user make their own list of steps THEY want to take to help themselves.
- The website will have an interface with buttons to:
	- Start / Stop a self-therapy session
	- Play some relaxing music (rain / ocean / forest, etc)
- When the user decides to take a break / end their self-therapy session, the website will show them the to-do list and notes they created, which is saved to their account.
---
## Implementation
- User account and authentication from a database. (username and password for simplicity)
- User to-do list and notes linked to their account and saved to the database.
- To-do list and notes implementation using React. Must be hidden unless the user chooses to create / edit the list.
- In-built music player will play predefined `.mp3` files seamlessly play music on the website / browser itself without redirecting to a new tab.
- Minimalist dark-themed GUI to reduce clutter and help the user think. Soft colour animations will be playing in the background. Add a soft colour trail to the mouse cursor if necessary.
- If the user decides to delete their account, all their data will be wiped from the database, and cannot be recovered. 
- To make a copy of user data, a `.txt` file can be produced from the database if the user requests it. User data deletion thus becomes lossless.