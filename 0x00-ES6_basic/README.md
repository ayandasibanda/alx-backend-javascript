# ES6 Basics ✨

## Overview
This repository contains exercises focusing on various ES6 features and concepts. Each exercise is designed to provide hands-on practice with ES6 syntax and functionality.

## What is ES6?
ES6, short for ECMAScript 6, is the sixth major release of the ECMAScript programming language specification. It brings significant enhancements and new features to JavaScript, making the language more expressive and powerful.

## New Features Introduced in ES6
ES6 introduced several new features and enhancements, including:
- Arrow functions
- Template literals
- Block-scoped variables (`let` and `const`)
- Default parameters
- Rest and spread operators
- Object literal extensions
- Classes
- Modules
- Promises
- Iterators and for-of loops

## Constant vs. Variable
In ES6, `const` and `let` are used to declare variables. The difference between them lies in their mutability:
- `const`: Variables declared with `const` are immutable, meaning their value cannot be changed once assigned.
- `let`: Variables declared with `let` are mutable, allowing their value to be reassigned.

## Setup 🛠️
1. **Install Node.js 12.11.x:**
   - Run the following commands in your terminal:
     ```
     curl -sL https://deb.nodesource.com/setup_12.x -o nodesource_setup.sh
     sudo bash nodesource_setup.sh
     sudo apt install nodejs -y
     ```
   - Verify the installation:
     ```
     nodejs -v
     npm -v
     ```

2. **Install Jest, Babel, and ESLint:**
   - Navigate to your project directory.
   - Use the supplied `package.json` to install dependencies:
     ```
     npm install
     ```

3. **Configuration Files:**
   - Add the following files to your project directory:
     - `package.json`
     - `babel.config.js`
     - `.eslintrc.js`

4. **Run the Exercises:**
   - Each exercise is located in its respective file within the directory `0x00-ES6_basic`.
   - Execute the exercises using `npm run dev <filename>`.

