# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshots](#screenshots)
  - [Links](#links)

- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)
## Overview
### Screenshots
https://github.com/sunilsharmapoudel/qrcomponent/blob/9b2bd92471345ca374354bc8248b1442a7014c94/design/desktop-design.jpg

https://github.com/sunilsharmapoudel/qrcomponent/blob/master/design/mobile-design.jpg

### Links

- Live Site URL: [https://sunilsharmapoudel.github.io/qrcomponent/](https://sunilsharmapoudel.github.io/qrcomponent/)

## My process
Structured the html and then finished the CSS part.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Mobile-first workflow

### What I learned

By participating in this challenge I mainly learned to use media querries for mobile first approach.

```html
<div class="container">
  <div class="qr-container">
    <div class="qr-holder">
      <img class="qr-img" src="images/image-qr-code.png" alt="QR">
    </div>
    <div class="qr-dec">
      <p class="bold-para">Improve your front-end skills by building projects</p>
      <p class="light-para">Scan the QR code to visit Frontend Mentor and take you rcoding skills to the next level.</p>
    </div>
  </div>
</div>
```
```css
body {
      background-color: hsl(0, 0%, 100%);
    }
    .container {
    
      background-color:hsl(212, 45%, 89%);
      width: 375px;
      margin-left: auto;
      margin-right: auto;
      padding-top: 50px;
      padding-bottom: 50px;
      margin-top: 50px;
      box-shadow: 5px 20px 40px  lightblue;
    }
    .qr-container {
      background-color: hsl(0, 0%, 100%);
      width: 250px;
      height: 400px;
      border-radius: 5%;
      margin-left: auto;
      margin-right: auto;
      position: relative;
      padding: 10px;
    }
    .qr-img{
      display: block;
      width: 250px;
      border-radius: 5%;
      margin-left: auto;
      margin-right: auto;
      
    }
    .qr-dec {
      text-align: center;
      margin-top: 20px;
      margin-bottom: 20px;
      font-family:'Outfit', sans-serif;
    }

    .bold-para {
      font-weight: 700;
      font-size: 20px;
      color: hsl(218, 44%, 22%);
    }
    .light-para {
      font-weight: 400;
      font-size: 15px;
      color:  hsl(220, 15%, 55%);
    }

    @media only screen and (min-width: 992px) {
      .container {
        width: 1440px;
      }
    }
```

## Author

- Website - [Sunil Sharma](https://github.com/sunilsharmapoudel)
- Facebook - [@mesunilsharmapoudel](https://www.facebook.com/mesunilsharmapoudel)
- Twitter - [@techsunilsharma](https://www.twitter.com/techsunilsharma)
