# Multi Password Strength Checker with PDF Report

A simple, lightweight web app to check the strength of multiple passwords, give detailed improvement advice, and generate a downloadable PDF report summarizing all password checks.

---

## Features

- Check up to 15 passwords one by one
- Instant feedback: password status (Strong/Weak) with reasons
- Download a comprehensive PDF report summarizing all passwords checked
- Runs entirely in the browser — no server needed
- Clean and minimal UI with clear advice

---

## How to Use

1. Open `multi_password_checker.html` in any modern web browser (Chrome, Firefox, Edge).
2. Enter your password in the input box.
3. Click **Check Password** to get strength results and tips.
4. Repeat for up to 15 passwords.
5. After 15 passwords, the PDF report downloads automatically.
6. Or click the **Download Report** button anytime after checking at least one password.

---

## Password Strength Criteria

- Minimum 8 characters
- Contains uppercase letters
- Contains lowercase letters
- Contains numbers
- Contains special characters (e.g., !, @, #, $)

If your password meets at least 4 out of 5 criteria, it is considered **Strong**.

---

## Tech Stack

- HTML, CSS, JavaScript
- [jsPDF](https://github.com/parallax/jsPDF) library for PDF generation (loaded via CDN)

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Author

 Pusarla Vinay

---

## Feel free to open issues or submit pull requests to improve this project!
