---
layout: default
---

{% include header.html %}

<style>
  /* THEME OVERRIDE: This pushes the theme's centered box to the far left */
  .wrapper, .container, .main-content, #main_content, .inner, .page-content {
    max-width: none !important;
    margin-left: 0 !important;
    margin-right: 0 !important;
    padding-left: 20px !important; /* Adjust this to match your desired side margin */
    width: 100% !important;
    display: block !important;
  }

  /* Your Profile Content Styles */
  .profile-container {
    display: flex;
    flex-direction: column;
    align-items: flex-start !important; 
    margin-top: 40px;
    font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
    width: 100%;
    text-align: left;
  }

  .profile-photo {
    width: 200px; 
    height: auto; 
    border-radius: 0; 
    margin-bottom: 20px;
    display: block;
  }

  .profile-name {
    font-size: 24px;
    font-weight: 700;
    margin: 0;
    color: #111;
  }

  .profile-title {
    font-size: 18px;
    color: #555;
    margin: 4px 0;
  }

  .profile-email {
    font-size: 16px;
    color: #3b71ca;
    text-decoration: none;
    margin-bottom: 40px; 
  }

  .group-header {
    font-size: 26px;
    font-weight: 700;
    margin-bottom: 30px;
    color: #111;
  }
</style>

<div class="profile-container">
  <h2 class="group-header">Group Members</h2>

  <img src="assets/me.jpg" alt="Wenjie Ji" class="profile-photo">
  <p class="profile-name">Wenjie Ji</p>
  <p class="profile-title">Principal Investigator</p>
  <a href="mailto:wenjieji@westlake.edu.cn" class="profile-email">wenjieji@westlake.edu.cn</a>
</div>
