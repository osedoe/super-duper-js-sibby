# Misc III

- What's the difference between an `undeclared` and `undefined` variable?
    undeclared: the variavle doesn't exist in the program.
    undefined: the variable has been declared but it doesn't have a value.


- What are global variables? What's the problem with them? How would you declare a global variable (add an example)?
    global varaibles are variables declared outside the function and they can be accessed by all the program.
    As they can be accessed by all the program it doesn't have privacy.
    ```javascript
    let state = true;
    var name = "Jhon";
    ```

- What does it mean when you put an exclamation before a value?.

    ``!`` or ``bang`` it's a logical operator and represent ``not``. It menas it return the opposite.
    
    ```javascript 
    const isHappy = true;

    const amIHapppy = !isHappy;
    ```

- What is the value `NaN`?

    Nan it ``not-a-number``. It means it's not a legal number. JS uses it as the result of a failed operation with numbers.

- What is the `typeof` operator?

- What is the difference between `session`, `local storage` and `session storage`?[IMPORTANT]

- What are different ways to put a string value in JS? When would you use each?

- There's various types of operators in JS. Name them and write down the different options for each group

- What are bitwise operators?

- What's the difference between `==` and `===`?

- How would you generate a random Integer number?