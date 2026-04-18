# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm) 

## Welcome! 👋

Thanks for checking out this front-end coding challenge.

## The challenge

[My challenge is to build this recipe page](./preview.jpg) and get it looking as close to the design as possible using HTML and CSS.

### Screenshot

[Design preview for the Recipe page coding challenge,desktop view](recipepagescreenshot(desktop%20view).JPG)

[Design preview for the Recipe page coding challenge,mobile](recipepagescreenshot(mobileview).JPG)

### Links

- Solution URL: [Solution URL](https://github.com/Bennyufy/FrontEndMentorRecipePageChallenge.git)
- Live Site URL: [Add live site URL](https://bennyufy.github.io/FrontEndMentorRecipePageChallenge/)

## My process

I started with the HTML code to build the body of the webpage.
I  made sure i linked the stylesheet and icon image in the head part of the code.
Building the body,i made a class named container to contain all the content.
In the body,i first linked the image, then i created a div for the content excluding the image for styling purposes.
In that div,there is an h1 element, a p element and another div with a class named preparation-time for the preparation time part of the page.
Next in the body is another div for the ingredients part of the web page.
Then i created a div with a class called instructions for the instructions part of the web page.
Next in the body is a div with the class nutrition where the nutrition part is,this div contains 4 different divs with classes called row and ul ol grouping for the Nutritions table.
Closing the Div container and main,I built the footer element and I closed the body and the html. 

Next is designing the web page with CSS.
First,i added the colors in the :root property so i can add them as easy values later.
Then,the * property with borderbox.
Next is the body with the background color,font,line-height to properly space out the letters and a padding of 1 rem for proper spacing.
Next was the .container property was background-color,margin,padding,border-radius and hidden overflow.
Then i made the .image width 100% to fill up the page.
Next was the h1,h2,h3 with their colors and font-weight. 
I made the p element have a margin-bottom to space the words out,and the ul and ol have a margin and padding to look like a proper table.
I styled the .preparation-time class,.nutrition class,.row classes,.value class and the .attribution class. all styled to look like the recipe page as much as possible.
Then,i made the web page responsive by first designing for a mobile device under 767px,I adjusted the body,.container class,.content class and .image class to be responsive on a mobile device.
Finally,i made the webpage responsive for devices above 768px,i adjusted the body and h1 for responsiveness for bigger devices.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow


### What I learned

I learnt that sectioning some parts of the web page were easy ways to properly style the Page


```html
proud of this html
<div>
  <h2>Ingredients</h2>
<ul>
  <li>2-3 large eggs</li> 
  <li>Salt, to taste</li>
  <li>Pepper, to taste</li>
  <li>1 tablespoon of butter or oil</li>
  <li>Optional fillings: cheese, diced vegetables, cooked meats, herbs</li>
</ul>
</div>
```
```css
.proud-of-this-css {
  @media screen and (max-width: 767px) {
    body{
        margin:0;
       padding:0;
    }
}
```
## Author

- Frontend Mentor - [@Bennyufy](https://www.frontendmentor.io/profile/Bennyufy)
- Github - [@Bennyufy](https://github.com/Bennyufy)
