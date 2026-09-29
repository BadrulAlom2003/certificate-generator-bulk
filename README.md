# 🎓 One-Click Bulk Certificate Generator

A lightweight, browser-based certificate generator that allows you to create **hundreds or thousands of certificates from a single CSV file** and export them as one PDF.

No backend or database is required. Everything runs directly in the browser.

---

## ✨ Features

* 📂 **CSV Upload**

  * Upload participant data from a `.csv` file.
  * Supports drag & drop.
  * Automatically detects rows and previews certificate data.

* 📑 **Bulk PDF Generation**

  * Generate certificates for all valid CSV records.
  * Export all certificates into a **single PDF file**.
  * Shows generation progress while processing.

* 🎨 **5 Certificate Designs**

  * Classic Navy
  * Modern Minimal
  * Elegant Maroon
  * Emerald & Gold
  * Royal Blue

* 🖼️ **10 Background Options**

  * Default Design
  * White
  * Cream Paper
  * Parchment
  * Sky Blue
  * Mint
  * Pink
  * Dot Pattern
  * Diagonal
  * Watermark Ring

* ✍️ **Advanced Certificate Editor**

  * Add custom text
  * Add images and logos
  * Add lines and shapes
  * Move elements with drag & drop
  * Change position, size, color and rotation
  * Change fonts and font sizes
  * Bold / Italic / Underline
  * Text alignment
  * List and bullet styles
  * Layer control
  * Duplicate elements
  * Hide or delete elements
  * Reset individual elements
  * Reset the complete template

* 🧩 **Flexible Layout**

  * Resize and reposition images
  * Crop images
  * Control image opacity
  * Lock image aspect ratio
  * Customize lines, shapes and borders

* 🌐 **Bilingual Interface**

  * English
  * বাংলা

* 👀 **Live Preview**

  * Preview certificates before generating the final PDF.
  * Navigate between different CSV records.

* ⚠️ **Incomplete Data Detection**

  * Detect missing required information.
  * Optionally skip incomplete records.
  * Download a CSV containing failed/incomplete records.

* 📧 **Email Support**

  * Developer email can be opened through Gmail or the default mail application.

* 📱 **Responsive UI**

  * Designed for desktop and smaller screens.

* 🌙 **Dark Mode Support**

  * Supports browser/system color preferences.

---

## 🧾 CSV Format

Your CSV file should contain the following columns.

### Required Columns

```csv
Name,Event Name,Date,Institution
```

### Optional Columns

```csv
Team Name,Student ID,Class,Department,Group
```

### Example

```csv
Name,Event Name,Date,Institution,Team Name,Student ID,Class,Department,Group
Badrul Alom,Programming Contest,2026-09-29,ABC University,Team Alpha,2026001,3rd Year,CSE,A
Rahim Ahmed,Programming Contest,2026-09-29,ABC University,Team Beta,2026002,3rd Year,CSE,B
Karim Hasan,Programming Contest,2026-09-29,ABC University,Team Gamma,2026003,4th Year,CSE,A
```

---

## 🚀 How to Use

### 1. Open the Application

Open:

```text
index.html
```

in a modern web browser.

### 2. Prepare Your CSV

Create a CSV file using the format described above.

### 3. Upload the CSV

Click the upload area or drag and drop your CSV file.

### 4. Choose Certificate Type

Available certificate types include:

* Participation
* Achievement
* Completion
* Excellence
* Appreciation

### 5. Choose a Design

Select one of the available certificate designs.

### 6. Customize the Certificate

You can customize:

* Text
* Fonts
* Font size
* Colors
* Position
* Rotation
* Images
* Logos
* Lines
* Shapes
* Backgrounds
* Borders
* Layers

### 7. Preview

Use the Previous/Next controls to inspect certificates generated from different CSV records.

### 8. Generate PDF

Click:

**Download All Certificates PDF**

The application generates and downloads:

```text
certificates.pdf
```

---

## 🛠️ Technologies Used

This project is built using:

* HTML5
* CSS3
* JavaScript
* Canvas API
* PapaParse
* jsPDF
* Google Fonts

### External Libraries

**PapaParse 5.4.1**

Used for CSV parsing.

**jsPDF 2.5.1**

Used for PDF generation.

---

## 🏗️ Project Structure

```text
certificate-generator/
│
├── index.html
└── README.md
```

The current version is a standalone frontend application.

---

## 🔒 Privacy

The application processes certificate data directly in the browser during the certificate-generation workflow.

No backend or database is required.

If external services, analytics, APIs or server-side processing are added in the future, review the privacy implications before using personal or student data.

---

## ⚡ Performance

The generator is designed for bulk certificate creation, including large CSV datasets.

For very large batches, browser memory and device performance may affect generation time.

It is recommended to test a small batch before generating a large production batch.

---

## 🎯 Use Cases

This project can be useful for:

* 🏆 Programming Contests
* 🎓 Workshops
* 🧑‍💻 Hackathons
* 🚀 NASA Space Apps / Technology Events
* 🏫 School & University Events
* 📚 Training Programs
* 🎤 Seminars
* 🏅 Competitions
* 👥 Volunteer Recognition
* 🎖️ Participation Certificates
* 📜 Completion Certificates
* 🌟 Achievement Certificates

---

## 💡 Workflow

```text
CSV
 ↓
Upload
 ↓
Choose Certificate Type
 ↓
Choose Design
 ↓
Customize
 ↓
Preview
 ↓
Generate
 ↓
One PDF
```

---

## 🧑‍💻 Customization

Developers can customize the application directly from `index.html`.

You can modify:

* Certificate designs
* Backgrounds
* Default texts
* Fonts
* Colors
* Certificate dimensions
* Developer information
* Language translations
* PDF filename
* Default certificate type

---

## 🌍 Language Support

The interface currently supports:

* 🇬🇧 English
* 🇧🇩 বাংলা

---

## 📌 Important Notes

* A modern browser is recommended.
* Internet access may be required because fonts and JavaScript libraries are loaded from CDNs.
* Make sure CSV headers match the expected column names.
* Test a small dataset before generating a very large batch.
* Keep a backup of the original CSV file.

---

## 🤝 Contributing

Contributions are welcome.

### Steps

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Test the application.
5. Create a Pull Request.

Example:

```bash
git clone https://github.com/your-username/one-click-bulk-certificate-generator.git

cd one-click-bulk-certificate-generator
```

Then open `index.html` in your browser.

---

## 📄 License

Add your preferred open-source license here.

For example:

```text
MIT License
```

If you choose the MIT License, add a `LICENSE` file to the repository.

---

## ⭐ Support the Project

If this project helps you generate certificates faster, consider giving the repository a ⭐ on GitHub.

---

## 👨‍💻 Developer

Add your information here:

```text
Name: Md. Badrul Alom
Email: mdbd644@gmail.com
```

---

# 🇧🇩 বাংলা সংস্করণ

# 🎓 One-Click Bulk Certificate Generator

এটি একটি lightweight এবং browser-based certificate generator, যার মাধ্যমে একটি CSV file ব্যবহার করে **শত শত বা হাজার হাজার certificate** তৈরি করা যায় এবং সবগুলোকে একটি PDF file হিসেবে export করা যায়।

এর জন্য কোনো backend বা database প্রয়োজন হয় না। Certificate তৈরির পুরো প্রক্রিয়াটি browser-এর মধ্যেই সম্পন্ন হয়।

---

## ✨ প্রধান বৈশিষ্ট্য

* 📂 **CSV Upload**

  * `.csv` file থেকে participant-এর তথ্য upload করা যায়।
  * Drag & Drop support রয়েছে।
  * CSV-এর data automatically detect করে certificate preview দেখায়।

* 📑 **Bulk PDF Generation**

  * CSV-এর সব valid record থেকে certificate তৈরি করা যায়।
  * সব certificate একটি **single PDF file** হিসেবে export করা যায়।
  * PDF তৈরির সময় generation progress দেখা যায়।

* 🎨 **৫টি Certificate Design**

  * Classic Navy
  * Modern Minimal
  * Elegant Maroon
  * Emerald & Gold
  * Royal Blue

* 🖼️ **১০টি Background Option**

  * Default Design
  * White
  * Cream Paper
  * Parchment
  * Sky Blue
  * Mint
  * Pink
  * Dot Pattern
  * Diagonal
  * Watermark Ring

* ✍️ **Advanced Certificate Editor**

  * Custom text যোগ করা যায়।
  * Image ও logo যোগ করা যায়।
  * Line ও shape যোগ করা যায়।
  * Drag & Drop করে element সরানো যায়।
  * Position, size, color এবং rotation পরিবর্তন করা যায়।
  * Font এবং font size পরিবর্তন করা যায়।
  * Bold / Italic / Underline ব্যবহার করা যায়।
  * Text alignment পরিবর্তন করা যায়।
  * List এবং bullet style ব্যবহার করা যায়।
  * Element-এর layer control করা যায়।
  * Element duplicate করা যায়।
  * Element hide অথবা delete করা যায়।
  * Individual element reset করা যায়।
  * সম্পূর্ণ template reset করা যায়।

* 🧩 **Flexible Layout**

  * Image resize ও reposition করা যায়।
  * Image crop করা যায়।
  * Image opacity control করা যায়।
  * Image aspect ratio lock করা যায়।
  * Line, shape এবং border customize করা যায়।

* 🌐 **দুই ভাষার Interface**

  * English
  * বাংলা

* 👀 **Live Preview**

  * PDF generate করার আগে certificate preview দেখা যায়।
  * CSV-এর বিভিন্ন record-এর certificate Previous/Next করে দেখা যায়।

* ⚠️ **Incomplete Data Detection**

  * Required information missing আছে কি না detect করে।
  * চাইলে incomplete record skip করা যায়।
  * Failed/incomplete record-এর CSV download করা যায়।

* 📧 **Email Support**

  * Developer-এর email Gmail অথবা default mail application-এর মাধ্যমে open করা যায়।

* 📱 **Responsive UI**

  * Desktop এবং ছোট screen-এর জন্য তৈরি করা হয়েছে।

* 🌙 **Dark Mode Support**

  * Browser/system-এর color preference support করে।

---

## 🧾 CSV Format

CSV file-এ নিচের columnগুলো ব্যবহার করা যাবে।

### Required Columns

```csv
Name,Event Name,Date,Institution
```

### Optional Columns

```csv
Team Name,Student ID,Class,Department,Group
```

### Example

```csv
Name,Event Name,Date,Institution,Team Name,Student ID,Class,Department,Group
Badrul Alom,Programming Contest,2026-09-29,ABC University,Team Alpha,2026001,3rd Year,CSE,A
Rahim Ahmed,Programming Contest,2026-09-29,ABC University,Team Beta,2026002,3rd Year,CSE,B
Karim Hasan,Programming Contest,2026-09-29,ABC University,Team Gamma,2026003,4th Year,CSE,A
```

---

## 🚀 কীভাবে ব্যবহার করবেন

### ১. Application চালু করুন

একটি modern web browser-এ:

```text
index.html
```

open করুন।

### ২. CSV প্রস্তুত করুন

উপরের format অনুযায়ী একটি CSV file তৈরি করুন।

### ৩. CSV Upload করুন

Upload area-তে click করুন অথবা CSV file Drag & Drop করুন।

### ৪. Certificate Type নির্বাচন করুন

Available certificate types:

* Participation
* Achievement
* Completion
* Excellence
* Appreciation

### ৫. Design নির্বাচন করুন

আপনার পছন্দের certificate design নির্বাচন করুন।

### ৬. Certificate Customize করুন

আপনি পরিবর্তন করতে পারবেন:

* Text
* Font
* Font size
* Color
* Position
* Rotation
* Image
* Logo
* Line
* Shape
* Background
* Border
* Layer

### ৭. Preview দেখুন

Previous/Next button ব্যবহার করে CSV-এর বিভিন্ন record-এর certificate preview করুন।

### ৮. PDF তৈরি করুন

**Download All Certificates PDF** button-এ click করুন।

Application সব certificate তৈরি করে:

```text
certificates.pdf
```

নামে একটি PDF download করবে।

---

## 🛠️ ব্যবহৃত Technology

এই project-এ ব্যবহার করা হয়েছে:

* HTML5
* CSS3
* JavaScript
* Canvas API
* PapaParse
* jsPDF
* Google Fonts

### External Libraries

**PapaParse 5.4.1**

CSV data parse করার জন্য ব্যবহৃত হয়েছে।

**jsPDF 2.5.1**

PDF generate করার জন্য ব্যবহৃত হয়েছে।

---

## 🏗️ Project Structure

```text
certificate-generator/
│
├── index.html
└── README.md
```

বর্তমান version-টি একটি standalone frontend application হিসেবে কাজ করে।

---

## 🔒 Privacy

Certificate তৈরির workflow-এর সময় application browser-এর মধ্যেই data process করে।

Certificate generation-এর জন্য কোনো backend বা database প্রয়োজন হয় না।

ভবিষ্যতে external service, analytics, API অথবা server-side processing যোগ করা হলে personal/student data ব্যবহারের আগে privacy বিষয়গুলো পর্যালোচনা করা উচিত।

---

## ⚡ Performance

এই generator bulk certificate creation-এর জন্য তৈরি করা হয়েছে এবং বড় CSV dataset নিয়েও কাজ করতে পারে।

তবে অনেক বড় batch generate করার সময় browser memory এবং device performance-এর কারণে generation time পরিবর্তিত হতে পারে।

তাই production-এর আগে ছোট একটি batch দিয়ে test করা ভালো।

---

## 🎯 কোথায় ব্যবহার করা যাবে

এই project ব্যবহার করা যেতে পারে:

* 🏆 Programming Contest
* 🎓 Workshop
* 🧑‍💻 Hackathon
* 🚀 NASA Space Apps / Technology Event
* 🏫 School ও University Event
* 📚 Training Program
* 🎤 Seminar
* 🏅 Competition
* 👥 Volunteer Recognition
* 🎖️ Participation Certificate
* 📜 Completion Certificate
* 🌟 Achievement Certificate

---

## 💡 কাজের ধাপ

```text
CSV
 ↓
Upload
 ↓
Certificate Type নির্বাচন
 ↓
Design নির্বাচন
 ↓
Customize
 ↓
Preview
 ↓
Generate
 ↓
একটি PDF
```

---

## 🧑‍💻 Customization

Developer চাইলে সরাসরি `index.html` থেকে application customize করতে পারবেন।

পরিবর্তন করা যাবে:

* Certificate Design
* Background
* Default Text
* Font
* Color
* Certificate Dimension
* Developer Information
* Language Translation
* PDF Filename
* Default Certificate Type

---

## 🌍 Language Support

Application-এ বর্তমানে রয়েছে:

* 🇬🇧 English
* 🇧🇩 বাংলা

---

## 📌 গুরুত্বপূর্ণ বিষয়

* একটি modern browser ব্যবহার করা recommended।
* Font এবং JavaScript library CDN থেকে load হওয়ার কারণে internet connection প্রয়োজন হতে পারে।
* CSV header অবশ্যই expected column name-এর সাথে মিল থাকতে হবে।
* অনেক বড় batch generate করার আগে ছোট dataset দিয়ে test করা ভালো।
* Original CSV file-এর একটি backup রাখা উচিত।

---

## 🤝 Contributing

এই project-এ contribution স্বাগত।

### Contribution করার ধাপ

1. Repository fork করুন।
2. একটি নতুন branch তৈরি করুন।
3. আপনার পরিবর্তন করুন।
4. Application test করুন।
5. একটি Pull Request তৈরি করুন।

উদাহরণ:

```bash
git clone https://github.com/your-username/one-click-bulk-certificate-generator.git

cd one-click-bulk-certificate-generator
```

এরপর `index.html` browser-এ open করুন।

---

## 📄 License

আপনার পছন্দের open-source license এখানে যোগ করতে পারেন।

উদাহরণ:

```text
MIT License
```

MIT License ব্যবহার করলে repository-তে একটি `LICENSE` file যোগ করুন।

---

## ⭐ Project Support

এই project আপনার certificate generation-এর কাজ সহজ করলে GitHub repository-তে ⭐ Star দিতে পারেন।

---

## 👨‍💻 Developer

এখানে আপনার developer information যোগ করুন:

```text
Name: Md. Badrul Alom
Email: mdbd644@gmail.com
```

---

# 🎓 One-Click Bulk Certificate Generator

**Upload → Customize → Preview → Generate → Download**

Fast এবং flexible bulk certificate generation-এর জন্য তৈরি।
