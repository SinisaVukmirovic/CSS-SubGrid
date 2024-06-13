## CSS SubGrid

### Subgrid allows Grid items with their own grid, to inherit the rows and columns from the parent grid.

#### When we add display of Grid to the wrapper element, only the direct children on that wrapper element become Grid items, the children in these element are not part of the grid.

#### Using SubGrid doesn't create rows or columns implicitly. Therefore, we need to explicitly define on how many tracks (rows/columns) items of the subgrid element spans, with grid-row/column property.