---
layout: default
---

{% include header.html %}

<style>
  /* 1. GLOBAL LAYOUT RESET: Force the theme to the far left */
  body, .wrapper, .container, .main-content, #main_content, .inner, .page-content, main {
    max-width: none !important;
    margin-left: 0 !important;
    margin-right: auto !important;
    padding-left: 20px !important; /* This is your actual margin from the screen edge */
    width: 100% !important;
    display: block !important;
  }

  /* 2. MEMBER CONTAINER */
  .member-row {
    display: flex;
    align-items: flex-start;
    gap: 25px; /* Space between photo and text */
    margin-bottom: 40px;
    font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
    text-align: left;
  }

  .member-photo {
    width: 180px; /* Adjust size to match the screenshot style */
    height: auto;
    flex-shrink: 0;
    border-radius: 0;
  }

  .member-details {
    display: flex;
    flex-direction: column;
  }

  /* Line 1: Bold Name + Normal Status */
  .name-line {
    font-size: 19px;
    margin: 0;
    line-height: 1.4;
    color: #000;
  }

  .bold-name {
    font-weight: 700;
  }

  .normal-status {
    font-weight: 400;
    color: #333;
  }

  /* Line 2: Email */
  .email-line {
    font-size: 15px;
    color: #3b71ca;
    text-decoration: none;
    margin: 4px 0 8px 0;
  }

  /* Line 3: Short Bio */
  .bio-line {
    font-size: 15px;
    color: #222;
    line-height: 1.6;
    margin: 0;
    max-width: 800px; /* Prevents text from stretching too wide */
  }

  .group-header {
    font-size: 26px;
    font-weight: 700;
    margin: 40px 0 30px 0;
    font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
  }
</style>

<div class="profile-container">
  <h2 class="group-header">Group Members</h2>

  <div class="member-row">
    <img src="assets/me.jpg" alt="Wenjie Ji" class="member-photo">
    
    <div class="member-details">
      <p class="name-line">
        <span class="bold-name">Wenjie Ji</span> 
        <span class="normal-status">Principal Investigator</span>
      </p>
      
      <a href="mailto:wenjieji@westlake.edu.cn" class="email-line">wenjieji@westlake.edu.cn</a>
      
      <p class="bio-line">
        Wenjie Ji is an Associate Professor at Westlake University. Her research interests 
        include theoretical condensed matter physics, and 
        quantum information science. 
      </p>
    </div>
  </div>
</div>
