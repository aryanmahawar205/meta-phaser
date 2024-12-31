# Meta-Phaser

**Meta-Phaser** is an open-source 2D metaverse application built using the Phaser game engine and the MERN stack. This project allows users to create their own virtual spaces where participants can interact as avatars, move around the environment, and communicate via audio and video chats. It's designed to blend the worlds of gaming, social interaction, and distributed systems into a seamless virtual experience.

## Features

- **Virtual Space Creation**: Users can design and set up unique virtual spaces.
- **Interactive Avatars**: Real-time avatar movements with character animations.
- **Audio and Video Communication**: Integrated WebRTC for seamless communication within the virtual space.
- **Real-Time Updates**: Powered by WebSockets for low-latency interactions and updates.
- **Scalable Architecture**: Built with distributed systems principles to handle multiple spaces and users efficiently.
- **Tech Stack**: MERN (MongoDB, Express, React, Node.js) and Phaser for the front-end gaming environment.

## Getting Started

To run Meta-Phaser locally, follow these steps:

### Prerequisites

- Node.js and npm installed
- MongoDB instance running

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/aryanmahawar205/meta-phaser.git
   cd meta-phaser
   ```
2. Install dependencies for both the client and server:
   ```bash
   cd client
   npm install
   cd ../server
   npm install
   ```
3. Configure environment variables:
   - Create a `.env` file in the `server` directory and add your MongoDB URI, WebRTC configurations, and other necessary variables.

### Running the Application

1. Start the server:
   ```bash
   cd server
   npm start
   ```
2. Start the client:
   ```bash
   cd client
   npm start
   ```
3. Open your browser and visit `http://localhost:3000` to explore the virtual metaverse!

## Contribution Guidelines

We welcome contributions from the community! If you'd like to contribute:

1. Fork the repository and create a new branch for your feature or bug fix.
2. Make your changes and ensure the code adheres to project guidelines.
3. Submit a pull request with a detailed description of your changes.

## License

This project is licensed under the [GNU GPLv3 License](https://www.gnu.org/licenses/gpl-3.0.en.html). See the `LICENSE` file for more details.

## Acknowledgments

Special thanks to the open-source community and the developers of Phaser, MERN stack, and WebRTC for providing the tools and inspiration to build this project.
