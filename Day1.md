##About ES6

#Const type
- BABEL.js for ES6?
- adding const type
 - const type for object is a reference, OK to update fields but not OK to change the reference

#Template literals
- back tick instead of double quote for string?
- ${} to inlcude functions and parameters in the string literal (like BASH kind of?)
- white space and newline preserved

Can write HTML within ES6???! Useful when using Node writing backend and want to change front end
</pre></code>
function add(a,b) => {a+b;};
const a = 1;
const b = 2;

var content = '
<h1>Hey!<\h1>
<p>This is ${a} and ${add(a,b)}<\p>
'
</code></pre>
