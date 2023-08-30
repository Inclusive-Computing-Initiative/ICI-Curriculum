# Lesson: Introduction to CSS Grid for SPED Kids

## Objective
By the end of this lesson, you will understand the basic concept of CSS Grid and how it helps organize elements on a webpage.

## What is CSS Grid?
CSS Grid is like a magic tool that helps us arrange things on a webpage. It's like a puzzle board with rows and columns that we can put different things in.

## How Does CSS Grid Work?
1. **Grid Container**: Think of this as a big box that holds our grid. It's like the frame of the puzzle.
2. **Grid Items**: These are the things we want to put in the grid. They go inside the boxes of the puzzle.
3. **Grid Lines**: These are like lines that divide the puzzle board into rows and columns.
4. **Grid Tracks**: These are the spaces between the lines where we can put our things.
5. **Grid Area**: This is the space inside the lines. It's where we put our special things.

## Let's See an Example
Imagine we have a big box divided into three columns. Each column can hold something different, like pictures or text. This is how it looks:

```html
<!DOCTYPE html>
<html>
<head>
  <style>
    .grid-container {
      display: grid;
      grid-template-columns: 1fr 1fr 1fr; /* Three equal columns */
    }

    .grid-item {
      background-color: lightblue;
      padding: 20px;
      text-align: center;
    }
  </style>
</head>
<body>

<div class="grid-container">
  <div class="grid-item">1</div>
  <div class="grid-item">2</div>
  <div class="grid-item">3</div>
</div>

</body>
</html>
