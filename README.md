🕵️‍♂️ Image Steganography Web App This is a simple and intuitive web-based steganography tool that allows you to hide (encode) and reveal (decode) secret messages inside images using the Least Significant Bit (LSB) method.

🚀 Features Upload any image (PNG, JPG)

Hide text message inside the image using LSB encoding

Download the encoded image

Decode and extract hidden message from the image

Clean and modern UI

📂 Files Overview index.html – Main HTML structure

style.css – Stylish and responsive UI

script.js – JavaScript logic for encoding/decoding and UI actions

🧪 How It Works The app takes your secret message and converts it into binary.

Each bit is hidden in the least significant bit of the red channel of image pixels.

When decoding, the app reads those bits back and reconstructs the message.

✅ Usage Open the app in a browser (index.html)

Select an image using the file input

Enter your secret message

Click Encode to hide the message

Click Download Encoded Image to save the stego image

Use the Decode button to reveal the hidden message

📸 Example Input: “Hello World!” Output: Image visually unchanged, but contains the hidden message Decoded message: “Hello World!”

🛠 Technologies Used HTML5 Canvas API

JavaScript (Vanilla)

CSS (Flexbox & Gradients)
