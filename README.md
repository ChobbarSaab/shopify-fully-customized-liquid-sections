# 🛍️ Shopify Custom Sections

A growing collection of reusable, responsive, and highly customizable **Shopify Online Store 2.0 sections and UI components** built with Liquid, CSS, and JavaScript.

These components are designed to be easy to drop into Shopify themes and customize directly from the **Shopify Theme Editor**.

---

## ✨ What's Inside

A collection of production-ready Shopify sections for common e-commerce use cases.

| Component               | Description                             | Status         |
| ----------------------- | --------------------------------------- | -------------- |
| 📢 Marquee Announcement | Seamless scrolling announcement bar     | ✅ Ready        |
| ⭐ Trust Badges          | Trust, guarantee and payment badges     | 🚧 Coming Soon |
| 💬 Testimonials         | Responsive customer testimonial section | 🚧 Coming Soon |
| ⏱️ Countdown Timer      | Customizable urgency countdown          | 🚧 Coming Soon |
| ❓ FAQ Accordion         | Responsive FAQ section                  | 🚧 Coming Soon |
| 🖼️ Before / After      | Interactive comparison slider           | 🚧 Coming Soon |
| 🏷️ Logo Marquee        | Infinite scrolling brand logo section   | 🚧 Coming Soon |
| 🛒 Sticky Add to Cart   | Floating product purchase bar           | 🚧 Coming Soon |

More components will be added over time.

---

## 🚀 Features

Depending on the component, sections may include:

* Shopify Theme Editor customization
* Responsive desktop / tablet / mobile layouts
* Custom colors
* Typography controls
* Font picker
* Spacing controls
* Animation controls
* Hover interactions
* Mobile-specific settings
* Accessibility support
* Reduced-motion support
* Individual content blocks
* Optional links
* No external libraries unless required

---

## 📦 Installation

Most components are designed to work with **Shopify Online Store 2.0 themes**.

### Method 1 — Add as a Section

1. Open your Shopify Admin.
2. Go to **Online Store → Themes → Edit code**.
3. Open the `sections` folder.
4. Create a new `.liquid` file.
5. Copy the component code from this repository.
6. Paste it into the new file.
7. Save the file.
8. Open **Customize** in the Shopify Theme Editor.
9. Click **Add section**.
10. Select the component.

### Method 2 — Custom Liquid

Some components may also be provided as standalone snippets that can be used inside Shopify's **Custom Liquid** section.

Check the individual component's README before installing.

---

## 📁 Repository Structure

```text
shopify-custom-sections/
│
├── announcement/
│   ├── marquee-announcement.liquid
│   ├── README.md
│   └── preview.png
│
├── trust-badges/
│   ├── trust-badges.liquid
│   ├── README.md
│   └── preview.png
│
├── testimonials/
│   ├── testimonials.liquid
│   ├── README.md
│   └── preview.png
│
└── README.md
```

Each component should ideally contain:

* `.liquid` source file
* `README.md`
* `preview.png`

---

# 📢 Marquee Announcement

A premium, continuously scrolling announcement bar for Shopify.

### Features

* Seamless infinite scrolling
* Right-to-left or left-to-right direction
* Multiple announcement blocks
* Individual announcement links
* Adjustable scrolling speed
* Pause on hover
* Shopify font picker
* Font weight control
* Text transformation
* Text decoration
* Desktop and mobile font sizes
* Desktop and mobile spacing
* Desktop and mobile bar height
* Custom background color
* Custom text color
* Custom separator color
* Multiple separator styles
* Separator size control
* Separator spacing
* Optional edge fade
* Responsive design
* `prefers-reduced-motion` support
* Automatic content duplication for seamless looping

### Preview

*Add preview image here.*

---

## 🎨 Customization

Components are designed to expose important settings through the Shopify Theme Editor rather than requiring users to edit the code manually.

For example, the Marquee Announcement section provides controls for:

**Animation**

* Speed
* Direction
* Pause on hover

**Typography**

* Font
* Font weight
* Font size
* Letter spacing
* Text transform
* Text decoration
* Line height

**Layout**

* Bar height
* Announcement spacing
* Mobile height
* Mobile spacing

**Colors**

* Background
* Text
* Separators

**Separators**

* Style
* Size
* Spacing
* Visibility

**Effects**

* Edge fade

---

## 🧩 Compatibility

Designed primarily for:

* Shopify Online Store 2.0
* Modern Shopify themes
* Responsive storefronts
* Shopify Theme Editor

Compatibility with heavily customized or legacy themes may require minor adjustments.

---

## ⚡ Performance

The components aim to remain lightweight and avoid unnecessary dependencies.

Where possible:

* CSS is used for animations
* JavaScript is kept minimal
* No external libraries are required
* Components use scoped styles
* Responsive behavior is handled with CSS

---

## ♿ Accessibility

Accessibility is considered during development.

Depending on the component, this may include:

* Reduced-motion support
* Semantic HTML
* Keyboard-accessible links and controls
* Appropriate ARIA attributes
* Readable color contrast
* Mobile-friendly interaction

---

## 🛠️ Development Guidelines

When adding a new component:

1. Keep it self-contained.
2. Avoid unnecessary dependencies.
3. Scope CSS to the section.
4. Use Shopify's Theme Editor settings whenever possible.
5. Make the component responsive.
6. Support reduced motion where animation is used.
7. Avoid hard-coded content when it can be exposed as a setting or block.
8. Test on both desktop and mobile.
9. Add a preview image.
10. Add documentation for installation and customization.

---

## 🤝 Contributing

Have an idea for a useful Shopify section?

Contributions and improvements are welcome.

Feel free to:

* Add new reusable components
* Improve existing components
* Fix bugs
* Improve accessibility
* Improve performance
* Add documentation

Please keep contributions focused on reusable Shopify theme components.

---

## 📄 License

Choose the license that matches how you want people to use these components.

For example:

**MIT License** — allows others to use, modify, and redistribute the code with minimal restrictions.

---

## ⭐ Support the Project

If you find these Shopify components useful, consider giving the repository a ⭐ on GitHub.

More reusable Shopify components coming soon.

---

### Built for Shopify 🛍️

Reusable components. Better themes. Faster development.
