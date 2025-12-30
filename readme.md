# Online Exam Registration Form ✅

**Simple web form** for registering students for online exams. This repository contains the HTML form and styling used for a small demo or class project.

---

## 🔧 Project Structure

- `form.html` — Main registration form (HTML)
- `style.css` — Styles for the form
- `readme.md` — This file

---

## 🧾 Features

- Personal information fields (name, email, phone)
- Gender selection using accessible radio inputs
- Exam type and exam center selection
- File uploads for ID proof and photo
- Declaration checkbox and form submission button

---

## 🚀 Getting Started

### Open locally (quick)
- Double-click `form.html` to open it in your default browser.

### Run a simple local server (recommended for file uploads or testing forms)
- Using Python 3 (Windows PowerShell):

```powershell
# from the project folder
python -m http.server 8000
# then open http://localhost:8000/form.html
```

---

## ✅ Notes & Accessibility
- Labels are properly associated with each radio input for the **Gender** field so clicking the labels selects the appropriate option.
- For improved accessibility consider wrapping each radio in a `<label>` element and adding keyboard focus styles.

---

## 🧪 Testing
- Open `form.html` and try selecting gender options by clicking the labels and using the keyboard (Tab + Arrow keys).
- Try submitting the form (this project uses `action="#"` by default). If you want form processing, connect a backend or change `action` to your endpoint.

---

## 🤝 Contributing
- Feel free to open issues or submit a pull request with improvements (styling, validation, accessibility fixes).

---

## 📄 License
- This project is free to use and modify — add a license file if you need a specific license.

---

If you'd like, I can add accessibility improvements, client-side validation, or a demo server endpoint for testing submissions.
