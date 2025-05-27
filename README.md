# TypeScript First Day Lecture

Welcome to the TypeScript First Day Lecture! This repository contains the basic setup and examples to get you started with TypeScript development.

## 📋 Table of Contents

- [Overview](#overview)
- [Prerequisites](#prerequisites)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Getting Started](#getting-started)
- [Running the Code](#running-the-code)
- [What You'll Learn](#what-youll-learn)
- [Key Concepts Covered](#key-concepts-covered)
- [Next Steps](#next-steps)
- [Resources](#resources)

## 🎯 Overview

This project serves as an introduction to TypeScript, covering fundamental concepts and providing hands-on examples. You'll learn how to set up a TypeScript environment, understand basic syntax, and see the benefits of static typing in JavaScript development.

## 🔧 Prerequisites

Before starting, make sure you have the following installed:

- **Node.js** (version 14 or higher)
- **npm** or **yarn** package manager
- A code editor (VS Code recommended)
- Basic knowledge of JavaScript

## 📁 Project Structure

```
TypeScript-Revision-01/
├── .idea/                  # IDE configuration files
│   ├── .gitignore
│   ├── misc.xml
│   ├── modules.xml
│   ├── vcs.xml
│   └── workspace.xml
├── ts-app.ts/             # TypeScript source directory
│   └── ts-app.js          # Compiled JavaScript files
├── app.js                 # Main application file
├── README.md              # Project documentation
└── TypeScript-Revision-01.iml
```

## 🚀 Installation

1. **Clone the repository:**
   ```bash
   git clone  https://github.com/manushamadubhashini/TypeScript-First-Day-Lecture.git
   cd TypeScript-Revision-01
   ```

2. **Install TypeScript globally (if not already installed):**
   ```bash
   npm install -g typescript
   ```

3. **Install project dependencies:**
   ```bash
   npm install
   ```

## 🏁 Getting Started

### 1. Initialize TypeScript Configuration

If you don't have a `tsconfig.json` file yet, create one:

```bash
tsc --init
```

### 2. Basic TypeScript Example

The project includes a simple greeting function in `app.js`:

```typescript
function greet(name: string): string {
    return `Hello ${name}`;
}

console.log(greet({ name: "JavaScript" }));
```

## ▶️ Running the Code

### Compile TypeScript to JavaScript:
```bash
tsc app.ts
```

### Run the compiled JavaScript:
```bash
node app.js
```

### Or use ts-node for direct execution:
```bash
npx ts-node app.ts
```

## 📄 License

This project is for educational purposes. Feel free to use and modify as needed for learning TypeScript.

---

**Happy Learning! 🎉**

*Remember: TypeScript is JavaScript that scales. The more you practice, the more you'll appreciate its benefits in larger applications.*
