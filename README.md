# stats-preview-card
Frontend Mentor Challenge - stats preview card component

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Accessibility Resources](#accessibility-resources )
  - [Continued development](#continued-development)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- Page should be responsive.

### Screenshot

![Stats preview card](/Screenshots/Desktop-Screenshot-Stats-Preview-Card.png)

![Stats preview card](/Screenshots/Mobile-Screenshot-Stats-Preview-Card.png.png)

### Links

- Solution URL: https://matthew-millard.github.io/stats-preview-card/

## My process

### Built with

- HTML
- CSS
- Grid
- Flexbox
- Firefox Developers Tools
- VS Code
- Mobile-first workflow
- BEM

### What I learned

- Overlay 

``` 
.card__overlay {
    opacity: 0.5;
    background-color: hsl(277, 64%, 61%);
    width: 100%;
    height: 100%;
    position: absolute;
    top: 0;    
}

```
- Using display: flex on the body to center the component, rather than using absolute positioning. 
``` 
body {
display: flex; 
}
``` 


- Hide content for accessibility. I was previously making the mistake setting `{visibility: hidden;}` Now I do the following:
``` 
.hidden {position: absolute !important;
    height: 1px;
    width: 1px;
    overflow: hidden;
    clip: rect(1px 1px 1px 1px);
    clip: rect(1px, 1px, 1px, 1px);}
```

- Trying out the justify-self property on a grid container to align the contents center. It wasn't required.


### Accessibility Resources 

- [](https://www.a11yproject.com/posts/how-to-hide-content/)

- [](https://snook.ca/archives/html_and_css/hiding-content-for-accessibility)

- [](https://developer.chrome.com/blog/full-accessibility-tree/)

### Continued development

- Accessibility practise.
- Keep trying to write efficent and readable code.
- Make an effort to add comments in the code.
- Develop a better workflow.

## Author

- Frontend Mentor - [@matthew-millard](https://www.frontendmentor.io/profile/matthew-millard)

- Github - [matthew-millard](https://github.com/matthew-millard)

## Acknowledgments

- Oh Shit, Git!?! [Ohshitgit.com](https://ohshitgit.com/)



