# Roomify | AI-powered Architectural Visualization App

Roomify is an AI-first design environment that helps you visualize, render, and ship architectural projects faster than ever. It transforms 2D floor plans into photorealistic 3D renders using state-of-the-art AI models.

## ✨ Features

- **2D-to-3D Visualization**: Instant architectural rendering that transforms flat floor plans into photorealistic 3D models.
- **Persistent Media Hosting**: Permanent file storage that generates public URLs for every upload and output.
- **Dynamic Project Gallery**: A personalized workspace that tracks your history of visualizations.
- **Side-by-Side Comparison**: Interactive tools to visualize the direct transformation from a source sketch to its AI-rendered counterpart.
- **Privacy Controls**: Granular public and private toggles for your architectural data.

## ⚙️ Tech Stack

- **React / React Router**: For building a modern, responsive user interface.
- **TypeScript**: Ensuring type safety and maintainable code.
- **TailwindCSS**: Utility-first CSS framework for rapid UI development.
- **Puter**: Cloud platform providing serverless Workers, KV storage, and AI model hosting.
- **Vite**: Next-generation frontend tooling for a fast development experience.

## 🤸 Quick Start

Follow these steps to set up the project locally.

### Prerequisites

Make sure you have the following installed:
- [Node.js](https://nodejs.org/en) (v18 or higher)
- [npm](https://www.npmjs.com/)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/naseemmig02/roomify.git
   cd roomify
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

### Set Up Environment Variables

Create a `.env` file in the root directory and add your Puter Worker URL:

```env
VITE_PUTER_WORKER_URL="your_puter_worker_url_here"
```

### Running the Project

Start the development server:

```bash
npm run dev
```

The application will be available at `http://localhost:5173` (or the port specified in your terminal).

## 🚀 Deployment

This project is designed to be hosted on **Puter**. You can deploy the frontend using Puter's hosting services and run the backend logic via Puter Workers.
