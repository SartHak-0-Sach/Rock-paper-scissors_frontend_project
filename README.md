# Rock Paper Scissors

## Experience the classic game of Rock Paper Scissors in a sleek and interactive online format. Play against the computer and test your luck!

## Table of Contents

- [Overview](#overview)
  - [The Challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My Process](#my-process)
  - [Built With](#built-with)
  - [What I Learned](#what-i-learned)
  - [Continued Development](#continued-development)
  - [Useful Resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)
- [Got Feedback for Me?](#got-feedback-for-me)

## Overview

### The Challenge

Experience the classic game of Rock Paper Scissors in a sleek and interactive online format. Play against the computer and test your luck!

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![Design Preview](./design/desktop-preview.jpg)

### Links

- Solution URL: [GitHub Repository](https://github.com/SartHak-0-Sach/Rock-paper-scissors_frontend_project)
- Live Site URL: [Live Site](https://rock-paper-scissors-frontend.netlify.app/)

## My Process

### Built With

- HTML5
- CSS3
- JavaScript

You will find all the required assets in the `/design` folder. The assets are already optimized.

There is also a `style-guide.md` file containing the information you'll need, such as color palette and fonts.

### What I Learned

- Implementing game logic for Rock Paper Scissors in JavaScript
- Styling and animating elements for an engaging user experience
- Handling user input and computer-generated choices for gameplay

This given code snippet I have mentioned took me a lot of time to implement due to the complexity of this design and thus really helped me out in clearing my CSS concepts to the next level.

```css
.game-body__circle-container-paper{
    position: absolute;
    left: 0;
    top: -6.5rem;
}
.game-body__circle-container-scissors{
    position: absolute;
    right: 0;
    top: -6.5rem;
}
.game-body__circle-container-rock{
    position: absolute;
    left: 50%;
    bottom: 6rem;
    transform: translateX(-50%);
}
.game-body__circle-container-paper,
.game-body__circle-container-scissors,
.game-body__circle-container-rock{
    transition: all 0.5s ease-in-out;
}
.game-body__big-circle{
    width: 13rem;
    height: 13rem;
    border-radius: 50%;
    overflow: hidden;
    position: relative;
    box-shadow: 0 3px 3px rgb(0 0 0 / 25%);
}
.game-body__big-circle--dark-blue{
    background-color: #2642bf;
}
.game-body__big-circle--dark-yellow{
    background-color: #c76b18;
}
.game-body__big-circle--dark-red{
    background-color: #9d1736;
}
.game-body__big-circle--light-blue,
.game-body__big-circle--light-yellow,
.game-body__big-circle--light-red{
    transform: translateY(-6px) scale(1.03);
}
.game-body__big-circle--light-blue{
    background-image: linear-gradient(120deg, hsl(230, 89%, 62%), hsl(230, 89%, 65%));
}
.game-body__big-circle--light-yellow{
    background-image: linear-gradient(120deg, hsl(39, 89%, 49%), hsl(40, 84%, 53%));
}
.game-body__big-circle--light-red{
    background-image: linear-gradient(120deg, hsl(349, 71%, 52%), hsl(349, 70%, 56%));
}
.game-body__tiny-circle{
    width: 10rem;
    height: 10rem;
    border-radius: 50%;
}
.game-body__tiny-circle--dark-white{
    background-color: #bfbfbf;
    overflow: hidden;
    position: absolute;
    left: 50%;
    top: 50%;
    transform: translate(-50%, -50%);
}
.game-body__tiny-circle--light-white{
    background-color: #ddd;
    transform: translateY(4px) scale(1.02);
}
```

### Continued development

The continuously learning journey of a programmer never ends. This project made me realize that there are many concepts that I need to work upon including fundamentals like flex-box and its properties, to more complex concepts like working with fetch and async await in javascript. These areas are some that I think I need to work more upon in the upcoming future as they highlight some of the most significant regions of web development that are important for every developer to know of. 

These key points mentioned here will help me grow accountable and consistent towards improving at writing good quality code and be a successful full stack developer one day.

### Useful resources

- [Harkirat Singh course notes](https://github.com/SartHak-0-Sach/harkirat-singh-course_code_and_notes) - I have added notes of all lectures along with code and lecture insights of all weeks along with bonus lectures to help you all as much as I can.
- [My development code and notes](https://github.com/SartHak-0-Sach/cwh-web-dev-playlist_code_and_notes) - These are my notes that I made while working on my development skills in initial days and did these courses. Make sure to star the repository if you like it.✨💫
- [MDN documentation hover state for CSS](https://developer.mozilla.org/en-US/docs/Web/CSS/:hover) - This is an amazing article which helped me finally understand hover states. I'd recommend it to anyone still learning this concept.

## Author

<b><strong>Sarthak Sachdev</strong></b>
- Website - [Sarthak Sachdev](https://itsmesarthak.netlify.app/)
- LeetCode - [@sarthak_sachdev](https://leetcode.com/u/sarthak_sachdev/)
- Twitter - [@sarthak_sach69](https://www.twitter.com/sarthak_sach69)

## Acknowledgments

I feel like the solutions provided on the website and the continuous doubt solving by industry experts on discord for free is something that is unmatched by anyone else and need to be acknowledged for their efforts in improving me as a developer by suggesting the best practices in your respective tech stack.

## Got feedback for me?

I love receiving feedback! I am always looking to improve my code and take up new innovative ideas to work upon. So if you have anything you'd like to mention, please email 'hi' at saarsaach30[at]gmail[dot]com.

If you liked this project make sure to spread the word and share it with all your friends.

**Happy coding!** ☺️🚀
