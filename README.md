SIZO Community Restoration Projects Website
1. Project Overview

SIZO Community Restoration Projects is a community-focused website designed to provide information about community development, restoration projects and opportunities for people to get involved.

The website was created to provide visitors with information about SIZO, its goals, services and ways in which community members can participate.

The website was developed using HTML5, CSS3 and JavaScript. The website also uses Git and GitHub for version control and project management.

2. Website Pages

The website consists of five main pages:

Home
About Us
Services
Get Involved
Contact
Home

The Home page introduces SIZO Community Restoration Projects and provides an overview of its purpose. It also contains links to the main sections of the website.

About Us

The About Us page provides information about SIZO, including its mission, vision, goals and values.

Services

The Services page describes the community development, restoration and support activities associated with SIZO.

Get Involved

The Get Involved page allows visitors to submit an inquiry and indicate how they would like to participate in community activities.

Contact

The Contact page provides information about contacting SIZO and directs visitors to the inquiry page for further communication.

3. Technologies Used

The following technologies and tools were used to develop the website:

HTML5
CSS3
JavaScript
Visual Studio Code
Git
GitHub
Google Chrome
Google Chrome Developer Tools
4. Project Folder Structure

The project is organised using the following folder structure:

SIZO-WEBSITE/
│
├── index.html
├── about.html
├── services.html
├── inquiry.html
├── contact.html
├── README.md
│
├── css/
│   └── style.css
│
├── js/
│   └── script.js
│
├── images/
│   ├── community.jpg
│   ├── desktop.png
│   ├── tablet.png
│   └── mobile.png
│
└── documents/
5. Part 2 Development

Part 2 focused on improving the website's visual appearance, layout, responsiveness and usability.

An external CSS stylesheet was created and used across all five HTML pages to maintain a consistent design.

6. CSS and Styling

The external stylesheet contains a CSS reset to remove inconsistent default browser spacing.

The website also includes consistent:

Font family
Font sizes
Font weights
Line heights
Letter spacing
Colours
Background colours
Margins
Padding
Borders
Border radius
Box shadows

The styling was applied consistently throughout the website to create a unified appearance.

7. Typography

The website uses a consistent font family and typography system.

Relative units such as rem are used for many font sizes and spacing values.

This allows the content to adjust more effectively between different screen sizes.

Headings, paragraphs, buttons and navigation elements have been styled to create a clear visual hierarchy.

8. Layout

CSS Flexbox and CSS Grid were used to create the website layouts.

Flexbox

Flexbox was used for the main navigation.

The navigation items are arranged horizontally on larger screens and adjusted to a vertical layout on smaller screens.

CSS Grid

CSS Grid was used for the website's content cards.

The card layout changes according to the screen size:

Desktop: three columns
Tablet: two columns
Mobile: one column

This allows the content to remain organised and readable across different devices.

9. Visual Design

The website uses a consistent colour scheme and visual design.

Visual styling includes:

Green header and footer sections
White content cards
Light background areas
Rounded corners
Borders
Box shadows
Styled buttons
Consistent spacing

These styles help separate different sections of the website and improve readability.

10. Pseudo-Classes

CSS pseudo-classes were included to improve interaction and usability.

The website uses:

:hover
:focus
:active

Hover effects are applied to navigation links, buttons and content cards.

Focus styles are included to make interactive elements easier to identify when using keyboard navigation.

Active states are included for buttons and navigation elements.

11. Responsive Design

Responsive design was implemented using CSS media queries.

The website includes different layouts for:

Desktop
Tablet
Mobile
Desktop

On larger screens, the website displays a three-column card layout and horizontal navigation.

Tablet

At the tablet breakpoint, the card layout changes to two columns and the spacing and font sizes are adjusted.

Mobile

At the mobile breakpoint, the website changes to a single-column layout.

The navigation becomes vertical and the content is adjusted to fit smaller screens.

The website also uses percentage widths and relative units to allow content to resize appropriately.

12. Responsive Image

The Home page includes a responsive community image.

The image uses the HTML picture element together with srcset and sizes attributes.

Example:

<picture>
    <img
        src="images/community.jpg"
        srcset="images/community.jpg 800w"
        sizes="(max-width: 600px) 100vw, 50vw"
        alt="Community members participating in a community project"
        loading="lazy"
    >
</picture>

This allows the image to adapt to different screen sizes while maintaining a responsive layout.

13. JavaScript

JavaScript is used on the Get Involved page to provide basic form validation.

The script checks that the required fields have been completed before displaying a confirmation message.

The form also resets after a successful submission.

The JavaScript file is stored in the js folder.

14. Accessibility Improvements

Several improvements were made to the HTML structure and accessibility of the website.

These include:

Descriptive page titles
Meta descriptions
Semantic HTML elements
Navigation labels
aria-current attributes for the current page
Descriptive image alternative text
Proper form labels
Focus styles for interactive elements

These features help make the website easier to understand and navigate.

15. Testing

The website was tested using Google Chrome and Google Chrome Developer Tools.

Testing was performed at desktop, tablet and mobile screen sizes.

The following areas were checked:

Navigation
Page links
Card layouts
Images
Buttons
Text readability
Form functionality
Responsive behaviour
Horizontal scrolling
Overall page layout
16. Desktop Testing

The website was tested using a desktop viewport of:

1440 × 900 pixels

The desktop layout displayed:

Horizontal navigation
Three-column card layouts
Full-width responsive content
Properly sized headings
Responsive images
Styled buttons

The pages remained readable and functional.

Desktop Screenshot




17. Tablet Testing

The website was tested using a tablet viewport of:

768 × 1024 pixels

The tablet layout displayed:

Responsive navigation
Two-column card layouts
Adjusted spacing
Responsive typography
Properly sized content

The website remained readable and functional at the tablet size.

Tablet Screenshot




18. Mobile Testing

The website was tested using a mobile viewport of:

390 × 844 pixels

The mobile layout displayed:

Vertical navigation
Single-column cards
Smaller responsive headings
Responsive images
Mobile-friendly spacing
Full-width buttons

The website remained readable and functional without horizontal scrolling.

Mobile Screenshot




19. Git and GitHub

Git was used for version control during the development of the website.

The project was committed with descriptive commit messages and pushed to the GitHub repository.

GitHub was used to maintain the project files and provide access to the completed website source code.

20. Part 2 Change Log
Change 1 — CSS Reset and Base Styling

The external CSS stylesheet was updated with a CSS reset.

The changes included:

Removing default margins
Removing default padding
Setting box-sizing
Setting the main font family
Setting the base font size
Setting line height
Setting text colours
Setting background colours
Change 2 — Navigation Styling

The navigation was redesigned using CSS Flexbox.

The changes included:

Horizontal navigation on desktop
Flexible navigation spacing
Navigation wrapping
Hover effects
Focus effects
Active states
Mobile vertical navigation
Change 3 — Responsive Card Layout

CSS Grid was added to the card sections.

The card layout was changed to:

Three columns on desktop
Two columns on tablet
One column on mobile
Change 4 — Visual Styling

Visual styling was added throughout the website.

This included:

Background colours
Borders
Rounded corners
Box shadows
Button styling
Hover effects
Consistent spacing
Section styling
Change 5 — Responsive Design

Media queries were added for different screen sizes.

The website was adjusted for:

Desktop
Tablet
Mobile

The navigation, card layout, typography, spacing and content widths were adjusted at different breakpoints.

Change 6 — Responsive Images

The Home page image was updated to support responsive behaviour.

The image uses:

srcset
sizes
Responsive CSS
Appropriate alternative text
Change 7 — HTML Improvements

The HTML pages were updated with improved structure and metadata.

The changes included:

Descriptive page titles
Meta descriptions
Keywords
Author information
Semantic HTML
Navigation labels
Current-page indicators
Image alternative text
Form labels
Change 8 — Form Improvements

The Get Involved page was updated with a structured inquiry form.

The form includes:

Full name
Email address
Contact number
Involvement selection
Message field
Submit button

Required fields were also added where appropriate.

Change 9 — JavaScript Form Validation

The existing JavaScript was connected to the inquiry form.

The script checks that required fields have been completed and displays a confirmation message after successful submission.

Change 10 — Responsive Testing

All five pages were tested at desktop, tablet and mobile screen sizes using Google Chrome Developer Tools.

The following were checked:

Navigation
Page layout
Text
Images
Cards
Buttons
Forms
Responsive behaviour
Horizontal overflow
Change 11 — Documentation

The README file was updated to document the Part 2 development process.

The documentation includes:

Project overview
Technologies used
Folder structure
CSS development
Responsive design
Testing
Screenshots
Change Log
GitHub information
References
Change 12 — GitHub Update

The completed Part 2 changes were committed using Git and pushed to the GitHub repository.

21. References

The following resources were used as references during development and testing:

MDN Web Docs — HTML documentation
MDN Web Docs — CSS documentation
MDN Web Docs — CSS Grid documentation
MDN Web Docs — CSS Flexbox documentation
MDN Web Docs — Responsive design documentation
MDN Web Docs — JavaScript documentation
W3C — Web Standards and Accessibility Guidelines
GitHub Documentation — Git and repository documentation
22. Conclusion

Part 2 improved the SIZO Community Restoration Projects website by introducing a consistent visual design, responsive layouts, interactive styling and improved usability.

The website now adapts to desktop, tablet and mobile screen sizes.

The project was tested using Google Chrome Developer Tools and the responsive behaviour of the five pages was checked.

The completed project was committed using Git and pushed to the GitHub repository.