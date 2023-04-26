---
# An instance of the Contact widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: blank

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 10

title: Videos
subtitle:

content:
  

design:
  columns: '1'
---


<style>
    .responsive-video-container {
        position: relative;
        height: 0;
        overflow: hidden;
        text-align: center;
        max-width: 853px; /* Add max-width */
        margin: 0 auto; /* Center the container */
    }
    
    .responsive-video-container iframe {
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        border: 0;
    }
</style>
<script>
    function setVideoHeight() {
        var container = document.querySelector('.responsive-video-container');
        var width = container.offsetWidth;
        var height = width * (480 / 853); // Maintain aspect ratio (height / width)
        container.style.paddingBottom = height + 'px';
    }

    window.addEventListener('resize', setVideoHeight);
    window.addEventListener('DOMContentLoaded', setVideoHeight);
</script>

[//]: # (add videos below)
[//]: # (- MM/DD/YYYY: DESCRIPTION OF VIDEO.)
[//]: # (<div class="responsive-video-container">)
[//]: # (    <iframe src="https://www.youtube.com/embed/YOUR-VIDEO-ID" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>)
[//]: # (</div>)

- 04/13/2023: Dian Wang gave a guest lecture on Equivariant Learning for Robotic Manipulation.
<div class="responsive-video-container">
    <iframe src="https://www.youtube.com/embed/dx5rDtdv7LM" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
</div>
