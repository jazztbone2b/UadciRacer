## Udaci Racer Racing Sim

This is a racing simulator built using Javascript. Read the instructions below to set the project up and run it on your computer.

## Getting Started

In order to build this game, we need to run two things: the game engine API and the front end.

### Start the Server

The game engine has been compiled down to a binary so that you can run it on any system. Because of this, you cannot edit the API in any way, it is just a black box that we interact with via the API endpoints.

To run the server, locate your operating system and run the associated command in your terminal at the root of the project.

| Your OS               | Command to start the API                                  |
| --------------------- | --------------------------------------------------------- |
| Mac                   | `ORIGIN_ALLOWED=http://localhost:3000 ./bin/server-osx`   |
| Windows               | `ORIGIN_ALLOWED=http://localhost:3000 ./bin/server.exe`   |
| Linux (Ubuntu, etc..) | `ORIGIN_ALLOWED=http://localhost:3000 ./bin/server-linux` |

If you are on an older OS and the above command doesn't run for you - or if you know that you are running a 32bit system - add `-32` to the end of the file name. For reference, here are the same commands but for a 32-bit system.

| 32 Bit Systems Only!  | Command to start the API                                     |
| --------------------- | ------------------------------------------------------------ |
| Mac                   | `ORIGIN_ALLOWED=http://localhost:3000 ./bin/server-osx-32`   |
| Windows               | `ORIGIN_ALLOWED=http://localhost:3000 ./bin/server-32.exe`   |
| Linux (Ubuntu, etc..) | `ORIGIN_ALLOWED=http://localhost:3000 ./bin/server-linux-32` |

Note that this process will use your terminal tab, so you will have to open a new tab and navigate back to the project root to start the front end.

### Start the Frontend

First, run your preference of `npm install && npm start` or `yarn && yarn start` at the root of this project. Then you should be able to access http://localhost:3000.
