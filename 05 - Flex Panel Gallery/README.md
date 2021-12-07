CSS
  - *before, *after selectors.
  - new css selectors like:
    - 'X > Y' (child selector) to choose all the Y elements that are direct children of an element X.
    - 'X:nth-child(n)' to choose the element X which is the nth child of some element.
    - 'X:first-child' or 'X:last-child' to choose the element X that's the first child
    or last child of a parent element.
  - overflow property.
  - transition shorthand property: this property can set the values for 4 transition related properties
  which are:
    - transition-property property.
    - transition-duration property.
    - transition-timing-function property.
    - transition-delay property.
  in that order.
  - cubic-bezier function: we met this function before in the second exercise (the JS Clock),
  it can be used as the value for the transition-timing-function property, and it allows us to
  customize the transition speed at different points in time during the transition duration.
  - translate(x-coord, y-coord?) function: this function takes one or two values for the x and
  (optionally) the y coordinates to move (if possible) the element in the two-dimensional plane.
  If passed a single a value, it evaluates the x-coord only, so it's equivalent to translateX(x-coord)
  or translate(x-coord, 0). The one used in the exercise is translateY(y-coord) which is similar to 
  translateX(x-coord).
  - We can nest as many flex containers inside each other as we need.
    