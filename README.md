# Personal_Portfolio 

Prerequisites:
Before starting, make sure you know basic or intermediate HTML, CSS, and JavaScript. These are essential for building and styling web pages.

1. Using Bootstrap 5:
Bootstrap is a framework that helps make websites look good and work well on all devices (responsive design). To use it, you need to add a few lines of code in your project.
Bootstrap CSS Link: Add this in the <head> section of your HTML to style the website with Bootstrap's default styles.
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/css/bootstrap.min.css" rel="stylesheet">
Bootstrap JavaScript Link: Add this just before the closing </body> tag to enable interactive features like buttons, modals, etc.
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/js/bootstrap.bundle.min.js"></script>

2. Using jQuery:
jQuery is a popular JavaScript library that makes working with JavaScript easier.
Add the jQuery CDN: Include this link in your HTML to use jQuery.
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.4/jquery.min.js"></script>

3. Bootstrap Icons:
To use icons (like a magnifying glass or heart), you can add the Bootstrap Icons library.
Link to Bootstrap Icons: Add this link in the <head> to use icons on your site.
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.4/font/bootstrap-icons.css"/>

4. Adding AOS (Animate on Scroll) Library:
AOS lets you animate elements when they come into view while scrolling down the page. To add animations:
Add Styles for AOS: Place this in the <head> section to include the styles.
<link rel="stylesheet" href="https://unpkg.com/aos@next/dist/aos.css" />

Add Script for AOS: Place this just before the closing </body> tag to enable AOS functionality.
<script src="https://unpkg.com/aos@next/dist/aos.js"></script>
<script>
  AOS.init(); 
</script>
You can also install AOS using package managers like npm or yarn for a more advanced setup.

5. Project Features:
This website will have several important sections, such as:
Sticky Responsive Navigation Bar
Hero Section
Service Section
Project Section
Contact Section
Footer Section
All sections will be fully responsive, meaning they’ll look good on all devices like phones, tablets, and desktops.

6. Google Fonts:
To change the font of your website, you can use Google Fonts. For this project, the Josefin Sans font is used.
Add the Font Link: Include this in the <head> section to use the font.
<link href="https://fonts.googleapis.com/css2?family=Josefin+Sans:wght@300;400;500;600;700&display=swap" rel="stylesheet"/>

In summary, you will use HTML, CSS, and JavaScript (with Bootstrap, jQuery, and AOS) to create a stylish and interactive portfolio website that’s responsive on all devices.
