# Brew & Bloom — Artisanal Café & Bakery Website

A responsive, single-page website for **Brew & Bloom**, a modern artisanal café and bakery. This project was developed as a First-Year B.Tech Computer Science and Engineering (CSE) Web Development lab assignment.

---

## 📌 Project Overview

**Brew & Bloom** is designed to provide guests with an inviting digital experience reflecting a warm, cozy café ambiance. The webpage includes handcrafted coffee selections, daily bakery items, savory snacks, chef's specials, verified customer testimonials, operating schedules, and precise location details with an interactive map.

---

## 🚀 Key Sections (In Specified Order)

1. **Sticky Navigation Bar**:
   - Fixed to the top of the viewport during scrolling with a translucent frosted-glass backdrop.
   - Contains café branding logo (`☕ Brew & Bloom`) and smooth-scrolling anchor links: *Home*, *Menu*, *Specials*, *Reviews*, and *Visit Us*.

2. **Hero / Welcome Section**:
   - Full-width hero background banner (`images/hero.jpg`) with a dark dual-gradient overlay for contrast.
   - Welcoming heading, engaging tagline, and call-to-action buttons (*View Menu* and *Find Our Café*).

3. **Menu Section (6 Items across 3 Categories)**:
   - **Coffee**: Classic Double Espresso (₹140), Velvet Cappuccino (₹180)
   - **Bakery**: Artisan Butter Croissant (₹160), Wild Blueberry Muffin (₹150)
   - **Snacks**: Grilled Garden Club Sandwich (₹220), Herb Garlic Sourdough (₹170)
   - Each card features an image, category pill, title, detailed description, and price in Indian Rupees (₹).

4. **Today's Specials**:
   - 3 highlighted cards showcasing signature chef creations: *Spiced Hazelnut Mocha* (₹240), *Berry Custard Danish* (₹210), and *Salted Caramel Waffle* (₹260).
   - Styled with prominent ribbon badges (`★ Special`) and hover elevation.

5. **Customer Reviews**:
   - 3 genuine feedback cards from students and regulars.
   - Includes star rating using `★` characters, customer testimonials, and reviewer avatars.

6. **Opening Hours & Location ("Visit Us")**:
   - **Opening Hours**: Clean HTML table (`<table>`) detailing weekday and weekend operating timings, plus a table reservation inquiry form.
   - **Location**: Café address in Indiranagar, Bengaluru, contact phone (`+91 98765 43210`), official email, and an embedded responsive Google Map iframe.

7. **Footer**:
   - Café brand story, quick navigation links, social media channels (Instagram, Facebook, Twitter), and copyright notice.

---

## 🎨 Design System & Aesthetics

- **Color Palette**:
  - `Deep Espresso Brown` (`#2a1b15`): Headings, navbar brand, and primary footer.
  - `Warm Roast Brown` (`#4a3428`): Subheadings and prominent labels.
  - `Caramel Gold Accent` (`#c07a3e`): Buttons, badges, icons, and interactive accents.
  - `Warm Cream Background` (`#faf5ee` & `#f3eae0`): Soothing base background for eye comfort.
  - `Pure White Cards` (`#ffffff`): Crisp content cards with subtle shadows.
- **Typography (Google Fonts)**:
  - **Heading Font**: `Playfair Display` (Classic, elegant serif)
  - **Body Font**: `Poppins` (Modern, readable sans-serif)
- **CSS Transitions**:
  - Smooth card translation (`transform: translateY(-6px)`) and elevation (`box-shadow`) on hover.
  - Animated underline indicator for navbar links.

---

## 🛠️ Tech Stack & Constraints Followed

- **HTML5**: Semantic tags (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<table>`, `<footer>`).
- **CSS3**: Pure CSS using Flexbox layout, CSS custom properties (variables), and media queries.
- **Zero External Frameworks**: No JavaScript, Bootstrap, or Tailwind CSS used.
- **Responsive Breakpoints**:
  - **Desktop**: 1280px+ (3-column grid)
  - **Tablet**: &le; 768px (2-column flexible grid, stacked navbar)
  - **Mobile**: &le; 480px (Single-column layout, full-width touch targets, no horizontal scroll)

---

## 📁 Project Directory Structure

```text
cafe-website/
│
├── index.html          # Semantic HTML5 single-page structure
├── css/
│   └── style.css       # Well-structured CSS3 stylesheet with organized sections
├── images/             # Café image assets
│   ├── hero.jpg
│   ├── espresso.jpg
│   ├── cappuccino.jpg
│   ├── croissant.jpg
│   ├── blueberry-muffin.jpg
│   ├── club-sandwich.jpg
│   ├── garlic-bread.jpg
│   ├── special-mocha.jpg
│   ├── special-pastry.jpg
│   └── special-waffle.jpg
└── README.md           # Project documentation and run guide
```

---

## 💻 How to Run the Project

1. **Option 1: Direct Browser Launch**
   - Navigate to the `cafe website` folder on your computer.
   - Double-click on `index.html` to open it in any web browser (Google Chrome, Mozilla Firefox, Microsoft Edge, Safari).

2. **Option 2: Live Server (VS Code)**
   - Open the project directory in **Visual Studio Code**.
   - Install the **Live Server** extension (by Ritwick Dey).
   - Right-click `index.html` and click **"Open with Live Server"**.
   - The webpage will open automatically at `http://127.0.0.1:5500/`.

---

## 🧪 Browser Compatibility & Verification

Tested and verified on modern rendering engines:
- Google Chrome (Desktop & Mobile emulation)
- Mozilla Firefox
- Microsoft Edge
- Safari (WebKit)

All sections load seamlessly without horizontal scrollbars at 1280px, 768px, and 375px viewport widths.
