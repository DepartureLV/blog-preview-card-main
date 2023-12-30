# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources) -->
  - [Author](#author)

## Task list

- [x] build HTML
- [x] style with pure CSS
- [x] complete the hover CSS
- [x] minor fix (font size, font weight, color, padding, margin, gap, etc.)

## Overview

- the challenge is to use the understanding in HTML and CSS to create a preview card.

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![solution screenshot (Desktop)](./screenshot/Solution%20Screenshot%20Desktop.png.jpg)
![solution screenshot (Mobile)](./screenshot/Solution%20Screenshot%20Mobile.png)

## My process

- Step1: build a required semantic HTML
- Step2: using CSS to style each element
- Step3: DONE! 😙

### Built with

- Semantic HTML5 markup
- pure CSS (maybe will try Tailwind or Bootstrap next time!!)
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

~~I learned that 'Figure' tag can be used as self-contained content, potentially with an optional caption, which is specified using the 'figcaption' element.~~
Thanks to [@xphstos](https://www.frontendmentor.io/solutions/cardbox-using-pure-css-and-figure-tag-in-html-bM89OA-QOL#comment-659040ac7869d8b98a3fd58e:~:text=%40DepartureLV%20Yes%20a,for%20the%20date.) comment, I decided to remove **figure** and **figcapture**, and replace with plain **img** **div** and **time** tag

```html
<figure class="Head-container">
  <img src="./assets/images/illustration-article.svg" alt="illustration" />
  <figcaption class="card-tag">Learning</figcaption>
  <figcaption class="publish-date">Published 21 Dec 2023</figcaption>
</figure>
```

I learned that I can set variable to use repeatedly in many sections by using :root then add --(variable name): (CSS value)

```css
:root {
  --primary-color: rgb(245, 208, 78);
}
. . . .card-tag {
  background-color: var(--primary-color);
}
```

### Continued development

- **clean code**
  - some CSS and html is not fully cleaned up, so i may clean it up later.
- **responsive**
  - because the mobile and desktop provided design are the same, I coded it with the fixed width and height for the card. but I assumed that the card should be responsive to the screen size. I will improve it later.
  - the hover state preview showed that the **Title** should turn yellow when hovering over. but it also shows that it is clickable too. So this may lead to somewhere. I will take this as a future extension part of this mini-project.

### Useful resources

- [Transition Generator](https://webcode.tools/css-generator/transition) - This helped me figure out which parameters should I use for the transition of the card.
- [README preview](https://readme.so/editor) - Because i'm new to Github readme. This is an amazing tool which helped me to look at the final version of the README which will be shown in the repository.

## Author

- LinkedIn - [Nattawat Pitikomon](https://www.linkedin.com/in/nattawat-pitikomon/)
- Frontend Mentor - [@departureLV](https://www.frontendmentor.io/profile/DepartureLV)
