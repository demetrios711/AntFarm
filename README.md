# Antfarm - An Interactive "Conway's Game of Life"

## Background and Overview
    * Motivation for project
      - I want to have a better understanding of algorithms and have always been fascinated with simulations. 
    * High level overview
      - https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life
      - Adjust certain generation parameters on the fly.
    
### Functionality and MVP Features
    * Basic CSS + HTML
      * Coloration for grid.
    * Base Grid Generation
      * Use can adjust grid size.
    * Cells 
       * Cell Types 
         - Still lifes (Cells that do not move)
         - Oscillators (Moving Cells)
         - Customizable Cells
    * Generation Parameters
      * Base Rules - 
         1. Any live cell with fewer than two live neighbours dies, as if by underpopulation.
         2. Any live cell with two or three live neighbours lives on to the next generation.     
         3. Any live cell with more than three live neighbours dies, as if by overpopulation.
         4. Any dead cell with exactly three live neighbours becomes a live cell, as if by reproduction
    * Interact Rules Modification
      - User's can add or change existing rules.
 
### Architecture and Technologies
    * HTML5
        * Justification - Required
    * JS
        * Justification - Required

### Implementation Timeline
    * Day 0
      - Grid Generation + Custom Styling     
    * Day 1
      - Basic Cell Types
    * Day 2
      - Base Rules
      - Customizable Cell Types
    * Day 3 
      - Customizable Additional Rules
    * Day 4
      - Real Time Rule Changes
    * Day 5
      - Filler
