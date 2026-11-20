# 📝 Smart Notes

> 🎓 Software Engineering project (**CSE315**), Department of CSE, Daffodil International University · Team of 5

A lightweight note-taking web app with user accounts, a built-in calculator and a dark mode. It runs entirely in the browser: no server and no installation needed.

🌐 **Try it live:** https://inglorious-star.github.io/Smart-Note-Taking-Webapp/

---

## ✨ Features

- 👤 **Sign up and log in** with a username and password (passwords are stored as SHA-256 hashes)
- 🔑 **Forgot password** reset for an existing username
- 📝 **Create, view, edit and delete notes**, each with a heading and content
- 🔍 **Search** your notes by heading
- 🕒 Created / updated **timestamps** on every note
- 🧮 **Floating calculator** you can open next to your notes
- 🌙 **Dark / light theme**, remembered between visits
- 💾 **Stays logged in** until you press Logout
- 📱 **Responsive layout** for desktop and mobile

---

## ▶️ How to use

1. Open the [live app](https://inglorious-star.github.io/Smart-Note-Taking-Webapp/), or download `index.html` and open it in any modern browser.
2. Type a username and password and click **Signup** (next time, click **Login**).
3. Write a heading and content, then click **Save Note**.
4. Click a heading or **Edit** to change a note, **View** to read it, or **Delete** to remove it.
5. Use **🧮 Calculator** and **🌙 Theme** in the top bar any time.

---

## 🛠️ Built with

- **HTML5** and **CSS3** (CSS variables, Grid, Flexbox, responsive media queries)
- **JavaScript** (vanilla, no frameworks)
- **localStorage** for saving users and notes in the browser
- **Web Crypto API** for SHA-256 password hashing

## 🧠 How it works

- All data is stored in your browser's `localStorage`, under each user's own record.
- Each note has an id, heading, content and created/updated timestamps.
- On login the entered password is hashed and compared with the stored hash.
- Note headings are escaped before display, so typed HTML can't run as code.

## 🚧 Limitations

- Data lives only in the browser where it was created: notes don't sync between devices, and clearing browser data deletes them.
- Because there is no server, accounts are local to that browser. "Forgot password" works without email verification, so this app is a learning project, not a place for sensitive notes.

## 🔮 Future improvements

- [ ] Backend database and real authentication (e.g. Firebase or Node.js)
- [ ] Note categories, tags and pinning
- [ ] Export notes to PDF or text
- [ ] Rich text formatting

---

## 📄 Documentation

- [Project report](Smart_Note_App_Project_Report.pdf): user stories, requirements, use case, activity, sequence and class diagrams, BPMN, COCOMO cost estimation, SQA and testing

---

## 👥 Team

- Fahim Montasir ([@inglorious-star](https://github.com/inglorious-star))
- Mubas Sera Noon
- Md Ibna Labid
- Mahmudul Hasan ([@mahmudulhasanprotik47](https://github.com/mahmudulhasanprotik47))
- Md Rizwan Karim Lam
