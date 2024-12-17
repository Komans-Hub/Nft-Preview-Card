# Nft-Preview-Card
# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor]

## Table of contents

- [Overview](#overview)
- [The task](#the-task)
- [Approach](#approach)
- [My process](#my-process)
- [Built with](#built-with)
- [Lessons](#lessons)
- [Useful resources](#useful-resources)

## Overview

For this task, I had to design a static page with active states.

## The task

I needed to do this for both Mobile & Desktop and activate the hover states.

## Approach

I used a Mobile-First approach and a CSS Flex layout.

## Built with

:gear: Semantic HTML5 markup  
:gear: CSS Flex  
:gear: Mobile-first workflow

## Lessons

1. `::before` and `::after` pseudo-elements. I didn't understand what the 'before' and 'after' really meant before, but now I know that these are states where we can alter or introduce content around an element to appear when an action is taken by the user. I also learnt that in the stacking context, these literally appear (linearly) **before** and **after** in the vertical information flow, so in this case, above and below the containing content. I didn't expect or know this before.
2. `position` properties! I had never really utilised these before and I learnt a lot about `position: relative;` and `position: absolute;` in this context. I also implemented `top`, `bottom`, `left`, `right` properties.
3. `<button>` element - A first for me. I made the mistake of using `<a>` in my HTML initially, where my hover overlay wouldn't work. This was a big moment of clarification.
4. Combining targeting both `pseudo-elements` and `pseudo-classes` at the same time in CSS! (Classes come first).
5. You can import an image via CSS with the `url()` function. They don't always need to be in your HTML, as with the `icon.svg` in this challenge.
6. Solidfying `order` property use in CSS.
7. It was my first time using the `transition` property - really fun.
8. I started to understand stacking contexts and how `z-index` is a comparative relative to other elements within a given stacking context.


## Useful resources

[How to Overlay Icons on Top of Images with CSS](https://dev.to/sanchithasr/how-to-overlay-icons-on-top-of-images-with-css-1kb9)  
[The CSS z-index Property: What You Need to Know](https://blog.hubspot.com/website/z-index)  
[What The Heck, z-index??](https://www.joshwcomeau.com/css/stacking-contexts/)  

# nft-preview-card
