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
</style>

<script>
    /* 2. SHRINK THE FOOTER */
    const footer = document.querySelector('footer');
    const footerContainer = footer ? footer.querySelector('.container') : null;
    
    if (footer) {
      footer.className = footer.className.replace(/\b(mt-\d+|py-\d+|pt-\d+|pb-\d+)\b/g, '');
      footer.style.paddingTop = "10px";
      footer.style.paddingBottom = "10px";
      footer.style.marginTop = "20px";
    }
    
    if (footerContainer) {
      footerContainer.className = footerContainer.className.replace(/\b(mt-\d+|py-\d+|pt-\d+|pb-\d+)\b/g, '');
      footerContainer.style.padding = "0";
    }
  });
</script>

