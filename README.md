📌 PepBoard

Welcome to PepBoard – A real-time collaborative whiteboard powered by Node.js, Express, and Socket.io. 🖊️✨

🚀 Features

🎨 Real-time Drawing: Draw and see updates instantly across multiple users.

🎭 Tool Selection: Change drawing tools and sync them with all users.

🎨 Color & Size Control: Customize the brush size and color in real-time.

⏪ Undo & Redo: Easily revert changes or redo an action.

📡 WebSocket Communication: Lightning-fast updates with Socket.io.

🏗 Simple & Lightweight: Built with minimal dependencies for seamless performance.

📦 Installation

Clone the repository:

git clone https://github.com/Pep-DEV101/PepBoard.git
cd PepBoard

Open your browser and navigate to:

http://localhost:3000

🛠️ Tech Stack

Backend: Node.js, Express

Real-time Communication: Socket.io

Frontend: HTML, CSS, JavaScript (Served from public/ directory)

📂 Project Structure

PepBoard/
├── public/             # Static files (HTML, CSS, JS)
├── express.js          # Main server file
├── package.json        # Project metadata and dependencies
├── package-lock.json   # Dependency lock file
└── README.md           # Project documentation

🖥️ How It Works

User connects – A client joins the whiteboard.

Drawing begins – Mouse movements are broadcast to other clients via WebSockets.

Sync tools & colors – When a user changes tools, color, or brush size, updates are sent across all clients.

Undo/Redo functionality – Actions can be undone or redone to enhance user control.

🤝 Contributing

Want to improve PepBoard? Feel free to fork and submit a PR! 🚀

Fork the repo

Create a feature branch

Commit your changes

Push and open a PR



