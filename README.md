# 3 Column card component - Practice with HTML & CSS

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)

## Overview

### The challenge

- Create the basic HTML framework for a 3 column code product card component 
- Use CSS to style the page to match the design spec

## My process

### Built with

- Semantic HTML5 markup
- CSS

### What I learned

This challenge was a step up from the QR code challenge in terms of being able to figure out flex box and how to get the corrent alignment, sizing and content within a respose set of 3 product cards. I had some minor issues around figuring out how to set a border-radius around only 4 of the edges, as it always set the border-radius across each each of the 3 product cards. 

Also, some issues around the responsiveness, I was able to set the site to be responsive to mobiles, but in this process (when sizing down) I found that the content in each product card would spill, also the button for the third card would not be visible. I was able to rectify the button issue, but still researching the spill issue. 


CSS in mention
```css
@media screen and (max-width:1440px){
    .container-sub{
        width: 30%;
    }
}


@media screen and (max-width:800px){
    .container-sub{
        width: 90%;
    }
}
```

