# Grid Layout 1.1 - Flexbox Sidebar Layout

This project demonstrates a **responsive web layout** using **Flexbox** to build a simple sidebar and main content area. It’s ideal as a starter layout for admin panels, dashboards, or content-heavy pages.

## 🔧 Technologies Used

- **HTML5**
- **CSS3 (Flexbox)**
- Responsive Design with **Media Queries**

## 📁 File Structure

/project-folder
│
├── index.html # Main HTML file
├── css/
│ └── flexboxlayout1.css # Stylesheet for layout and responsive design

markdown
Copy
Edit

## 🧱 Layout Description

- **Sidebar (`<aside>`):**
  - Fixed width (`250px`)
  - Contains a vertical menu list
  - Dark background with hover effects
- **Main Content (`<main>`):**
  - Flexible width (`flex: 1`)
  - Scrollable if content overflows
  - Contains sample content for demonstration

## 📱 Responsive Behavior

- At screen widths **≤768px**:
  - The `.container` switches to a **column layout**
  - The **sidebar is hidden** to prioritize main content

## 🖥️ Preview

![Desktop View](https://via.placeholder.com/800x400?text=Desktop+View)  
_Sidebar visible on large screens_

![Mobile View](https://via.placeholder.com/400x600?text=Mobile+View)  
_Sidebar hidden on smaller screens_

> Replace the image URLs with your own screenshots if needed.

## 🚀 How to Use

1. Clone or download this project.
2. Open `index.html` in your browser.
3. Modify content as needed for your use case (e.g. admin panel, profile settings, blog layout, etc).

## 📌 Note

- The layout is made using **Flexbox**, not CSS Grid, despite the name "Grid Layout 1.1".
- This is intentional and serves as a learning base for combining layout systems.

## ✍️ Author

Created with 💻 by [Toni wicaksono]

---
