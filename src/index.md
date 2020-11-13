---
title: My first page!
layout: base.njk
templateEngineOverride: njk,md
---

<button>Independent developer</button>  &nbsp;&nbsp; Normal button 

<button class="disabled">Register</button>  &nbsp;&nbsp; Disabled button 

<button class="accent-button">Get Started</button>  &nbsp;&nbsp; Accent button 

<!-- <button class="muted-button">Register</button> -->


## Blog Posts
{% include "postlist.njk" %}

## Cat of the Day

<img src="{{ catpic }}">
