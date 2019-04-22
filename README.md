# Stateful CSS

**NOTE: This is incomplete and an idea I might play with later. This code was uploaded just to show others this proof of concept**

An experimental website that aims to look and animate incredibly well but have all of it's state handled by HTML and CSS only.

## Motivation

Websites loading times are getting slower and slower, I'd like to see the smallest payload I can deliver while still:
- Animating between on/off states nicely
- Supporting all major browsers, this may require I complexify the repository with a PostCSS step for CSS variables.
- Experiment with various HTML/CSS techniques for fun

## Goals

- Works in all browsers, IE10+, Firefox, Chrome, iOS Safari and Android.
  - To prove that you could theoretically make a production-quality website using only HTML/CSS. 
- [Rule Break] Add a very thin amount of vanilla JavaScript that improves screen reader accessibility only, such as modifying/syncing aria tags.
