# 12 column CSS Grid
Based on the 12 column grid we all know from Bootstrap, made with CSS Grid.

## Internet Explorer
Internet Explorer doesn't support CSS Grid, but only the older version. To get pretty much the same result in IE as you get in modern browsers, I've created a fallback with Flexbox.

## Edge
Edge does support CSS Grid, but it doesn't yet support display:contents.

## One grid per row
Because of the limitations that occur in IE and Edge, it's neccessary to create a new grid for every row.

## Responsive
Both CSS Grid and Flexbox are perfectly responsive. In this grid, all div's will be placed below each other on everything smaller than a tablet (768px) and everything larger than that will have more or less of the same grid layout.