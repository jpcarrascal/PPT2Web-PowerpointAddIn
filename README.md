# PPT2Web

Service and tools for exporting your Powerpoint presentation as a Web page. I built this tool for sharing decks outside my organization for UX research purposes.
It is currently a work in progress, a lot of improvements are still ongoing.

PPT2Web is composed of 3 components:
- A Powerpoint add-in (this repository) exports to a web-deck and manages the URL (copying to clipboard, opening in browser).
- A Web API for uploading and serving the web-decks (can be found [here](https://github.com/jpcarrascal/PPT2Web-BackEnd)).
- A Web front-end for viewing the web-decks ([here](https://github.com/jpcarrascal/PPT2Web-FrontEnd)). It provides simple navigation through the deck as well as displaying the slide comments.