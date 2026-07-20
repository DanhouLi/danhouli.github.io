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
</style>
