# Customer Display


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
- Starting from the starter file ( technical-task-L2.html below) please build out this display of customers, their names, logos, and call-to-action buttons according to the comp in image 1 below.
- You should use the customers array in the starter file to write each customer’s data as a child of div.customers-container .
- Use vanilla HTML, CSS, and JS (ES6 okay) — no libraries or frameworks.
- At mobile breakpoints (~500px wide or below), the customer cards should collapse to a single column. (See image 3 below)
- When you hover one of the call-to-action buttons, the colors of the button should reverse. (See image 2 below).
- We encourage you to start with and spend the most time on whatever piece feels most comfortable to you. If you are less comfortable with JS, you are welcome to start with static HTML on the page before you write the script — or vice versa. Show us what you are best at
- Looking stuff up is fine and expected.

### Screenshot
### Mobile view
![Screenshot 2022-03-09 at 16-56-14 Technical Task for L2](https://user-images.githubusercontent.com/19538219/157553712-aa840ba9-e0c0-4a12-b506-e59e70c074c4.png)

### Desktop view
![Screenshot 2022-03-09 at 16-55-51 Technical Task for L2](https://user-images.githubusercontent.com/19538219/157553745-e18ed897-376a-4812-a8ca-3d1286279b2d.png)




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
