---
layout: default
---

{% include header.html %}

<style>
  /* 1. MINIMAL THEME FULL-WIDTH RESET */
  /* This kills the theme's sidebar-style layout and centers the whole page */
  header {
    width: 100% !important;
    float: none !important;
    position: relative !important;
    margin: 0 0 40px 0 !important;
  }

  section {
    width: 100% !important;
    float: none !important;
    margin: 0 !important;
    padding: 0 !important;
  }

  .wrapper {
    max-width: 900px !important; /* Limits width for readability, but keeps it left */
    margin-left: 0 !important; 
    padding-left: 40px !important;
  }

  /* 2. MEMBER CONTAINER STYLE */
  .member-row {
    display: flex;
    align-items: flex-start;
    gap: 30px;
    margin-bottom: 50px;
    font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
  }

  .member-photo {
    width: 200px;
    height: auto;
    flex-shrink: 0;
  }

  .member-details {
    display: flex;
    flex-direction: column;
  }

  .name-line {
    font-size: 19px;
    margin: 0;
    color: #000;
  }

  .bold-name {
    font-weight: 700;
  }

  .normal-status {
    font-weight: 400;
    color: #555;
  }

  .email-line {
    font-size: 15px;
    color: #3b71ca;
    text-decoration: none;
    margin: 4px 0 10px 0;
  }

  .bio-line {
    font-size: 15px;
    color: #333;
    line-height: 1.6;
    margin: 0;
  }

  .group-header {
    font-size: 25px;
    font-weight: 700;
    margin: 40px 0 30px 0;
    font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
  }
</style>

<h2 class="group-header">Group Members</h2>

<div class="member-row">
  <img src="assets/me.jpg" alt="Wenjie Ji" class="member-photo">
  
  <div class="member-details">
    <p class="name-line">
      <span class="bold-name">Wenjie Ji</span> 
      <span class="normal-status">Principal Investigator</span>
    </p>
    <a href="mailto:wenjieji@westlake.edu.cn" class="email-line">wenjieji@westlake.edu.cn</a>
    <p class="member-bio">
      Wenjie Ji is an Associate Professor at Westlake University. Her research interests 
      include theoretical condensed matter physics, and 
      quantum information science.
    </p>
  </div>
</div>
