# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview
*This is me taking up the product-card-component challenge from [Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). An inside look on how I tackled the challenge, you will see screenshots of the finished product, and the process I took for the challenge.*
### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![Desktop View](/overview/desktop-view.png)
![Mobile View](/overview/mobile-view.png)
![Active State](/overview/active-state.png)

### Links

- Live Site URL: [Live-site](dd-product-card-component.netlify.app)

## My process
**I always start with looking into the design first so I can plan ahead and come up with a solution on how to tackle the project.**

1. I built the structure of the project using HTML, adding all the necessary assets such as the stylesheet, scripts, fonts, or icons needed for the project. 
 - For this project the structure includes a container which holds the component, I created a `<div>` with the class of 'container'.
 - Inside the container is another `<div>` with the class of 'product-card' this container is the card component.
 - The card component is separated by two `<div>`'s left and right the left containing an image for the product image and the right contains contains two `<div>`'s which serves as the container for the product-description and the product-price and a `<button>` to add the product to your cart.
2. After I created the markup I proceed on making the design.
 - I set the container to display flex so I can center the card component properly. There are other ways to center a component but I find this much easier since I only have one component.
 - I also set the product-card (`<div class="product-card>"`) to display flex since I'm starting on a desktop first workflow which makes it easier to have two colums for each `<div>` inside the product card. Which is the `<div class=product-card__left>` and `<div class=product-card__right>`
 - The `<div class=product-card__right>` has a helper class `flex-colum` which is reusable, this set's the container to a flex with a vertical main axis.
 - For responsiveness, I used the Sass Mixins so I can easily implement media queries.
 - I used two breakpoints at 375px and 550px.
 - The flex direction of the product-card will be set to column once the screen size is below 550px.
 - The rest of the components adjusts depending on the screen size of the user.
### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Desktop-first workflow
- [Sass](https://sass-lang.com/) - Sass preprocessor
- [Google fonts](https://fonts.google.com/) - For font-styles


### What I learned

I learned how to efficiently use flex-box on this design and I also learned how to use Sass mixins to implement media queries, Sass mixins are very helpful not just for implementing media queries, you can also use it to create a mixin that will make a component absolute and centered.

### Continued development

I'm still working on mastering flexbox for different layouts and applications. I also want to learn how to use sass mixins and functions, and implement it to my project.

### Useful resources

- [Udemy](https://www.udemy.com/) - This helped me get started with web development and design and gave me a strong foundation.
- [mdndocs](https://developer.mozilla.org/en-US/) - This helped me a lot when I'm having troubles with my html, css, or even javascript. I find this really useful especially when learning new techniques.
- [chatGPT](https://openai.com/product/chatgpt) - ChatGPT is really helpful when I'm encountering errors that I have never encounterd before or if I forgot something and I need a quick recall.

## Author

- Frontend Mentor - [@daviidii](https://www.frontendmentor.io/profile/daviidii)
- GitHub - [@daviidii](https://github.com/daviidii)
