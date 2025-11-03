---
layout: default
title: Research Project
---  

# My Final Research Project  

This is a big project, and you definitely want a place to show it off! Here's a suggested layout for that (but feel free to display your work however you prefer).
You can link to your project here, or embed it.
If it is easier to embed your project in an HTML file, just change the .md on this one to .html, and write in HTML! (Be sure to update the links to this page to reflect the new name though!)

# Abstract

Here is my abstract. 


# Works Cited

(add HTML code to do the hanging indentation, as seen below)

<style>
  .works-cited {
    margin-left: 2em;
    text-indent: -2em;
    line-height: 1.5;
  }
</style>

<p class="works-cited">
  Lastname, Firstname. <em>Book Title</em>. Press, 2025.
</p>

<p class="works-cited">
  Doe, Jane. "Journal Article.” <em>Journal Name</em>, vol. 15, no. 2, 2025, pp. 45–67.
</p>

<div>
<!-- HTML Block for Chatbots -->
  <!-- Load Botpress webchat only once -->
  <script src="https://cdn.botpress.cloud/webchat/v3.3/inject.js"></script>

  <!-- Each bot container -->
  <div id="oneiros-container"></div>
  <div id="logos-container"></div>
  <div id="pathos-container"></div>
  
  <script>  
    // Oneiros, The Dreamer
    window.botpressWebChat.init({
      clientId: "6ZTJIPYJ",
      container: document.getElementById("oneiros-container")
    });
  
    // Logos, The Analyst
    window.botpressWebChat.init({
      clientId: "AIMIS500",
      container: document.getElementById("logos-container")
    });
  
    // Pathos, The Listener
    window.botpressWebChat.init({
      clientId: "98f267cc-02dd-46a5-bedc-25b77ad07e1d"
    });
  </script>
</div>
