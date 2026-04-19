---
layout: default
---

{% include header.html %}

<style>
  .member-row {
    display: flex;
    align-items: flex-start;
    gap: 25px;
    margin-top: 40px;
    margin-bottom: 50px;
    font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
  }

  .member-photo {
    width: 180px;
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

  .bold-name { font-weight: 700; }
  .normal-status { font-weight: 400; color: #333; }

  .email-line {
    font-size: 15px;
    color: #3b71ca;
    text-decoration: none;
    margin: 4px 0 8px 0;
  }

  .bio-line {
    font-size: 15px;
    color: #222;
    line-height: 1.6;
    margin: 0;
  }

  .group-header {
    font-size: 26px;
    font-weight: 700;
    margin: 40px 0 20px 0;
    font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
  }
</style>

<h2 class="group-header">Group Members</h2>

<div class="member-row">
  <img src="assets/me.jpg" alt="Wenjie Ji" class="member-photo">
  <div class="member-details">
    <p class="name-line">
      <span class="bold-name">Wenjie Ji</span> 
      <span class="normal-status">(Principal Investigator)</span>
    </p>
    <a href="mailto:wenjieji@westlake.edu.cn" class="email-line">wenjieji@westlake.edu.cn</a>
    <p class="bio-line">
      Wenjie Ji is an Associate Professor in the Department of Physics at Westlake University. Her research interests 
      include theoretical condensed matter physics, and 
      quantum information science.
    </p>
  </div>
</div>
