---
layout: default
---

{% include header.html %}

<style>
  /* Container forces everything to the LEFT */
  .profile-container {
    display: flex;
    flex-direction: column;
    align-items: flex-start; 
    margin-top: 40px;
    font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
    width: 100%;
  }

  .profile-photo {
    width: 200px; /* Adjust width as needed */
    height: auto; /* Maintains aspect ratio */
    border-radius: 0; /* Ensures rectangle shape */
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
    margin-bottom: 40px; /* Space before the next person */
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
