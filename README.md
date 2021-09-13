# Sanvello Viewer
This is a program that allows you to visualize Sanvello data on your browser in a way that makes it easier to see patterns, view mood logs, and more.

## Setup
- Sign into [Sanvello](https://web.sanvello.com) on a web browser.
- On that same browser, go to [https://app.sanvello.com/app/activity/history?startTime=0](https://app.sanvello.com/app/activity/history?startTime=0), take its contents, and put them into a file in this directory called `data.json`.
- Run `python3 -m http.server` (or some equivalent) to start a web server in this directory.
- Navigate to whatever URL the web server is hosting at ([localhost:8000](https://localhost:8000) for the given command), and the viewer will show up!