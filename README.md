# ReportNRepair

ReportNRepair is a React-based web application that enables users to report civic issues in their communities. This project is built with Vite for fast development and TailwindCSS for styling.

## Features

- **User Authentication**: Secure login and signup functionality.
- **Report Submission**: Submit detailed reports with descriptions, images, and contact information.
- **Protected Routes**: Access certain features only after logging in.
- **Responsive Design**: Optimized for all devices.
- **Category-Based Reporting**: Predefined categories for common civic issues.

## Tools and Technologies Used

### Frontend Stack
- React 19.0.0
- Vite 6.3.1
- TailwindCSS 4.1.4
- DaisyUI 5.0.27
- React Router DOM 7.5.1
- React Icons 5.5.0

### Backend Stack
- Python Flask
- PostgreSQL 17.4
- psycopg2
- Flask-CORS

### AI/ML Technologies
- Ollama
- Hugging Face Transformers
- TensorFlow/Keras

### Development Tools
- Git & GitHub
- VS Code
- ESLint 9.22.0


### Prerequisites

Ensure you have the following installed:

- [Node.js](https://nodejs.org/) (version 16 or higher)
- [npm](https://www.npmjs.com/) (comes with Node.js)

```
frontend/
├── public/               # Static assets
├── src/
│   ├── assets/           # Images and other assets
│   ├── components/       # Reusable components
│   │   └── layout/       # Layout components (Navbar, Footer, etc.)
│   ├── context/          # Context API for state management
│   ├── pages/            # Page components (HomePage, LoginPage, etc.)
│   ├── routes/           # Route definitions and protected routes
|   ├── App.css
│   ├── App.jsx           # Main app component
│   ├── main.jsx          # Entry point
│   └── index.css         # Global styles
├── .gitignore            # Files to ignore in Git
├── index.html            # HTML template
├── package.json          # Project metadata and dependencies
├── vite.config.js        # Vite configuration
└── README.md             # Project documentation
```

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/civic-reporter.git
   cd civic-reporter

2. Install dependencies:
    npm install
    npm install tailwindcss@latest @tailwindcss/vite@latest daisyui@latest
    npm install react-router-dom  
    npm install react-icons         

3. Start the development server:
    npm run dev

### Dependencies

- **Core Dependencies**:
    1. React: A JavaScript library for building user interfaces.
    2. React Router DOM: For routing and navigation.
    3. TailwindCSS: A utility-first CSS framework.
    4. DaisyUI: TailwindCSS components for faster UI development.
- **Dev Dependencies**:
    1. Vite: A fast build tool for modern web projects.
    2. ESLint: For linting and code quality.
    3. @vitejs/plugin-react: React plugin for Vite.

---

🌐 Live Demo: 

---
