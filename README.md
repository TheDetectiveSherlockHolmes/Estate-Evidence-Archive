# 🕵️‍♂️ Estate-Evidence-Archive  
### A Frontend Case Study in Real Estate UI Design

This repository contains **DreamHome Real Estate**, a responsive single-page real estate website built as a **capstone project**.  

The goal of this project is to present a clean, modern real estate interface that showcases properties, agents, blog posts, and contact options — all organized like a well-structured **case file** in an evidence archive.

---

## 📁 Project Overview

**EstateEvidenceArchive** is a purely **frontend** implementation (HTML + CSS) of a real-estate landing page that could be used by:

- Real estate agencies  
- Property listing platforms  
- Brokers or independent agents  

The site focuses on:

- Clear visual hierarchy  
- Realistic layout of a real-estate portal  
- Fully responsive design for desktop, tablet, and mobile  

---

## 🧩 Features Implemented

- **Sticky Navigation Bar**
  - Logo + navigation links: Properties, Agents, Why Us, Blog, Contact
  - Mobile-friendly menu icon (for future JS enhancement)

- **Hero Section**
  - Full-width background image with overlay
  - Title & tagline: *“Find Your Home – Discover the best properties for sale and rent”*

- **Search Bar (UI)**
  - Location input
  - Filters for price, bedrooms, and property type  
  > *Note: This is a frontend-only search interface (no backend logic yet).*

- **Property Listings**
  - Grid layout of featured properties
  - Each card includes image, price, title, features (beds, baths, area, location)

- **Property Detail Mock Section**
  - Highlight view of a “Luxury Villa in Miami”
  - Description, features, and price in a two-column layout (image + info)

- **Featured Agents**
  - Cards for 3 agents with photo, role, and short description

- **Why Choose Us Section**
  - Four feature cards:
    - Trusted Experts  
    - 24/7 Support  
    - Wide Selection  
    - Best Deals  

- **Stats Strip**
  - Horizontal stripe with key metrics:
    - Properties Sold  
    - Happy Clients  
    - Years Experience  
    - Expert Agents  

- **Blog Preview Section**
  - Three blog cards with image, heading, short description, and “Read More” links

- **Newsletter Signup**
  - Email input + subscribe button

- **Contact Form**
  - Name, email, subject, message fields
  - “Send Message” button (UI only)

- **Footer**
  - 4 columns: About, Quick Links, Contact, Social Links
  - Footer bottom with © 2024 text

---

## 🛠️ Tech Stack

- **HTML5**
  - Semantic structure for sections: header, hero, sections, footer, forms, etc.

- **CSS3**
  - Custom CSS (no framework)  
  - CSS variables for consistent theming:
    - `--primary`, `--secondary`, `--accent`, `--dark`, `--light`, `--gray`
  - Flexbox and CSS Grid for layout
  - Media queries for responsiveness (`900px`, `768px`, `600px` breakpoints)

- **Fonts & Media**
  - Google Fonts: **Montserrat**
  - External images from Unsplash & RandomUser.me (via direct URLs)

---

## 📂 Project Structure

```bash
Estate-Evidence-Archive/
├── index.html      # Main HTML file
├── styles.css      # Main stylesheet
└── README.md       # Project documentation
