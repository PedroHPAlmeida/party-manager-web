# Party Manager Web

The front-end of the Party Manager application.

## Project Structure

```
party-manager-web/
├── public/                   # Static files served as-is
│   └── vite.svg
├── src/                      # Application source code
│   ├── assets/               # Images, fonts, and other static resources
│   ├── components/           # Generic, reusable components
│   ├── features/             # Domain-based modules (feature-based)
│   ├── hooks/                # Custom React Hooks
│   ├── layouts/              # Layout components (Header, Footer, etc.)
│   ├── pages/                # Pages/routes
│   ├── services/             # API calls and external integrations
│   ├── store/                # State management (Redux, Context, Zustand)
│   ├── styles/               # Global CSS, SASS, or CSS-in-JS themes
│   ├── types/                # TypeScript interfaces and types
│   ├── utils/                # Utility functions and constants
│   ├── config/               # Environment variables and configuration
│   ├── App.tsx               # Main application component
│   └── main.tsx              # React entry point (render)
├── .eslint.config.js         # ESLint configuration
├── .gitignore
├── package.json
├── tsconfig.json
└── vite.config.ts
```
