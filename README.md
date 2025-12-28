# Verbena Committee Website

## Project Overview
This repository contains the source code for the official website of the **Verbena Committee**. The platform serves as a digital hub for the committee's cultural activities, showcasing events, member portfolios, and galleries. It facilitates user engagement through contact forms and provides a central location for committee updates.

**Live URL:** [https://warm-otter-897929.netlify.app/](https://warm-otter-897929.netlify.app/)

## Features
- **Event Galleries:** Dedicated photo galleries for major events (e.g., 15th August, Blood Donation Camps, Sports).
- **Member Directory:** A section profiling committee members.
- **User Authentication:** Login and Registration pages for member/user access.
- **Interactive UI:** Smooth animations, responsive sliders, and lightbox integrations for media viewing.
- **Contact Forms:** Integrated PHP forms for inquiries and table bookings.

## Technologies Used
- **Frontend:**
  - HTML5 & CSS3
  - [Bootstrap](https://getbootstrap.com/) (Responsive Framework)
  - [Animate.css](https://animate.style/) (Animations)
  - JavaScript (ES6+)
- **Libraries & Plugins:**
  - [Swiper](https://swiperjs.com/) (Touch Slider)
  - [GLightbox](https://github.com/biati-digital/glightbox) (Media Lightbox)
- **Backend:**
  - PHP (Form handling)

## Installation
To run this project locally:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/YOUR_USERNAME/verbena-committee-website.git
   ```
2. **Navigate to the project directory:**
   ```bash
   cd verbena-committee-website
   ```
3. **Launch the project:**
   - Open `index.html` directly in your browser.
   - OR use a local development server (e.g., Live Server in VS Code):
     ```bash
     # If you have Python installed
     python -m http.server 8000
     ```

## Usage
- **Home Page:** Access via `index.html`. Navigation to all other sections is available here.
- **Galleries:** Navigate to the `gallery/` folder or click through the gallery links on the homepage to view specific event photos.
- **Forms:** Note that the PHP contact forms in `home/forms/` require a PHP-enabled server (like Apache/XAMPP) to function correctly locally.

## Deployment
This project is currently deployed on Netlify.
- **Build Settings:** Static HTML/CSS site.
- **Publish Directory:** `/` (Root)

## Contributing
Contributions are welcome!
1. Fork the repository.
2. Create a new Feature Branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request.

## License
Distributed under the MIT License. See `LICENSE` for more information.
