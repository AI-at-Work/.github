# AI-at-Work

AI-at-Work is an organization dedicated to simplifying the development of AI agents through a comprehensive chat management system. Our suite of services provides developers with the tools they need to focus on implementing AI agents without getting bogged down in infrastructure management.

## Our Vision

We aim to streamline the process of AI agent development by handling the complexities of chat sessions, summaries, file management, and historical data retrieval. By providing these core functionalities, we enable developers to channel their efforts into creating sophisticated AI agents.

## Key Components

Our system consists of several interconnected services:

1. **Chat-Backend**: The core service that manages chat sessions, handles websocket connections with the client-side UI, and communicates with AI agents via gRPC.

2. **Chat-AI**: An AI agent service that processes chat inputs and generates responses.

3. **Chat-UI**: The client-side user interface for interacting with the chat system.

4. **Sync-Backend**: A service that ensures data consistency between Redis (for caching) and PostgreSQL (for persistent storage).

## System Architecture

Our system utilizes a microservices architecture to ensure scalability and maintainability:

- Redis is used for caching and real-time data access.
- PostgreSQL serves as the persistent data store.
- Websockets facilitate real-time communication between the Chat-UI and Chat-Backend.
- gRPC is employed for efficient communication between the Chat-Backend and Chat-AI services.

## Features

- Automated chat session management
- Chat summaries generation
- File handling capabilities
- Retrieval of specific numbers of chats from previous sessions
- Real-time communication between client and server
- Scalable and maintainable microservices architecture

## Getting Started

To get started with AI-at-Work's chat system, please refer to the individual repositories for each service:

- [Chat-Backend](https://github.com/AI-at-Work/Chat-Backend)
- [Chat-AI](https://github.com/AI-at-Work/Chat-AI-Service)
- [Chat-UI](https://github.com/AI-at-Work/Chat-UI)
- [Sync-Backend](https://github.com/AI-at-Work/Sync-Backend)

Each repository contains specific instructions for setup and deployment.

## Contributing

We welcome contributions from the community! If you're interested in improving our services or adding new features, please check out our individual service repositories for contribution guidelines.

## Support

If you encounter any issues or have questions, please file an issue in the appropriate service repository or contact our support team.

Thank you for your interest in AI-at-Work. Together, we're making AI agent development more accessible and efficient!
