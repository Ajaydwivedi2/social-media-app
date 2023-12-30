# snapgram

Welcome to Snapgram, a user-friendly social media app that enables users to create and explore posts within a robust authentication system.
Live demo [here](https://snapgram-liart.vercel.app).

![App Screenshot](https://github.com/Ajaydwivedi2/whisper-app/blob/master/public/css/image/snapgram_schreenshot.png?raw=true)

## Table of Contents

- [General Information](#general-information)
- [Technologies Used](#technologies-used)
- [Features](#features)
- [Installation](#installation)
- [Project Status](#project-status)
- [Demo](#demo)
- [Contact](#contact)

## General Information

A cutting-edge social media platform designed for seamless user interaction. Snapgram offers an intuitive interface empowering users to effortlessly create, share, and discover posts. Our platform prioritizes user security and privacy through a robust authentication system, ensuring a safe and reliable social networking experience. The project also served as a valuable learning experience in building Single Page Applications (SPAs).

## Technologies Used

- HTML
- CSS
- JavaScript
- React.js
- Tailwind
- react-query
- TypeScript
- Shadcn
- Appwrite

## Features

👉 **Authentication System**: A robust authentication system ensuring security and user privacy

👉 **Explore Page**: Homepage for users to explore posts, with a featured section for top creators

👉 **Like and Save Functionality**: Enable users to like and save posts, with dedicated pages for managing liked and saved content

👉 **Detailed Post Page**: A detailed post page displaying content and related posts for an immersive user experience

👉 **Profile Page**: A user profile page showcasing liked posts and providing options to edit the profile

👉 **Browse Other Users**: Allow users to browse and explore other users' profiles and posts

👉 **Create Post Page**: Implement a user-friendly create post page with effortless file management, storage, and drag-drop feature

👉 **Edit Post Functionality**: Provide users with the ability to edit the content of their posts at any time

👉 **Responsive UI with Bottom Bar**: A responsive UI with a bottom bar, enhancing the mobile app feel for seamless navigation

👉 **React Query Integration**: Incorporate the React Query (Tanstack Query) data fetching library for, Auto caching to enhance performance, Parallel queries for efficient data retrieval, First-class Mutations, etc

👉 **Backend as a Service (BaaS) - Appwrite**: Utilize Appwrite as a Backend as a Service solution for streamlined backend development, offering features like authentication, database, file storage, and more.

## Installation

To run this project locally, follow these steps:

**Cloning the Repository**

```bash
git clone https://github.com/Ajaydwivedi2/social-media-app.git
cd social-media-app
```

**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Set Up Environment Variables**

Create a new file named `.env` in the root of your project and add the following content:

```env
VITE_APPWRITE_URL=
VITE_APPWRITE_PROJECT_ID=
VITE_APPWRITE_DATABASE_ID=
VITE_APPWRITE_STORAGE_ID=
VITE_APPWRITE_USER_COLLECTION_ID=
VITE_APPWRITE_POST_COLLECTION_ID=
VITE_APPWRITE_SAVES_COLLECTION_ID=
```

Replace the placeholder values with your actual Appwrite credentials. You can obtain these credentials by signing up on the [Appwrite website](https://appwrite.io/).

**Running the Project**

```bash
npm start
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.

## Project Status

The project is currently considered complete. Future enhancements and improvements are being planned.

## Demo

Explore the live demo [here](https://snapgram-liart.vercel.app).

## Contact

Created by [@ajaydwivedi](https://github.com/Ajaydwivedi2). Feel free to reach out for any questions or collaborations!
