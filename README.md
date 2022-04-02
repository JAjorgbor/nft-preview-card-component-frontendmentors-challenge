# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)

  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)



## Overview
Design preview for the NFT preview card component coding challenge](./design/desktop-preview.jpg)
### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./screenshots/Screenshot%202022-04-02%20at%2018-50-12%20Frontend%20Mentor%20NFT%20preview%20card%20component.png)
![](./screenshots/Screenshot%202022-04-02%20at%2018-50-42%20Frontend%20Mentor%20NFT%20preview%20card%20component.png)



### Links

- Solution URL: (https://github.com/joshuaAj003/nft-preview-card-component-frontendmentors-challenge)
- Live Site URL:( https://joshuaaj003.github.io/nft-preview-card-component-frontendmentors-challenge/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Mobile-first workflow




### What I learned

I learnt how to implement css animations into a hover effect
```html
<div class="blue-background"></div>
            <img src="./images/icon-view.svg" alt="" class="image-icon">
        </div>
```
```css
.card-image {
    border-radius: 10px;
    width: 87%;
    margin: 20px auto 0 auto;
    height: 45%;
}

.image-icon {
    position: absolute;
    bottom: 40%;
    left: 42%;
    z-index: -1;
}

.blue-background {
    position: absolute;
    top: 29%;
    left: 28%;
    background-color: var(--Cyan);
    width: 43.6%;
    height: 46.1%;
    opacity: 0.5;
    border-radius: 5px;
    z-index: -1;
    transition: transform 0.1s;
    cursor: pointer;
}

.card-pics:hover .blue-background {
    z-index: 0;
    transform: scale(2, 2);
}

.card-pics:hover .image-icon {
    z-index: 0;
}

```


### Continued development

I want to focus on getting better at using css animations in future projects 



### Useful resources

- [w3schools](https://www.w3schools.com/css/css3_animations.asp) - This helped me understand css animations to a certain level . 

## Author

- Website - [Joshua Ajorgbor](https://github.com/joshuaAj003/nft-preview-card-component-frontendmentors-challenge)
- Frontend Mentor - [@joshuaAj003](https://www.frontendmentor.io/profile/joshuaAj003)
- Twitter - [@JAjorgbor](https://www.twitter.com/JAjorgbor)



