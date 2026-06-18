---
layout: default
---
<style>
  /* This stretches the page so the header can actually fit in one line */
  .wrapper {
    max-width: 1000px !important; 
    margin: 0 auto !important;
  }
  /* This hides the theme's empty sidebar area entirely */
  header {
    display: none !important;
  }
  /* This ensures our new content uses the full width */
  section {
    width: 100% !important;
    float: none !important;
  }
</style>

<style>
  header h1 a { color: #333 !important; } /* #333 is a nice "soft" black */
  header h1 a:hover { color: #000 !important; } /* Full black when hovering */
</style>

<style>
  body {
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif;
    color: #333;
    line-height: 1.6;
  }
</style>

{% include header.html %}
