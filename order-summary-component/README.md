## Frontend Mentor - Order Summary Card Component

Design preview for the Order Summary card component coding challenge
Welcome! 👋
Thanks for checking out this front-end coding challenge.
Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## The Challenge

The challenge is to build an order summary card component that closely matches the provided design. The component displays details of a music subscription plan, including the plan type, cost, and options to proceed with payment or cancel the order, with hover effects for interactivity.
Users should be able to:
View the optimal layout for their device's screen size (desktop or mobile).
See hover states for interactive elements, such as the "Change" link, "Proceed to Payment" button, and "Cancel Order" link.

## Where to Find Everything

The project includes designs in the /design folder, with both mobile and desktop versions in JPG format. Use your best judgment for styles like font-size, padding, and margin based on these designs.
All required assets (e.g., hero illustration, music icon, favicon) are in the /images folder and are optimized for use. The style-guide.md file contains the color palette and font details:
Fonts: Not explicitly specified in the code, but inferred as a sans-serif font (e.g., default system fonts or a custom font from Frontend Mentor designs).
Colors:
Primary:
Pale Blue: hsl(225, 100%, 94%)
Bright Blue: hsl(245, 75%, 52%)
Neutral:
Very Pale Blue: hsl(225, 100%, 98%)
Desaturated Blue: hsl(224, 23%, 55%)
Dark Blue: hsl(223, 47%, 23%)

## Building the Project

# My Process

I followed a mobile-first workflow, structuring the content with semantic HTML before applying styles. The process included:
Setting up a public repository on GitHub.
Writing clean, semantic HTML to structure the card, including the header image, title, description, plan details, buttons, and attribution.
Using CSS Flexbox for alignment and layout consistency within the card and plan section.
Implementing hover effects, such as color changes for the "Change" link, "Proceed to Payment" button, and "Cancel Order" link.
Using CSS custom properties (:root) for consistent color management.
Applying a background pattern image and ensuring responsiveness with media queries for smaller screens.

## Built With

Semantic HTML5 markup
CSS custom properties
Flexbox (for alignment and layout)
Mobile-first workflow
Background pattern image for visual design
Box shadows for card and button depth
What I Learned
This project deepened my understanding of:
Flexbox Layouts: Used Flexbox to align the plan details and buttons, ensuring consistent spacing with justify-content: space-around.
Hover Effects: Implemented smooth color transitions for interactive elements, like the button changing to mediumpurple on hover.
CSS Custom Properties: Managed colors efficiently with :root variables for reusability.
Responsive Backgrounds: Applied a background pattern image that scales appropriately across devices.
CSS snippet I’m proud of:
css
.plan {
display: flex;
flex-direction: row;
justify-content: space-around;
align-items: center;
background-color: var(--Very-pale-blue);
margin: 30px;
border-radius: 16px;
padding: 16px;
}
This code creates a clean, aligned layout for the plan section, ensuring the music icon, plan details, and "Change" link are well-balanced.

## Continued Development

In future projects, I plan to:
Incorporate CSS animations for button or card transitions to enhance user experience.
Improve accessibility by adding ARIA attributes and ensuring keyboard navigation for interactive elements.
Optimize background images for faster loading with modern formats like WebP.
Explore CSS Grid for more complex card layouts in similar projects.

## Useful Resources

MDN Web Docs - Flexbox - Helped with Flexbox properties for the plan and button layouts.
CSS Tricks - A Guide to Flexbox - A great reference for Flexbox alignment.
Frontend Mentor Slack - For community support and feedback.
MDN Web Docs - CSS Custom Properties - For understanding variable usage.
Deploying the Project
The project was hosted using:
GitHub Pages

Links
Solution URL: Add your solution URL here
Live Site URL: Add your live site URL here
Author
Name - Moshood
Frontend Mentor - mosho1
Twitter - @EMPERORMOSH

## Acknowledgments

Thank you to Frontend Mentor for providing this challenge and the design assets. The clear structure of their challenges helped me focus on both design fidelity and technical implementation. I also appreciate the community for offering inspiration and feedback.
