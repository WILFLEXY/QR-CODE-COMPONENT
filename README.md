# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- Overview
  - Screenshot
  - Links
- My process
  - Built with
  - What I learned
  - Continued development
  - Useful resources
- Author
- Acknowledgments


## Overview

### Screenshot

![](./screenshot.jpg)

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Bootstrap 5
- Mobile-first workflow


### What I learned

This was my first hands on project using Bootstrap 5. I learnt to integrate Bootstrap functionalities such as container breakpoints, card and other Bootstrap 5 utilities into into a real project. I also learnt to use basic css styling to override Bootstrap 5 style. And to use media query to build a responsive website.

Code snippets:

```html
<div class="card-footer text-center text-white bg-primary rounded">Designed By | Umahi Wilfred | 2023</div>
```
```css
.container-sm{
      background-color: hsl(212, 45%, 89%);
      padding: 80px 0 80px 0;
      height: 100vh;
    }
```
```Bootstrap 5
<div class="card mx-auto" style="max-width: 300px;">
      <img src="./images/image-qr-code.png" class="card-img-top p-3" alt="qr-code-image">
      <div class="card-body">
        <h4 class="card-title text-center fw-bold">Improve your front-end skills by building projects</h4>
        <p class="card-text text-center">Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
      </div>
      <div class="card-footer text-center text-white bg-primary rounded">Designed By | Umahi Wilfred | 2023</div>
    </div>
``````Media query
@media screen and (min-width: 768px) {

      #container{
        height: 80vh;
        margin-top: 60px;
        margin-bottom: 60px;
        padding: 70px 0 70px 0;
      }
    }
```

### Continued development

I enjoyed using Bootstrap and hope to consolidate on its use in future projects.

### Useful resources

- [Bootstrap 5 documentation](https://getbootstrap.com/docs/5.0/) - This was helpful with the needed Bootstrap 5 classes.

- [Google](https://www.google.com) - This was helpful with further research during the cause of building


## Author

- Website - [Umahi Wilfred](https://github.com/WILFLEXY)
- Frontend Mentor - [@WILFLEXY](https://www.frontendmentor.io/profile/WILFLEXY)


## Acknowledgments

I acknowledge and celebrate Umahi Wilfred for his commitment to personal growth.