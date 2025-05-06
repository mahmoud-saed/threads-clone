# Threads Clone

A modern, full-stack clone of Meta's Threads app, built with Next.js, TypeScript, Tailwind CSS, and MongoDB. This project offers a responsive and interactive social media experience, allowing users to create threads, interact with others, and manage their profiles.

## 🌐 Live Demo

Check out the live application here: [threads-clone-rouge.vercel.app](https://threads-clone-rouge.vercel.app/)

## 📖 Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## ✨ Features

- **User Authentication**: Secure login and registration system.
- **Thread Creation**: Users can create, edit, and delete threads.
- **Responsive Design**: Optimized for various devices and screen sizes.
- **Profile Management**: Users can update their profile information.
- **Real-time Updates**: Dynamic content rendering for an interactive experience.

## 🛠️ Tech Stack

- **Frontend**: Next.js, React, TypeScript, Tailwind CSS
- **Backend**: Next.js API Routes, MongoDB
- **Authentication**: Clerk
- **Styling**: Tailwind CSS
- **Deployment**: Vercel

## 🚀 Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/mahmoud-saed/threads-clone.git
   cd threads-clone
   ```


2. **Install dependencies**:

   ```bash
   npm install
   ```


3. **Set up environment variables**:

   Create a `.env.local` file in the root directory and add the following:

   ```env
   MONGODB_URI=your_mongodb_connection_string
   NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
   CLERK_SECRET_KEY=your_clerk_secret_key
   ```


4. **Run the development server**:

   ```bash
   npm run dev
   ```


   The application will be available at [http://localhost:3000](http://localhost:3000).

## 📸 Usage

- **Home Page**: View a feed of all threads.
- **Create Thread**: Click on the "New Thread" button to create a thread.
- **Profile Page**: Access your profile to view and edit your information.
- **Authentication**: Use Clerk to sign in or register.

## ⚙️ Configuration

- **Tailwind CSS**: Configured in `tailwind.config.ts`.
- **ESLint**: Linting rules defined in `.eslintrc.json`.
- **TypeScript**: Configuration in `tsconfig.json`.
- **Next.js**: Custom settings in `next.config.js`.

## 📁 Project Structure


```plaintext
├── app/                 # Next.js app directory
├── components/          # Reusable UI components
├── constants/           # Application constants
├── lib/                 # Utility functions and libraries
├── public/              # Static assets
├── .eslintrc.json       # ESLint configuration
├── next.config.js       # Next.js configuration
├── tailwind.config.ts   # Tailwind CSS configuration
├── tsconfig.json        # TypeScript configuration
└── README.md            # Project documentation
```


## 🤝 Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.
