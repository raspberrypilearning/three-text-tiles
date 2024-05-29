![A page with three equal height tiles in the centre. Each tile has centred text.](images/three-tiles.PNG)

The code example creates three tiles of equal height. The text within the tile is centred on the x-axis and y-axis.

- `xcenter` plaatst de tekst horizontaal in het midden
- `ycenter` places the text in the centre vertically
- `tile` stelt een vaste hoogte in voor de `div`-inhoud

## --- code ---

language: HTML
filename: index.html
line_numbers: true
line_number_start:
line_highlights:
-----------------------------------------------------

```
  <section class="wrap">
    <div class="tertiary xcenter ycenter tile">
      <p>Voeg hier tekst toe.</p>
    </div>
    <div class="secondary xcenter ycenter tile">
      <p>Voeg hier tekst toe.</p>
    </div>
    <div class="tertiary xcenter ycenter tile">
      <p>Voeg hier tekst toe.</p>
    </div>
  </section>
```

\--- /code ---
