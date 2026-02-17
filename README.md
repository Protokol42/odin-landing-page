# odin-landing-page

This project is a high-fidelity landing page built as part of The Odin Project curriculum.
https://protokol42.github.io/odin-landing-page/

## Core Concepts Practiced

### CSS Foundations

- **Image Optimization:** Establishing a global `img` rule with `max-width: 100%` and `display: block` to prevent layout overflows and remove default inline spacing gaps.
- **Typography Hierarchy:** Utilizing the Roboto font family with weights ranging from 300 for italics up to 900 for high-impact headers.
- **Visual Styling:** Applying properties like `border-radius` for curved containers, custom borders for image cards, and specific hex-color palettes to match a professional aesthetic.
- **Basic Styling:** Using basic CSS properties, with different selectors and layouts.

### Flexbox Mastery

- **Flex Containers:** Using `display: flex` to align navigation links, header content, and information grids.
- **Alignment & Spacing:** Leveraging `justify-content: space-between` and `align-items: center` to create balanced, symmetrical layouts across different sections.
- **Fluid Layouts:** Implementing `flex-basis` and `flex-grow` (using shorthands like `flex: 0 1 auto`) to allow content to shrink or grow based on the available viewport.
- **Directional Control:** Utilizing `flex-direction: column` to switch between horizontal and vertical flows for the header and information sections.

### Structural Architecture

- **Content Centering:** Implementing a `.content-wrapper` with a `max-width` of 1400px and `margin: 0 auto` to keep content centered on ultra-wide displays while maintaining side gutters.
- **Component-Based Styling:** Breaking the page into logical sections like `.header`, `.information`, `.quote-container`, and `.ad-wrapper` for cleaner, more maintainable code.

## Technologies Used

- **HTML5:** Providing the semantic structure of the page.
- **CSS3:** Handling all layout via Flexbox and custom styling.
- **Google Fonts API:** Integrating the Roboto font family.
- **Git & GitHub:** Managing version control and project deployment.
