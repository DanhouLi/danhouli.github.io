---
layout: about
title: About
permalink: /
# subtitle: <a href='#'>Affiliations</a>. Address. Contacts. Motto. Etc.

profile:
  align: left
  image: new_photo_website.png
  image_circular: false
  more_info: '<div style="text-align: center; width: 100%; line-height: 1.3;"><div style="font-size: 1.5em; font-weight: 500; margin-bottom: 2px;">Danhou Li <span style="margin-left: 5px;"> 李丹厚</span></div><div style="font-weight: 400; font-size: 1em;">PhD Candidate in Economics<br>National University of Singapore</div></div>'
  
selected_papers: false
social: false

announcements:
  enabled: false

latest_posts:
  enabled: false
---

<div style="font-weight: 400; font-size: 1.15em; font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;" markdown="1">

Welcome to my homepage!

I am Danhou Li, a PhD candidate from the Department of Economics, National University of Singapore (NUS). Before joining NUS, I obtained my Bachelor’s and Master’s degrees in economics from the Chinese University of Hong Kong (CUHK).

Research Interests: Industrial Organization, Platform Economics, Digital Economy

My recent projects focus on platform leakage (disintermediation) and price discrimination of Internet service providers, encompassing both theoretical and empirical approaches.

Happy to connect and chat!

<p>Here is my <a href="{{ 'assets/pdf/Danhou_Li_CV.pdf' | relative_url }}" target="_blank" style="color: #0056b3 !important; text-decoration: underline !important;">CV</a>.</p>

<p>Email: <a href="mailto:danhou@u.nus.edu" style="color: #0056b3 !important; text-decoration: underline !important;">danhou@u.nus.edu</a></p>

</div>

<style>

  /* =========================================
     PAGE WIDTH / SCROLLBAR
     ========================================= */

  html {
    overflow-y: scroll;
  }


  /* =========================================
     PAGE FONT
     ========================================= */

  /*
   * Do NOT import Roboto from Google Fonts here.
   * The font download/swap was causing the page jump.
   */
  body,
  p,
  h1,
  h2,
  h3,
  h4,
  h5,
  h6,
  a,
  span,
  div,
  .title {
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI",
                 Roboto, Helvetica, Arial, sans-serif !important;
  }


  /* =========================================
     ABOUT PAGE HEADER
     ========================================= */

  /* Hide the giant page title on the homepage */
  .post-header,
  h1.post-title {
    display: none !important;
  }

  /* Allow the navbar name to appear */
  nav .navbar-brand,
  nav .title,
  header .title {
    display: block !important;
    opacity: 1 !important;
    visibility: visible !important;
  }


  /* =========================================
     PROFILE PHOTO
     ========================================= */

  .profile img {
    max-width: 250px !important;
    width: 100% !important;
    height: auto !important;
    margin: 0 auto !important;
    display: block !important;
  }

  /* Center the information below the photo */
  .profile .address,
  .profile .more-info {
    text-align: center !important;
    width: 100% !important;
  }


  /* =========================================
     MAIN PAGE LAYOUT
     ========================================= */

  body {
    display: flex !important;
    flex-direction: column !important;
    min-height: 100vh !important;
  }

  body > .container,
  body > div.container {
    flex-grow: 1 !important;
  }

  article.post,
  .post-content {
    max-width: 100% !important;
    padding-left: 0 !important;
    padding-right: 0 !important;
    margin-left: auto !important;
    margin-right: auto !important;
  }


  /* =========================================
     NAVIGATION BAR
     ========================================= */

  /*
   * Give the navbar explicit and consistent
   * vertical spacing.
   *
   * Use these SAME two padding values on
   * Research and Teaching.
   */
  header nav.navbar {
    padding-top: 0.5rem !important;
    padding-bottom: 0.5rem !important;

    border-bottom: 0.2px solid transparent !important;
    box-shadow: none !important;

    /* Prevent navbar initialization animations */
    transition: none !important;
  }

  /* Vertically center everything inside the navbar */
  header nav.navbar .container {
    align-items: center !important;
  }

  /* Right-side navigation buttons */
  nav .navbar-nav .nav-link {
    font-weight: 400 !important;
    font-size: 1.1rem !important;
    line-height: 1.2 !important;
  }

  /*
   * Navbar name.
   * Do NOT force font-size or line-height here.
   * Let the theme use its normal navbar-brand geometry.
   */
  nav .navbar-brand {
    font-weight: 400 !important;
  }

  /* No manual horizontal nudge */
  nav .navbar-collapse,
  nav .navbar-nav {
    padding-right: 0 !important;
  }

  /* Active page / hover color */
  nav .navbar-nav .nav-item.active .nav-link,
  nav .navbar-nav .nav-link.active,
  nav .navbar-nav .nav-link:hover {
    color: #0056b3 !important;
  }

  /* Override the template's theme color */
  :root {
    --global-theme-color: #0056b3 !important;
  }

  /* Blue line after scrolling */
  header nav.navbar.scrolled,
  header nav.navbar.top-nav-collapse {
    border-bottom: 0.2px solid var(--global-theme-color) !important;
    box-shadow: 0 1px 0 0 var(--global-theme-color) !important;
  }


  /* =========================================
     MAIN TEXT FONT WEIGHT
     ========================================= */

  body,
  p,
  ul,
  ol,
  li,
  a,
  td,
  th {
    font-weight: 400 !important;
  }


  /* =========================================
     FOOTER
     ========================================= */

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

  /* Restore lighter footer font */
  footer,
  footer p,
  footer a,
  footer span,
  footer div,
  footer .container {
    font-weight: 300 !important;
  }

</style>

<script>
  document.addEventListener("DOMContentLoaded", function() { /* 1. EXACT CLONE OF THE NAVBAR NAME */ 
    const navbarContainer = document.querySelector('nav .container') || document.querySelector('nav'); 
    if (navbarContainer && !document.querySelector('.navbar-brand')) { const myName = document.createElement('a'); 
    /* Use the exact template classes used on your other pages */ 
    myName.className = 'navbar-brand title font-weight-lighter'; 
    myName.innerText = 'Danhou Li'; 
    myName.style.fontFamily = "'Roboto', sans-serif"; 
    myName.style.display = 'inline-block'; 
    myName.style.fontWeight = '400';
    navbarContainer.insertBefore(myName, navbarContainer.firstChild); } });
</script>
