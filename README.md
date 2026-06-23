Technologies Used # web-kallpa

For the development of the Kallpa product website, HTML5, CSS3, and JavaScript technologies were used, following an organized structure that facilitates readability, maintenance, and scalability of the project.

* HTML5 for content structure.
* CSS3 for design, animation, and layout.
* JavaScript for interactive buttons, displays, and effects.

The site is contained within the main folder “web1,” which includes all the files necessary for its operation. This folder contains:

HTML files, which define the structure and content of each page.

A dedicated folder for CSS files, where visual styles are managed following the design guidelines outlined in Practice 1.
A folder for JavaScript files, responsible for the site's interactions and animations.

Additional folders for images and videos, used to maintain proper order and ensure correct organization of the multimedia material.

This structure allows for working in an organized and coherent manner with the design guidelines, keeping the visual, structural, and interactive elements of the project separate. The Visual Studio Code IDE was used to facilitate the work. The project structure is shown below.

HTML Structure
Several pages were developed for the website structure: index, history, recipes, and mate-preparation. All pages maintain the same basic structure, composed of:

* Top menu.
* Content.
* Footer.
* Logo.

The only exception is the homepage (index), which includes a featured banner at the top with an image and text, following the design guidelines.
Implemented Animations
To make the website more attractive and improve the user experience, various animations were implemented using CSS and JavaScript. External CSS and JS files were linked from the HTML file to keep the code separate and facilitate project organization and maintenance. The applied animations include:

Opacity (CSS): To add a brightness effect when hovering over images.
Transform (CSS): To scale the size of images when hovering with the mouse pointer.
Transition (CSS): To control the time that elapses during changes in a property's value.
Smooth scroll (JS): This effect smooths the scrolling as you scroll down the page; a floating button appears on the right side when the user scrolls down.
Drag and drop (JS): Used to create the interactive game, where the user can drag and drop the images in the correct order to learn the steps for preparing mate.

Multimedia Integration
The website integrates various multimedia elements to complement the information and improve the user experience:

Video on the homepage: The homepage includes a demonstration video on how to prepare mate. The video file was saved in the video folder and is played using the HTML5 video tag. The code commented out an iframe with a link to YouTube as an alternative to embedding the video from an external platform; however, for this exercise, the local version was chosen.
Images: Throughout the site, illustrative images about mate and the positive vibes it conveys are used.
Vector Image (SVG): An SVG file depicting a mate gourd steaming was added. This resource is located in the images folder, and the code is found on the index page.
Animations and Interaction

Examples of implemented interaction:
"See More" button that displays text.
Cards that enlarge on hover.
Animated icons using hover and transition.

Team Responsibilities

Throughout the website development, each team member assumed specific tasks, maintaining clear organization and a collaborative workflow. Responsibilities were distributed as follows:

* Sheyla Barbachan: Developed the History page. She also implemented interactions such as the "See More" button and the show/hide content functions.
* Yanedi Abreu: Was in charge of the layout of the homepage and integration of all the site's pages. She implemented the JavaScript functions related to smooth scrolling and the interactive game, with the support of the team.
* Ezequiel Abraham: Initial page layout, partial integrations, and documentation review. QA Tester: Functionality and usability testing.
* Nahuel Deschutter: Designed and programmed the top menu and footer. He also collaborated on the creation of the main banner for the homepage.
* Mehdi Ghanami: Developed the Documentation page and was responsible for the homepage video. He also handled the integration of the documentation.
