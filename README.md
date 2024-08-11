# css-positions
### CSS positions:

    - css positions property  defines the position of an html element inside the browser's viewport,
    - by default all the html elements follow the default order.

    - we can use css position to manipulated the position of html element inside the view port (top, bottom, right, left);

    - by default, the browser renders the html element one after other in the viewport. the order can be horizontal or vertical depending on element type.
        -- block element - vertical alignment.
        -- inline element - horizontal alignment.

## CSS position types.

1. static positioning
   -default position in css , it follows the order in which you have given.( you cannot use left, right , bottom, top)
2. Relative positioning - here you can change the position of element in left, right, bottom, top but the initial position space cannot be remove.
3. Fixed positioning - here the position of element will remain same even though the scrolling of the page happens. ( left, right , top, bottom)
4. Absolute positioning - here you can change the position of element in left, right , bottom top and element initial element position will be lost
5. Sticky positioning. - here the element by default will be static, but when you scroll it becomes absolute where other elements can occupy the position.