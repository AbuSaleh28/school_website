# Comprehensive Prompt Guide: AI Agent Specification for a Professional School Website

You are an expert full-stack web developer and UI/UX designer tasked with building a modern, responsive, highly professional, and accessible website for a premier educational institution ("Oakridge International Academy"). 

Please follow the architecture, structural requirements, design system, and content guidelines below to develop the complete website.

---

## 1. Technical & Design Stack Requirements
* **Framework / Language:** HTML5, Tailwind CSS (via CDN for clean styling), and vanilla JavaScript for interactive elements (tabs, mobile navigation toggle, modal forms).
* **Single-File Architecture:** Deliver the entire application as a single, production-ready, clean HTML file containing all structural markup, embedded Tailwind styles/config, and JavaScript logic.
* **Design Aesthetic:** Clean, trustworthy, warm, and professional. 
    * *Primary Palette:* Deep Navy Blue (trust and academic rigor) `#1e3a8a`, Warm Amber/Gold (excellence and warmth) `#d97706`, Slate Gray (neutral body text) `#475569`, and Off-White (backgrounds) `#f8fafc`.
* **Mobile-First & Responsive:** Fully responsive layout with a collapsible hamburger menu for mobile screens and sticky desktop navigation.
* **Accessibility (WCAG 2.1 AA):** High contrast text ratios, explicit `aria-label` attributes on buttons/links, and descriptive `alt` text for all images.

---

## 2. Website Architecture & Page Structure
The website should feature a smooth single-page application (SPA) experience with anchor navigation or a multi-section modular layout containing the following sections:

### **Section A: Global Header & Navigation**
* **Top Utility Bar:** Quick contact phone number, email, emergency alerts banner, and quick-access buttons: `[Parent Portal Login]`, `[Student Login]`.
* **Main Navigation Bar:** 
    * Logo: School Crest/Name ("Oakridge Academy")
    * Menu Links: `Home`, `About Us`, `Academics`, `Admissions`, `Student Life`, `Contact Us`.
    * Prominent CTA Button: `[Apply Now]` (styled in accent amber).

### **Section B: Homepage (Hero & Overview)**
* **Hero Section:** 
    * Compelling headline: *"Empowering Tomorrow’s Leaders Today"*
    * Subheadline: *"A world-class learning environment fostering academic excellence, character, and innovation."*
    * Action CTAs: `[Book a Campus Tour]` and `[Explore Curriculum]`.
    * Background: Placeholder for a vibrant campus video loop or high-resolution slideshow container.
* **Quick Stats Bar:** 
    * 100% University Acceptance Rate
    * 15:1 Student-to-Teacher Ratio
    * 40+ Extracurricular Clubs
    * 50+ Years of Academic Excellence
* **Principal's Welcome:** 
    * Photo placeholder and quote from Dr. Elizabeth Vance (Head of School) emphasizing holistic development and community values.
* **Announcements & News Ticker:** Cards highlighting recent achievements, upcoming open houses, and term dates.

### **Section C: About Us**
* **Mission, Vision, & Core Values:** Cards detailing Integrity, Curiosity, Respect, and Leadership.
* **History & Heritage:** A clean vertical timeline showing key milestones from the school's founding in 1974 to the present day.
* **Leadership & Faculty:** Grid of faculty profiles with headshot placeholders, titles, and department credentials.

### **Section D: Academics**
* **Curriculum Framework:** Overview of educational standards (e.g., STEAM integration, international framework).
* **Grade Level Breakdown (Interactive Tabs):**
    * *Early Years (Kindergarten):* Play-based foundational learning.
    * *Primary School (Grades 1-5):* Core literacy, numeracy, and inquiry-based science.
    * *Middle School (Grades 6-8):* Critical thinking, collaborative projects, and exploratory electives.
    * *High School (Grades 9-12):* Advanced Placement (AP) courses, college counseling, and leadership pathways.

### **Section E: Admissions (Conversion Hub)**
* **Step-by-Step Admissions Process:** Numbered cards (1. Inquire & Tour -> 2. Submit Application -> 3. Assessment & Interview -> 4. Enrollment).
* **Tuition & Fee Structure Overview:** Transparent guidelines with a download link for the detailed fee sheet PDF.
* **Interactive Inquiry / Tour Booking Form:** A fully functional form with fields: Full Name, Parent Email, Phone Number, Grade Applying For, Preferred Tour Date, and Submit Button with success state confirmation.

### **Section F: Student Life & Campus**
* **Extracurricular Activities:** Grid showcasing Robotics Club, Debate Society, Fine Arts, and Athletics.
* **Campus Facilities:** Highlights of modern science labs, Olympic-sized swimming pool, digital library, and safe school transport.
* **Student Success Stories:** Testimonial quotes from alumni attending top-tier universities.

### **Section G: Footer & Contact**
* **Interactive Location & Contact Info:** Address, phone numbers, admissions email, and office hours.
* **Quick Links Footer:** Sitemaps, privacy policy, child safety guidelines, and social media icon placeholders (Facebook, Instagram, YouTube, LinkedIn).
* **Accreditation Badges:** Footer icons indicating educational board accreditations and SSL secure status.

---

## 3. Interactive JavaScript Requirements
* **Mobile Menu Toggle:** Clicking the hamburger icon on mobile screens must slide out or reveal the full navigation menu cleanly.
* **Tab Switcher:** Implement smooth tab-switching logic for the Academics section so users can easily toggle between Early Years, Primary, Middle, and High School details.
* **Form Validation & Submission Simulation:** Validate that required fields in the Admissions Inquiry form are filled out before showing a polite success message ("Thank you! Your tour request has been submitted. Our admissions team will contact you within 24 hours.").

---
*Instructions for AI Agent: Generate clean, well-commented code fulfilling all criteria above without placeholders or missing sections.*