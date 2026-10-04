# Fita Dwi Oktavia — Personal Portfolio

A responsive personal portfolio website for **Fita Dwi Oktavia**, an Electrical Automation Engineering graduate with interests and hands-on experience in robotics, automation, artificial intelligence, industrial data acquisition, networking, and engineering systems.

The website is designed with a clean **white + sky blue** visual theme and uses **Poppins** throughout the interface.

## ✨ Features

- Responsive design for desktop, tablet, and mobile
- Personal landing page with profile photo
- About / profile section
- Educational background
- Work experience
- Project showcase
- Skills and competencies
- Organization and committee experience
- Achievements
- Direct email contact
- Direct WhatsApp contact
- LinkedIn profile link
- Smooth scrolling navigation
- Scroll reveal animations
- Mobile navigation menu
- Single-file website architecture

## 🧰 Technologies

- HTML5
- CSS3
- JavaScript
- Google Fonts — Poppins

No framework or build process is required.

## 📁 Project Structure

```text
portfolio/
├── index.html
└── README.md
```

The portfolio is intentionally built as a **single `index.html` file**. The profile photo is embedded directly into the HTML, so no separate image file is required for the current version.

## 🚀 Run Locally

You can simply open `index.html` in a web browser.

Alternatively, run a local server from the project directory:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## 🌐 Deploy with GitHub Pages

### 1. Create a repository

Create a new GitHub repository, for example:

```text
fita-dwi-oktavia.github.io
```

### 2. Upload the files

Upload:

```text
index.html
README.md
```

to the root of the repository.

### 3. Enable GitHub Pages

Go to:

**Repository → Settings → Pages**

Under **Build and deployment**:

- Source: `Deploy from a branch`
- Branch: `main`
- Folder: `/ (root)`

Click **Save**.

After GitHub finishes deploying the repository, the portfolio can be accessed through the GitHub Pages URL.

## 📬 Contact Integration

The portfolio includes direct contact buttons:

### Email

The **Email Me** and **Start a Conversation** buttons use a `mailto:` link and open the user's default email application.

### WhatsApp

The **WhatsApp** buttons use a `wa.me` link and open a WhatsApp conversation directly.

### LinkedIn

The LinkedIn button links to:

`https://linkedin.com/in/fita-oktavia/`

## 🎨 Design

The visual direction is based on:

- **Primary:** Sky Blue
- **Secondary:** White
- **Accent:** Deep Blue
- **Typography:** Poppins
- **Style:** Minimal, modern, clean, engineering/technology-oriented
- **Layout:** Responsive card-based sections
- **Interaction:** Hover effects, smooth scrolling, and reveal animations

## 📌 Portfolio Sections

### 01 — About

Includes profile summary, educational background, interests, and professional strengths.

### 02 — Experience

Includes:

- PT. Bintang Toedjoe (Kalbe Group) — Operational Technology
- NTT DATA — Network Engineering Division
- ROBOKidz Computer and Robotics Learning Center — Education Training

### 03 — Projects

Includes projects related to:

- Industrial Andon System Data Acquisition
- Juniper Switch Device Monitoring
- Inventory Warehouse Management System
- Deep Learning-Based Automatic Waste Sorting
- Sensor Data Acquisition & Monitoring Application
- YOLO-Based Shrimp Seed Detection & Counting
- IoT-Based Smart Vertical Garden

### 04 — Skills

Includes competencies in:

- Network installation and configuration
- Cisco and Juniper networking
- Industrial automation
- Data acquisition
- Machine learning
- YOLO and LSTM
- Web development
- C# / .NET
- Go
- PostgreSQL / MySQL
- Node-RED
- MQTT
- Project management
- Problem solving
- Communication
- Teamwork

### 05 — Achievements

Highlights academic, innovation, essay, paper/poster, and entrepreneurship achievements.

### 06 — Organizations & Committees

Includes laboratory, robotics competition, project management, and entrepreneurship activities.

### 07 — Contact

Provides direct contact options through email, WhatsApp, and LinkedIn.

## ✏️ Customization

To update the portfolio, edit `index.html`.

Common sections that can be customized:

```text
Personal information
Profile description
Education
Work experience
Projects
Skills
Achievements
Organizations
Email
WhatsApp number
LinkedIn URL
```

### Updating the profile photo

The current profile photo is embedded as Base64 inside `index.html`.

If you want to replace it, the easiest approach is to update the embedded image data or modify the HTML to reference an external image file.

## 📄 Source

Portfolio information is based on the provided Curriculum Vitae of **Fita Dwi Oktavia**.

## 📜 License

This portfolio is a personal website.

You may use the structure and implementation as a reference, but personal information, profile photo, contact information, and portfolio content belong to the portfolio owner.

---

**Built with HTML, CSS, JavaScript & ☁️ curiosity.**
