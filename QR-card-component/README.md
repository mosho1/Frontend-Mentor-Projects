## Frontend Mentor - QR Code Card Component
Design preview for the QR code card component coding challenge
Welcome! 
Thanks for checking out this front-end coding challenge.
Frontend Mentor challenges help you improve your coding skills by building realistic projects.
## The Challenge
The challenge is to build a QR code card component that closely matches the provided design. The component displays a QR code image with a title and description, encouraging users to scan the code to visit Frontend Mentor and enhance their coding skills.
Users should be able to:
View the optimal layout for their device's screen size (desktop or mobile).

See a clean, centered card with a subtle hover effect for interactivity.

## Where to Find Everything
The project includes designs in the /design folder, with both mobile and desktop versions in JPG format. Use your best judgment for styles like font-size, padding, and margin based on these designs.
All required assets (e.g., QR code image, favicon) are in the /images folder and are optimized for use. The style-guide.md file contains the color palette and font details:
# Fonts:
Outfit (weights: 400, 700) - For title and description

# Colors:
Primary:
Light Gray: hsl(212, 45%, 89%)

Grayish Blue: hsl(220, 15%, 55%)

Dark Blue: hsl(218, 44%, 22%)

Neutral:
White: hsl(0, 0%, 100%)

## Building the Project
My Process
I followed a mobile-first workflow, structuring the content with semantic HTML before applying styles. The process included:
Setting up a public repository on GitHub.

Writing semantic HTML using a <section> element for the card, with a descriptive alt text for the QR code image and an attribution section.

Centering the card using Flexbox on the body, simplifying the layout compared to absolute positioning.

Styling the card with the Outfit font, rounded corners, and a subtle box shadow, ensuring responsiveness with a media query.

Adding a hover effect to the card that lifts it slightly and enhances the shadow for interactivity.

Improving accessibility with ARIA attributes, focus states for links, and high-contrast colors.

## Built With
Semantic HTML5 markup

CSS Flexbox (for centering and layout)

Mobile-first workflow

Outfit - For title and description

Box shadow and border-radius for card design

CSS transitions for hover animation

Lazy-loading for the QR code image

## What I Learned
This project deepened my understanding of:
Semantic HTML: Used a <section> element with role="region" and aria-label to improve accessibility for screen readers.

Flexbox Centering: Simplified card positioning by leveraging Flexbox on the body, eliminating the need for absolute positioning.

Hover Animations: Implemented a smooth hover effect with transform: translateY(-8px) and an enhanced box-shadow, making the card more interactive.

Accessibility: Added focus states for attribution links and used relative units (rem) to respect user browser settings, ensuring WCAG-compliant color contrast.

Responsive Design: Refined media queries to adjust card size, padding, and font sizes for smaller screens, ensuring a consistent experience.

CSS snippet I’m proud of:
css

.card {
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
  max-width: 320px;
  background-color: hsl(0, 0%, 100%);
  border-radius: 20px;
  text-align: center;
  padding: 16px;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.card:hover {
  transform: translateY(-8px);
  box-shadow: 0 8px 16px rgba(0, 0, 0, 0.15);
}

This code creates a visually appealing, interactive card that lifts and deepens its shadow on hover, enhancing user engagement while maintaining a clean design.
## Continued Development
In future projects, I plan to:
Explore WebP image formats to further optimize performance, as suggested in the design feedback.

Implement card entry animations (e.g., fade-in) to enhance the initial user experience.

Test with screen readers to ensure full accessibility compliance.

Experiment with CSS Grid for alternative layout approaches in similar projects.

## Useful Resources
MDN Web Docs - Flexbox - Helped with Flexbox properties for centering the card.

Google Fonts - For selecting and implementing the Outfit font.

CSS Tricks - Centering in CSS - A great reference for centering techniques.

WebAIM Contrast Checker - For verifying color contrast ratios.

Frontend Mentor Slack - For community support and feedback.

## Deploying the Project
The project was hosted using:
GitHub Pages


## Links
Solution URL: Add your solution URL here

Live Site URL: Add your live site URL here

## Author
Name - Moshood

Frontend Mentor - mosho1

Twitter - @EMPERORMOSH

## Acknowledgments
Thank you to Frontend Mentor for providing this challenge and the design assets. The clear structure of their challenges helped me focus on both design fidelity and technical implementation. I also appreciate the community for offering inspiration and feedback.

