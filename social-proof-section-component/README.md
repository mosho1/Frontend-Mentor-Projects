Here is your updated text with `##` added to all relevant headers:

---

## Frontend Mentor - Social Proof Section

## Design preview for the Social proof section coding challenge

## Welcome!

Thanks for checking out this front-end coding challenge.
Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## The Challenge

The challenge is to build a social proof section component that closely matches the provided design. The component showcases customer testimonials, star ratings, and a headline to highlight the popularity and quality of a product or service, arranged in a responsive layout with decorative background patterns.
Users should be able to:

- View the optimal layout for their device's screen size (desktop or mobile).
- See a visually appealing section with staggered testimonials and ratings for enhanced engagement.

## Where to Find Everything

The project includes designs in the `/design` folder, with both mobile and desktop versions in JPG format. Use your best judgment for styles like font-size, padding, and margin based on these designs.
All required assets (e.g., star icons, testimonial images, background patterns, favicon) are in the `/images` folder and are optimized for use. The `style-guide.md` file contains the color palette and font details:

**Fonts:**
Spartan (weights: 400, 500, 700) – For headings, body text, and ratings

**Colors:**
**Primary:**

- Very Dark Magenta: hsl(300, 43%, 22%)
- Soft Pink: hsl(333, 80%, 67%)

**Neutral:**

- Dark Grayish Magenta: hsl(303, 10%, 53%)
- Light Grayish Magenta: hsl(300, 24%, 96%)
- White: hsl(0, 0%, 100%)

## Building the Project

## My Process

I followed a mobile-first workflow, structuring the content with semantic HTML before applying styles. The process included:

- Setting up a public repository on GitHub.
- Writing semantic HTML using `<header>`, `<main>`, `<article>`, and `<footer>` to structure the headline, ratings, testimonials, and attribution.
- Using CSS Flexbox to create a responsive layout, with a single-column mobile view and a multi-column desktop view via media queries.
- Implementing background patterns (`bg-pattern-top-mobile.svg` and `bg-pattern-bottom-mobile.svg` for mobile, switching to desktop versions) to enhance the visual design.
- Styling testimonials with rounded corners, profile images, and verified buyer labels, staggering their positions on desktop for a dynamic look.
- Testing the layout across screen sizes to ensure responsiveness and readability.

## Built With

- Semantic HTML5 markup
- CSS Flexbox (for layout and alignment)
- Mobile-first workflow
- Spartan – For headings, body text, and ratings
- Background SVG patterns for visual design
- Media queries for responsive design

## What I Learned

This project deepened my understanding of:

- **Semantic HTML**: Used `<article>` for testimonials and `<blockquote>` for quotes to improve accessibility and structure.
- **Flexbox Layouts**: Created a flexible grid with `display: flex` for ratings and testimonials, adjusting alignments for mobile and desktop.
- **Background Patterns**: Positioned SVG backgrounds with `background-image` and `background-position` to create a visually engaging effect.
- **Responsive Design**: Implemented media queries to switch from a single-column mobile layout to a staggered multi-column desktop layout, with precise margins for testimonials.
- **Typography**: Applied Spartan font weights (400, 500, 700) to establish a clear hierarchy for headings, ratings, and testimonials.

## CSS snippet I’m proud of:

```css
@media screen and (min-width: 768px) {
  .header-container {
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  .testimonials {
    display: flex;
    flex-direction: row;
    width: 100%;
    margin-top: 2rem;
  }
  .testimonial:nth-child(2) {
    margin-top: 3rem;
    margin-left: 40px;
  }
  .testimonial:nth-child(3) {
    margin-top: 6rem;
    margin-left: 40px;
  }
}
```

This code transforms the mobile layout into a desktop view with a side-by-side header and staggered testimonials, creating a dynamic and balanced design.

## Continued Development

In future projects, I plan to:

- Add hover effects for testimonials or ratings to enhance interactivity.
- Improve accessibility with ARIA attributes (e.g., `aria-label` for ratings) and screen reader testing.
- Optimize background images with modern formats like WebP for better performance.
- Explore CSS Grid for alternative layout approaches in multi-section components.

## Useful Resources

- **MDN Web Docs - Flexbox** – Helped with Flexbox properties for layout and alignment.
- **Google Fonts** – For selecting and implementing the Spartan font.
- **CSS Tricks - A Guide to Flexbox** – A great reference for Flexbox alignment.
- **WebAIM Contrast Checker** – For verifying color contrast ratios.
- **Frontend Mentor Slack** – For community support and feedback.

## Deploying the Project

The project was hosted using:

- GitHub Pages

## Links

- **Solution URL**: Add your solution URL here
- **Live Site URL**: Add your live site URL here

## Author

**Name** – Moshood
**Frontend Mentor** – mosho1
**Twitter** – @EMPERORMOSH

## Acknowledgments

Thank you to Frontend Mentor for providing this challenge and the design assets. The clear structure of their challenges helped me focus on both design fidelity and technical implementation. I also appreciate the community for offering inspiration and feedback.
