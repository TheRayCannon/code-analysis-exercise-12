# Programming Exercise

Your task is to figure out how this code works.

* Come with a test input for the function.
* Trace the flow of the program with your test input **without running the code**, keeping track of all of the variables and transformations until you can determine the output.
* Keep coming up with new inputs until you're confident until you're confident that you know how the function works.
* Write a summary of what the function does.

```js
function (currentColor){
  if (currentColor === "green"){
    nextColor = "yellow"
  } else if (currentColor === "yellow"){
    nextColor = 'red'
  } else if (currentColor === "red"){
    nextColor = 'green'
  }

  return nextColor
}
```

| Input | Output |
| ----------- | ----------- |
|  red        |    green    | 
|  yellow     |    red      | 
|  green      |    yellow   | 

<table>
  <tr>
    <th>What does this program do?</th>
    <td>This program creates rootamentary (only 3 colors) reference to a color wheel. Where the input will be one of the three strings which will be colors "red" "yellow" "green" abnd the oputput will be a string of the "next color" on the color wheel which is corosponding to the input with a direct out put; green to yellow, yellow to red, and red to green. Why does this color wheel not include Blue? the missing primary color that might actually fall in these sequence instead of green? that is because the program does not know it is making a color wheel or that the next _primary_ color would be blue. It is printyint an output of the assigned value "
nextColor" from the input "currentColor" sent in. </td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible
