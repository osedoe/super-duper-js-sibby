# Arrays

- What are arrays in JS? How would you create one, access/modify its elements and add elements?

    ``Arrays`` are object in JS which grow and shrink dynamically and can store a list of values.

    Create arrays:
    ```javascript
    const colors = ['blue', 'red', 'green'];
    ```
    Access/modify an array content:
    ```javascript
    let carColor = colors[1];
    ```
    Add am element to an array:
    ```javascript
    colors.push('orange')       //['blue', 'red', 'green', 'orange']
    ```


- What possible types can have an array? Can you mix them?

    Arrays can have any types. Yes we can mix them.

- Explain the following array methods: [ join(), pop(), push(), shift(), unshift(), concat(), map(), filter(), reduce(), every(), some(), indexOf(), lastIndexOf(), find(), findIndex(), includes() ]

    ``join``: to join two strings.

    ``pop``: to remove the last element of an array.

    ``push``: to add an element by the end of the array.

    ``shift``: to remove the first element of an array.

    ``unshift``: to add element by the beginning of the array.

    ``concat``: to join two arrays in one.

    ``map``: to copy an array aplying the changes of the callback function.

    ``filter``: create a new array with the elements that fullfilled the condition of the callback function.

    ``reduce``: to reduce the array depeding on the callback function.

    ``every``: return true if all the array's element fullfill the condition of the callback function.

    ``some``: return true if any element (not neccesary all) fullfill the condition of the callback function.

    ``indexOf``: return the first index at which a given element/substring can be found in the array/ string (if it isn't any it return -1) It's posible to especify the index where we want to start 

    ``lastIndexOf``: return the 


- What's the spread syntax? And the rest syntax? What are their differences?

- What it means to destructure an array? How would you do it?

- When you destructure an array and/or an object, how would you assign default values to those?

- What's the difference between `forEach` and `map`?

- What is a regular expression in JS? How would you test a string contains the letter `A` with regex?

