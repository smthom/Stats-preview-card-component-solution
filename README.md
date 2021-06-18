# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). 
Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![screenshot of desktop view](./screenshot.jpg)
![screenshot of mobile view](./screenshot2.jpg)

### Links

- Solution URL: [Solution](https://github.com/smthom/Stats-preview-card-component-solution)
- Live Site URL: [Live Site](https://smthom.github.io/Stats-preview-card-component-solution/stats_preview.html)

## My process

Looking at the design, I knew I wanted to apply the element to a grid. In the CSS, I 
arranged the stat card into a grid of 1 row and 2 columns, a text box and an image 
box. Within the text box, I created another grid to help give, the header text, 
description and stats their own space within the text box. This process was supported
by arranged each element within a number of nested 'div' tags. I used the responsive
view in FireFox to begin work on the layout for various devices with different widths.
For smaller widths, I created a media query that altered the structure of the grids to 
allow everything to be displayed in a single column.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

I found out that you can see the layouts of grid using the developer tools in FireFox, 
you can toggle a number of grids and they will be highlighted in different colours 
within the tool.

I learned how to create a colour overlay that applies a colour over an image.

I learned how to add google fonts to the HTML and make use of them in the CSS.
I used the 'mark' tag in the HTML to highlight the word 'insight' in the description 
header. 

I found I wasn't able to get rid of the background colour. I finally learned to 
eliminate the highlight colour was to make it completely transparent.

I found I could add images to the page using CSS and not just by using the HTML.

I learned I can create curved corners of a border individually rather than just 
applying the same property to all the corners at once. Meaning I could round of the 
certain corners I need to round off.

### Continued development

At this point I want to keep practicing the use of CSS in the design of webpages. I will
aim to find more challenges to get the practice in. I've seen other examples of CSS code
where there isn't large amounts of code contained in the media queries which leads me to 
believe there are ways of refining the code I am using in this area.

### Useful resources

- [Kevin Powell](https://www.youtube.com/channel/UCJZv4d5rbIKd4QHMPkcABCw) - I've learned 
alot from this YouTuber so far and his videos were a help for some of the aspects of this 
project.

## Author

- Frontend Mentor - [@smthom](https://www.frontendmentor.io/profile/smthom)
