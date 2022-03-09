# Email Generator


This is a solution to the [dbt Lab take home challenge](#). 

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

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page
- Receive an error message when the `form` is submitted if:
  - The `input` field is empty
  - The email address is not formatted correctly

### Screenshot
![Screenshot 2021-12-09 at 22-13-33 Base Apparel Coming Soon](https://user-images.githubusercontent.com/19538219/145516742-522aadd6-26c9-4af8-947c-68e22ac658eb.png)


### Links

- Repo URL: [https://github.com/sadiejay/dbtlabs-take-home](https://github.com/sadiejay/dbtlabs-take-home)
- Live Site URL: [https://sadiejay.github.io/dbtlabs-take-home/index](https://sadiejay.github.io/dbtlabs-take-home/index)

## My process
- Built out basic HTML structure
    - got one div structured first before copy and pasting using vscode shortcuts
- Add styling
    - focused on mobile-first layout with flexbox
    - added desktop media query
    - used CSS for hover states 

### Built with

- Semantic HTML5
- Flexbox
- Mobile-first workflow


### What I learned

- Need to declare height if you want all the cards the same outside of content
- The order for link states matter!

  #### code snippets

```css
    .customers-container {
        display: flex;
        flex-flow: column wrap;
        justify-content: center;
        align-items: center;
        gap: 20px;
    }
```
  - `gap` vs `margin` is something I need to investigate, but it works great!


### Continued development

- I would love to `align-self` the buttons to the bottom to create a more consistent look.
    - as well as set the `aspect-ratio` for each logo and get them all the same size.

- Would also like to explore creating the site using JS to avoid hard coding. I think it could be done without a framework, by using some sort of `for` loop and then making the elements of the DOM using JS.
    - I've never done it, but I'm tempted to try it.

### Useful resources

- [Box shadow Generator](https://html-css-js.com/css/generator/box-shadow/) - Box shadow generator
- [Styling Links Like a Boss](https://css-tricks.com/css-basics-styling-links-like-boss/) - Learned about link state styling order importance.
- [Difference Between Width and Flex Basis](https://mastery.games/post/the-difference-between-width-and-flex-basis/) - was thinking to use flex basis but 

## Author

- Github - [@sadiejay](https://github.com/sadiejay)


## Acknowledgments
 - Thank you dbt Labs for this opportunity!
