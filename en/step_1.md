![A screenshot of a webpage with three equal height tiles in the center. Each with centred text.](images/three-tiles.PNG)

The code example below will create three tiles of equal height. The text within the tile will be centred on the x and y axis. 

+ `xcenter` places the text in the centre horizontally
+ `ycenter` places the text in the center vertically
+ `tile` sets the height for the `div` content

--- code ---
---
language: HTML
filename: index.html
line_numbers: true
line_number_start: 
line_highlights: 
---
      <section class="wrap">
        <div class="tertiary xcenter ycenter tile">
          <p>Add text here.</p>
        </div>
        <div class="secondary xcenter ycenter tile">
          <p>Add text here.</p>
        </div>
        <div class="tertiary xcenter ycenter tile">
          <p>Add text here.</p>
        </div>
      </section>
--- /code ---