# Simple WebRTC Implementation using Socket.io as Signaling Protocol

This is a simple implementation of WebRTC using Socket.io as the signaling protocol. This implementation allows users to establish a peer-to-peer connection between their web browsers, enabling video and audio communication in real-time.

## How it works

WebRTC is a technology that allows for real-time communication between web browsers without the need for plugins or external software. In order to establish a connection between two browsers, a signaling protocol is needed to exchange information such as session descriptions, ICE candidates, and other metadata. Socket.io provides a simple way to implement this signaling protocol.

This implementation consists of a server and a client. The server uses Node.js and Socket.io to handle the signaling process between clients. The client uses JavaScript and WebRTC to establish the peer-to-peer connection.

## Installation

To use this implementation, you will need Node.js installed on your machine.

1. Clone this repository: `git clone https://github.com/zkrami/webrtc-example.git`
2. Install dependencies: `npm install`
3. Start the server: `npm start`
4. Open two browser windows and navigate to `http://localhost:3000` in each window.

## Usage

Once you have two browser windows open and connected to the server, the call will automatically initiate between the connected peers.

You should be able to see and hear each other in the connected windows. To end the call, simply close the browser window.

## Credits

This implementation was based on the following resources:

- [WebRTC samples](https://webrtc.github.io/samples/)
- [Socket.io documentation](https://socket.io/docs/)
- [WebRTC codelab](https://codelabs.developers.google.com/codelabs/webrtc-web/#0)

## License

This project is licensed under the MIT License. See the LICENSE file for details.
