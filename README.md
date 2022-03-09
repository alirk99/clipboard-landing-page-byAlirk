# Frontend Mentor - Clipboard landing page solution

This is a solution to the [Clipboard landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/clipboard-landing-page-5cc9bccd6c4c91111378ecb9). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
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

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://alirk99.github.io/clipboard-landing-page-byAlirk/)

## My process

### Built with

- Semantic HTML5 markup like; header, section, nav, footer.
- Flexbox used in section 1 (s1), footer, navigation links, social links.
- Media Query to give separate styling in small and large width screens.

### What I learned

- In this project i used media query first time and its a powerfull method to specify CSS styling depending on device size etc, i am looking forward to learn more variations of this command. 
- Flexbox also has many variations possible, some of its commands were used in this project. I enjoyed the convenience it offers to achieve various designs. 
- I also used CSS variables to call colors of buttons.
```CSS
:root{
    --cyan: hsl(171, 66%, 44%);
    --blue: hsl(233, 100%, 69%);
}  
``` 
- Hover selector was used to provide interactive experience to navigation links and download buttons.
```CSS
.ios:hover, .mac:hover{
    cursor: pointer;
    opacity: .7;
}
``` 

### Continued development

- I want to make this site more optimized and make the code more concise.
- There was some issue with selectors syntax, i want to clerify my concept for how to use selectors in a more effective way.
- I could not produce the hover effect on social links because they are images not text, i might have to replace the images while hovering. 

### Useful resources

- (https://www.w3schools.com/css/default.asp) - This site helped me with all CSS syntax and concepts for various commands. Its very easy to use, learn, and understand resource.

## Author

- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

## Acknowledgments

- (https://youtube.com/playlist?list=PLu0W_9lII9agiCUZYRsvtGTXdxkzPyItg) - I want to acknowledge this Youtube channel for teaching web development from vary basics. I learned the use of many CSS commands from here.

