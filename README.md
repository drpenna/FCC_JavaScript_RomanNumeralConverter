# FCC_JavaScript_RomanNumeralConverter
This is my solution for the [**Build a Roman Numeral Converter**](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures-v8/build-a-roman-numeral-converter-project/build-a-roman-numeral-converter)
required project for the [**freeCodeCamp's JavaScript Algorithms and Data Structures (Beta)**](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures-v8/) certification using JavaScript, HTML, and CSS. <br />

## Contents
- [What is a Roman Numeral](#what-is-a-roman-numeral)
- [How to use the Roman Numeral Converter in a Website](#how-to-use-the-roman-numeral-converter-in-a-website)
- [Project Tasks Summary](#project-tasks-summary)
- [Files](#files)
- [Project tests](#project-tests)

## What is a Roman Numeral
A Roman Numeral uses letters to represent numbers, the main ones being:
|Roman numerals	|Arabic numerals|
|:-:|:-:|
|I	|1|
|V	|5|
|X	|10|
|L	|50|
|C	|100|
|D	|500|
|M	|1000|

Those letters can be combined to create other numbers. Up to the number `3`, you may just repeat the letter that represents `1`:
|Roman numerals	|Arabic numerals|
|:-:|:-:|
|I	|1|
|II	|2|
|III|3|
|X	|10|
|XX	|20|
|XXX	|30|
|C	|100|
|CC	|200|
|CCC	|300|
|M	|1000|
|MM	|2000|
|MMM	|3000|

For `6`, `7`, and `8`, you'll need to make an addition (for example, `5 + 1` or `50 + 20`):
|Roman numerals	|Arabic numerals|
|:-:|:-:|
|V	|5|
|VI	|6|
|VII	|7|
|VIII	|8|
|L	|50|
|LX	|60|
|LXX	|70|
|LXXX	|80|
|D	|500|
|DC	|600|
|DCC	|700|
|DCCC	|800|

For `4` and `9`, you'll need to make a subtraction (for example, `5 - 1`, `10 - 1`, `100 - 10` or `1000 - 100`). The number to be subtracted is written to the left:
|Roman numerals	|Arabic numerals|
|:-:|:-:|
|IV	|4|
|IX	|9|
|XL	|40|
|XC	|90|
|CD	|400|
|CM	|900|

[<sub>Back to top</sub>](#top)

## How to use the Roman Numeral Converter in a website
- Click on the text box (where the placeholder text "Type here" can be found) and type the number you want to check.
  ![image](https://github.com/user-attachments/assets/505b42fe-fe71-4b78-a9f6-a4d26d7b840d)
- Click on the "Convert" button or press "Enter" on your keyboard. Right below it, the converted number will appear.
  ![image](https://github.com/user-attachments/assets/105d4607-e125-47d1-bcba-db3295cc70a0)
- If the "Convert" button is clicked or "Enter" is pressed without a valid number, you'll get an error message instead of the Roman Numeral. Valid numbers are from 1 to 3999. 
- To clear the number in the number box, you can click on the "Reset" button.

[<sub>Back to top</sub>](#top)

## Project Tasks Summary
To build an app that functions similarly to [https://roman-numeral-converter.freecodecamp.rocks/](https://roman-numeral-converter.freecodecamp.rocks/).

[<sub>Back to top</sub>](#top)

## Files
- index.html
- styles.css
- script.js

[<sub>Back to top</sub>](#top)

## Project Tests
For project completion, the app must pass the following tests (more details on [**Build a Roman Numeral Converter**](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures-v8/build-a-roman-numeral-converter-project/build-a-roman-numeral-converter)):
1. You should have an `input` element with an id of `"number"`.
2. You should have a `button` element with an id of `"convert-btn"`.
3. You should have a `div`, `span`, or `p` element with an id of `"output"`.
4. When you click on the `#convert-btn` element without entering a value into the `#number` element, the `#output` element should contain the text `"Please enter a valid number"`.
5. When the `#number` element contains the number `-1` and the `#convert-btn` element is clicked, the `#output` element should contain the text `"Please enter a number greater than or equal to 1"`.
6. When the `#number` element contains the number `4000` or greater and the `#convert-btn` element is clicked, the `#output` element should contain the text `"Please enter a number less than or equal to 3999"`.
7. When the `#number` element contains the number `9` and the `#convert-btn` element is clicked, the `#output` element should contain the text `"IX"`.
8. When the `#number` element contains the number `16` and the `#convert-btn` element is clicked, the `#output` element should contain the text `"XVI"`.
9. When the `#number` element contains the number `649` and the `#convert-btn` element is clicked, the `#output` element should contain the text `"DCXLIX"`.
10. When the `#number` element contains the number `1023` and the `#convert-btn` element is clicked, the `#output` element should contain the text `"MXXIII"`.
11. When the `#number` element contains the number `3999` and the `#convert-btn` element is clicked, the `#output` element should contain the text `"MMMCMXCIX"`.
12. When the `#number` element contains a random negative number and the `#convert-btn` element is clicked, the `#output` element should contain the text `"Please enter a number greater than or equal to 1"`.
13. When the `#number` element contains a number greater than `4000` and the `#convert-btn` element is clicked, the `#output` element should contain the text `"Please enter a number less than or equal to 3999"`.

[<sub>Back to top</sub>](#top)
