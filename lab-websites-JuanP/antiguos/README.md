# 🧬 NeuroBio Lab Website

A modern, responsive HTML + CSS template for building a clean and professional website for your scientific or academic lab.

This template is designed for beginners: no frameworks or JavaScript required. Just open, customize, and publish.

---

## 🚀 Features

- Hero header with lab logo and welcome message
- Navigation bar with section links
- Team section with profile photos and roles
- Research project highlights
- Upcoming events or courses
- Contact section with social media icons and links
- Mobile-friendly responsive layout
- Easy to modify and deploy

---

## 📁 Project Structure
lab-website/
├── index.html # Main webpage
├── style.css # CSS file for layout and styling
└── images/ # Store all images here
├── logo.png # Your lab logo
├── ana.jpg # Photo of team member
└── mark.jpg # Photo of team member

---

## ⚙️ Configuration Instructions

Follow these steps to configure and personalize the template:

### 1. Customize the Lab Name and Logo
- Replace `images/logo.png` with your own logo (same filename or update the path in HTML).
- Edit the `<h1>` inside the `<header>` in `index.html` to change the lab name.

### 2. Update Team Members
- Replace or add images inside `/images/` (e.g., `ana.jpg`, `mark.jpg`)
- In the `#team` section of `index.html`, update names, roles, and photos:

```html
<img src="images/ana.jpg" alt="Dr. Ana Rivera" class="team-photo" />
<h3>Dr. Ana Rivera</h3>
<p>Principal Investigator</p>


3. Edit Research Projects
In the #research section, add or modify each project card:

html
Copiar
Editar
<h3>Project Title</h3>
<p>Short description here.</p>
4. Configure Events/Courses
Update the dates and titles in the #events section:

html
Copiar
Editar
<ul>
  <li><strong>Aug 12:</strong> EEG Workshop</li>
  <li><strong>Sep 5:</strong> Machine Learning in Neuroscience</li>
</ul>
5. Set Contact and Social Links
In the #contact section:

Change the email address (lab@example.com)

Update links for Twitter, Facebook, Instagram, LinkedIn

html
Copiar
Editar
<a href="https://twitter.com/yourlab"><i class="fab fa-twitter"></i> Twitter</a>
💻 How to Use Locally
Download or clone this repo to your computer:

bash
Copiar
Editar
git clone https://github.com/yourusername/lab-website.git
Open the folder.

Double-click index.html to preview it in your browser.

You can also use VS Code or another code editor to make changes.

