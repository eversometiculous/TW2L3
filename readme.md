# Coder Academy - Portfolio

## Overview
This is a portfolio website for displaying information and services that Coder Academy provides. This is a development page and we will keep on adding those features in this readme that we add on to the website.

--
## Components

--
### Header
Header has logo and name of the company along with the navigation bar. Here is the code for the header we have:
```html
<header>
        <div class="logo-name">
            <a href="./index.html">
                <img src="./images/logo.png" alt="Coder Academy Logo">
            </a>
            <p class="name">
                <span class="coder-text">Coder</span> 
                <span class="academy-text">Academy</span>
            </p>
        </div>
        <nav class="nav-items">
            <a href="./pages/about.html">About</a>
            <a href="./pages/services.html">Services</a>
            <a href="./pages/contact.html">Contact</a>
        </nav>
</header>
```

--
### Footer
Footer has social media links, contact number and address. Here is the code that we have:
```html
    <footer>
        <div class="social-media">
            <a href="https://github.com/coder-academy-students"><i class="fa-brands fa-github"></i></a>
            <a href="https://au.linkedin.com/school/coder-academy/"><i class="fa-brands fa-linkedin"></i></a>
            <a href="https://www.instagram.com/coder_academy/?hl=en"><i class="fa-brands fa-instagram"></i></a>
        </div>
        <div class="info">
            <p>Contact: 0404040404</p>
            <p>Address: 1 Street, Suburb</p>
        </div>
    </footer>
```