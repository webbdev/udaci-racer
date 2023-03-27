## UdaciRacer Simulation Game

## Getting Started

In order to build this game, we need to run two things: the game engine API and the front end.

### How to run

1. git clone https://github.com/webbdev/udaci-racer.git
2. cd udaci-racer
3. Start the server
4. In another terminal tab, start the frontend
5. Navigate to http://localhost:3000

#### Start the Server

The game engine has been compiled down to a binary so that you can run it on any system. Because of this, you cannot edit the API in any way, it is just a black box that we interact with via the API endpoints.

To run the server, locate your operating system and run the associated command in your terminal at the root of the project.

| Your OS               | Command to start the API                                  |
| --------------------- | --------------------------------------------------------- |
| Mac                   | `ORIGIN_ALLOWED=http://localhost:3000 ./bin/server-darwin-amd64`   |
| Windows               | `ORIGIN_ALLOWED=http://localhost:3000 ./bin/server-windows-amd64.exe`   |
| Linux (Ubuntu, etc..) | `ORIGIN_ALLOWED=http://localhost:3000 ./bin/server-linux-amd64` |

Note that this process will use your terminal tab, so you will have to open a new tab and navigate back to the project root to start the front end.

#### WINDOWS USERS -- Setting Environment Variables
If you are using a windows machine:
1. `cd` into the root of the project containing data.json 
2. Run the following command to add the environment variable:
```set DATA_FILE=./data.json```

If you still run into issues running the API server on your machine, you can run this project in the Udacity classroom.


#### Start the Frontend

First, run your preference of `npm install && npm start` or `yarn && yarn start` at the root of this project. Then you should be able to access http://localhost:3000.
