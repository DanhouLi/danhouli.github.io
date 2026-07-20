---
layout: about
title: About
permalink: /
# subtitle: <a href='#'>Affiliations</a>. Address. Contacts. Motto. Etc.

profile:
  align: left
  image: 1013.jpg
  image_circular: false
  more_info: '<div style="text-align: center; width: 100%; line-height: 1.3;"><div style="font-size: 1.3em; font-weight: bold; margin-bottom: 2px;">Danhou Li</div><div style="font-size: 0.9em;">PhD Candidate in Economics<br>National University of Singapore</div></div>'
  
selected_papers: false
social: false

announcements:
  enabled: false

latest_posts:
  enabled: false
---

Welcome to my homepage!

I am a PhD student from the Department of Economics, National University of Singapore (NUS). Prior to this, I obtained my Bachelor’s and Master’s degrees from Chinese University of Hong Kong (CUHK).

Research Interests: Industrial Organization, Platform Economics, Digital Economy

My recent projects focus on platform leakage (disintermediation) and price discrimination of Internet service providers, encompassing both theoretical and empirical approaches.

Happy to connect and chat!

<p>Here is my <a href="{{ '/assets/pdf/Danhou_Li_CV.pdf' | relative_url }}" target="_blank" style="color: darkblue !important; text-decoration: underline !important;font-weight: bold;">CV</a>.</p>

<p>Email: <a href="mailto:danhou@u.nus.edu" style="color: darkblue !important; text-decoration: underline !important; font-weight: bold;">danhou@u.nus.edu</a></p>

<style>
  /* Import the clean, modern Roboto font */
  @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap');
  
  /* 1. Hide the giant name block on the homepage */
  .post-header, h1.post-title {
    display: none !important;
  }

  /* 2. Force the name to appear in the top navbar on the homepage */
  /* Targets both old Bootstrap and new Tailwind title classes */
  nav .navbar-brand, nav .title, header .title {
    display: block !important;
    opacity: 1 !important;
    visibility: visible !important;
  }

  /* 3. Apply the new sans-serif font to all text */
  body, p, h1, h2, h3, h4, h5, h6, a, span, div, .title {
    font-family: 'Roboto', sans-serif !important;
  }

  /* 4. Resize and perfectly center the profile photo */
  .profile img {
    max-width: 250px !important; /* Change this number to adjust size */
    width: 100% !important;
    height: auto !important;
    margin: 0 auto !important; 
    display: block !important;
  }
  
  /* 5. Force the container below the photo to align to the center */
  .profile .address, .profile .more-info {
    text-align: center !important;
    width: 100% !important;
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

  /* Nudge the right-side menu buttons to perfectly align with other pages */
  nav .navbar-collapse, nav .navbar-nav {
    padding-right: 4px !important; /* Increase this to push buttons further left, or decrease to push right */
  }
  
  /* Dial back the navigation name nudge */
  nav .navbar-brand {
    margin-left: -6px !important; /* Try 0px first. If it needs a tiny push, try 2px or 3px */
  }
</style>

<script>
  document.addEventListener("DOMContentLoaded", function() {
    /* 1. EXACT CLONE OF THE NAVBAR NAME */
    const navbarContainer = document.querySelector('nav .container') || document.querySelector('nav');
    
    if (navbarContainer && !document.querySelector('.navbar-brand')) {
      const myName = document.createElement('a');
      
      /* Use the exact template classes used on your other pages */
      myName.className = 'navbar-brand title font-weight-lighter';
      myName.href = '/'; 
      myName.innerText = 'Danhou Li';
      
      myName.style.fontFamily = "'Roboto', sans-serif";
      myName.style.display = 'inline-block';
      
      navbarContainer.insertBefore(myName, navbarContainer.firstChild);
    }
</script>
