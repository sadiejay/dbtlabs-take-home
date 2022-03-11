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
![Screenshot 2022-03-11 at 00-50-16 Technical Task for L2](https://user-images.githubusercontent.com/19538219/157818011-a8ecc490-afa3-4d60-9575-d585cfa93ecc.png)


### Desktop view
![Screenshot 2022-03-11 at 00-50-02 Technical Task for L2](https://user-images.githubusercontent.com/19538219/157817987-6117374a-403a-42c3-a406-c90df03809d1.png)





### Links

- Repo URL: [https://github.com/sadiejay/dbtlabs-take-home](https://github.com/sadiejay/dbtlabs-take-home)
- Live Site URL: [https://sadiejay.github.io/dbtlabs-take-home/index](https://sadiejay.github.io/dbtlabs-take-home/index)

## My process
- Using pseudocode
  - Break down the design into chunks and write out what all needed to be created
    - in order from Outside - Inside starting with the customers-container div
      - the individual cards
        - the company name
        - company image
        - company link
  - Then google how to create dom elements with js
    - insert needed code with an idea of keeping variable names consistent
  - Look up `for each` loop syntax
- Created the `for each` method and gave `customers` as the parameter
- Logged my for each loop to see if it was working
- Inserted my first element from pseduocode (individual cards)
  - Create a style rule to see what was happening:
  ```css
  div {
    outline: red 1px solid;
  }
  ```
- Inserted the rest of my element as defined from pseduocode
- Added styles as time allowed

### Built with

- Pseudocode
- JS script
- Stackoverflow
- CSS Flexbox
- Media queries


### What I learned

- I CAN DO IT!! 🙌🏾 🙌🏾 🙌🏾  I sorely underestimated myself and my abilities 😭 I'm excited to implement what I've learned in other projects, especially my in progress [email generator](https://github.com/sadiejay/email-generator)!

  #### code snippets

```javascript
const customerCard = document.createElement("div");
  customerCard.className = "customer-card";
  const customersContainer = document.querySelector('.customers-container');
  customersContainer.appendChild(customerCard);
```


### Continued development

- I could continue to add the styling for example to the a tags as well as play around with sizing of the cards.
- I'm curious if I could add mulitle class names using js but I couldn't figure that out with the time I gave myself


### Useful resources

- [Adding images to an HTML document with JavaScript](https://stackoverflow.com/questions/2735881/adding-images-to-an-html-document-with-javascript) - Trying to understand the syntax of adding an img and the src and this was super helpful.
- [How to add <a> tag and href using javascript [duplicate]](https://stackoverflow.com/questions/45193524/how-to-add-a-tag-and-href-using-javascript) - Same with understanding how set the `href` attribute for the links.
- [JavaScript forEach – How to Loop Through an Array in JS](https://www.freecodecamp.org/news/javascript-foreach-how-to-loop-through-an-array-in-js/) - I was debating whether to do a for loop but I'm so glad I refreshed my memory on the forEach method. It's so much simpler.
    (something like this for reference):
    ```javascript
    for (i = 0 i < customers.length i++){
      ...
    }
    ```

- [JavaScript- how to print p element inside div](https://stackoverflow.com/questions/39286511/javascript-how-to-print-p-element-inside-div) - Not only did this help for creating the p elements, but also for creating classes!
- [Document.getElementsByClassName()](https://developer.mozilla.org/en-US/docs/Web/API/Document/getElementsByClassName) - This is what I DON'T want - I think it's more useful for creating an array of elements with x class name.

## Author

- Github - [@sadiejay](https://github.com/sadiejay)


## Acknowledgments
 - Thank you Thank you Thank you Lise and Rob. There are no words to express the depths of my gradtitude.
