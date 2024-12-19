Here's the entire README in one code block:

```markdown
# Chat Application using Tkinter and Sockets

This project implements a simple chat application using Python's `tkinter` for the GUI and `socket` for network communication. It creates a server and two client instances where users can communicate with each other in real-time.

## Features

- Real-time messaging between clients
- Simple Tkinter-based GUI for the chat application
- Ability to set and change usernames
- Server that manages client connections
- Available for two clients in a chat room

## Requirements

To run the chat application, you'll need Python 3.x installed on your system.

You can install the necessary dependencies using `pip`:

```bash
pip install tkinter
```

## How It Works

1. **Server:**  
   The server listens on a specified IP and port, waiting for client connections. Once two clients connect, the server allows communication between them by forwarding messages from one client to the other.

2. **Client:**  
   Each client runs its own instance of a Tkinter-based GUI where users can enter messages and receive real-time updates. Clients connect to the server using the server's IP and port.

3. **GUI:**  
   - A text area displays the message history.
   - An input box allows users to type messages.
   - A "Send" button sends the typed message to the server.
   - A settings button lets users change their username.

## How to Run

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/yourusername/chat-application.git
   cd chat-application
   ```

2. Run the script to start the server and the two clients:

   ```bash
   python chat_app.py
   ```

   - The server will automatically start and bind to a local IP and available port.
   - Two client windows will open, allowing communication between them.

3. The first client will prompt for a username, and the second client will connect automatically.

## Customization

- You can modify the number of clients by adjusting the `Server` class and adding more client instances.
- The GUI can be customized further by adding themes, font options, and additional features like message timestamps.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```
