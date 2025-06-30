# QR-Generator

This is a simple Node.js CLI application that generates a QR code from a user-provided URL and saves both the QR image and the original URL to local files.

## Features

- Takes user input (a URL) from the terminal
- Generates a QR code image from the URL using the `qr-image` package
- Saves the generated QR code as `qr_img.png`
- Saves the original URL to a `URL.txt` file

## Demo

![QR Image](./qr_img.png)

## Getting Started

### Prerequisites

- Node.js (v18 or higher recommended)
- npm

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/QR-generator.git
   cd QR-generator
   Install dependencies:
npm install

To run the QR generator:
node index.js

You will be prompted to enter a URL. After input, the following files will be created:
qr_img.png – QR code representing the URL
URL.txt – A text file containing the input URL

Example:
? Type in your URL: https://www.youtube.com/@RiteshPrasad07
The file has been saved!

Built With
inquirer – For interactive CLI prompts
qr-image – For generating QR codes
Node.js fs module – For writing files

Project Structure
QR-generator/
├── index.js
├── package.json
├── package-lock.json
├── qr_img.png
└── URL.txt




