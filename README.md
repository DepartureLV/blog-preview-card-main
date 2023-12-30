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
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

- the challenge is to use the understanding in HTML and CSS to create a preview card.

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./screenshot/screenshot1.jpg)

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

I learned that <figure> tag can be used as self-contained content, potentially with an optional caption, which is specified using the <figcaption> element.

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

### !!!This part below will be revise when i'm done with the code in the final commit

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.**

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**
