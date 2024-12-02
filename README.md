# Dev Chat

**Dev Chat** is a real-time chat application designed for developers to collaborate, share ideas, and communicate efficiently. Built with simplicity, speed, and developer-friendly features in mind, Dev Chat is the perfect tool for teams and communities.

---

## Features

- **Real-Time Messaging**: Instant communication with no delays.
- **Code Snippets**: Share and format code directly in the chat.
- **Markdown Support**: Use Markdown to format your messages.
- **Channels and Groups**: Organize conversations into public or private channels.
- **File Sharing**: Upload and share files with your team.
- **Dark Mode**: A sleek, developer-friendly dark theme.
- **Cross-Platform**: Available on web, desktop, and mobile.

---

## Installation

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn
- MongoDB (for backend database)

### Steps

1. Clone the repository:

bash
git clone https://github.com/yourusername/dev-chat.git
cd dev-chat

2. Install dependencies:

bash
npm run build

3. Set up environment variables:
   Create a `.env` file in the root directory and add the following:
    PORT=3000
    MONGODB_URI=
    JWT_SECRET=
    NODE_ENV=development
    CLOUDINARY_CLOUD_NAME=
    CLOUDINARY_API_KEY=
    CLOUDINARY_API_SECRET=

4. Start the development server:

bash
npm run dev

5. Open your browser and navigate to:
   http://localhost:3000

---

## Usage

1. **Sign Up**: Create an account or log in with your existing credentials.
2. **Join Channels**: Browse or create channels to start chatting.
3. **Share Code**: Use the code snippet feature to share formatted code.
4. **Collaborate**: Communicate with your team in real-time.

---

## Tech Stack

- **Frontend**: React, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JSON Web Tokens (JWT)
- **Real-Time Communication**: Socket.IO

---

## Contributing

We welcome contributions! To contribute:

1. Fork the repository.
2. Create a new branch:
bash
git checkout -b feature/your-feature-name

unknown
Copy Code

3. Commit your changes:
bash
git commit -m "Add your message here"
