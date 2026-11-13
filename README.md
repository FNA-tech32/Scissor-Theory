# ✂️ Scissor Theory

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Swiper](https://img.shields.io/badge/Swiper-6332F6?style=for-the-badge&logo=swiper&logoColor=white)](https://swiperjs.com/)
[![ScrollReveal](https://img.shields.io/badge/ScrollReveal-000000?style=for-the-badge)](https://scrollrevealjs.org/)

> **Saúde natural para os seus cabelos.**  
> An exclusive, modern, and fully responsive landing page website for **Scissor Theory**, a premier hair and scalp wellness salon specializing in natural therapies, precision haircuts, and vegan treatments.

---

## 📌 Table of Contents

- [Overview](#-overview)
- [Key Features](#-key-features)
- [Brand & Contact Information](#-brand--contact-information)
- [Page Sections](#-page-sections)
- [Technologies & Libraries](#-technologies--libraries)
- [Project Structure](#-project-structure)
- [Getting Started](#-getting-started)
- [Customization](#-customization)
- [Browser Compatibility](#-browser-compatibility)
- [License](#-license)

---

## 🌟 Overview

**Scissor Theory** is a refined web application designed to present salon services, natural haircare philosophies, client testimonials, and accessible appointment booking options. Built with modern, lightweight web technologies, it delivers high performance, clean animations, and a seamless mobile-first user experience.

---

## ✨ Key Features

- **📱 Fully Responsive Design**: Mobile-first architecture that seamlessly adapts from smartphone screens to large desktop monitors.
- **💈 Dynamic Header & Navigation**:
  - Transparent sticky header that transitions to a shaded backdrop with elevation on scroll.
  - Interactive hamburger menu with smooth open/close toggle on mobile viewports.
  - Active section spy highlighting the current viewport section in the navigation menu.
- **✨ Smooth Scroll Animations**: Powered by **ScrollReveal** with staged interval reveals for headings, images, cards, and testimonials.
- **💬 Touch-Friendly Testimonials Carousel**: Integrated with **Swiper.js v7** featuring pagination bullets, navigation arrows, touch gestures, and responsive column layouts (1 slide on mobile, 2 slides on screens > 992px).
- **📅 Direct WhatsApp Booking**: Instant appointment scheduling via WhatsApp API integration.
- **📞 Comprehensive Contact Channels**: Includes primary and alternative telephone lines, direct email addresses, and physical studio location.
- **⬆️ Back-to-Top Button**: Smooth floating button that activates dynamically when scrolling past 1680px.

---

## 🏢 Brand & Contact Information

| Channel | Detail |
| :--- | :--- |
| **Brand Name** | **Scissor Theory** |
| **Primary Phone** | `+55 (11) 98765-4321` |
| **Alternative Phone** | `+55 (11) 3456-7890` (Linha Alternativa) |
| **Primary Email** | `contato@scissortheory.com` |
| **Alternative Email** | `agendamento@scissortheory.com` (Agendamento / Suporte) |
| **Studio Address** | Rua Oscar Freire, 1238 - Jardins, São Paulo - SP |
| **WhatsApp Booking** | [Iniciar conversa](https://api.whatsapp.com/send?phone=5511987654321&text=Olá!%20Gostaria%20de%20agendar%20um%20horário%20na%20Scissor%20Theory.) |
| **Instagram** | [@scissortheory](https://instagram.com/scissortheory) |
| **Facebook** | [@scissortheory](https://facebook.com/scissortheory) |
| **YouTube** | [@scissortheory](https://youtube.com/@scissortheory) |

---

## 📑 Page Sections

1. **Header (`#header`)**: Brand logo (`Scissor Theory.`), navigation links (`Início`, `Sobre`, `Serviços`, `Depoimentos`, `Contato`), and mobile menu toggle.
2. **Hero (`#home`)**: Visual presentation with high-resolution salon imagery, value proposition, and an "Agendar um horário" call to action.
3. **About (`#about`)**: Studio background, philosophy on hair wellness, and dedication to personalized client care.
4. **Services (`#services`)**: Interactive service cards showcasing:
   - **Terapia Capilar**: Scalp and strand therapy designed for all hair types.
   - **Cortes**: Precision trend-setting and classic cuts by experienced stylists.
   - **Tratamentos**: 100% vegan, natural treatments tailored for individual hair needs.
5. **Testimonials (`#testimonials`)**: Swiper slider displaying verified client reviews, ratings, and quotes.
6. **Contact (`#contact`)**: Interactive booking call-to-action with complete primary and alternative contact links.
7. **Footer**: Brand mark, copyright statement, and direct links to social media profiles.

---

## 🛠️ Technologies & Libraries

- **Markup**: [HTML5](https://html.spec.whatwg.org/) (Semantic structure & accessible landmarks)
- **Styling**: [CSS3](https://www.w3.org/Style/CSS/)
  - Custom CSS properties / variables for unified theming (`:root`)
  - CSS Grid & Flexbox layouts
  - Responsive media queries (`min-width: 767px`, `992px`, `1200px`)
- **Scripting**: Vanilla [JavaScript (ES6+)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
- **Slider Library**: [Swiper 7](https://unpkg.com/swiper@7/swiper-bundle.min.css)
- **Animation Library**: [ScrollReveal](https://unpkg.com/scrollreveal)
- **Typography**: [Google Fonts](https://fonts.google.com/) — *Poppins* (headings) & *DM Sans* (body)
- **Icons**: [IcoMoon](https://icomoon.io/) custom icon font package

---

## 📁 Project Structure

```plaintext
Scissor-Theory/
├── assets/
│   ├── fonts/
│   │   ├── fonts/
│   │   │   ├── icomoon.eot
│   │   │   ├── icomoon.svg
│   │   │   ├── icomoon.ttf
│   │   │   └── icomoon.woff
│   │   ├── style.css           # IcoMoon font glyph definitions
│   │   └── selection.json      # IcoMoon project configuration
│   └── demo.html               # Icon glyph reference sheet
├── index.html                  # Main website markup
├── style.css                   # Primary stylesheet & responsive rules
├── main.js                     # Navigation, slider & scroll logic
└── README.md                   # Project documentation
```

---

## 🚀 Getting Started

No build tools or package managers are required. You can launch the site directly in any modern browser:

### Option 1: Open Directly
Simply double-click `index.html` or open it in your preferred web browser.

### Option 2: Live Server (VS Code)
1. Open the project folder in Visual Studio Code.
2. Install the **Live Server** extension (by Ritwick Dey).
3. Right-click `index.html` and choose **"Open with Live Server"**.

### Option 3: Python Simple Server
Run the following in the project root directory:
```bash
# Python 3
python -m http.server 8000
```
Then navigate to `http://localhost:8000` in your browser.

---

## 🎨 Customization

### Changing the Color Scheme
All core colors are controlled via CSS custom properties in [style.css](style.css):

```css
:root {
  /* Change the HUE degree (0 - 360) to instantly alter the brand color */
  --hue: 300;
  
  --base-color: hsl(var(--hue) 36% 57%);
  --base-color-second: hsl(var(--hue) 65% 88%);
  --base-color-alt: hsl(var(--hue) 57% 53%);
  --title-color: hsl(var(--hue) 41% 10%);
}
```

### Updating Contact Details
Edit the `#contact` section in [index.html](index.html):
- Update telephone numbers in `<div class="links">`.
- Update email addresses and office locations.
- Update the WhatsApp phone number in the booking link:
  ```html
  <a href="https://api.whatsapp.com/send?phone=YOUR_PHONE_NUMBER&text=..." ...>
  ```

---

## 🌐 Browser Compatibility

Tested and fully supported on:
- Google Chrome (latest)
- Mozilla Firefox (latest)
- Apple Safari (latest)
- Microsoft Edge (latest)
- Mobile browsers (iOS Safari, Android Chrome)

---

## 📄 License

This project is open-source and available under the [MIT License](https://opensource.org/licenses/MIT).

