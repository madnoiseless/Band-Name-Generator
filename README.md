# Band Name Generator

## Overview

This project is a simple web application that generates a random band name. The application is built using Node.js, Express, and EJS (Embedded JavaScript Templates) for server-side logic and rendering. It also includes a basic HTML structure and CSS styling for the user interface.

## Getting Started

To run this project, you'll need to have Node.js and npm (Node Package Manager) installed on your machine. Additionally, you'll need to set up a local development environment with a text editor or IDE of your choice.

1. Clone the repository to your local machine:
```bash
git clone https://github.com/madnoiseless/Band-Name-Generator.git
```
2. Navigate to the project directory:
```bash
cd band-name-generator
```
3. Install the required dependencies:
```bash
npm install
```
4. Start the development server:
```bash
node index.js
```
The application will be accessible at `http://localhost:3000`.

## How it Works

The Band Name Generator consists of several files:

1. `index.js`: This file sets up the Express server, configures middleware, and defines routes for the application. When a user submits the form, the server generates a random band name using two words from the `adj` and `noun` arrays and renders the updated page with the new name.
2. `index.ejs`: This is the main template for the webpage. It includes the header, form, and footer templates, and displays the generated band name if it exists.
3. `header.ejs` and `footer.ejs`: These templates define the structure for the header and footer sections of the webpage, respectively.
4. `main.css`: This file contains the CSS styles for the webpage, including layout and typography.
