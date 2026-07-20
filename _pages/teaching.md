---
layout: page
permalink: /teaching/
title: Teaching
description: Course materials, schedules, and resources for classes taught.
nav: true
nav_order: 6
calendar: true
---

This page displays a collection of courses with detailed schedules, materials, and resources. You can organize your courses by years, terms, or topics.

{% include calendar.liquid calendar_id='test@gmail.com' timezone='Asia/Shanghai' %}

{% include courses.liquid %}

<style>
    /* 6. Push the footer to the absolute bottom of the screen */
  body {
    display: flex;
    flex-direction: column;
    min-height: 100vh; /* Forces the body to be at least the height of your screen */
  }
  
  body > .container, body > div.container {
    flex-grow: 1; /* Forces the middle of the page to stretch and fill the empty space */
  }

  footer {
    margin-top: auto !important; /* Pushes the footer to the very bottom of that stretched space */
  }

  /* 7. Reduce the footer font size */
  footer, footer .container {
    font-size: 0.8rem !important; /* Adjust this number to be smaller (e.g., 0.75rem) or larger */
  }

  /* Expand the about page content to match, but force it to stay perfectly centered */
  article.post, .post-content {
    max-width: 100% !important;
    padding-left: 0 !important;
    padding-right: 0 !important;
    margin: 0 auto !important; /* "auto" guarantees it stays dead-center! */
  }
/* 2. SHRINK THE FOOTER */
  footer, footer.fixed-bottom {
    padding-top: 10px !important;
    padding-bottom: 10px !important;
    margin-top: 20px !important;
    height: auto !important;
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
</style>

