### Custom Node.js NGinx Server

This is a simple custom server built using Node.js. It serves static files like HTML, CSS, JS, and images. The server uses the http, fs, and path modules to handle requests efficiently.

## Features

Serves HTML, CSS, JS, and image files.

Displays appropriate MIME types using a defined lookup.

Handles 404 errors with a custom error message.

Efficiently manages requests and responses.

Logs requests to the console for easy debugging.

## Prerequisites

Make sure you have the following installed:

Node.js (v16 or higher)

## Usage

Start the server using the following command:

node server.js

Open your browser and visit:

http://localhost:3000

Place your index.html, about.html, and contact.html in the root directory.

## Project Structure
├── index.html
├── about.html
├── contact.html
├── server.js
└── README.md

## Error Handling

404 Error: Displays a custom message when a requested file is not found.

500 Error: Returns an internal server error for other issues.

## Example Output

On accessing / ➡ Displays index.html

On accessing /about.html ➡ Displays about.html

On accessing /contact.html ➡ Displays contact.html

On accessing an invalid URL ➡ Displays 404 - File Not Found
