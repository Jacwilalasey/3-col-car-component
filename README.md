# 3 Column card component - Practice with HTML & CSS

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)

## Overview

### The challenge

- Create the basic HTML framework for a QR code card component 
- Use CSS to style the page to match the design spec

## My process

### Built with

- Semantic HTML5 markup
- CSS

### What I learned

Issues figuring out how to put a border radius across only 4 corners of the 3 columns.

Issues with sizing of the product card as a whole.

HTML in mention
```html
<body>
  <div class="container-main flex">
    <div class="container-sub">
      <img src="./images/image-qr-code.png" style="width:250px; height:250px;" alt="">
      <p><b>Improve your front-end skills by building projects</b></p>
      <p class="subtext">Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>  
    </div>
  </div>
</body>-->
```

CSS in mention
```css
<!--.container-sub {
    margin: auto;
    border-radius: .6rem;
    justify-items: center;
    background-color: hsl(0, 0%, 100%);
    max-width: 50%;
    box-shadow: 5px 5px 10px 5px hsl(220, 15%, 55%);
} -->
```

