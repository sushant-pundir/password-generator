# Password Generator

A customizable password generator built using HTML, CSS and JavaScript.

## Features

- Generate random passwords
- Adjustable password length
- Lowercase and uppercase characters
- Numbers and symbols
- Optional duplicate character restriction
- Clipboard copy functionality
- Password strength indicator

## Technologies

- HTML5
- CSS3
- JavaScript

## Getting Started

Clone the repository:

    git clone https://github.com/sushant-pundir/password-generator.git

Enter the directory:

    cd password-generator

## Run

Start a local development server:

    python3 -m http.server 5502

Open:

    http://localhost:5502

## Project Structure

    password-generator/
    ├── index.html
    ├── style.css
    ├── script.js
    ├── README.md
    └── LICENSE

## Attribution

Based on the MIT-licensed Password Generator
by Coding With Enjoy.

Original source:
https://github.com/CodingWithEnjoy/Password-Generator-HTML-CSS-JS

Original MIT license retained.

## Security Note

This is a learning project. The original implementation
uses Math.random(). Replace it with the Web Crypto API
before using generated passwords for real accounts.
