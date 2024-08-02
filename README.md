# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)

## Overview

### The challenge

- Build out the project to the designs provided

### Screenshot

![Desktop view](./design/Screenshot%202024-07-15%20095546.png)
![Mobile view](./design/Screenshot%202024-07-15%20095624.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

After a few head scratches I was able to get the result I wanted. It turned out better than I expected, however it felt like there was things that could be done differently, although I tried to change a few things, I could not make it work, so I decided to leave as is. 
At the start I couldn't figure it out how to make it position at the center of the screen the proper way using flex, so instead I used:

```css
{
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  }
```
Got the job done, but looking at the solution, it could have been better, so for future project, I'll remember to set the height or the width with viewport, then use flex to center it.

Another thing was the name and age, although initialy I had done a paragraph with a span for the age, I thought it could be written separetely, so it would be easier to stylize in CSS, however it only made things complicated and I couldn't get it aligned , so I went back to span inside a paragraph.

The other thing, and maybe the biggest one, was that I did not see the, what I called social media status area, as a list, so instead I created 3 divs with 2 paragaphs each containing the number and what the number meant. Although I could achieve the same result, it could have been much easier if I had used list to do it.
For the next project, I'll try to find things that carry the same type of information and could be grouped up, and remember that a list isn't just a top to bottom line by line, but can be modified to look as we want to.

For this being my first project using the concepts of HTML and CSS that I've been studying for the past month, I would say that I have a lot to learn and so much to practice.


### Continued development

Figuring out what concept to use and at what point use them is something that I have to learn more and focus, or at least be more mindful about it when starting a project, having a better scope at what needs to be done and what can be used to do it is 
