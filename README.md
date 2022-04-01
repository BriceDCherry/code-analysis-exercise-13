# Programming Exercise

Your task is to figure out how this code works.

* Come with a test input for the function.
* Trace the flow of the program with your test input **without running the code**, keeping track of all of the variables and transformations until you can determine the output.
* Keep coming up with new inputs until you're confident that you know how the function works.
* Write a summary of what the function does.

```js
function (firstName, lastName, age){
  const person = {
    firstName: firstName,
    lastName: lastName,
    age: age,
  }

  return person
}
```

Inputs and outputs should be valid JavaScript values!

| Input | Output |
| ----- | ------ |
| "Brice", "Cherry", 27      |     {firstName: "Brice", lastName: "Cherry", age: 27}   | 
| "Kyle", "Coberly", 35      |     {firstName: "Kyle", lastName: "Coberly", age: 35}   | 
| "Shawn", "Cannon", 30      |     {firstName: "Shawn", lastName: "Cannon", age: 30}   | 

<table>
  <tr>
    <th>What does this program do?</th>
    <td>the function puts in an input of two strings and a number and returns it formated with the info labelled.</td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible
