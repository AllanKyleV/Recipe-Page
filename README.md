# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

- Recipe Page: a challenge to create a 'Recipe Page' from the Frontend Mentor.

### Screenshot

![](/screenshot/Screenshot.png)

### Links

- Solution URL: [https://github.com/AllanKyleV/Recipe-Page](https://your-solution-url.com)
- Live Site URL: [https://allankylev.github.io/Recipe-Page/](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

While building with this project, I have encountered an issue with an ordered list, the spacing between the bullets and the text of the list does not behave the way I expected, also, there is a part of the text that should be in larger font-weight while the rest stays at default, using span element for the bolded text creates a block behavior that pushes the rest of the text as a new block and the text wraps below that block. The text should cover the whole list.

The internet suggest that I should try ::marker with this problem. And I did. What I learned is that ::marker separates the bullet and the text without converting them as block element, in that way I was able to apply some part of the text border and the rest as default. Also, I was be able change the colors of the bullet without affecting the text.

PS. English is not my first language, please don't take my english and grammar seroiusly.

## Author

- Frontend Mentor - [@allankylev](https://www.frontendmentor.io/profile/AllanKyleV)