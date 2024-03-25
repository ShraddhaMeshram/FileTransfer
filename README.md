##FileTransfer Project
This project aims to provide a seamless and efficient file transfer solution utilizing various technologies including NodeJS, ExpressJS, Web Sockets, WebRTC, and NextJS. The project focuses on delivering a user-friendly interface and high-speed file transfer capabilities.

###Features
NextJS Interface: Developed a user-friendly interface using NextJS, ensuring a seamless and intuitive experience for users.

Signaling Server: Implemented a signaling server with NodeJS & web sockets (Socket.io) to enable real-time communication between users.

WebRTC for Peer-to-Peer Connections: Leveraged WebRTC technology and UDP to establish fast and secure peer-to-peer connections for efficient file transfer.

Non-blocking Functionality: Enhanced user experience by implementing non-blocking functionality through the use of worker threads.

Impressive Transfer Speeds: Achieved impressive file transfer speeds, averaging around 1 minute & 30 seconds for transferring a 1GB file between end-users.

###Setup
To set up the project locally, follow these steps:

Clone the repository: git clone https://github.com/your_username/FileTransfer.git
Navigate to the project directory: cd FileTransfer
Install dependencies: npm install
Start the server: npm start
Access the application at http://localhost:3000
Usage
Once the application is running, users can access the interface through the provided URL.
Users can initiate file transfer by selecting the file they want to send and specifying the recipient.
The signaling server facilitates real-time communication between users, establishing peer-to-peer connections using WebRTC.
Users can monitor the progress of file transfer and receive notifications upon completion.
