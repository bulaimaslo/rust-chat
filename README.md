# Real-Time Chat Microservice

This project is a real-time chat microservice implemented in Rust, leveraging the asynchronous programming capabilities and WebSocket technology. The microservice allows clients to establish persistent, bidirectional communication channels for real-time messaging.

## Project Tasks

- [x] Task 1: Project Setup and WebSocket Library Selection
    - [x] Set up a new Rust project
    - [x] Choose a WebSocket library for Rust (e.g., "websocket" or "tungstenite")
    - [x] Add the chosen library as a dependency in your project

- [ ] Task 2: Server-Side Implementation
    - [ ] Create a WebSocket server that listens for incoming connections
    - [ ] Implement the WebSocket handshake process
    - [ ] Establish and manage the lifecycle of connected clients
    - [ ] Handle disconnections and cleanup

- [ ] Task 3: Message Handling
    - [ ] Define the message structure (e.g., JSON format)
    - [ ] Implement message serialization and deserialization
    - [ ] Handle sending and receiving messages
    - [ ] Broadcast messages to all connected clients

- [ ] Task 4: User Authentication
    - [ ] Choose an authentication mechanism (e.g., OAuth or custom authentication)
    - [ ] Implement user registration and login functionality
    - [ ] Secure WebSocket connections with authenticated users
    - [ ] Handle unauthorized access and enforce authentication rules

- [ ] Task 5: Room Management
    - [ ] Design a room data structure to hold connected clients and messages
    - [ ] Implement room creation and deletion
    - [ ] Handle client subscriptions and unsubscriptions to rooms
    - [ ] Ensure messages are only broadcasted to participants in the same room

- [ ] Task 6: Message Persistence
    - [ ] Choose a persistence mechanism (e.g., PostgreSQL or Redis)
    - [ ] Design a schema or data model to store chat messages
    - [ ] Implement storing and retrieving messages from the chosen database
    - [ ] Integrate message persistence into the message handling logic

- [ ] Task 7: Additional Features
    - [ ] Choose additional features to implement based on project requirements
    - [ ] Examples: private messaging, message editing, message reactions, file sharing, bots, etc.
    - [ ] Plan and implement each selected feature as separate tasks

- [ ] Task 8: Client-Side Implementation
    - [ ] Develop a web-based chat interface using HTML, CSS, and JavaScript
    - [ ] Establish a WebSocket connection with the server
    - [ ] Implement sending and receiving messages in the client application
    - [ ] Handle UI updates based on received messages

## Getting Started

To get started with the development or deployment of this microservice, follow these steps:

1. Clone the repository:
```
git clone https://github.com/bulaimaslo/rust-chat.git
```
2. Install Rust if not already installed (refer to official Rust documentation).
3. Install project dependencies:
```
cargo update
```
4. Build and run the microservice:
```
cargo run
```

## License

This project is licensed under the [MIT License](LICENSE).




