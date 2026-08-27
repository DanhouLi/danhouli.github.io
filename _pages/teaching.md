---
layout: page
permalink: /teaching/
title: Teaching
nav: true
nav_order: 6
calendar: false
---

<hr class="teaching-divider">

**Teaching Assistant, National University of Singapore**

* RE6010 Applied Microeconomic Theory (PhD level, Instructor: Prof. Zhonglin Li), Fall 2026
* EC5101 Microeconomic Theory (PhD level, Instructor: Prof. John Quah and Prof. Xiao Luo), Fall 2024, 2025
* EC5101 Microeconomic Theory (PhD level, Instructor: Prof. John Quah and Prof. Yi-Chun Chen), Fall 2023
* EC6101 Advanced Microeconomic Theory (PhD level, Instructor: Prof. Xiao Luo), Spring 2023

**Teaching Assistant, The Chinese University of Hong Kong**

* ECON3011 Intermediate Microeconomic Theory (undergraduate level, Instructor: Prof. Ce Matthew Shi), Spring 2020, 2021, Fall 2019, 2020

**Mentor, National University of Singapore**

* Economic Research Workshop (undergraduate), Fall 2025

<style>
  /* Shrink the main page title */
  header.post-header .post-title {
    font-size: 2rem !important; /* Default is usually around 2.5rem to 3rem */
  }

  /* 1. STRIP THE HEADER BOX */
  header.post-header {
    margin-bottom: 0 !important;
    padding-bottom: 0 !important;
  }

  /* 2. STRIP THE CONTENT BOX */
  .post-content, article.post {
    margin-top: 0 !important;
    padding-top: 0 !important;
  }

  /* 3. CONTROL THE LINE EXACTLY */
  hr.teaching-divider {
    margin-top: 30px !important; /* Increase this if it is TOO close now! */
    margin-bottom: 40px !important;
    border-top: 1px solid #ddd !important;
  }
    
  /* 6. Push the footer to the absolute bottom of the screen */
  body {
    display: flex;
    flex-direction: column;
    min-height: 100vh; /* Forces the body to be at least the height of your screen */
  }
  
  body > .container, body > div.container {
    flex-grow: 1; /* Forces the middle of the page to stretch and fill the empty space */
  }

  /* Expand the about page content to match, but force it to stay perfectly centered */
  article.post, .post-content {
    max-width: 100% !important;
    padding-left: 0 !important;
    padding-right: 0 !important;
    margin: 0 auto !important; /* "auto" guarantees it stays dead-center! */
  }
    
  /* 2. SHRINK THE FOOTER */
  footer, footer.fixed-bottom, footer .container {
    font-size: 0.8rem !important;
    padding-top: 6px !important;
    padding-bottom: 6px !important;
    margin-top: 0px !important;
    height: auto !important;
    text-align: left !important;
  }
  
  /* (Optional) Force the footer to stay at the bottom of short pages */
  body {
    display: flex !important;
    flex-direction: column !important;
    min-height: 100vh !important;
  }
  .container {
    flex-grow: 1 !important;
  }

  /* TEACHING PAGE SPACING */
  /* 1. Reduce the gap between the title and the bullet points */
  p {
    margin-bottom: 5px !important; /* Shrinks the space below the title. Default is usually ~16px */
    font-size: 1.1em !important;
  }

  /* THICKER NAVIGATION BUTTONS */
  nav .navbar-nav .nav-link {
    font-weight: 400 !important; /* Change to 600 or "bold" if you want them even thicker! */
  }

  /* CHANGE NAV BAR NAME FONT THICKNESS */
  nav .navbar-brand {
    font-weight: 400 !important; 
  }

  /* CHANGE THE ACTIVE PAGE HIGHLIGHT COLOR TO BLUE */
  nav .navbar-nav .nav-item.active .nav-link,
  nav .navbar-nav .nav-link.active,
  nav .navbar-nav .nav-link:hover {
    color: #0056b3 !important; /* A nice, professional dark blue */
  }

  /* 1. OVERRIDE THE TEMPLATE'S MASTER PURPLE VARIABLE */
  :root {
    --global-theme-color: #0056b3 !important; 
  }

  /* 2. HIDE THE BORDER AT THE TOP OF THE PAGE */
  header nav.navbar {
    border-bottom: 0.2px solid transparent !important;
    box-shadow: none !important;
    transition: all 0.3s ease-in-out !important;
  }

  /* 3. FORCE BLUE ONLY WHEN SCROLLING DOWN */
  /* (Removed the permanent "fixed-top" class from here!) */
  header nav.navbar.scrolled,
  header nav.navbar.top-nav-collapse,
  header nav.navbar.auto-hiding-navbar {
    border-bottom: 0.2px solid var(--global-theme-color) !important;
    box-shadow: 0 1px 0 0 var(--global-theme-color) !important;
  }

  /* INCREASE FONT THICKNESS */
  body, p, ul, ol, li, a, td, th {
    font-weight: 300 !important; 
  }
</style>
