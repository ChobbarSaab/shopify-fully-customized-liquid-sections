# 🛍️ Shopify Custom Sections

A growing collection of reusable, responsive and **fully customizable Shopify Online Store 2.0 sections**, built with Liquid, CSS and JavaScript.

Drop a section into any modern theme and control everything (layout, colors, fonts, spacing, animations, mobile settings) from the **Shopify Theme Editor**. No apps, no monthly fees, no external libraries.

---

## ✨ What's Inside

| Component | Description | Settings | Status |
| --- | --- | --- | --- |
| 📢 [Marquee Announcement](./announcement-bar) | Seamless scrolling announcement bar | 25+ | ✅ Ready |
| ⭐ [Trust Badges](./trust-badges) | Shipping, returns, secure checkout and payment badges | 100+ | ✅ Ready |
| ❓ [FAQ Accordion](./faq-accordion) | FAQs with topic tabs, search and Google FAQ schema | 125+ | ✅ Ready |
| ⏱️ [Countdown Timer](./CountdownTimer) | Fixed, evergreen and daily sale timers | 130+ | ✅ Ready |
| 💬 [Testimonials](./testimonials) | Grid, carousel, masonry and scrolling "wall of love" | 135+ | ✅ Ready |
| 🖼️ Before / After | Interactive image comparison slider | | 🚧 Coming Soon |
| 🏷️ Logo Marquee | Infinite scrolling brand logo strip | | 🚧 Coming Soon |
| 🛒 Sticky Add to Cart | Floating product purchase bar | | 🚧 Coming Soon |

---

## 🚀 What every section includes

- Full control from the Shopify Theme Editor, no code editing needed
- Ready-made presets to start from (light, dark and minimal looks)
- Separate desktop, tablet and mobile settings
- Font pickers, color controls, spacing and size sliders
- Modern effects: glass cards, gradient borders, cursor spotlight, scroll-in animations
- Gradient highlight for any italic word in a heading
- Accessible markup, keyboard support and `prefers-reduced-motion` support
- Scoped CSS, so sections never clash with your theme or with each other
- Lightweight vanilla JavaScript, no external libraries

---

## 📦 Installation

1. In Shopify Admin, go to **Online Store → Themes → … → Edit code**.
2. In the `sections` folder, click **Add a new section**.
3. Give it the same name as the file (e.g. `trust-badges`).
4. Delete the starter code, paste the full contents of the `.liquid` file, and click **Save**.
5. Open **Customize**, click **Add section**, and pick the section (or one of its presets).

Each section's folder has its own README with every setting and tip explained.

---

## 📁 Repository Structure

```text
shopify-fully-customized-liquid-sections/
│
├── announcement-bar/
│   ├── marquee-announcement.liquid
│   └── preview.png
│
├── trust-badges/
│   ├── trust-badges.liquid
│   ├── README.md
│   └── preview.png
│
├── faq-accordion/
│   ├── faq-accordion.liquid
│   ├── README.md
│   └── preview.png
│
├── countdown-timer/
│   ├── countdown-timer.liquid
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

---

## 🧩 Compatibility

Built for **Shopify Online Store 2.0** themes, including Dawn and other modern themes. Heavily customized or legacy (vintage) themes may need small adjustments.

Modern CSS features such as `color-mix`, `@property` and `backdrop-filter` are used for the newest effects; older browsers fall back to clean static styling.

---

## 🛠️ Development Guidelines

When adding a new section:

1. Keep it self-contained in one `.liquid` file.
2. Scope all CSS to the section ID.
3. Expose content and styling as Theme Editor settings or blocks instead of hard-coding them.
4. Provide separate desktop and mobile settings where sizes matter.
5. Support reduced motion wherever there is animation.
6. Avoid external libraries.
7. Test on desktop and mobile.
8. Add a `README.md` and a `preview.png` in the section's folder.

---

## 🤝 Contributing

Ideas, bug reports and improvements are welcome. Feel free to open an issue or a pull request, and please keep contributions focused on reusable Shopify theme sections.

---

## ⭐ Support the Project

If these sections help your store or your clients, consider giving the repository a ⭐ on GitHub.

---

### Built for Shopify 🛍️

Reusable sections. Better themes. Faster development.
