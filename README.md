# Akhila-dubbbigalla
Resume Builder Web App

A simple and interactive Resume Builder web application that allows users to enter their personal, educational, and professional details, preview their resume in real time, and download it as a PDF using jsPDF.

 Features

- Responsive and clean UI layout
- Live preview of resume as user enters data
- Download resume as a PDF
- Basic input validation
- Built using **HTML**, **CSS**, **JavaScript**, and **jsPDF**

 Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla JS)
- [jsPDF CDN](https://cdnjs.com/libraries/jspdf)

Preview

| Form Input  | Live Preview | Download PDF |
|-------------|--------------|---------------|
| Fill personal, education, and experience details | See changes in real-time on the right panel | Click "Download PDF" to save your resume |

Project Structure

Resume-Builder/
│
├── index.html # Main HTML file with form and preview
├── README.md # This file

markdown
Copy
Edit

How It Works

1. User enters their full name, email, phone, summary, education, and experience.
2. Clicking **"Generate Resume"** updates the right-side preview in real-time.
3. Clicking **"Download PDF"** creates a professional-looking PDF using jsPDF and downloads it.

 Setup Instructions

1. **Clone or Download** this repository.
2. Open `index.html` in any modern web browser.
3. Fill out the form on the left and click "Generate Resume".
4. Click "Download PDF" to save the resume.

 Notes

- Required fields: Name, Email, Phone, Summary.
- Make sure to include jsPDF via CDN as included in the `<script>` tag:
  ```html
  <script src="https://cdnjs.cloudflare.com/ajax/libs/jspdf/2.5.1/jspdf.umd.min.js"></script> License
This project is open-source and free to use.

