Project Documentation: Personal 
Portfolio Website 
Student/Developer Name: Vaishnavi Ray 
Project Title: Single-Page Personal Portfolio 
Date: January 14, 2026 
1. Project Overview and Objectives 
Overview 
This project involves the development of a personal portfolio website designed to serve as a 
digital resume. The website acts as a central hub to showcase my professional background, 
technical skills, and projects to potential employers or clients. It is built using standard 
HTML5 and CSS3 technologies, ensuring compatibility across modern web browsers. 
Objectives 
● To create a professional online presence that represents my personal brand 
("Vaishnavi Ray"). 
● To implement a responsive layout that works on desktop and mobile screens. 
● To demonstrate proficiency in semantic HTML structure and internal CSS styling. 
● To provide a functional and accessible user interface with clear navigation and 
contact methods. 
2. Setup and Installation Instructions 
Since this project relies on static HTML and CSS with no backend dependencies, the setup 
process is straightforward. 
Prerequisites: 
● A text editor (e.g., VS Code, Notepad++, Sublime Text). 
● A modern web browser (e.g., Chrome, Firefox, Edge). 
Steps to Run: 
1. Create Project Folder: Create a new folder on your computer named 
portfolio-vaishnavi. 
2. Create File: Inside the folder, create a new file named index.html. 
3. Add Code: Open index.html in your text editor and paste the provided source code. 
4. Launch: Locate the index.html file in your file explorer and double-click it. The 
website will open immediately in your default web browser. 
3. Code Structure Explanation 
The codebase consists of a single file (index.html) which contains both the structural markup 
and the stylistic presentation. 
HTML5 Structure 
The document follows a semantic hierarchy to ensure accessibility and SEO optimization: 
● <header> & <nav>: Contains the site logo (Vaishnavi Ray) and unordered list 
(<ul>) links for navigation. These links use anchor tags (#about, #skills) to jump to 
specific page sections. 
● <main>: The container for the primary page content. 
○ About Section: Features a profile image and a short biography using 
paragraph tags. 
○ Skills Section: Utilizes a grid-like layout to display technical competencies 
(HTML, CSS, JS, etc.) in individual cards. 
○ Contact Section: Houses a <form> element with input fields for name, email, 
and a message. 
● <footer>: Contains copyright information and closes the page layout. 
CSS Styling 
The styles are embedded in the <head> to keep the project portable. 
● Global Reset: A universal selector (*) resets margins and padding to ensure 
consistent spacing. 
● Flexbox Layouts: Flexbox is used extensively in the nav, .about-content, and 
.skills-grid classes to ensure elements align side-by-side and wrap responsively on 
smaller screens. 
● Visual Design: The color palette uses professional tones (Dark Blue #2c3e50 and 
Bright Blue #3498db) to create contrast and focus. 
4. Screenshots of Working Application 
(Note: When you create your final document, take actual screenshots of your browser and 
paste them in the areas below.) 
Figure 1: Header and Navigation 
[Insert Screenshot here showing the top of the page with the "Vaishnavi Ray" 
logo and navigation links] 
Description: The sticky header stays at the top of the viewport, allowing users to 
navigate easily. 
Figure 2: About and Skills Section 
[Insert Screenshot here showing your bio and the skill cards] 
Description: The About section displays the profile image alongside the text, 
while the Skills section uses a flex-wrap grid for the cards. 
Figure 3: Contact Form 
 
[Insert Screenshot here showing the input fields and "Send Message" button] 
 
Description: A user-friendly form layout allowing visitors to input their name, 
email, and message. 
 
5. Meeting Technical Requirements 
This project successfully implements all the specified technical requirements: 
 
Requirement Implementation Details 
Proper HTML5 
Structure 
The document starts with <!DOCTYPE html> and contains valid 
<html>, <head>, and <body> tags. 
At least 3 
Sections 
The <main> element houses three distinct sections: #about, #skills, 
and #contact. 
Semantic HTML 
Tags 
Instead of generic divs, the code uses <header>, <nav>, <main>, 
<section>, and <footer> to define the page structure. 
Working Contact 
Form 
A <form> element is included with input types for text and email, 
and a textarea for the message. Attributes like required are used for 
validation. 
Images and Alt 
Text 
The profile image includes the alt attribute (alt="Portrait of the 
portfolio owner") to ensure accessibility for screen readers. 
Internal 
Navigation 
The navigation menu uses ID anchors (e.g., href="#contact") to 
smoothly scroll the user to the relevant section on the same page. 
 
