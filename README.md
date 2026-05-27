# Laptop-showcase-website
Best way to find best product
# Meenish Tech Arena 💻🔥

A modern laptop showcase website built using HTML and CSS featuring laptop cards, specifications tables, customer reviews, pricing sections and responsive design.

---

# Features

- Sticky navigation bar
- Hero section
- Laptop showcase cards
- Specifications table
- Customer review cards
- Contact form
- Responsive layout
- Hover effects
- Modern tech UI

---

# Technologies Used

- HTML5
- CSS3

---

# Folder Structure

```text
LaptopShowcase/
│
├── laptop.html
├── README.md
```

---

# How To Run

Step 1:

Download or clone project

Step 2:

Open project folder

Step 3:

Open:

```text
laptop.html
```

using:

- Chrome
- Edge
- Firefox

Website runs directly in browser.

---

# Project Structure

## Navigation Bar

```html
<header>

<nav>

Home
Laptops
Reviews
Contact

</nav>

</header>
```

Purpose:

Navigation allows users to move through website sections.

Concept used:

```css
position:sticky;
top:0;
```

Sticky navigation stays visible while scrolling.

---

# Hero Section

Hero section is the top large section of website.

Contains:

- Website title
- Slogan
- Banner image
- Description
- Buttons

Example:

```text
Meenish Tech Arena

Power • Performance • Innovation

Image

Explore Laptops
Buy Now
```

---

# Laptop Cards

Example:

```html
<div class="laptop-card">

Image

ASUS ROG Strix

Gaming Laptop

₹1,29,999

Buy Now

</div>
```

Purpose:

Displays laptops in organized cards.

Concept used:

```css
display:grid;
```

Cards align automatically.

---

# Grid Layout

```css
.laptop-grid{

display:grid;

grid-template-columns:
repeat(auto-fit,minmax(250px,1fr));

}
```

Purpose:

Automatically creates card layout.

Example:

```text
□ □ □

□ □ □
```

---

# Hover Effects

```css
.laptop-card:hover{

transform:translateY(-10px);

}
```

Purpose:

Card moves upward when mouse hovers.

Makes website interactive.

---

# Specifications Table

Columns:

- Laptop
- Processor
- RAM
- Storage

Purpose:

Displays technical details.

Example:

```text
ROG | i9 | 32GB | 1TB SSD

MacBook | M4 | 16GB | 512GB
```

---

# Customer Reviews

Example:

```html
<div class="review-card">

⭐ Amazing service

</div>
```

Purpose:

Shows customer feedback.

---

# Contact Form

Fields:

- Name
- Email
- Laptop Choice
- Message

Concepts used:

```html
<input>

<select>

<textarea>
```

Purpose:

Collect customer inquiries.

---

# CSS Concepts Learned

margin

Space outside elements

padding

Space inside elements

border-radius

Rounded corners

display:flex

Row/column layouts

display:grid

Card layouts

hover

Interactive effects

object-fit:cover

Prevents image stretching

position:sticky

Sticky navigation

---

# Areas I Need To Improve

- CSS Grid mastery
- Responsive design
- JavaScript
- Better UI design
- Flexbox mastery

---

# Future Improvements

- Search laptops
- Shopping cart
- Product filtering
- Dark/light mode
- JavaScript validation

---

# What I Learned

Through this project I practiced:

- Hero sections
- Navigation bars
- Product cards
- Tables
- Forms
- CSS Grid
- Website structure
- Better naming conventions

---

# Author

Meenish
