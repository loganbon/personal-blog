---
title: Nothing Here Yet...
subtitle: Here is some extra detail about the post.
layout: post
date: 2020-06-21
keywords: blogging, writing
published: true
---

Here are some words. And this is some math:

# header
{% katexmm %}
$$
e = mc^2. \tag{1}
$$
{% endkatexmm %}

Cool!

<canvas id="myCanvas" width="200" height="200"></canvas>

<script>
    const canvas = document.querySelector("#myCanvas")
    canvas.width  = canvas.getWidth();
    canvas.height = 200
    const ctx = canvas.getContext("2d")
    // fill color of rectangle
    ctx.fillStyle = "tomato"    
    // draw rectangle, and fill it with "tomato" color  
    // x = 10  
    // y = 20  
    // width = 200  
    // height = 300  
    ctx.fillRect(0, 0, 300, 300)
    // now change style to stroke 
    ctx.strokeStyle = "green"    
    // draw rectangle with "green" color stroke (no fill)  
</script>