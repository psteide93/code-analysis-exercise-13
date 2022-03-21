# Programming Exercise

Your task is to figure out how this code works.

* Come with a test input for the function.
* Trace the flow of the program with your test input **without running the code**, keeping track of all of the variables and transformations until you can determine the output.
* Keep coming up with new inputs until you're confident until you're confident that you know how the function works.
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

| Input | Output |
| ----- | ------ |
|    ("Parnell", "Steide", 28)   | {firstName: "Parnell", lastName:"Steide", age: 28,}| 
|("dog" "cat" "fish")       |   {firstName: "dog", lastName:"cat", age: "fish",}    | 
|(-34, 0, "111111111111")       | {firstName: -34, lastName:0, age: "111111111111",}  | 

<table>
  <tr>
    <th>What does this program do?</th>
    <td> This function assigns the arguments you pass into it as attributes in an object called person. Even though the variables are called firstName, lastName, and age, you could put anything and it will make the 3 attribute object with it.</td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible
