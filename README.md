# 📧 Mass‑Mail Dispatcher

## Overview

**Mass‑Mail Dispatcher** is a web‑based system that automates composing, personalizing, validating, and sending bulk emails efficiently. It supports CSV import, email validation, and SMTP dispatch to streamline campaigns or transactional mail.

---

## 🛠️ Features

- **CSV Upload & Parsing**: Upload lists of email addresses.
- **Email Validation**: Separates valid and invalid addresses before dispatch.
- **Personalized Mailer UI**: Input sender, subject & body in one form.
- **Bulk Email Dispatch**: Uses SMTP.js via ElasticEmail for dispatch.
- **Realtime Metrics**: Tracks count of valid/invalid & sent emails.
- **UX Enhancements**: Smooth navigation, scroll-to-buttons, animations (Animate.css, Wow.js).
- **Responsive Design**: Built with HTML/CSS, Font Awesome icons.

---

## 🧩 Tech Stack

| Area             | Technology / Library        |
|------------------|-----------------------------|
| Frontend         | HTML5, CSS3                 |
| Layout & Icons   | Font Awesome, Animate.css, Wow.js |
| Scripting        | Vanilla JavaScript, SMTP.js |
| Email Delivery   | ElasticEmail SMTP Relay     |

---

## 📁 Repository Structure

mass-mail-dispatcher/
├── index.html # Main UI layout
├── style.css # Styles and design
├── main.js # CSV, validation, UI logic
├── smtp.js # SMTP.js integration
└── README.md # Project documentation


---

## 🚀 Setup and Execution

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/mass-mail-dispatcher.git
    cd mass-mail-dispatcher
    ```

2. **Important**: Edit `smtp.js` credentials (ElasticEmail SMTP host, username & password).
3. **Open** `index.html` in your browser — no server required.
4. Upload a `.csv` file of emails (one-per-line).
5. Compose your email (from, subject, body) and click **Send**.
6. Sent count appears in an alert; valid/invalid lists shown in real time.

---

## 📊 CSV Format

CSV should list email IDs in a single column, one per row:

alice@example.com
bob@example.com
charlie@example.org


---

## 🔐 Security & Best Practices

- 🔑 **Never expose your SMTP credentials** in client-side code.
- ✅ Use a backend proxy to **secure credentials** and avoid client-side exposure.
- ✔️ Implement server-side **authentication**, CSRF protection, and **rate-limiting** before production deployment.

---

## 📈 Future Enhancements

- ✅ **Server-Side Email Dispatch** using Node.js, Express, or Django.
- ✅ **User Auth & Management** via login/registration.
- ✅ **Email Templating & Personalization** using placeholders per recipient.
- ✅ **Delivery Reports** (opens, clicks) via SMTP logs or API.
- ✅ **Retry/Throttle Controls** for large campaigns.
- ✅ **Bounce & Complaint Handling** (via Webhooks).
- ✅ **Scheduler & Campaign Dashboards** for campaign management.

---

## 📝 Use Cases

- Newsletter distributions
- Event announcements
- Transactional alerts (password resets, confirmations)
- Promotional and marketing mailers

---

## 🧑‍💻 Author

**Hima Shaju** — Student, Dept. of CSE (AI & ML),  
Global Academy of Technology, Bengaluru

---

## 📌 License

This project is for **academic and educational use**. Please seek permission before commercial deployment.

---

## 📨 Feedback

Feel free to report issues or suggest enhancements under the **Issues** tab or by contacting me at **himashaju77@gmail.com**.

