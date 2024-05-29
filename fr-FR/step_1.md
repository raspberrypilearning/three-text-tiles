![A page with three equal height tiles in the centre. Each tile has centred text.](images/three-tiles.PNG)

The code example creates three tiles of equal height. The text within the tile is centred on the x-axis and y-axis.

- `xcenter` place le texte au centre horizontalement
- `ycenter` places the text in the centre vertically
- `tile` définit une hauteur fixe pour le contenu `div`

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
      <p>Ajouter du texte ici.</p>
    </div>
    <div class="secondary xcenter ycenter tile">
      <p>Ajouter du texte ici.</p>
    </div>
    <div class="tertiary xcenter ycenter tile">
      <p>Ajouter du texte ici.</p>
    </div>
  </section>
```

\--- /code ---
