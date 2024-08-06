# Random Password Generator

## Description
A simple web application that generates random passwords based on user-selected criteria such as length, lowercase letters, uppercase letters, numbers, and symbols.

## Features
- Select password length
- Include lowercase letters
- Include uppercase letters
- Include numbers
- Include symbols

## Technologies Used
- HTML
- CSS
- JavaScript

## Usage
1. Open `index.html` in your web browser.
2. Adjust the settings for password length and character
3. Click the "Generate Password" button
4. The generated password will be displayed on the screen

## How to Run
1. Clone the repository or download the project files
2. Open `index.html` in any web browser
3. Follow the usage instructions to generate a random password

<br>

### JavaScript Explanation
The `index.js` file contains two main functions:

1. **generatePassword**
   - Generates a random password based on:
     - Length
     - Lowercase letters
     - Uppercase letters
     - Numbers
     - Symbols
   - Adds selected character types to a pool and randomly picks characters to create the password

2. **generateAndDisplayPassword**
   - Gets user settings from the HTML page
   - Calls `generatePassword` with these settings
   - Displays the generated password on the page
   
      ![pass_gen_pic](https://github.com/user-attachments/assets/5c705096-f074-41a6-a7aa-d3bd02f22128)
