
# Challa Tejaswi 
## Indian Institute Of Technology Bhubaneswar
## Electrical Engineering
# New Chat Frontend

This project is a complete MERN-based web application integrating **ZugoCloud** API for video/audio calls, **Stream** for chat functionality, and **Firebase** for authentication and data storage.

## Features
- Real-time Video and Audio Calls (ZugoCloud)
- Chat Functionality (Stream API)
- Firebase Authentication
- Emoji Picker (Emoji Mart)
- Modern UI Components (Headless UI and Heroicons)

## Project Structure
- `src/`: Contains the React frontend code
- `public/`: Contains static files
- `package.json`: Lists project dependencies and scripts

## Installation

1. **Clone the repository:**

   ```bash
   https://github.com/ChallaTejaswi/chat_care.git
   cd new-chat-frontend
   ```

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Set up Firebase:**

   - Create a Firebase project and configure Firestore and Authentication.
   - Replace Firebase config in your app with your Firebase project details.

4. **Run the project:**

   ```bash
   npm start
   ```

   The app will be running on `http://localhost:3000`.

## Dependencies

Here are the major dependencies used in the project:

- **ZugoCloud UIKit Prebuilt** (`@zegocloud/zego-uikit-prebuilt`): Provides video/audio call functionality.
- **Stream Chat** (`stream-chat`, `stream-chat-react`): Provides real-time chat functionality.
- **Firebase** (`firebase`, `@firebase/firestore`, `react-firebase-hooks`): Manages user authentication and Firestore database.
- **Axios**: For making HTTP requests.
- **React Router Dom**: For routing between pages.
- **Emoji Mart** (`@emoji-mart/react`, `@emoji-mart/data`): For emoji picker in chat input.
- **Headless UI** (`@headlessui/react`): Provides unstyled accessible UI components.
- **Heroicons** (`@heroicons/react`): Icons for the UI.
- **Sendbird Calls**: For additional call features.

### Full list of dependencies:

```json
{
  "@emoji-mart/data": "^1.2.1",
  "@emoji-mart/react": "^1.1.1",
  "@firebase/firestore": "^4.7.2",
  "@headlessui/react": "^2.1.8",
  "@heroicons/react": "^2.1.5",
  "@testing-library/jest-dom": "^5.17.0",
  "@testing-library/react": "^13.4.0",
  "@testing-library/user-event": "^13.5.0",
  "@zegocloud/zego-uikit-prebuilt": "^2.9.1",
  "axios": "^1.7.7",
  "emoji-mart": "^5.6.0",
  "firebase": "^10.13.2",
  "react": "^18.3.1",
  "react-dom": "^18.3.1",
  "react-firebase-hooks": "^5.1.1",
  "react-icons": "^5.3.0",
  "react-router-dom": "^6.26.2",
  "react-scripts": "5.0.1",
  "sendbird-calls": "^1.10.19",
  "stream-chat": "^8.40.8",
  "stream-chat-react": "^12.0.0",
  "web-vitals": "^2.1.4"
}
```

## Available Scripts

In the project directory, you can run:

- **`npm start`**: Runs the app in development mode. Open [http://localhost:3000](http://localhost:3000) to view it in the browser.
- **`npm build`**: Builds the app for production to the `build` folder.
- **`npm test`**: Runs the tests.


