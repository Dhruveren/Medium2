# Medium2 - A Modern Blogging Platform


---

## Overview

**Medium2** is a full-stack web application designed to provide a sleek, performant, and user-friendly blogging experience. Built with modern technologies like Next.js, TypeScript, and a robust backend, it empowers users to create, share, and explore content seamlessly. Whether you're a writer showcasing your thoughts or a reader diving into rich articles, Medium2 delivers a responsive and intuitive platform with real-time features and a polished UI.

This project highlights my skills in full-stack development, state management, and deployment optimization, making it a standout addition to my portfolio.

---

## Features

- **User Authentication**: Secure login/signup with JWT-based authentication.
- **Post Creation & Editing**: Rich text editor for crafting and updating blog posts with ease.
- **Real-Time Updates**: Auto-refreshing feeds and notifications using WebSockets.
- **Responsive Design**: Mobile-first UI built with Tailwind CSS for a consistent experience across devices.
- **Media Support**: Upload images and embed videos within posts via Cloudinary integration.
- **Dark/Light Mode**: Toggleable themes for enhanced user accessibility.
- **Search & Discovery**: Fast, keyword-based search to explore posts and authors.
- **Performance Optimized**: Server-side rendering (SSR) and static site generation (SSG) with Next.js for lightning-fast load times.
- **Deployment Ready**: Dockerized app with a CI/CD pipeline for streamlined updates.

---

## Tech Stack

### Frontend
- **Next.js**: React framework for SSR and SSG.
- **TypeScript**: Type-safe JavaScript for robust code.
- **Tailwind CSS**: Utility-first CSS for rapid UI development.
- **Zustand**: Lightweight state management for global app state.

### Backend
- **Node.js & Express**: RESTful API for handling requests.
- **Prisma**: ORM for efficient database interactions.
- **PostgreSQL**: Relational database for storing user data and posts.
- **JWT**: Secure token-based authentication.
- **Cloudinary**: Image and media storage solution.

### DevOps
- **Docker**: Containerization for consistent environments.
- **Vercel**: Seamless deployment and hosting.
- **CI/CD**: Automated workflows with GitHub Actions.
- **Vitest**: Unit testing for backend endpoints.

---

## Installation

Follow these steps to run Medium2 locally:

### Prerequisites
- Node.js (v16+)
- PostgreSQL (v13+)
- Docker (optional, for containerized setup)
- Git

### Steps
1. **Clone the Repository**  
   ```bash
   git clone https://github.com/Dhruveren/Medium2.git
   cd Medium2
