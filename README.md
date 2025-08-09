# AI-Driven TRPG Browser Game

This is a browser-based AI-driven tabletop RPG game that uses [Ollama](https://ollama.com/) for local LLM inference.

## Setup Instructions

Follow the steps below to get the game running locally on your machine.

---

### 1. Install Ollama

- Download and install Ollama from [https://ollama.com/](https://ollama.com/)
- Follow their installation instructions for your platform (Windows or Linux).

---

### 2. Download the game files

Clone this repository or download the HTML file and assets to a folder on your machine:

```bash
git clone https://github.com/FlyinEye/ai-trpg-ollama.git
cd ai-trpg-ollama
3. Run a local web server
To serve the HTML and allow it to connect to Ollama, start a simple HTTP server in the project directory.

On Windows:

Open Command Prompt or PowerShell and run:

powershell
Copy
Edit
python -m http.server 8080
On Linux/macOS:

Open a terminal and run:

bash
Copy
Edit
python3 -m http.server 8080
4. Open the game in your browser
Navigate to: http://localhost:8080/

Notes
Ensure Ollama is running and accessible on your machine when you launch the game.

You may need to adjust firewall or network settings to allow local connections if you run into issues.

This project assumes you have Python installed. If not, install Python from https://python.org.

Feel free to open issues or contribute!

