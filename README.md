# UanI Chat

**UanI** chat is a simple chat application for exploring WebSocket technology with Firebase Realtime Database and Firebase Firestore.

## Tech Stack

- Vue.js
- TypeScript
- UnoCSS
- Pinia
- Firebase

## Getting Started

To get started running the project locally, please follow the steps below.

First, clone the repository.

```bash
git clone https://github.com/kalwabed/us-chat.git
```

Then, install dependencies and fetch data to your local machine. **Note that I use [Bun](https://bun.sh/docs/installation).**

```bash
cd us-chat
bun install
```

Then, copy and set your Firebase credentials to the `.env.local` file.

```bash
cp .env.local.example .env.local
```

> Please note that we use **Firebase Realtime Database** and **Firebase Firestore**. Therefore, please ensure that you have set up your own Firebase instance.

Finally, run the development server.

```bash
bun dev
```

Open [localhost:5173](http://localhost:5173) with your browser to see the result.

## Screenshots

![Login page screenshot](/public/ss-login.png)
![Chat page screenshot](/public/ss-chat.png)
