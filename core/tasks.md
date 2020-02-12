1. Explain Node and V8 in your own words ? 
// Answer here... 
    node is ues for sevsr-side web development. 
    v8 is an open source runtime engine written in c++. 
     Javascript and node is using v8 javascript runtime engine. The v8 engine takes your javascript code and convert into a low-level machine code which the computer can run easily.

2. Explain steps in REPL(here) and command to start REPL ?
// Answer here...
  REPL is like browser console we can write javascript code in it.
  we can run javascript code file by using 
    ```js
    $ node index.js
    ```
      1. open terminal
      2. type node in terminal
      ```
      $ node
      > console.log("Hello world")
      ```
      

3. Run `index.js` in the same directory as script writer using `node FILE_NAME.js` and output result of console here.
```
hello world
```
4. Require fs module and read `theory.md` using fs.readFile method in index.js file.
    done
5. Explain Buffer and different methods to create a buffer ?
  buffer is for storing row data is alocate the outside to v8.
  ```js
  var buffer = new Buffer("hello world"); 
  ```
6. What is blocking code ? How is it different from non-blocking/async codes ? Correct blocking code in index.js to run asynchronously ?
// Answer here ...


7. Request from browser `https://altcampus.io` and copy request, response and general headers into answer.js.

8. Parse the URL `http://localhost:3000/api/v3?token=8372fcb8y2874b2t478t6t48cbtbc72t4` using `url` module's parse method and write output in answer.js

9. parse the query object as well from above url using `url.parse(url, true)` and output result in answer.js

10. create a file `math.js`
  1. Export variables and functions
    - define a const pie = 3.14
    - define functions to add and multiply 2 numbers
    - export it from math.js
    - require in index.js and console the output by executing it there.
```js
// math.js
const pie = 3.14;
function sum() {}
function multiply() {}
// export it from math.js
```

  2. Define above const and functions as properties and methods on module.exports object.
    - require in index.js and execute it.

```js
  module.exports = {
    pie: 3.14,
    add: () => {}
  }
```
  3. Define above using exports 

```js
exports.sum = () => {}
```
