# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### Links

- Solution URL: [Git Repo](https://github.com/N1Dovud/Recipe-Page)
- Live URL: [Live Site](https://n1dovud.github.io/Recipe-Page)


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- tables, ordered and unordered lists

### What I learned

I learned about pseudo selector `::before` which is used for creating content that precedes the list item. I did not know about it before. I also studied about hr, its semantic meaning and how to style it according to my own taste. Other than that, I figured out that there is another selector `::marker` which is used to refer to the bullet point or some other content that comes before the list item. Lastly, I learned how to apply a different styling to the last child of a parent by using the `last-child` pseudo selector. 
```css
ul li::before {
    content: "\2022";
    display: inline-block;
    font-size: 1.5rem;
    margin-right: 1.5rem;
    color: var(--Dark-Raspberry);
    position: relative;
    top: 2px;
}
.line {
    border:none;
    background-color: var(--Light-Grey);
    height: 1px;
    margin-top:1rem;
}
ol li::marker {
    color: var(--Nutmeg);
    font-weight: 700;
}
tr:last-child {
    border-bottom: none;
}
```
### Continued development
I need to continue to work on creating really cool responsive websites. The problem I have is I am not sure about when to use rem exactly. Am I supposed to use it instead of pixels everywhere. If yes, why? Because I can also use flex for responsiveness, how do I create high level design without causing any confusion or interruptions because of using both rem and flexbox. Lastly, should I use vh and vw for responsiveness too. If yes, when exactly?

## Author
- Frontend Mentor - [N1Dovud](https://www.frontendmentor.io/profile/N1Dovud)