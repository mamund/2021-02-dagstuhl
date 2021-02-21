# AMEE : Autonomous Maze Environment Explorer

_Demo apps for "Autonomous Agents on the Web" Dagstuhl, 2021_

## Maze+XML 
The Maze+XML media type is designed to render/represent 2-dimensional mazes of any size. See http://amundsen.com/media-types/maze/ for more on the format. Also see http://amundsen.com/examples/misc/maze-client.html for some background. The Maze+XML format was featured in the book "RESTful Web APIs" (2013) by Richardson & Amundsen.

## Server
There are currently two servers in the folder named `servers`. 

 * Use `node app.js` to launch the RDF version of the server.
 * Use `node app-xml.js` to launch the XML version of the server.
 
## The Game
There is an interactive game client in the folder named `the-game`. 

## The Bots
There are a number of clients in the the folder named `the-bot`. 

 * `node the-slow-bot.js <starting-url>` runs the maze while pausing one second between moves
 * `node the-bot.js <startingurl>` runs the maze without any pauses
 * `node the-signifier-bot.js <starting-url>` runs the maze and looks for the "green" links that indicate a shortcut rhough the maze (if/when they exist).
 

