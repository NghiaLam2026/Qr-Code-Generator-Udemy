# Overview
This project involves creating a QR Code Generator using Node.js. It leverages user input to generate QR codes from URLs, saving the generated QR code as a PNG image alongside a text file containing the URL. This practical application combines user interaction with file handling in Node.js, making it an excellent tool for learning and demonstrating Node.js capabilities.
<br>
<br>
# Technologies
• `Node.js`: The core technology behind the project, used for running JavaScript on the server side.
<br>
• `Inquirer`: An npm package used for collecting user input through the command line.
<br>
• `qr-image`: An npm package used to generate QR codes from text, specifically URLs in this project.
<br>
• `fs (File System)`: A native Node.js module for handling file operations.
<br>
<br>
# Project Structure
1) `User Input`: Utilize the inquirer package to collect a URL from the user.
2) `QR Code Generation`: Use the qr-image package to convert the provided URL into a QR code image, saved as a PNG file in the local directory.
3) `Saving URL`: Alongside the QR code image, the URL is saved in a text file using Node.js's native fs module.
