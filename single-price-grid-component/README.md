## Frontend Mentor - Single Price Grid Component

## Design preview for the Single Price Grid component coding challenge

## Welcome!

Thanks for checking out this front-end coding challenge.
Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## The Challenge

The challenge is to build a single price grid component that closely matches the provided design. The component showcases a subscription service with a community introduction, monthly pricing, and a list of benefits, arranged in a responsive grid layout.
Users should be able to:

* View the optimal layout for their device's screen size (desktop or mobile).
* See a clean, interactive button with a subtle shadow effect for the "Sign Up" action.

## Where to Find Everything

The project includes designs in the /design folder, with both mobile and desktop versions in JPG format. Use your best judgment for styles like font-size, padding, and margin based on these designs.
All required assets (e.g., favicon) are in the /images folder and are optimized for use. The style-guide.md file contains the color palette and font details:

**Fonts:**
Karla (weights: 400, 700) - For headings, body text, and button

**Colors:**
**Primary:**

* Cyan: hsl(179, 61%, 44%)
* Bright Yellow: hsl(71, 73%, 54%)

**Neutral:**

* Light Gray: hsl(203, 44%, 93%)
* Grayish Blue: hsl(218, 22%, 67%)
* Darker Cyan: hsl(179, 47%, 52%)

## Building the Project

## My Process

I followed a mobile-first workflow, structuring the content with semantic HTML before applying styles. The process included:

* Setting up a public repository on GitHub.
* Writing semantic HTML using `<main>` and `<section>` elements to structure the community description, subscription details, and benefits list, with a `<footer>` for attribution.
* Using CSS Flexbox to create a responsive grid layout, switching from a single-column mobile layout to a two-column desktop layout with media queries.
* Styling the "Sign Up" button with a bright yellow background, rounded corners, and a box shadow for emphasis.
* Applying the Karla font with weights 400 and 700 for text hierarchy and ensuring consistent spacing and colors.
* Testing the layout across screen sizes to ensure responsiveness and accessibility.

## Built With

* Semantic HTML5 markup
* CSS Flexbox (for grid layout)
* Mobile-first workflow
* Karla - For headings, body text, and button
* Media queries for responsive design
* Box shadow for button and card depth

## What I Learned

This project deepened my understanding of:

* **Semantic HTML**: Used `<main>`, `<section>`, and `<footer>` to create a clear, accessible structure for the component.
* **Flexbox Grid**: Implemented a responsive grid with `display: inline-flex` and `flex-wrap: wrap` to arrange sections in a two-column layout on desktop.
* **Responsive Design**: Utilized media queries to adjust card widths, heights, and margins for mobile (max-width: 335px) and desktop (max-width: 700px) layouts.
* **Button Styling**: Created a prominent "Sign Up" button with box-shadow and rounded corners, enhancing interactivity.
* **Typography**: Applied Karla font weights (400 for body, 700 for headings) to establish a clear visual hierarchy.

## CSS snippet I’m proud of:

```css
@media (min-width: 768px) {
  .container {
    margin-top: 150px;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  main {
    max-width: 700px;
    display: inline-flex;
    margin: 0 auto;
    flex-wrap: wrap;
    justify-content: center;
    align-items: center;
  }
}
```

This code transforms the single-column mobile layout into a two-column desktop grid, ensuring a balanced and responsive design.

## Continued Development

In future projects, I plan to:

* Add hover and focus states for the "Sign Up" button to improve interactivity and accessibility.
* Enhance accessibility with ARIA attributes (e.g., `aria-label` for the button) and screen reader testing.
* Optimize performance by minimizing CSS and using modern image formats if images are added.
* Explore CSS Grid for alternative layout approaches in similar multi-section components.

## Useful Resources

* **MDN Web Docs - Flexbox** - Helped with Flexbox properties for the grid layout.
* **Google Fonts** - For selecting and implementing the Karla font.
* **CSS Tricks - A Guide to Flexbox** - A great reference for Flexbox alignment.
* **WebAIM Contrast Checker** - For verifying color contrast ratios.
* **Frontend Mentor Slack** - For community support and feedback.

## Deploying the Project

The project can be hosted using:

* GitHub Pages
* Vercel
* Netlify

## Links

* **Solution URL**: Add your solution URL here
* **Live Site URL**: Add your live site URL here

## Author

**Name** - Moshood
**Frontend Mentor** - mosho1
**Twitter** - @EMPERORMOSH

## Acknowledgments

Thank you to Frontend Mentor for providing this challenge and the design assets. The clear structure of their challenges helped me focus on both design fidelity and technical implementation. I also appreciate the community for offering inspiration and feedback.

---

Would you like me to export this into a downloadable `.md` file now?
