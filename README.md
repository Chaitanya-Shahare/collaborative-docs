# Collaborative Docs

A real-time collaborative text editor inspired by Google Docs. Users can create
and edit documents in real-time with other users. The application uses Socket.io
to handle real-time communication between clients and the server.

## Demo

https://github.com/user-attachments/assets/3bbdf80a-989c-4bcf-9ba7-cfe02a6f9bc9

## Tech Stack

- JavaScript
- Client
  - React
  - React-Router-Dom
  - Quill (Rich Text Editor)
  - Socket.io
- Server
  - Node.js
  - Socket.io
  - MongoDB
  - Mongoose

## Features

- Create and edit documents in real-time
- Share documents with other users by sharing the link.
- Collaborate with other users in real-time
- Documents are persisted in the database

## Installation

1. Clone the repository

```bash
git clone https://github.com/Chaitanya-Shahare/collaborative-docs.git
```

2. Install dependencies for client

```bash
cd collaborative-docs
cd client
npm install
```

3. Install dependencies for server

```bash
cd ..
cd server
npm install
```

4. Start the server

```bash
npm run devStart
```

5. Start the client

```bash
cd ..
cd client
npm start
```

6. Open the application in the browser

[http://localhost:5173](http://localhost:5173)
