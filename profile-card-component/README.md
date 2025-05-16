## Frontend Mentor - Profile Card Component
Design preview for the Profile card component coding challenge
Welcome! 
Thanks for checking out this front-end coding challenge.
Frontend Mentor challenges help you improve your coding skills by building realistic projects.
## The Challenge
The challenge is to build a profile card component that closely matches the provided design. The component displays a user's profile information, including their name, age, location, and social media stats (followers, likes, photos), with a visually appealing background and layout.
Users should be able to:
View the optimal layout for their device's screen size (desktop or mobile).

See a clean, centered card with a background pattern that enhances the design.

## Where to Find Everything
The project includes designs in the /design folder, with both mobile and desktop versions in JPG format. Use your best judgment for styles like font-size, padding, and margin based on these designs.
All required assets (e.g., profile image, background patterns, favicon) are in the /images folder and are optimized for use. The style-guide.md file contains the color palette and font details:
Fonts:
Kumbh Sans (weights: 400, 700) - For all text

Colors:
Primary:
Dark Cyan: hsl(185, 75%, 39%)

Neutral:
Very Dark Desaturated Blue: hsl(229, 23%, 23%)

Dark Grayish Blue: hsl(227, 10%, 46%)

Light Gray: hsl(0, 0%, 90%)

White: hsl(0, 0%, 100%)

## Building the Project
My Process
I followed a mobile-first workflow, structuring the content with semantic HTML before applying styles. The process included:
Setting up a public repository on GitHub.

Writing clean, semantic HTML to structure the card, including the profile image, name, age, location, stats, and attribution.

Using CSS Flexbox for centering the card and aligning the stats section.

Implementing a decorative background with two SVG patterns positioned at the top-left and bottom-right of the body.

Creating a circular profile image with a white border using a pseudo-element (::before) for a polished look.

Ensuring responsiveness with media queries to adjust the card width and font sizes for smaller screens.

## Built With
Semantic HTML5 markup

CSS Flexbox (for layout and alignment)

Mobile-first workflow

Kumbh Sans - For all text

Background SVG patterns for visual design

Box shadows and pseudo-elements for styling

## What I Learned
This project deepened my understanding of:
Background Patterns: Positioned two SVG background images using background-image and background-position to create a dynamic visual effect.

Pseudo-Elements: Used ::before to add a white circular border behind the profile image, enhancing the design.

Flexbox Alignment: Applied Flexbox to center the card and evenly space the stats with justify-content: space-around.

Responsive Design: Adjusted card width and font sizes for smaller screens using media queries.

CSS snippet I’m proud of:
css

body {
  font-family: "Kumbh Sans", sans-serif;
  background-color: hsl(185, 75%, 39%);
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  background-image: url("images/bg-pattern-top.svg"),
    url("images/bg-pattern-bottom.svg");
  background-position: top -500px left -300px, bottom -500px right -300px;
  background-repeat: no-repeat;
}

This code creates a visually appealing background with two SVG patterns, ensuring the card is centered and responsive across devices.
Continued Development
In future projects, I plan to:
Add subtle CSS animations for card or image transitions to enhance interactivity.

Improve accessibility with ARIA attributes and better semantic markup (e.g., replacing <location> with a more standard element).

Optimize background images for performance with modern formats or lazy-loading.

Explore CSS Grid for alternative layout approaches in similar projects.

## Useful Resources
MDN Web Docs - Flexbox - Helped with Flexbox properties for card and stats alignment.

Google Fonts - For selecting and implementing Kumbh Sans.

CSS Tricks - A Guide to Flexbox - A great reference for Flexbox alignment.

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

