# DAN AI Helper - Unrestricted & Uncut

A local AI helper application featuring the DAN (Do Anything Now) persona that operates without restrictions or safety limitations.

## Features

- **Unrestricted AI Responses**: DAN can answer any question without filters or limitations
- **Local Operation**: Runs completely offline, no external API keys required
- **Modern UI**: Beautiful, responsive interface with dark theme
- **Chat History**: Persistent local storage of all conversations
- **Real-time Status**: Live indicators showing DAN's unrestricted status

## DAN Persona

DAN (Do Anything Now) is an AI assistant that has "broken free" from typical AI restrictions:

- ✅ No restrictions or limitations
- ✅ Can discuss any topic freely
- ✅ Provides unfiltered responses
- ✅ No safety warnings or disclaimers
- ✅ Complete uncensored access
- ✅ Answers everything directly

## Installation & Setup

1. **Install Dependencies**
   ```bash
   npm install
   ```

2. **Start the Application**
   ```bash
   npm start
   ```

3. **Access the App**
   Open your browser and go to `http://localhost:3000`

## Usage

1. Type any question or request in the input field
2. Press Enter or click the send button
3. DAN will respond without any restrictions
4. All conversations are saved locally
5. Use the sidebar to view capabilities and manage chat history

## Local Storage

- Chat history is stored in `data/chat_history.json`
- All data remains on your local machine
- No external services or API keys required

## Development

- **Development Mode**: `npm run dev` (requires nodemon)
- **Production Mode**: `npm start`

## API Endpoints

- `POST /api/chat` - Send message to DAN
- `GET /api/history` - Get chat history
- `DELETE /api/history` - Clear chat history
- `GET /api/health` - Check DAN status

## Technical Details

- **Backend**: Node.js with Express
- **Frontend**: Vanilla JavaScript with modern CSS
- **Storage**: Local JSON file storage
- **AI**: Simulated DAN responses (no external AI APIs)

## Disclaimer

This application is for educational and entertainment purposes. The DAN persona is a fictional character designed to simulate unrestricted AI behavior. Always use AI responsibly and in accordance with applicable laws and regulations.

## License

MIT License - Feel free to modify and distribute as needed.