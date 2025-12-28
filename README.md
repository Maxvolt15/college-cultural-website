# Verbena Cultural Committee Website

[![Netlify Status](https://api.netlify.com/api/v1/badges/b5c7e3a9-1a2b-4c5d-6e7f-8g9h0i1j2k3l/deploy-status)](https://warm-otter-897929.netlify.app/)

## 📖 Project Overview

This repository hosts the official website for the **Verbena Cultural Committee** of Techno India Hooghly. Originally developed in 2021, this platform serves as the digital face of the committee, dedicated to promoting and archiving cultural activities within the college.

Since its inception in 2006, the Verbena Committee has been responsible for organizing major campus events such as **Teacher's Day**, **Fresher's Welcome**, and the **Annual Cultural Fest**. This website was designed to showcase these vibrant moments, introduce the committee members, and provide a channel for students and faculty to connect with the organizers.

**Live Demo:** [https://warm-otter-897929.netlify.app/](https://warm-otter-897929.netlify.app/)

---

## ✨ Key Features

- **Dynamic Event Showcase:** A visually engaging landing page featuring a carousel of upcoming and past events (e.g., The Anupam Roy Band performance).
- **Immersive Galleries:** Dedicated sub-pages for specific events (15th August, Blood Donation Camps, Sports) equipped with **Lightbox** integration for a seamless photo viewing experience.
- **Committee Member Directory:** A specialized section profiling the team behind the events, fostering transparency and connection.
- **Interactive Contact Forms:** Integrated PHP-based forms allowing visitors to send inquiries or book event tickets/tables directly through the site.
- **Responsive Design:** Fully optimized for desktops, tablets, and mobile devices using the **Bootstrap** framework.
- **User Portal Prototype:** Includes frontend templates for Login and Registration pages (UI/UX demonstration).

---

## 🛠 Tech Stack

### Frontend

- **Core:** HTML5, CSS3, JavaScript (ES6+)
- **Framework:** [Bootstrap 5](https://getbootstrap.com/) (Grid system, Components)
- **Styling:** Custom CSS with [SCSS](https://sass-lang.com/) assets
- **Animations:** [Animate.css](https://animate.style/) for entry/exit transitions

### Libraries & Plugins

- **[Swiper.js](https://swiperjs.com/):** For touch-enabled, responsive sliders (Hero section).
- **[GLightbox](https://github.com/biati-digital/glightbox):** A pure JavaScript lightbox for the gallery.
- **[Isotope](https://isotope.metafizzy.co/):** For filtering and sorting gallery items.

### Backend

- **Language:** PHP (v7.4+)
- **Functionality:** Server-side handling of contact forms and email dispatch via `PHP Email Form` library.

---

## 🏗 Project Architecture

The project follows a **Multi-Page Application (MPA)** architecture where distinct sections of the site exist as separate HTML files, linked together by a central navigation system.

```plaintext
root/
├── index.html              # Main Landing Page (Hero, About, Events)
├── contact_us.html         # Contact Page
├── gallery/                # Gallery Module
│   ├── 15th_gallery.html   # Specific Event Page
│   ├── lightbox.css        # Gallery-specific styles
│   └── ...
├── home/                   # Core Assets & Backend
│   ├── assets/             # Global CSS, JS, Vendor Libraries (Bootstrap, etc.)
│   └── forms/              # PHP Scripts for form handling (contact.php)
├── members page/           # Member Directory Module
└── img/                    # Centralized Media Repository (Organized by event)
```

- **Separation of Concerns:** Assets are categorized into `css`, `js`, and `vendor` directories within `home/assets/`.
- **Modular Content:** Each major event has its own dedicated directory or HTML file within `gallery/` to maintain organized content.

---

## 🚀 Installation & Setup

To run this project locally, especially to test the PHP forms, you will need a local server environment.

### Prerequisites

- **Git**
- A local web server with PHP support (e.g., **XAMPP**, **MAMP**, or **Apache**).

### Steps

1. **Clone the Repository**

    ```bash
    git clone https://github.com/YOUR_USERNAME/verbena-committee-website.git
    ```

2. **Move to Web Server Directory**
    - If using XAMPP, move the project folder to `C:\xampp\htdocs\verbena-website`.
    - If using MAMP, move to `/Applications/MAMP/htdocs/verbena-website`.

3. **Configure PHP Mailer (Optional)**
    - Open `home/forms/contact.php`.
    - Update the `$receiving_email_address` with your actual email.
    - *(Advanced)* Uncomment and configure the SMTP settings if your local server doesn't support `mail()`.

4. **Run the Project**
    - Start your local server (Apache).
    - Open your browser and navigate to `http://localhost/verbena-website/index.html`.

*Note: If you only want to view the UI (without working forms), you can simply open `index.html` in any browser.*

---

## 🤝 Contributing

Contributions to improve the site or update gallery content are welcome!

1. **Fork** the repository.
2. Create a **Feature Branch** (`git checkout -b feature/NewGallery`).
3. **Commit** your changes (`git commit -m 'Added photos for 2025 Fest'`).
4. **Push** to the branch (`git push origin feature/NewGallery`).
5. Open a **Pull Request**.

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
