# Frontend Loader Animation Project

## Project Overview

This project is a simple frontend loader animation built using HTML, CSS, and SVG (Scalable Vector Graphics). The goal of the project is to create smooth, visually appealing loader animations that can be easily incorporated into any web application or website. Two types of loaders are included: a circular rotating loader and a line loader. Both animations are made using CSS keyframes for smooth and continuous animation.

## Project Files

1. **index.html**: The main HTML file that defines the structure of the web page and includes the SVG loaders.
2. **style.css**: The stylesheet that defines the layout and animations for the loaders. The CSS provides the flexbox layout and animations such as rotation and stroke-dasharray transitions for the loader elements.

## Features

- **Circular Loader**: A circle SVG element that rotates and uses the `stroke-dasharray` and `stroke-dashoffset` properties to create a dynamic loading effect.
  
- **Line Loader**: A horizontal line SVG element that animates with a similar stroke-dasharray effect, giving the illusion of a loading process.

- **CSS Animations**: The animations are controlled using CSS keyframes, which create smooth and continuous movement for both the circular and line loaders.

## How It Works

- **HTML Structure**: The HTML document contains two loader elements wrapped in `<div>` containers. The first loader is a rotating circular loader, and the second is a horizontal line loader.

- **CSS Layout**: The page uses flexbox for center alignment of the loaders both vertically and horizontally. The loader elements are styled to have fixed dimensions and animations applied using CSS.

- **SVG Animations**: The circular and line loaders leverage the `stroke-dasharray` and `stroke-dashoffset` CSS properties to animate the drawing of the SVG shapes over time.