# Ragini Singh JavaScript Practice
# 🚀 Day 3: JavaScript Practice
This repository contains my Day 3 JavaScript practice tasks. It includes fill-in-the-blanks, challenge-based problems, and DOM + API concepts.

---

## 🧠 JavaScript Basics – Fill in the Blanks
1. JavaScript is a **client**-side scripting language.

2. You can declare a variable using let, const, or **var**.

3. To assign a string to a variable, use quotes like this:  
   `let name = "Ragini";`

4. The **function** keyword is used to define a function.  

5. To output something in the browser console, you use **console.log()**.  

6. The data type that stores true or false values is called **Boolean**.  

7. To compare two values for equality in value and type, use **===**.  

8. The loop that runs as long as a condition is true is the **while** loop.  

9. In JavaScript, arrays are defined using **square** brackets.  

10. An if statement checks for a **condition** to decide what code to run.  

11. HTML elements can react to JavaScript using **events** like onclick.  

12. The method to convert a string to a number is **Number()**.  

13. To add a new element to the end of an array, use array.**push()**  

14. To check the length of a string, use string.**length**.  

15. The operator + can be used for both addition and **concatenation**.  

16. JavaScript code is typically run inside the web browser or using **Node.js**.  

17. You can use document.getElementById() to access an HTML element by its **ID**.  

18. The keyword used to stop the execution of a loop is **break**.  

19. A function can return a value using the **return** keyword.  

20. The typeof operator returns the **data type** of a variable.  

---

## 🎯 JavaScript Practice – Challenge Style Questions

### 1. Greet Me
```js
let language = "JavaScript";
console.log("I am learning " + language + "!");

𝟐. 𝐂𝐫𝐞𝐚𝐭𝐞 𝐚 𝐆𝐫𝐞𝐞𝐭𝐢𝐧𝐠 𝐅𝐮𝐧𝐜𝐭𝐢𝐨𝐧
function greet(name) {
  return "Hello, " + name + "!";
}
console.log(greet("Alex"));

𝟑. 𝐄𝐯𝐞𝐧 𝐨𝐫 𝐎𝐝𝐝
let num = 7;
if (num % 2 === 0) {
  console.log("Even");
} else {
  console.log("Odd");
}


𝟒. 𝐂𝐨𝐮𝐧𝐭𝐝𝐨𝐰𝐧 𝐓𝐢𝐦𝐞𝐫
for (let i = 5; i >= 1; i--) {
  console.log(i);
}
console.log("Boom!");

𝟓. 𝐏𝐫𝐢𝐧𝐭 𝐀𝐥𝐥 𝐂𝐨𝐥𝐨𝐫𝐬
let colors = ["red", "blue", "green"];
for (let color of colors) {
  console.log(color);
}

𝟔. 𝐁𝐮𝐭𝐭𝐨𝐧 𝐂𝐥𝐢𝐜𝐤 𝐀𝐥𝐞𝐫𝐭 (𝐇𝐓𝐌𝐋 + 𝐉𝐒)
<button onclick="alert('You clicked me!')">Click Me</button>

𝟕. 𝐂𝐡𝐚𝐧𝐠𝐞 𝐭𝐡𝐞 𝐏𝐚𝐫𝐚𝐠𝐫𝐚𝐩𝐡 𝐓𝐞𝐱𝐭
<p id="text">Original Text</p>
<button onclick="document.getElementById('text').innerText = 'Text Changed!'">Change Text</button>

𝟖. 𝐆𝐞𝐧𝐞𝐫𝐚𝐭𝐞 𝐚 𝐑𝐚𝐧𝐝𝐨𝐦 𝐍𝐮𝐦𝐛𝐞𝐫
let randomNum = Math.floor(Math.random() * 100);
console.log(randomNum);

𝟗. 𝐒𝐢𝐦𝐩𝐥𝐞 𝐀𝐝𝐝 𝐅𝐮𝐧𝐜𝐭𝐢𝐨𝐧
function add(a, b) {
  return a + b;
}
console.log(add(3, 5));

𝟏𝟎. 𝐋𝐨𝐠𝐢𝐧 𝐒𝐭𝐚𝐭𝐮𝐬
let isLoggedIn = true;
if (isLoggedIn) {
  console.log("Welcome back!");
}

𝟏𝟏. 𝐒𝐭𝐫𝐢𝐧𝐠 𝐋𝐞𝐧𝐠𝐭𝐡
let word = "developer";
console.log(word.length);


𝟭𝟮. 𝗔𝗱𝗱 𝘁𝗼 𝗙𝗿𝘂𝗶𝘁𝘀 𝗔𝗿𝗿𝗮𝘆
let fruits = ["apple", "banana"];
fruits.push("orange");
console.log(fruits);


𝟭𝟯. 𝗕𝗿𝗲𝗮𝗸 𝗮 𝗟𝗼𝗼𝗽 𝗮𝘁 𝟱
for (let i = 0; i < 10; i++) {
  if (i === 5) break;
  console.log(i);
}


𝟭𝟰. 𝗙𝗶𝗻𝗱 𝗩𝗮𝗿𝗶𝗮𝗯𝗹𝗲 𝗧𝘆𝗽𝗲
let age = 21;
console.log(typeof age);

𝟭𝟱. 𝗠𝗮𝗸𝗲 𝗧𝗲𝘅𝘁 𝗥𝗲𝗱 (𝗛𝗧𝗠𝗟 + 𝗝𝗦)
<p id="para">This is a paragraph.</p>
<button onclick="document.getElementById('para').style.color = 'red'">Make Red</button>


 🧩 𝐉𝐚𝐯𝐚𝐒𝐜𝐫𝐢𝐩𝐭 𝐂𝐫𝐨𝐬𝐬𝐰𝐨𝐫𝐝 𝐏𝐮𝐳𝐳𝐥𝐞 - 𝐉𝐒𝟏
Welcome to the JavaScript Crossword Puzzle (JS1)! This fun and educational crossword is designed to help you learn and review key JavaScript concepts and keywords in an engaging way.


📘 𝐎𝐯𝐞𝐫𝐯𝐢𝐞𝐰
This crossword puzzle includes essential JavaScript terms and keywords such as:

Variables (let, const, var)

Control structures (for, switch)

Methods (pop, push, foreach)

Core concepts (function, return, event, length, typeof)

DOM and logical values (dom, true, false)
...and more!


📸 𝐏𝐮𝐳𝐳𝐥𝐞 𝐏𝐫𝐞𝐯𝐢𝐞𝐰

<img width="679" alt="Screenshot 2025-05-30 at 12 42 52 PM" src="https://github.com/user-attachments/assets/fcf643bd-6028-42be-8a84-36960ccae2ae" />



ACROSS
1. A way to declare a variable that can change
3. A Boolean value meaning “no” or “incorrect”
6. A loop that repeats code a set number of times
8. Tells the type of a variable (e.g. number, string, object)
9. Removes the last value from an array
11. A way to run different code based on different values
13. The structure of a webpage that JavaScript can read and change
15. A container for storing data in a program
17. A way to declare a variable that cannot be reassigned
19. A reusable block of code that does something
20. Gives back a value from a function
21. Tells how many items are in an array or string
23. Runs a function once for each item in an array
26. Adds a value to the end of an array
28. Something that happens like a click, scroll, or key press
29. Listener Code that waits for an event and runs when it happens
30. The name used in an object to access a value



DOWN

2. Used after "if" to run different code if the condition is false
4. A list-like structure used to store multiple values
5. A statement that runs code only if a condition is true
7. log() Prints a message or value to the browser console
10. A value you pass into a function
12. A type of event triggered by mouse click
14. random() Gives a random number between 0 (inclusive) and 1 (exclusive)
16. The data stored in an object under a key
18. Skips the rest of the loop and starts the next cycle
22. A Boolean value meaning “yes” or “correct”
24. A collection of data with key-value pairs
25. A loop that keeps running while a condition is true
27. Stops a loop early
                                                                          |                    |
