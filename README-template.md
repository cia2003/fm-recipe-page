# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### Screenshot

- On desktop Screen:
![](/screenshots/desktop-device.png)

- On Mobile Screen:
![](/screenshots/mobile-device.png)


### Links

- [Solution URL](https://github.com/cia2003)
- [Live Site URL](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I learned to use BEM methodology to increase the clarity of my code. It is useful so that I (and other developer) could read and understand my code (I hope so, :D).

I think that BEM methodology is simple to use because you can categorize the component into three: Block, Element, and Modifier. You can see the details at part [useful resources](#useful-resources).

For example, I have a code like this:

```html
<div class="card">
    <img class="card__img" src="assets/images/image-omelette.jpeg" alt="omelette_img" width="100%">
    <div class="card__content">
      <!-- Other codes -->
      <section class="card__section card__section--preparation">
        <!-- Other codes -->
      </section>
    </div>
  <!-- Other codes -->
</div>
```

I create a block called "card" so I can reuse this component in case I want to add a new recipe. After that, I create other component (img.card__img) that are tied to the "card" block. Then, I want to modify certain part, like the preparation time section. So, I use the format "element__name--modifier" to modify that section.

If there is a feedback about this project's code, please info me.

### Useful Resources

- [BEM Methodology](https://en.bem.info/methodology/quick-start/#block): This helps me to understand how to 


## Author

- Frontend Mentor - [@cia2003](https://www.frontendmentor.io/profile/cia2003)
