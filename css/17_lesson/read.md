# 📱 Responsive Design Breakpoints – Complete Guide

This `README.md` explains **common media query breakpoints**, **Bootstrap breakpoints**, and **Tailwind CSS breakpoints** in a simple and practical way.

---

## 1️⃣ Common Media Query Breakpoints (CSS)

These are widely used breakpoints based on common device sizes. They work with **pure CSS media queries**.

### 🔹 Standard Breakpoints

| Device Type | Width Range |
|------------|-------------|
| Extra Small (Mobile) | 0 – 575px |
| Small (Large Mobile) | 576px – 767px |
| Medium (Tablet) | 768px – 991px |
| Large (Laptop) | 992px – 1199px |
| Extra Large (Desktop) | 1200px+ |

### 🔹 Example CSS Media Queries

```css
/* Mobile */
@media (max-width: 575px) {
  body {
    background: lightblue;
  }
}

/* Tablet */
@media (min-width: 768px) {
  body {
    background: lightgreen;
  }
}

/* Desktop */
@media (min-width: 1200px) {
  body {
    background: lightcoral;
  }
}
