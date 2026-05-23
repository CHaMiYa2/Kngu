# Kngu — Flowers & Bouquets

Kngu is a premium, modern, and fully responsive e-commerce landing page designed for a boutique flower and bouquet shop. It provides a visually stunning user experience showcasing floral arrangements, gifts, seasonal collections, and customer stories.

## 🌸 Features

- **Sticky Navigation**: A clean, responsive header that shrinks and shadow-fades upon scrolling. Includes multi-level dropdowns for *Shop*, *Blog*, and *Pages* alongside a mobile-friendly slide-out drawer menu.
- **Announcement Bar**: An dismissible banner at the very top of the page highlights active promotions.
- **Dynamic Hero Slider**: An interactive, touch-friendly carousel displaying major promotional collections (e.g., Mother's Day, Valentine's Day, Spring Collection) with slide-in typography and custom SVG controls.
- **Store Badges**: Visual highlights showcasing key benefits such as *Free Delivery*, *Online Order*, *Guaranteed Freshness*, and *Artisan Design*.
- **Interactive Product Catalog**: A dynamic grid layout highlighting products with ratings, pricing, discounts, and hover-triggered interaction effects.
- **Customer Testimonials**: A responsive slider showcasing customer reviews and ratings.
- **Social Media Hub**: An styled Instagram integration layout that reveals hovering details and links to social channels.

## 🛠️ Technology Stack

- **Markup & Layout**: Semantic HTML5 structures.
- **Styling**: [Tailwind CSS](https://tailwindcss.com) (loaded via CDN) configured with a custom color palette (Primary Rose, Accent Yellow-Orange, and Muted Grays) and premium fonts:
  - *Playfair Display* (for elegant, editorial headings)
  - *Lato* (for clean, readable body copy)
- **Interactions**: Vanilla JavaScript for handling sliders, menus, close buttons, and pagination dots.

## 🚀 How to Run

Since this is a client-side static web application, you do not need to install any servers or dependencies. 

1. **Directly in Browser**:
   Double-click the `index.html` file or drag it into any modern web browser to open it locally.

2. **Using a Local Server**:
   To run it with a proper local server environment (highly recommended for performance and asset path resolution):
   - **VS Code**: Install the **Live Server** extension, open the project folder, and click **Go Live** in the status bar.
   - **Python**: Run the following command in your terminal from the project folder:
     ```bash
     python -m http.server 8000
     ```
     Then navigate to `http://localhost:8000`.
   - **Node.js (npx)**: Run:
     ```bash
     npx serve
     ```

## 📁 Project Structure

```text
Kngu/
├── index.html        # Main HTML layout, CSS rules, and JavaScript logic
├── README.md         # Documentation file
└── images/           # Local image assets for bouquets, backgrounds, and icons
```
