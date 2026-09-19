# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)
- [Acknowledgments](#acknowledgments)



## Overview
This is basically a frontend Mentor 
challenge to make a blog preview card 
.It is quite interesting and challenging
most especially to newbies and mobile 
users like myself,i would recommend
this challenge to a learner like to help
become more used to handling html and css. 
### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./img-Screenshot.jpg) 

### Links

- Solution URL: [solution URL ](https://github.com/Bisaac-coder/blog-preview-card-main)
- Live Site URL: [ live site ](https://bisaac-coder.github.io/blog-preview-card-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS internal styling <style>



### What I learned
i learnt how to use box-shadow property
for styling more effectively and also 
how to import fonts and use them .lastly
i improved my html structuring.




```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0"> <!-- displays site properly based on user's device -->

  <link rel="icon" type="image/png" sizes="32x32" href="./assets/images/favicon-32x32.png">
  
  <title>Frontend Mentor | Blog preview card</title>

  
  
</head>
<body>
  <div class="main">
  <img class="one" src="./assets/images/illustration-article.svg" alt="illustration-article">
  <header>
    <b class="b">
      Learning  
    </b>
  </header>

  <p>
    Published 21 Dec 2023
  </p> 
  
    <a href="#"> 
   <h2>
    HTML & CSS foundations
  </h2> 
      </a>
    <div class="text">
     <p>
    These languages are the backbone
    of every website, defining structure,
    content, and presentation.
     </p>
   </div>

    <span>
    <img class="two" src="./assets/images/image-avatar.webp" alt="image-avatar" width="50px" height="50px">
   
  <p class="ll">
    Greg Hooper
  </p>
  </span>
      
    
  <footer class="attribution">
    Challenge by <a href="https://www.frontendmentor.io?ref=challenge">Frontend Mentor</a>. 
    Coded by <a href="https://www.frontendmentor.io/profile/Bisaac-coder">Bisaac-coder</a>.
  </footer>
    </div>
</body>
</html> 
```
```css
  
  @font-face {font-family:figtree;
    src: url(./assets/fonts/static/Figtree-medium.ttf)
    format("truetype");
  }
  @font-face {font-family:figtreeExtra;
    src: url(./assets/fonts/static/Figtree-ExtraBold.ttf)
    format("truetype");
  }
  
  *{
    margin:0;
    padding:0;
    box-sizing:border-box;
  }
  
  body{
    font-family:figtree;
    background-color:#f4d04e;
    min-width:320px;
   min-height:400px;
  }
  
 .main{
    background-color:#fff;
    width:320px;
    min-height:400px;
    padding:20px;
   
    margin:20px auto;
     display:flex;
    flex-direction:column;
    gap:16px;
   border:2px solid #333;
   border-radius:30px;
   box-shadow:9px 10px 0px -3px  #000;
   
  }
  
 .one{
  border-radius:24px;
  height:auto;
   width:100%;
  display:block;
 }
  .b {
    display:inline-block;
  background-color: #f4d04e;
  padding: 4px 12px;
  border-radius: 4px;
  font-weight: 800;
  font-family: figtreeExtra;

}
 

  a{
    text-decoration:none;
    color:inherit;
  }
  a:hover h2{
   color: hsl(35, 77%, 62%);
  }
  a:focus h2 {
  color: hsl(35, 77%, 62%);
  outline: 1px double #333;
}
  h2{
    font-size:22px;
   font-family:figtreeExtra;
  }
  .text{
   min-width:190px;
    min-height:10px;
    margin-bottom:50px;
    color:hsl(0, 0%, 42%);
    font-size:14px;
 
  }
  .two{
    border-radius:100%;
  }
  
  .ll{

    font-weight:900;
    font-family:figtreeExtra;
  }
  
  span{
    display:flex;
    flex-direction:row;
    align-items:center;
    gap:10px;
   
  }
  
  
    .attribution { font-size: 0.6875rem; text-align: center; }
    .attribution a { color: hsl(228, 45%, 44%);  }
  
 
```





### Continued development
I would like to master html and css 
,so i would continue to focus on them 
as a beginner ,most especially using css concepts




### Useful resources

-  resource 1. Claude  - This helped me during debugging
and i would like to use it in the future.



### AI Collaboration

Describe how you used AI tools (if any) during this project. This helps demonstrate your ability to work effectively with AI assistants.

- tools I used? Claude
- How  I used them ? debugging, brainstorming solutions
- What worked well? 
debugging and brainstorming
 solution.
What didn't?
well i didn't understand claude's concept on 
the border radius of my image.

## Author


- Frontend Mentor - [@Bisaac-coder](https://www.frontendmentor.io/profile/Bisaac-coder)
- Twitter - [@Isaackbags](https://www.twitter.com/Isaackbags)


## Acknowledgments

special thanks to kenedybok my mentor,
dave gray's - youtube videos and
frontend mentor for the challenge.
