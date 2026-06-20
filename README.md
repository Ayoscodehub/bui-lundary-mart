[README-1.md](https://github.com/user-attachments/files/29158182/README-1.md)
# bui-lundary-mart# 🧺 BU Laundry Mart

> A full-featured laundry management web app built for Bowen University students.

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)

---

## ✨ Features

### 🔐 Authentication
- Phone-based sign up with **OTP verification** (Twilio-ready)
- Two account types at registration: **Student** or **Laundry Staff**
- Persistent sessions via **localStorage** — stay logged in on refresh
- Secure login with phone + password validation

### 🎓 Student Dashboard
- **Place Orders** — choose wash type (Standard / Express / Dry Clean), quantity, and hostel room
- **Live price estimate** — auto-calculated before submission
- **Order tracking** — real-time status (Pending → Washing → Ready → Collected)
- **Receipts** — itemised breakdown for completed orders
- **Real-time chat** — message laundry staff directly about your order

### 👕 Staff Dashboard
- **Incoming orders view** — new orders highlighted for quick action
- **Status management** — update any order from Pending to Collected inline
- **Revenue tracking** — see total earnings from collected orders
- **Student chat** — reply to student messages in real time

---

## 🛠 Tech Stack

| Layer | Technology |
|---|---|
| Frontend | HTML5, CSS3, Vanilla JavaScript |
| UI Framework | React *(extended version)* |
| Mobile | Flutter / Dart *(mobile build)* |
| SMS/OTP | Twilio *(backend integration ready)* |
| Storage | localStorage (frontend), Node.js backend *(planned)* |
| Typography | Bebas Neue + Inter |

---

##  Getting Started

### Run locally
```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/bu-laundry-mart.git

# Open in browser — no build step needed
open index.html
```

### Demo accounts
You can create accounts directly in the app. Two roles are available:

| Role | What to select |
|---|---|
| 🎓 Student | Select "Student" on sign up, enter matric number |
| 👕 Staff | Select "Laundry Staff" on sign up |

The OTP code is displayed on screen for demo purposes.

---

## 📁 Project Structure

```
bu-laundry-mart/
├── index.html          # Main app (single-file build)
├── README.md           # This file
└── assets/             # Images and icons (coming soon)
```

---

##  Roadmap

- [ ] Node.js + Express backend
- [ ] Live Twilio OTP integration
- [ ] Push notifications for order status updates
- [ ] Flutter mobile app (iOS & Android)
- [ ] Admin analytics dashboard
- [ ] Payment integration (Paystack)

---

## 👨‍💻 Author

**Jonathan Olutoye**
Software Engineering Student · Bowen University · Class of 2029
JavaScript Specialist

---

## 📄 License

MIT License — feel free to use and build on this project.
roject.
