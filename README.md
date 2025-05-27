TypeScript First Day Lecture
Welcome to the TypeScript First Day Lecture! This repository contains the basic setup and examples to get you started with TypeScript development.
📋 Table of Contents

Overview
Prerequisites
Project Structure
Installation
Getting Started
Running the Code
What You'll Learn
Key Concepts Covered
Next Steps
Resources

🎯 Overview
This project serves as an introduction to TypeScript, covering fundamental concepts and providing hands-on examples. You'll learn how to set up a TypeScript environment, understand basic syntax, and see the benefits of static typing in JavaScript development.
🔧 Prerequisites
Before starting, make sure you have the following installed:

Node.js (version 14 or higher)
npm or yarn package manager
A code editor (VS Code recommended)
Basic knowledge of JavaScript

📁 Project Structure
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
🚀 Installation

Clone the repository:
bashgit clone <repository-url>
cd TypeScript-Revision-01

Install TypeScript globally (if not already installed):
bashnpm install -g typescript

Install project dependencies:
bashnpm install


🏁 Getting Started
1. Initialize TypeScript Configuration
If you don't have a tsconfig.json file yet, create one:
bashtsc --init
2. Basic TypeScript Example
The project includes a simple greeting function in app.js:
typescriptfunction greet(name: string): string {
    return `Hello ${name}`;
}

console.log(greet({ name: "JavaScript" }));
▶️ Running the Code
Compile TypeScript to JavaScript:
bashtsc app.ts
Run the compiled JavaScript:
bashnode app.js
Or use ts-node for direct execution:
bashnpx ts-node app.ts
