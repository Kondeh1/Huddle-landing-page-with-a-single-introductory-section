# Frontend Mentor - Huddle landing page with single introductory section solution

This is a solution to the [Huddle landing page with single introductory section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)
- [Acknowledgments](#acknowledgments)



## Overview

### The challenge

Users should be able to:

- View the optimal layout for the page depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![](images/Screenshot%20001.png)
![](images/Screenshot%20002.png)
![](images/Screenshot%20003.png)
![](images/Screenshot%20004.png)


### Links

- Solution URL: [Repository link](https://github.com/Kondeh1/Huddle-landing-page-with-a-single-introductory-section)
- Live Site URL: [Live site](https://kondeh1.github.io/Huddle-landing-page-with-a-single-introductory-section/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox (Flex)
- [Styled Components](https://fonts.google.com/specimen/Poppins) - For font styles



### What I learned

I doing this it was quite simple compare to my first frontend mentor challenges, i learned more about creating responsive design, which was my best path.

```html
<h1>Some HTML code I'm proud of</h1>
```
```css
 @media (min-width: 300px) and (max-width: 800px){
      body{
       background-image: url(./images/bg-mobile.svg);
       background-repeat: no-repeat;
      }
      .container{
        flex-direction: column;
        margin: 30px;
      }
      .child{
        text-align: center;
        width: 100%;
      }
      .f-icon{
      display: flex;
      justify-content: center;
      margin-top: 60px;
    }
    .child > button{
      width: 250px;
      height: 40px;
      border-radius: 20px;
      border: none;
    }
    }
    
    @media  (min-width: 801px) and (max-width: 1440px) {
      .child{
        margin-left: 30px;
      }
      .container{
        margin-left: 35px;
      }
       .f-icon{
      display: flex;
      justify-content: end;
      margin-top: 60px;
    }
    }
```


**Note: Delete this note and the content within this section and replace with your own learnings.**

### Continued development

Concerning the area i want to focus on more is creating more responsive and user frendly design, this area will make me become a better version of myself.



## Author

- Website - [Moriba Sahr Kondeh](https://www.your-site.com)
- Frontend Mentor - [@Kondeh1](https://www.frontendmentor.io/profile/Kondeh1)
- Twitter - [@KondehMe](https://www.twitter.com/KondehMe)



## Acknowledgments

I would like to express my sincere gratitude for the opportunity to participate in this Frontend Mentor challenge. Completing this project has been an invaluable learning experience, allowing me to deepen my understanding of (e.g.median queries, flexbox and responsive design). I am proud of the work accomplished and appreciate the platform Frontend Mentor provides for practical, real-world coding challenges.
It's well.
