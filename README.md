# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges helps me improve my coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview
This is the component card challenge from the frontend mentor where I have used the basic of HTML5 and Custom CSS3 & Bootstrap v4.6 to bring the layout as provided in the design files of the project.

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size (Mobile Resposive).
- Being able to implement the CSS overlay for the image provided with the respective stats table .

### Screenshot

![image](https://user-images.githubusercontent.com/42742924/118837346-6f0b5500-b8e4-11eb-928e-cc8f3df221ad.png)
![image](https://user-images.githubusercontent.com/42742924/118837404-7d597100-b8e4-11eb-977e-de1b0ab76433.png)


### Links

- Solution URL: https://github.com/Skyz03/component-card
- Live Site URL: https://skyz03.github.io/component-card/index.html

## My process

- As this is the start of the project, so the basic measure taken to solve this challenge was implementing the HTML5 elements to make the design as equivalent as the given design files. 
- Implementation of styles.css to make the Custom style as it is via use of CSS positioning as Display property.
- Finally, the layouts of all the components was accomplished using Bootstrap grid. 

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Bootstrap v4.6

### What I learned

The major thing that I learned in this challenge was the implemetation of BootStrap grid layouts, plus CSS color overlay section which bring that outstanding purple color to the image.    


```bootstrap
<div class="row stats">

        <div class="col-lg-4">
          <h3 class="stats-heading"> 10k+</h3>
          <p class="stats-description">companies</p>
        </div>

        <div class=" col-lg-4">
          <h3 class="stats-heading">314</h3>
          <p class="stats-description">templates</p>
        </div>

        <div class="col-lg-4">
          <h3 class="stats-heading">12M+</h3>
          <p class="stats-description">queries</p>
        </div>

      </div>
```

```css
.stats {
  position: relative;
  top: 50px;
```


### Useful resources

- (https://getbootstrap.com/docs/4.0/layout/grid/) - This helped me for quick & easy responsive layout.
- {https://developer.mozilla.org/en-US/docs/Web/CSS/grid} - This helped me understand the grid basics before even applying bootstrap


## Author

- Website - Aakib Shah Sayed (https://www.your-site.com)
- Frontend Mentor - [@Skyz03](https://www.frontendmentor.io/profile/Skyz03)

## Acknowledgments

I grabbed the resposive idea for mobile version of stats from his avaialble code and made it much simpler with bootstrap

- Solution Link: https://www.frontendmentor.io/solutions/atom-and-google-crome-uLj2PughJ
- UserName: John Cornelissen
