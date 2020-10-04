# openicons
A repository full of Scalable Vector Graphics (SVG) files written by hand for you to use in your projects.

## Writing your SVG

If you want to write an icon for this repository, please followw the guides below.

- Define the SVG element with exactly three attributes:
  - `width`: If you want, you may set this higher than the standard 16 for editing, though it should be committed with a width of 16.
  - `height`: Same rules apply hear as in width.
  - `viewBox`: Must be `"0 0 16 16"`, to define the bounds of the coordinate space as 16x16.
- Use basic shapes only when it would be easier to do it with them. `polygon` and `path` must be used for more complicated shapes, even if it contains basic shapes.
- Don't use too many colors. If you have to use more than five, you're probably overdoing it. The only exception is for logos. Also note that logos should be the official thing unless they are not licensed for free use.
  - You can use the color designer at [Paletton.com](https://paletton.com/) to create a monochromatic scheme with multiple brightnesses.
- Don't use shading such as drop shadows or animations in the SVG files you submit. Any files containing these will immediately be discarded. Once again, the only exception is with logos licensed for free use.
- Don't include sub-element SVG files (`svg` node with `svg` child node).
- If you are copying an official logo icon that requires attribution and/or is licensed under a different license than Apache-2.0, make sure it is mentioned in a comment element.

## Credits

If you want, you can create your own icons and sumbit via a Pull Request (see [Writing your SVG](#writing-your-svg)). When you do so, we will credit you below.

- [@AdrianGjerstad](https://github.com/AdrianGjerstad): Base repository
