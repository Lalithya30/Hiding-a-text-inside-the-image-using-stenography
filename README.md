# Hiding-a-text-inside-the-image-using-stenography
# 🕵️‍♂️ Steganography Project

This Python project implements basic steganography techniques to **hide and extract secret text messages in images** using the Least Significant Bit (LSB) method.

## 🚀 Features

- 🔐 Hide text messages inside images
- 🔍 Extract hidden text from images
- 🛠️ Easy-to-use command-line interface
- 📦 Modular code with utility functions

## 📁 Project Structure

steganography_project/
│
├── hide_text.py # Script to hide text in an image
├── extract_text.py # Script to extract text from an image
├── utils.py # Helper functions for image processing
├── requirements.txt # List of dependencies


## 🛠️ Requirements

Install dependencies using:

```bash
pip install -r requirements.txt

🧪 Usage
🔒 Hide Text in Image
python hide_text.py --input input_image.png --output output_image.png --message "Your secret message"
✅ Example
bash
Copy
Edit
python hide_text.py --input cat.png --output secret_cat.png --message "The cake is a lie."
python extract_text.py --input secret_cat.png
Output:

csharp
Copy
Edit
Extracted message: The cake is a lie.
