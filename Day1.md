##About ES6

#Const type
- BABEL.js for ES6?
- adding const type
 - const type for object is a reference, OK to update fields but not OK to change the reference

#Template literals
- back tick instead of double quote for string?
- ${} to inlcude functions and parameters in the string literal (like BASH kind of?)
- white space and newline preserved

NOTE: Can write HTML within ES6???! Useful when using Node writing backend and want to change front end

#destructuring
- for objects and arrays
- for arrays, index is important so sometimes unused vars are given destrctured names => Solve: use , to escape
- functions take objects and destructured fields

#dot dot dot(fun! combine two things together)
- when used in function parameters, takes all the input parameters and convert it into an array
- when used in push, insert elements instead of array, can even skip push to merge arrays
- when used in objects, gonna merge to one objects with additional fields, if duplicated fields merging, the one comes after overwrites
