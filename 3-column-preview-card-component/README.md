Frontend Mentor - 3-column Preview Card Component

## Design preview for the 3-column preview card component coding challenge

Welcome!
Thanks for checking out this front-end coding challenge.
Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## The Challenge

The challenge is to build a 3-column preview card component that closely matches the provided design. The component showcases three vehicle types (Sedans, SUVs, and Luxury) with distinct styling and hover effects.
Users should be able to:
View the optimal layout for their device's screen size (desktop or mobile).

See hover states for interactive elements, such as the "Learn More" buttons.

## Where to Find Everything

The project includes designs in the /design folder, with both mobile and desktop versions in JPG format. Use your best judgment for styles like font-size, padding, and margin based on these designs.
All required assets (e.g., icons, favicon) are in the /images folder and are optimized for use. The style-guide.md file contains the color palette and font details:
Fonts: Lexend Deca (body text), Big Shoulders Display (headings)

Colors:
Sedans: hsl(31, 77%, 52%)

SUVs: hsl(184, 100%, 22%)

Luxury: hsl(179, 100%, 13%)

Background: lightgray

Text: hsla(0, 0%, 100%, 0.75) (paragraphs), lightgray (headings, buttons)

## Building the Project

My Process
I followed a mobile-first workflow, structuring the content with semantic HTML before applying styles. The process included:
Setting up a public repository on GitHub.

Writing clean, semantic HTML to structure the three cards and attribution.

Using CSS Grid for the desktop layout and Flexbox for alignment and responsiveness.

Styling each card with unique colors and hover effects for buttons.

Implementing media queries to ensure a single-column layout on mobile devices.

Testing the layout across different screen sizes to ensure responsiveness.

Built With
Semantic HTML5 markup

CSS custom properties

CSS Grid (desktop layout)

Flexbox (alignment and mobile layout)

Mobile-first workflow

Lexend Deca - Body text

Big Shoulders Display - Headings

## What I Learned

This project deepened my understanding of:
CSS Grid: Used to create a 3-column layout for desktop, with grid-template-columns: repeat(3, 1fr) for equal-width columns.

Responsive Design: Media queries ensured a smooth transition to a single-column layout on mobile devices (max-width: 768px).

Hover Effects: Implemented button hover states with color changes and borders using transition: all 0.3s ease.

Font Pairing: Combining Lexend Deca and Big Shoulders Display for a modern, readable design.

CSS snippet I’m proud of:
css

.main {
display: grid;
grid-template-columns: repeat(3, 1fr);
margin: 20% auto 5px auto;
width: 85%;
}

@media (max-width: 768px) {
.main {
grid-template-columns: 1fr;
place-items: center;
}
}

This code handles the responsive layout efficiently, switching from a 3-column grid to a single-column stack on smaller screens.

## Continued Development

In future projects, I plan to:
Experiment with CSS animations for smoother transitions (e.g., card entrances).

Improve accessibility by adding ARIA landmarks and testing with screen readers.

Explore CSS custom properties for reusable color schemes.

Optimize performance by lazy-loading images and minimizing CSS.

Useful Resources
MDN Web Docs - CSS Grid - Helped me understand grid properties for the desktop layout.

Google Fonts - For selecting and implementing the fonts.

CSS Tricks - Flexbox - A great reference for Flexbox alignment.

Frontend Mentor Slack - For community support and feedback.

## Deploying the Project

The project can be hosted using:
GitHub Pages

## Links

Solution URL: Add your solution URL here

Live Site URL: Add your live site URL here

##Author
Name - Moshood

Frontend Mentor - https://www.frontendmentor.io/profile/mosho1

Twitter - https://twitter.com/EMPERORMOSH

Acknowledgments
Thank you to Frontend Mentor for providing this challenge and the design assets. The clear structure of their challenges helped me focus on both design fidelity and technical implementation. I also appreciate the community for offering inspiration and feedback.
