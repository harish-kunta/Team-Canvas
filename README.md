# Team Canvas

// link for website

<p align="center"><img width="650px" height="360px" src="https://i.ibb.co/0CYwLwN/Screenshot-2021-09-17-at-8-03-32-AM.png" alt="riddle-logo" /></p>
## Collaborative Whiteboard Application

The Team Canvas project is a collaborative whiteboard application that allows users to create a shared whiteboard and collaborate in real-time. Users can create a new room and invite others by sharing a unique ID. The whiteboard contents can be saved to the local computer by any participant in the room.

## Installation

To install the application, follow these steps:

1. Clone the repository: `git clone https://github.com/your-repo.git`
2. Navigate to the project directory: `cd Team-Canvas`
3. Install the dependencies: `npm install`

## Usage

To start the application, run the following commands:

1. Build the project: `npm run build`
2. Start the server: `npm run start`

## About

The Team Canvas application utilizes the NKN (New Kind of Network) protocol for communication between clients. When a client accesses the app, a public address is allocated to them. The person who creates the room (main user) shares their public address with others who want to join. When a new person joins, they ping the main user to get the latest state of the canvas and the public addresses of all the other members in the room. The whiteboard updates made by each user are broadcasted to everyone in the room.

## Technologies Used

The Team Canvas application is built using the following technologies:

1. [NKN](https://nkn.org/) - A decentralized network protocol for secure and efficient data transmission.
2. [Fabric.js](http://fabricjs.com/) - A powerful and convenient layer of abstraction built over the canvas API for creating interactive graphics.
3. [React](https://reactjs.org/) - A JavaScript library for building user interfaces.

For more information about the project, you can refer to the [official blog post](https://nkn.org/community/blog/riddle-a-collaborative-whiteboard-web-app-powered-by-nkn/).
<br/>


# installation

npm install

npm run build

npm run start

# About

Using the App, you can create a new room and invite others by using the Share Id provided to you and start collaborating in the shared white board.
The whiteboard contents can be saved to local computer by anyone in the room.

[Read more here](https://nkn.org/community/blog/riddle-a-collaborative-whiteboard-web-app-powered-by-nkn/)

# Communication protocol

1. When a client accesses the app, a public address is allocated to him.
2. The person who creates the room (Main user) shares his public address with people who want to join.
3. When a new person joins, they ping the main user to get the latest state of the canvas and the public addresses of all the other members in the room.
4. The whiteboard updates made by each user is broadcasted to everyone so that everyone updates their board with the new changes.
5. When the main user leaves, another user is made the main user and if somebody wants to join, he has to use the public address of the new main user.

# Technologies used

1. [NKN](https://nkn.org/)
2. [Fabric](http://fabricjs.com/)
3. [React](https://reactjs.org/)

# The whiteboard

The whiteboard is made using [Fabric.js](http://fabricjs.com/), a very powerful and convenient layer of abstraction built over the canvas API.
