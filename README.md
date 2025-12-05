# Franklin Elvis - Portfolio

![Portfolio Badge](https://img.shields.io/badge/Status-Active-success) ![License](https://img.shields.io/badge/License-MIT-blue)

A modern, responsive portfolio website for a UI/UX Designer & Web + AI Developer. This project features a simulated "Client Dashboard" demo, an AI chatbot interface, and a sleek landing page.

## ⚡ Tech Stack

This project was built using a modern React ecosystem:

- **Framework**: [React 18](https://react.dev/)
- **Language**: [TypeScript](https://www.typescriptlang.org/)
- **Build Tool**: [Vite](https://vitejs.dev/)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/) (Runtime CDN configuration)
- **Icons**: [Lucide React](https://lucide.dev/)
- **Charts**: [Recharts](https://recharts.org/)
- **Fonts**: Inter, Oswald, Space Grotesk, Geist (via Google Fonts)

## 📂 Project Structure

The project uses a flat, modular structure optimized for Vite:

```text
franklin-portfolio/
├── components/          # React components (Dashboard, LandingPage, etc.)
├── App.tsx             # Main application layout and routing logic
├── index.html          # Entry point with Tailwind CDN and font links
├── index.tsx           # React DOM mounting
├── types.ts            # TypeScript interfaces and type definitions
├── package.json        # Dependencies and scripts
├── vite.config.ts      # Vite configuration
└── README.md           # Project documentation
```

## 🚀 Getting Started

To run this project locally or upload to GitHub, follow these steps:

### 1. Installation

Ensure you have Node.js (v16+) installed.

```bash
# Install dependencies
npm install
```

### 2. Development

Start the local development server:

```bash
npm run dev
```

The application will be available at `http://localhost:5173`.

### 3. Build for Production

Compile the project for deployment:

```bash
npm run build
```

## 🎨 Features

- **Responsive Landing Page**: High-performance UI with smooth animations.
- **Client Dashboard Demo**: A fully functional mock dashboard showing charts and data visualization.
- **AI Agent Interface**: A conversational sidebar simulating an AI assistant.
- **Dark Mode**: Fully supported system-aware dark mode.

## 📝 Configuration Note

This project uses Tailwind CSS via a CDN script in `index.html` for instant portability and runtime configuration. For a production environment involving large scale, you may consider migrating to a PostCSS build process, though the current setup is fully functional and highly performant for a portfolio site.

## 👤 Author

**Franklin Elvis**
- UI/UX & Web + AI Developer
- [GitHub Profile](https://github.com/)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
