---
layout: page
permalink: /teaching/
title: Teaching
nav: true
nav_order: 6
calendar: false
---

<hr class="teaching-divider">

<div class="teaching-content" markdown="1">

**Teaching Assistant, National University of Singapore**

* RE6010 Applied Microeconomic Theory (PhD level, Instructor: Prof. Zhonglin Li), Fall 2026
* EC5101 Microeconomic Theory (PhD level, Instructor: Prof. John Quah and Prof. Xiao Luo), Fall 2024, 2025
* EC5101 Microeconomic Theory (PhD level, Instructor: Prof. John Quah and Prof. Yi-Chun Chen), Fall 2023
* EC6101 Advanced Microeconomic Theory (PhD level, Instructor: Prof. Xiao Luo), Spring 2023

**Teaching Assistant, The Chinese University of Hong Kong**

* ECON3011 Intermediate Microeconomic Theory (undergraduate level, Instructor: Prof. Ce Matthew Shi), Spring 2020, 2021, Fall 2019, 2020

**Mentor, National University of Singapore**

* Economic Research Workshop (undergraduate), Fall 2025

</div>

<style>

  /* ================================
     PAGE TITLE
     ================================ */

  /* Shrink the main page title */
  header.post-header .post-title {
    font-size: 2rem !important;
  }


  /* ================================
     PAGE LAYOUT
     ================================ */

  /* Remove extra space below the page header */
  header.post-header {
    margin-bottom: 0 !important;
    padding-bottom: 0 !important;
  }

  /* Remove extra space above the page content */
  .post-content,
  article.post {
    margin-top: 0 !important;
    padding-top: 0 !important;
  }

  /* Keep the content wide and centered */
  article.post,
  .post-content {
    max-width: 100% !important;
    padding-left: 0 !important;
    padding-right: 0 !important;
    margin-left: auto !important;
    margin-right: auto !important;
  }


  /* ================================
     DIVIDER
     ================================ */

  hr.teaching-divider {
    margin-top: 30px !important;
    margin-bottom: 40px !important;
    border-top: 1px solid #ddd !important;
  }


  /* ================================
     TEACHING CONTENT
     ================================ */

  /* Increase the size of all teaching-page text */
  .teaching-content {
    font-size: 1.15rem !important;
  }

  /* Section headings */
  .teaching-content p,
  .teaching-content p strong,
  .teaching-content strong {
    font-size: 1.15rem !important;
  }

  /* Course entries */
  .teaching-content ul,
  .teaching-content li,
  .teaching-content li p,
  .teaching-content li span {
    font-size: 1.15rem !important;
  }

  /* Reduce space between section headings and bullet lists */
  .teaching-content p {
    margin-bottom: 5px !important;
  }

  /* Bullet-point font weight */
  .teaching-content li,
  .teaching-content li p,
  .teaching-content li span {
    font-weight: 400 !important;
  }


  /* ================================
     NAVIGATION BAR
     ================================ */

  /* Navigation links */
  nav .navbar-nav .nav-link {
    font-weight: 400 !important;
    font-size: 1.1rem !important;
    line-height: 1.2 !important;
  }

  /* Website name in navbar */
  nav .navbar-brand {
    font-weight: 400 !important;
  }

  /* Active page and hover color */
  nav .navbar-nav .nav-item.active .nav-link,
  nav .navbar-nav .nav-link.active,
  nav .navbar-nav .nav-link:hover {
    color: #0056b3 !important;
  }

  /* Override the template's theme color */
  :root {
    --global-theme-color: #0056b3 !important;
  }

  /* Hide navbar border at the top of the page */
  header nav.navbar {
    border-bottom: 0.2px solid transparent !important;
    box-shadow: none !important;

    /* Only animate border/shadow to prevent page jumping */
    transition: border-color 0.3s ease-in-out,
                box-shadow 0.3s ease-in-out !important;
  }

  /* Show blue border when scrolling */
  header nav.navbar.scrolled,
  header nav.navbar.top-nav-collapse,
  header nav.navbar.auto-hiding-navbar {
    border-bottom: 0.2px solid var(--global-theme-color) !important;
    box-shadow: 0 1px 0 0 var(--global-theme-color) !important;
  }


  /* ================================
     FOOTER
     ================================ */

  /* Push footer toward the bottom on short pages */
  body {
    display: flex !important;
    flex-direction: column !important;
    min-height: 100vh !important;
  }

  body > .container,
  body > div.container {
    flex-grow: 1 !important;
  }

  /* Make footer smaller */
  footer,
  footer.fixed-bottom,
  footer .container {
    font-size: 0.8rem !important;
    padding-top: 6px !important;
    padding-bottom: 6px !important;
    margin-top: 0 !important;
    height: auto !important;
    text-align: left !important;
  }

</style>
