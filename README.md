# Restaurant-Frontend
Built a frontend design for a Food Delivery Website using HTML, CSS, and basic JavaScript.


PROJECT REPORT
Food Delivery Website – Frontend UI

1. Introduction
The Food Delivery Website project is a fully responsive, user-friendly frontend interface designed for a modern food ordering platform. The goal of the project is to create an attractive and intuitive UI where users can browse food items, filter categories, view recommendations, and navigate through menus seamlessly.
This project is built using HTML, CSS, JavaScript, and Ionicons, along with jQuery animations for smooth scrolling. The design focuses on modern UI elements such as a sidebar navigation menu, search bar, recommendation slider, category filters, and product listings.

2. Objectives of the Project
The main objectives of the Food Delivery Web UI are:
To design a visually appealing and responsive food ordering interface.


To provide an easy navigation experience through a sidebar menu.


To implement category filters and product display cards.


To allow smooth horizontal scrolling using JavaScript and jQuery animations.


To ensure compatibility across mobile and desktop devices.


To demonstrate real-world UI/UX design concepts.



3. Technologies Used
Frontend Technologies
Technology
Purpose
HTML5
Structure of the website
CSS3
Styling, layout, responsiveness
JavaScript (Vanilla)
Sidebar toggle, mobile menu control
jQuery 2.2.4
Smooth scrolling animations
Ionicons
Icon library for UI elements
Google Fonts – Open Sans
Typography


4. System Requirements
Hardware Requirements
PC/Laptop with minimum 2GB RAM


Any modern web browser (Chrome, Edge, Firefox)


Software Requirements
Code editor (VS Code recommended)


Live Server extension (optional for preview)


Internet connection (for Google fonts and Ionicons)



5. Project Structure
/project-folder
│── index.html
│── style.css
│── app.js
│── /images
│     ├── burger.jpg
│     ├── coffee.jpg
│     ├── pizza.jpg
│     ├── salad.jpeg
│     ├── seafood.jpg
│     └── wine.jpg


6. User Interface Overview
6.1 Sidebar Navigation
Located on the left side, containing:
Home


Bills


Wallet


Notifications


Contact Us


Settings


Logout


The sidebar automatically hides on mobile and appears via the menu toggle button.

6.2 Main Navigation Bar
Includes:
Menu toggle icon (mobile)


Search bar (with search button)


Cart & User profile icons



6.3 Recommendation Slider
A horizontally scrollable section showing recommended items such as:
Fresh Salad


Coffee


Pizza


Burger


Navigation arrows are added for left-right sliding.

6.4 Category Filters
Categories include:
All Menus


Burger


Pizza


Wine


Ice Cream


Coffee


SeaFood


Healthy


Each category card has an icon + label.

6.5 Food Item Listing
Cards include:
Item Image


Item Name


Description


Price


Bookmark Icon


The grid layout is fully responsive and adjusts based on screen size.

7. Working of the Project (Step-by-Step)
Step 1: Building the Structure using HTML
The complete UI layout—sidebar, navbar, recommendation slider, category filters, and menu cards—was created using semantic HTML elements.
 (Ref: index.html
index
)

Step 2: Designing and Styling the UI using CSS
All design components such as colors, card layout, responsiveness, hover effects, grid layout, and shadows were created using CSS.
 Key features include:
Responsive sidebar


Grid layout for food items


Flexbox for alignment


Color variables


Smooth hover transitions
 (Ref: style.css
 style
)



Step 3: Adding Interactivity with JavaScript
JavaScript provides core interactive features:
a) Mobile Menu Toggle
When the hamburger icon is clicked:
Sidebar appears/disappears


Class is-active toggles
 (Ref: app.js
 app
)


b) Auto-close Menu When Clicking Inside
On small screens, clicking inside the sidebar closes it.
c) Horizontal Scrolling using jQuery
Buttons .back / .next scroll the recommendations section.
 Buttons .back-menus / .next-menus scroll the category filter section.
Smooth animation is implemented using:
$(".heighlight-wrapper").animate({
    scrollLeft: "+=" + step + "px"
})


8. Features Implemented
✔ Responsive UI
Works on desktops, tablets, and mobiles.
✔ Interactive Sidebar
Opens & closes smoothly on mobile.
✔ Recommendation Slider
Scrollable with arrow navigation.
✔ Dynamic Category Filters
Scrollable horizontally.
✔ Food Item Cards
Beautiful UI cards with images, descriptions, and price.
✔ jQuery-Based Animation
Smooth horizontal animation for better user experience.

9. Output Screens (Dashboard Screenshots)
You can insert your website screenshots here.
 If you want, I can create a PDF with your screenshots embedded.

10. Conclusion
This project successfully demonstrates the ability to build a professional and responsive food delivery UI using modern web technologies. The interface is easy to navigate, visually engaging, and provides a smooth experience for users. It effectively uses HTML, CSS, JS, and jQuery to simulate real-world food ordering platforms.
The project can further be expanded by adding backend integration, cart functionality, and database operations.

11. Future Enhancements
Add login and signup authentication


Add real order and cart system


Backend using Node.js or Python


Store data in MySQL / MongoDB


Add admin dashboard for managing items


Implement real-time order tracking



12. References
Ionicons Icon Library


Google Fonts


jQuery Official Documentation


MDN Web Docs (HTML/CSS/JS)

