# Bouncing Ball Animation with GSAP README

This is a JavaScript animation project that uses the GreenSock Animation Platform (GSAP) to create a captivating bouncing ball animation on an HTML canvas. The animation includes a sequence of images that make up the bouncing ball and text elements that appear and disappear as you scroll down the page.

## Table of Contents
- [Prerequisites](#prerequisites)
- [Setup](#setup)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [How It Works](#how-it-works)
- [Credits](#credits)

## Prerequisites

To run this animation project, you need a modern web browser that supports HTML5, CSS3, and JavaScript.

## Setup

1. Clone this repository or download the code to your local machine.

2. Open the `index.html` file in your web browser. The animation will start automatically when the page loads.

## Usage

- As you scroll down the page, you'll witness a captivating animation of a bouncing ball.
- Text elements will appear and fade away at specific scroll positions, creating an engaging visual experience.
- You can customize the animation's behavior by adjusting the GSAP scroll triggers and animation settings in the JavaScript code.

## Project Structure

The project directory structure is as follows:

- `index.html`: The main HTML file that displays the canvas and animations.
- `styles.css`: The CSS file used for styling the HTML elements on the page.
- `script.js`: The JavaScript file that manages the animation and GSAP scroll triggers.
- `best-ball/`: This directory contains a sequence of images (`.jpg`) used to create the bouncing ball animation. The images should be stored in this directory.

## How It Works

- The JavaScript code loads a sequence of images from the `best-ball/` directory and stores them in an array. Each image represents a different frame of the bouncing ball animation.

- GSAP (GreenSock Animation Platform) is used to control the animation. GSAP provides powerful tools for creating smooth and interactive animations.

- The `gsap.to` function animates the ball's position based on the scroll position, using the "scrub" property to synchronize the animation with scrolling. It also pins the canvas to the screen and sets the animation's end point.

- The `gsap.fromTo` function animates the opacity of text elements, making them appear and disappear at specific scroll positions.

- The `render` function updates the canvas with the current frame of the animation, creating the illusion of a bouncing ball.

## Credits

This animation project was created using the GreenSock Animation Platform (GSAP) and Blender. For more information about GSAP and its features, please visit the [GSAP website](https://greensock.com/gsap/).

![Blender](./Screenshot%202023-10-29%20034456.png)


# Issue

This website experiences slow loading times due to the large number of images that load as you scroll. The site's functionality involves replacing the current image with the next one as you scroll, and there are a total of 180 images. If anyone has a solution to address this issue, please feel free to share it.

Enjoy exploring and customizing this animation project to suit your needs!
