# 📚 Classor

**Classor** is a lightweight, modern study planner designed for students to organize their school life in one place.

It provides a Persian (RTL) interface with a Jalali calendar, homework management, weekly class scheduling, activities, and local data backup — all inside a single HTML file.

---

## ✨ Features

### 📅 Jalali Calendar

* Full Persian/Jalali calendar
* Month navigation
* Current date highlighting
* Leap-year support
* Gregorian ↔ Jalali date conversion
* Calendar-based activity and homework management

### 📝 Homework Management

* Add homework
* Edit existing homework
* Delete homework
* Mark homework as completed
* Filter by:

  * All
  * Pending
  * Completed
* Set:

  * Subject
  * Description
  * Due date

### 🗓️ Weekly Class Schedule

* Create a weekly school timetable
* Add and remove class periods
* Configure active school days
* Organize subjects throughout the week

### 🎯 Activities

* Add personal or school activities
* Set date and time
* Assign a subject
* Mark activities as completed
* Edit and delete activities

### 💾 Backup & Restore

* Export your planner data as JSON
* Import a previous backup
* Restore your data whenever needed
* Reset all local data

---

## 🎨 UI & UX

Classor is designed with a clean and student-friendly interface.

* 🇮🇷 Persian RTL layout
* 📱 Responsive design
* 🖥️ Desktop-friendly interface
* 📲 Mobile bottom navigation
* 🌙 Automatic dark-mode support
* ♿ Accessibility-focused interactions
* 🔔 Toast notifications
* ↩️ Undo support after deleting items
* 🎛️ Modal and bottom-sheet interfaces
* ⌨️ Keyboard-friendly focus states

---

## 🛠️ Technologies

Classor intentionally uses a simple, dependency-light architecture:

* **HTML5**
* **CSS3**
* **Vanilla JavaScript**
* **SVG**
* **Web Storage / LocalStorage**
* **HTML `<dialog>`**
* **Responsive CSS**
* **Jalali calendar algorithms**

No frontend framework is required.

There is also no backend server or database.

---

## 🧠 Jalali Calendar

Classor includes its own Jalali calendar implementation in JavaScript.

The application handles:

* Jalali → Gregorian conversion
* Gregorian → Jalali conversion
* Jalali leap years
* Month lengths
* Calendar calculations

This allows the planner to work naturally with the Persian calendar without relying on a calendar library.

---

## 📦 Project Structure

The project is intentionally kept simple:

```text
Classor/
│
├── index.html
└── README.md
```

The main application contains the HTML, CSS, and JavaScript required to run Classor.

---

## 🚀 Getting Started

### Option 1 — Run Locally

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/classor.git
```

Open the project directory and launch:

```text
index.html
```

No installation or build process is required.

### Option 2 — GitHub Pages

Because Classor is a static web application, it can be deployed directly using **GitHub Pages**.

Simply enable GitHub Pages for the repository and use the branch containing `index.html` as the deployment source.

---

## 💾 Data Storage

Classor stores planner data locally in the browser.

This includes information such as:

* Weekly schedule
* Homework
* Activities
* Active school days
* Backup information

Because the application uses browser storage, the data remains on the user's device rather than being sent to a remote server.

> **Important:** Clearing browser/site data can remove locally stored planner information. Use the built-in backup feature to keep a copy of your data.

---

## 🔐 Privacy

Classor is designed as a local-first application.

There is no account system, backend API, or remote database required to use the planner.

Your planner data is stored locally in the browser.

---

## 📱 Responsive Design

Classor adapts to different screen sizes:

* Desktop
* Laptop
* Tablet
* Mobile

On smaller screens, the navigation changes into a mobile-friendly bottom navigation interface.

---

## 🧩 Architecture

Classor follows a simple single-page architecture.

The application is divided conceptually into:

```text
UI
├── Calendar
├── Homework
├── Weekly Schedule
├── Activities
├── Backup / Restore
└── Notifications

Application Logic
├── Date & Calendar Logic
├── Homework State
├── Schedule State
├── Activity State
└── Local Storage

Persistence
└── Browser LocalStorage
```

This keeps the project easy to understand, modify, and deploy.

---

## 🗺️ Roadmap

Possible future improvements include:

* [ ] Cloud synchronization
* [ ] User accounts
* [ ] Multi-device synchronization
* [ ] Notifications and reminders
* [ ] More calendar customization
* [ ] Advanced statistics
* [ ] PWA installation support
* [ ] Offline-first improvements
* [ ] More personalization options

---

## 🤝 Contributing

Contributions, ideas, and improvements are welcome.

If you find a bug or have an idea for a new feature:

1. Open an issue.
2. Describe the problem or idea.
3. Provide screenshots or reproduction steps when useful.
4. Submit a pull request for improvements.

---

## 📄 License

No specific open-source license has been defined for this project yet.

If you plan to publish Classor as an open-source project, consider adding an appropriate license such as MIT.

---

## ❤️ About Classor

Classor was created with a simple goal:

> **Make organizing school life easier, clearer, and more enjoyable for students.**

Instead of managing homework, classes, and activities across multiple apps or notebooks, Classor brings them together into one focused student planner.

---

**Made with ❤️ for students.**
