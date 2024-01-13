# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot
![](screenshots/desktop.png)

![](screenshots/mobile.png)

### Links

- Live Site URL:  ![](https://adebimpeabdulhamideniola.github.io/testimonial_grid/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned
My knowledge of CSS  grids is further enhanced
```
main {
        grid-template-areas: 
            "first first second fifth"
            "third fourth fourth fifth";
        gap: 1.6em;
        grid-template-columns: repeat(4,277px);        /*giving the grid-template-rows and grid template columns, specific width and height in specific units not `fr` so as to match the design given */ 
        grid-template-rows: 310px 350px;

    
    }

```

## Author
Adebimpe Abdulhamid Eniola
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Whatsapp: +2348109419385
