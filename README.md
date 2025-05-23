# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [deployment](#deplpyment)


**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

- In this project I have created a social links profiles. That contain al of my social networks profiles.

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./assets/images/Screenshot%202025-05-24%20000014.png)

A

### Links

- Solution URL: (https://github.com/pandey-prince/social-profile-links)
- Live Site URL: (https://social-profile-links-princepandey.vercel.app/)


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid



### What I learned

I majorly learned about the working of CSS and creating more intaractive sites.




```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Social Links Profile</title>
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:ital,opsz,wght@0,14..32,100..900;1,14..32,100..900&display=swap" rel="stylesheet">
</head>
<body>
    <div class="box">
        <div class="profile-photo">
            <img src="/assets/images/p.jpg" alt="profile-photo">
        </div>
        <div class="details">
            Prince Pandey <br>
            <span>Lucknow, India</span>
        </div>
        <div class="title">
            "Front-end Developer and amid reader." 
        </div>
        <div class="social-profiles">
            <div class="links">
                <a href="https://github.com/pandey-prince">GitHub</a>
            </div>
            <div class="links">
                <a href="https://www.frontendmentor.io/profile/pandey-prince">Frontend-mentor</a>
            </div>
            <div class="links">
                <a href="https://www.linkedin.com/in/prince-pandey-686863224/">Linkdln</a>
            </div>
            <div class="links">
                <a href="https://x.com/pandey___prince">Twitter</a>
            </div>
            <div class="links">
                <a href="https://www.geeksforgeeks.org/user/princepandey6150/">GeeksforGeeks</a>
            </div>
        </div>
    </div>
</body>
</html>
```
```css
*{
    font-family:Inter, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
    color:white;
     
}
body{
    background-color: hsl(0, 0%, 8%);
    display: flex;
    align-items: center;
    justify-content: center;
    padding-top:5%;
}
.box{
    display:flex;
    flex-direction: column;
    align-items: center;
    justify-content: space-between;
    
    width:240px;
    background-color:hsl(0, 0%, 12%) ;
    border-radius:8px;
   
}
.profile-photo{
    margin-bottom: 10px;
    margin-top:10px;
    transition:transform 0.3s ease;
}
.profile-photo img{
    width:100px;
    border-radius: 50px;

}

.details{
    
    margin-bottom: 10px;
    font-weight: 700;
}
.details span{
    margin-top:7px;
    font-weight: 400;
    color:yellow;
}

.title{
   
    font-size:14px;
    margin-bottom:10px;
    text-align: center;
    font-weight: 400;
   
}

.social-profiles{
    
    display:flex;
    flex-direction: column;

}

.links{
    background-color:hsl(0, 0%, 20%);
    padding-left:40px;
    padding-bottom:10px;
    padding-right:40px;
    padding-top:10px;
    margin-bottom:10px;
    
    text-align: center;
    font-weight: 600;
    border-radius:7px;
    transition: background-color 0.3s ease, color 0.3s ease,transofrom 0.3s ease;

    
}
.links:hover{
    cursor: pointer;
    background-color: yellow;
    a{
        color:black;
    }
}

.profile-photo:hover img,
.links:hover
{
    transform: scale(1.07);
    cursor: pointer;
}

.links a{
    text-decoration: none;
}
```

### Deployment 

- User vercel.com for the deployment of the project.