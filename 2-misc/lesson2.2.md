# Misc II

> Tip: to put pieces of code in a *.md file, you put three backsticks, code and three backsticks in the following way: 
\```javascript 
// code in new line
// and another three backsticks in a new line
\```
https://www.markdownguide.org/basic-syntax/#code


- What are the different ways to create an object in JavaScript?

        LITERAL NOTATION:
        ```javascript
        const car {
            model: "Mutivan",
            km: 0,
            camera: false,
            drive: function() {
                km = km++;
            }
        }
        ```
        CONSTRUCTOR NOTATION:
        ```javascript
        const car = new Object();

        car.model = "Transporte";
        car.km: 1000;
        car.drive = function() {
            km = km++;
        }
        ```


- What is Prorotype in JS?

        It's the mechanism by JS objsects to inherit features from other objs

- What does JSON mean? What is it used for?

        JSON is JavaScript Objects Notation.
        It's a format for storing and transporting data.

- What are primitives values? What are those in JS?

        Primitive values are the ones which are not obj and don't have methods. They are immutable (cannot be altered).
        They are: ``Number``, ``String``, ``Boolean``, ``Undefined``, ``Symbol`` and ``BigInt``. There is also `null`.

- Name and explain the different operators in JS

    - Arithmetic operators: `+`, `-`, `*`, ``/``, ``%``, ``++``, `--`. For mathematical operations.
    - String concatenation: ``+``.
    - Comparison operators: ``==``, ``===``, ``!=``, `>`, ``<``, ``>=``, ``<==``.
    - Logical operators: ``&&``, ``||``, ``!``. To combine 2 or more conditions.
    - Assignment operators: `=`. ``+=``. ``-=``, ``*=``, ``/=``, ``%=``.
    - Ternary operator: 
        ```javascript
        <condition> ? <value1> : <value2>;
        ```
- What are closures in JS?

         Are functions that can access values outside of their own curly braces. Only one level below.

- What is hoisting in JS?

    It's a variable can be used before it has been declared. 
    
    ``!!! ->`` But cannot be initizalize before the function is called.

- What type of variable declaration will you normally use? In what cases will you use `let`?

- What is a callback function? Why do we need them?

- What is a promise? Could you name the three states of a promise?

- Why do we need promises?

- What is the difference between `null` and `undefined`?