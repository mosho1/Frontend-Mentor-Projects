Here is your updated text with `##` added to all headers, formatted for proper Markdown rendering:

---

## Frontend Mentor - Stats Preview Card Component

## Design preview for the Stats preview card component coding challenge

## Welcome!

Thanks for checking out this front-end coding challenge.
Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## The Challenge

The challenge is to build a stats preview card component that closely matches the provided design. The component showcases the benefits of data analytics with a headline, description, key statistics, and a tinted background image, arranged in a responsive layout.

Users should be able to:

- View the optimal layout for their device's screen size (desktop or mobile).
- See a visually appealing card with a tinted image and clear statistics presentation.

## Where to Find Everything

The project includes designs in the `/design` folder, with both mobile and desktop versions in JPG format. Use your best judgment for styles like font-size, padding, and margin based on these designs.
All required assets (e.g., header images, favicon) are in the `/images` folder and are optimized for use. The `style-guide.md` file contains the color palette and font details:

**Fonts:**

- Inter (weights: 400, 700) – For headings and body text
- Lexend Deca (weight: 400) – For statistic labels

**Colors:**
**Primary:**

- Very Dark Blue (main background): hsl(233, 47%, 7%)
- Dark Desaturated Blue (card background): hsl(244, 38%, 16%)
- Soft Violet (accent): hsl(277, 64%, 61%)

**Neutral:**

- White: hsl(0, 0%, 100%)
- Slightly Transparent White (paragraphs): hsla(0, 0%, 100%, 0.75)
- Slightly Transparent White (stats): hsla(0, 0%, 100%, 0.6)

## Building the Project

## My Process

I followed a mobile-first workflow, structuring the content with semantic HTML before applying styles. The process included:

- Setting up a public repository on GitHub.
- Writing semantic HTML using `<div>` for the card container, `<h2>` for the main heading, `<p>` for the description, and `<ul>` for statistics, with a `<footer>` for attribution.
- Using CSS Flexbox to create a responsive layout, switching from a stacked mobile view to a side-by-side desktop view with media queries.
- Implementing a tinted image effect with two overlay divs using HSL colors and `mix-blend-mode: color-burn` for a vibrant look.
- Styling text with Inter and Lexend Deca fonts, ensuring clear hierarchy and contrast.
- Testing the layout across screen sizes to ensure responsiveness and accessibility.

## Built With

- Semantic HTML5 markup
- CSS Flexbox (for layout)
- Mobile-first workflow
- Inter – For headings and body text
- Lexend Deca – For statistic labels
- CSS overlays and mix-blend-mode for image tinting
- Media queries for responsive design

## What I Learned

This project deepened my understanding of:

- **Semantic HTML**: Used `<ul>` for statistics to ensure a structured, accessible list of data points.
- **Flexbox Layout**: Implemented a responsive card with `display: flex` and `flex-direction: row-reverse` on desktop to position the image alongside text.
- **Image Overlays**: Created a tinted image effect with layered `<div>` elements, HSL colors, and `mix-blend-mode: color-burn` for a unique visual.
- **Typography**: Combined Inter (400, 700) and Lexend Deca (400) fonts to achieve a modern, readable design with clear hierarchy.
- **Responsive Design**: Used media queries to adjust card dimensions, text alignment, and image sources (`header-mobile.jpg` to `desktop-header.jpg`) for mobile and desktop.

## CSS snippet I’m proud of:

```css
.bg-img {
  background: url(images/header-mobile.jpg) no-repeat;
  height: 240px;
  width: 325px;
  background-size: contain;
  border-radius: 10px 10px 0 0;
}
.overlay {
  background: hsl(277deg, 100%, 50%, 0.45);
  overflow: hidden;
  height: 100%;
  border-radius: 10px 10px 0 0;
}
.overlay2 {
  height: 100%;
  background: hsl(293, 42%, 35%, 0.27);
  mix-blend-mode: color-burn;
}
```

This code creates a vibrant, tinted image effect with layered overlays, maintaining rounded corners and responsiveness across devices.

## Continued Development

In future projects, I plan to:

- Add hover or focus effects for interactive elements (e.g., statistics or attribution links) to enhance user engagement.
- Improve accessibility with ARIA attributes (e.g., `aria-label` for the stats list) and screen reader testing.
- Optimize images with modern formats like WebP to improve performance.
- Explore CSS Grid for alternative layout approaches in similar card components.

## Useful Resources

- **MDN Web Docs - Flexbox** – Helped with Flexbox properties for the card layout.
- **Google Fonts** – For selecting and implementing Inter and Lexend Deca fonts.
- **CSS Tricks - A Guide to Flexbox** – A great reference for Flexbox alignment.
- **MDN Web Docs - mix-blend-mode** – For understanding image overlay effects.
- **WebAIM Contrast Checker** – For verifying color contrast ratios.
- **Frontend Mentor Slack** – For community support and feedback.

## Deploying the Project

The project was hosted using:

- GitHub Pages
-

## Links

- **Solution URL**: Add your solution URL here
- **Live Site URL**: Add your live site URL here

## Author

**Name** – Moshood
**Frontend Mentor** – mosho1
**Twitter** – @EMPERORMOSH

## Acknowledgments

Thank you to Frontend Mentor for providing this challenge and the design assets. The clear structure of their challenges helped me focus on both design fidelity and technical implementation. I also appreciate the community for offering inspiration and feedback.

---

Would you like me to convert this into a `.md` file for download?
