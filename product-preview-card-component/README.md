## Frontend Mentor - Product Preview Card Component

Design preview for the Product preview card component coding challenge
Welcome!
Thanks for checking out this front-end coding challenge.
Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## The Challenge

The challenge is to build a product preview card component that closely matches the provided design. The component showcases a perfume product ("Gabrielle Essence Eau De Parfum") with an image, description, pricing, and an "Add to Cart" button, featuring hover effects for interactivity.
Users should be able to:
View the optimal layout for their device's screen size (desktop or mobile).

See hover states for interactive elements, such as the "Add to Cart" button.

## Where to Find Everything

The project includes designs in the /design folder, with both mobile and desktop versions in JPG format. Use your best judgment for styles like font-size, padding, and margin based on these designs.
All required assets (e.g., product images, cart icon, favicon) are in the /images folder and are optimized for use. The style-guide.md file contains the color palette and font details:
Fonts:
Montserrat (weights: 500, 700) - For body text and button

Fraunces (weight: 700) - For headings and price

Colors:
Primary:
Dark Cyan: hsl(158, 36%, 37%)

Cream: hsl(30, 38%, 92%)

Neutral:
Very Dark Blue: hsl(212, 21%, 14%)

Dark Grayish Blue: hsl(228, 12%, 48%)

White: hsl(0, 0%, 100%)

## Building the Project

My Process
I followed a mobile-first workflow, structuring the content with semantic HTML before applying styles. The process included:
Setting up a public repository on GitHub.

Writing clean, semantic HTML to structure the card, including the product image, text content, pricing, button, and attribution.

Using CSS Flexbox for the desktop layout and switching to a columnar layout for mobile with media queries.

Implementing hover effects, such as a darker cyan background for the "Add to Cart" button.

Using CSS custom properties for consistent styling and Google Fonts for typography.

Ensuring responsiveness by swapping desktop and mobile images based on screen size.

Built With
Semantic HTML5 markup

CSS Flexbox (for layout)

Mobile-first workflow

Montserrat - For body text and button

Fraunces - For headings and price

Media queries for responsive design

## What I Learned

This project deepened my understanding of:
Responsive Images: Used separate desktop and mobile images, toggling visibility with display: none/block in media queries.

Flexbox Layouts: Created a side-by-side layout for desktop with display: flex and adjusted to a stacked layout for mobile.

Typography: Combined Montserrat and Fraunces fonts for a modern, elegant look, with specific weights for hierarchy.

Hover Effects: Implemented a subtle background color change for the button using hsl(158, 36%, 22%) on hover.

CSS snippet I’m proud of:
css

.container {
margin: 20% auto;
display: flex;
border-radius: 10px;
width: 59%;
height: auto;
}

@media only screen and (max-device-width: 768px) {
.container {
display: flex;
flex-direction: column;
}
}

This code ensures a flexible, responsive layout that adapts seamlessly from a horizontal desktop view to a vertical mobile view.

## Continued Development

In future projects, I plan to:
Add CSS animations for button or image transitions to enhance interactivity.

Improve accessibility with ARIA attributes and better keyboard navigation.

Optimize images further with modern formats like WebP or lazy-loading.

Explore CSS Grid for alternative layout approaches in similar projects.

## Useful Resources

MDN Web Docs - Flexbox - Helped with Flexbox properties for the card layout.

Google Fonts - For selecting and implementing Montserrat and Fraunces fonts.

CSS Tricks - A Guide to Flexbox - A great reference for Flexbox alignment.

Frontend Mentor Slack - For community support and feedback.

## Deploying the Project

The project was hosted using:
GitHub Pages

Links
Solution URL: Add your solution URL here

Live Site URL: Add your live site URL here

## Author

Name - Moshood

Frontend Mentor - mosho1

Twitter - @EMPERORMOSH

## Acknowledgments

Thank you to Frontend Mentor for providing this challenge and the design assets. The clear structure of their challenges helped me focus on both design fidelity and technical implementation. I also appreciate the community for offering inspiration and feedback.
