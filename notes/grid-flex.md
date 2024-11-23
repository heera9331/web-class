# Flex and Grid



## Flex

1 Dimensional Layout system

`flex`

default - row
- axis - main-axis, cross-axis

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Flex-Grid</title>

    <style>
      * {
        margin: 0;
        padding: 0;
      }

      .parent {
        display: flex;
        flex-direction: row;
        border: 1px solid gray;
        padding: 1rem;
        gap: 12px;
        /* row-gap: 12px; */
        column-gap: 12px;
        height: 300px;
        justify-content: end;
        justify-content: start;
        justify-content: center;
        /* justify-content: space-between;
        justify-content: space-evenly;
        justify-content: space-around; */

        align-items: start;
        align-items: end;
        align-items: center;
        flex-wrap: wrap;
      }

      .child {
        border: 1px solid gray;
        width: 150px;
        height: 150px;
      }
    </style>
  </head>
  <body>
    <div class="parent">
      <div class="child">child 1</div>
      <div class="child">child 2</div>
      <div class="child">child 3</div>
      <div class="child">child 4</div>
      <div class="child">child 4</div>
      <div class="child">child 4</div>
      <div class="child">child 4</div>
      <div class="child">child 4</div>
    </div>
  </body>
</html>

```

## Grid

2 Dimensinal Layout Sytem

`grid`
