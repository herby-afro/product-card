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

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./screenshot/descktop-screenshot.jpg)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- HTML5
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned

This project is one of many projects that [Frontend Mentor](https://www.frontendmentor.io) offers free to anyone who wants to learn how to code and design websites. I suppose that for great code developers and/or for experienced programmers, these types of challenges are very simple, but the truth is that I have realized that working only with html and css (basic knowledge) is something that everyone who wants to become a good developer must master.

With the practical method of the Frontend Mentor challenges (something similar to clone style) I have learned not to forget the basics and not only in programming, in all kinds of knowledge that is acquired.

I learned to design a responsive card with classes named by me (and others by renowned libraries) which shows me that by learning programming languages correctly, we can make computers transmit anything we want to express to the whole world.

I remembered some HTML tags that I just stopped using and came up with some CSS classes while trying to make the card responsive

```html
<header></header>
<main></main>
<footer></footer>
```
```css
.the-container, .grid-container, .card, .card-image-top, .etc...{

}



.card-image-top {
  ...
}

y

.card-image-left {
  ...
}
```

The truth is that if it took me some time to make the two images that come in the starter package for the construction of this project [descktop-design.jpg](./design/descktop-design.jpg) and [mobile - design.jpg](./design/mobile-design.jpg) will be displayed each depending on the size of the user's screen.

At first it was a bit frustrating and I was about to copy the code from any existing library like Bootstrap or any other that would solve the problem for me, but I would only fool myself.

So I started browsing until I discovered that by applying the "display" property to the selector to the image shown on smartphones with the value ":none", they hid that image and showed the image intended for computer screens [.card- image-left] (/images/image-product-desktop.jpg)
```css
.card-image-top {display:none;}

.card-image-left {display:inline-flex}
```
In this way I was able to add the other elements of the html document and I gave them the style that was closest to the prewview of the challenge.
So when I continued with the design of the product card but now with the necessary features to be displayed correctly on smaller screens, I only added the media query that is triggered when the browser detects that the screen has reduced its size to a maximum value of 444px hiding the image [.card-image-left](/images/image-product-desktop.jpg) and instead displaying the image for smartphones [.card-image-top](./design/mobile-design. jpg)
```css
@media only screen and (max-width: 444px) {
  .card-img-left {
    display: none;
  }
  .card-img-top {
    display: inline-flex;
    width: 100%;
  }
}
```

It is worth mentioning that it uses css grid as the guiding base of all the css code that gives those responsive characteristics to the solution that I found for this challenge.


### Continued development

Undoubtedly, css style sheets and their rules are something that if you don't use them often, over time it is somewhat difficult to remember their benefits, for this reason css is something that I will always try to develop or program according to the needs of each project. Avoiding using libraries that although they offer structured content and facilitate optimal experiences for users, I think that for someone who is learning they only hinder learning.

The next thing to learn will be to modify the html elements and style them but with javascript


### Useful resources

- [W3-Schools](https://www.w3schools.com/ - De los primeros curso en línea que realicé. los recomiendo para quienes están empenzando y para mantener como referencia en estapas avanzadas del aprendizaje.
- [Developer.mozila-CSS_Grid_Layout](https://developer.mozilla.org/es/docs/Web/CSS/CSS_Grid_Layout) - No sé tú pero para mi estos devs son unos cracks y con su sección Tecnología para el desarrollo web' pude darle solucion al reto de [Frontend Mentor](https://www.frontendmentor.io).
- [Bootstrap] (https://getbootstrap.com/) Creo que no hay nada mejor que trbajar con la librería que estos masters en desarrollo han creado y mantienen al día con actualizaciones cada vez más sorprendentes.

## Author

- Website - [herby-afro - GitHub](https://github.com/herby-afro)
- Frontend Mentor - [@herby-afro](https://www.frontendmentor.io/profile/herby-afro)
- Twitter - [@Estriplet3](https://www.twitter.com/Estriplet3)


## Acknowledgments
Developer initiatives that motivate new students with free online programs are welcome. Personally, I thank [Frontend Mentor](https://www.frontendmentor.io) for the ease with which they have provided their challenges to anyone who wants to learn and/or improve their design and programming skills.
The main reason why I have decided to stop copying and pasting other people's code to see how websites are made is that I have decided to take seriously this fascinating career that is software development and programming.
My next step is to get into the online school of [Microverse](https://apply.microverse.org/) The learning and job placement opportunities are good and to get in but above all to finish satisfactorily with the plan of studies, I will be closer to my goal.

So Thank you and may the code be on your side


