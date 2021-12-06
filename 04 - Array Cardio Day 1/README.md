JS
  - Array methods:
    - .filter()
    - .map()
    - .sort() : sort() takes two arguments (say 'a' and 'b'), compares them together, and
    if a should precede b, returns -1 and if the opposite is true, returns 1.
    - .reduce()
  
  - console.table()
  - We can use .querySelector() and .querySelectorAll() on all Node Objects/Elements not just
  the document element.
  - Array methods don't work with NodeList objects. We have to convert NodeLists
  to Arrays if we wish to use any of the methods above. To do so, we can use the
  Array.from(NodeList) function or by using the spread operator [...NodeList].