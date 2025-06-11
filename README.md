.././././<...>
# Exam Entry Form & Card

This project is a simple web-based application that allows users to fill out a form with their personal and exam-related details and then view/print an official-style exam entry card. The interface and content are in Persian (Farsi), suitable for local exam systems.

## 📄 Project Pages

### 1. `index.html` – Registration Form

On this page, users enter the following details:

- Name  
- Father’s Name  
- Year of Birth  
- Serial Number  
- Province  
- School  
- Exam Center  
- Exam Time  
- ID  

After submitting the form, the data is saved to the browser's **localStorage**, and the user is redirected to the card display page.

### 2. `card.html` – Exam Entry Card

This page reads the saved form data from `localStorage` and displays it in a printable card layout. Key features:

- Displays all the entered information in a table
- Official-style header with a logo and exam authority titles
- Generates a barcode based on the user’s ID using **JsBarcode**
- Includes a **Print Card** button
- Shows an important note to guide students (e.g. "Use black pen on the answer sheet")
...
## 🎨 Styling

All styling is managed through the `styel.css` file, which gives the form and the card a clean, presentable design.

## 📦 Libraries Used

- [JsBarcode](https://github.com/lindell/JsBarcode): Used for generating the barcode from the student's ID.

## ⚠️ Notes

- Ensure JavaScript is enabled in the browser; otherwise, the form and card functionality won't work properly.
- All data is handled on the client-side (browser); no server or database is involved.

https://rezaaslami.github.io/shomooliat-form/

