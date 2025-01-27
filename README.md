# Frontend Mentor - Interactive rating component solution

This is a solution to the [Interactive rating component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/interactive-rating-component-koxpeBUmI).

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I Did](#what-i-did)
- [Author](#author)

## Overview

### The challenge

The challenge is to build out this interactive rating component and get it looking as close to the design as possible.


Users should be able to:

- View the optimal layout for the app depending on their device's screen size
- See hover states for all interactive elements on the page
- Select and submit a number rating
- See the "Thank you" card state after submitting a rating

This is how the design should look like 

![Desktop Design](./design/desktop-preview.jpg)

This is how the active states should look like

![Active States](./design/active-states.jpg)

This is the Thank You state, which appears when you click the Submit button after selecting a rating.

![Than You state](./design/desktop-thank-you-state.jpg)

---

### Screenshot

This is how my solutions looks like.

- First we have the Desktop design with the two states Rating state and Thank You state

![My Solution](./design/My_Desktop_Solution.png)
![My Solution ThanksState](./design/My_Desktop_Solution_2.png)

- Finally we have the Mobile design with the two states Rating state and Thank You state

![My Solution](./design/My_Mobile_Solution.png)
![My Solution ThanksState](./design/My_Mobile_Solution_2.png)


When the mouse hovers over any of the ratings from 1 to 5, they are highlighted in orange. The same happens with the Submit button, but it turns white.

Once a rating is clicked, it changes to white and remains that way until another rating is selected or the rating is submitted, triggering the Thank You state.

---

### Links

- Solution URL: [Frontend Solution](https://www.frontendmentor.io/solutions/interactive-rating-component-with-js-html-and-css-L-g1nMn20h)
- Live Site URL: [Interactive Rating Component](https://ness505.github.io/Interactive-Rating-Component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- JavaScript


### What I Did

To ensure that submitting the form changed the content within the same page rather than loading a different page, I used **JavaScript** and **CSS** with functions like ***display*** and ***block*** on the divs containing the main content for each state. I also utilized the ***value*** and ***checked*** properties of the radio buttons to determine the rating selected by the user.


## Author

- Frontend Mentor - [@ness505](https://www.frontendmentor.io/profile/ness505)
