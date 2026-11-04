# Portfolio Website

A polished personal portfolio built with Vite, React, Tailwind CSS, and Framer Motion for a modern, responsive experience.

## Features
- Responsive layout for desktop, tablet, and mobile
- Smooth motion-driven section transitions
- Strong portfolio storytelling with services, skills, and project highlights
- Contact section with clear calls to action
- Firebase Hosting configuration for Google deployment

## Tech Stack
- React
- Vite
- Tailwind CSS
- Framer Motion
- React Icons

## Local Development

Open this folder in VS Code and press **F5** to start the Vite development server
and open the site in Chrome. This uses the built-in JavaScript debugger.

You can also start the server from a terminal:

```bash
npm install
npm start
```

Open `http://localhost:5173` in your browser.

## Production Build

```bash
npm run build
```

## Google Firebase Hosting

1. Install Firebase tools:

```bash
npm install -g firebase-tools
```

2. Log in and initialize your project:

```bash
firebase login
firebase init hosting
```

3. When prompted, select your Firebase project and set the public directory to `dist`.

4. Deploy:

```bash
firebase deploy --only hosting
```

The project is already configured with an example Firebase config in `firebase.json` and `.firebaserc`.

## Notes
- Replace the placeholder email, phone number, and social links in the portfolio before publishing.
- Update the Firebase project ID in `.firebaserc` with your real Google Firebase project name.

---
Made with care for a stronger portfolio presentation.
