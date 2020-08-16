# 102 - Day 06

## What I learned today

### Dynamic web pages with Javascript (ES6)
```
`var greeting = 'Hello There'`
- `document.write('<h3>' + variable + '</h3>')`
- `var el = getElementById('idname')`
    `el.textContent = greeting;`
var today = newDate();
var hourNow = today.getHours();
var greeting;
if (hourNow > 18) {
    greeting = 'Evening';
} else if (hourNow > 12) {
    greeting = 'Afternoon';
} else if (hourNow > 0) {
    greeting = 'Morning';
} else {
    greeting = 'Hi';
}
```

- Data types
    - Variable
    - String: `''`
    - Number
    - Boolean: T or F
    - NaN
    - Obj
    - Array
    - Function
- If / if else / else statments control logical flow of program
- Javascript has type coercion built into the program. Type coercion ties to make sense automatically
    - `===` is a strict *comparison* and ignores coercion
    - `==` is lenient
- `console.log()` is a  DEBUGGER
    - make sure you use a label on logs
    - ```
    var a = 8;
    console.log("this is var a", a)
    ```
- `<script src=""></script>` adds the javascript into HTML

### Computer Architect and Logic
- inventions help people with manual work; the computer as helped people with the thinking work.
- What makes a computer a computer?
    - electronic and manupliates information.
    - Takes Input
    - Stores information as data
    - processes information
    - output results
    - These are common to ALL computers

- Binary Data
    - 1s and 0s
    - Electric wires and circuits
    - wires = bits
        - more wires = more bits
        - more bits = more complex information

- Binary Number System: backbone of all computers
    - multiples of 4
    - any number can be represented by 0 and 1
    - text, sound, video, games are all represented by nummbers
    - pixel of color is represented by 0 and 1
    - sound: displayed as wave forms, wave forms can be represented by 0 and 1s
    - higher bit(64-bit vs 8-bit) = more quality

- all technology requires lots of info to be processed quickly
- under all the complexity = lots of circuits
    - binary signals: output, video, sound, music, games, cures, DNA evaluation etc.

- Input: converts input to binary info
- memory: stores info
- cpu: calculates info
- output: converts info into physical output

- to display a letter 
    - computer goes through thousands of instructions
- improvements to speed, size of memory and cpu
    - able to handle more complicated and more information = more processign power and memory the computer needs

- CPU
    - controls all other parts
    - simple commands designates which circut to do a certain job
    - binary commands are stored in memory which the CPU fetches and executes

- OS: master program
    - manages how software uses hardware of coputer
    - program w/ special abilities
    - controls other programs on computer

- only thing that makes computers smart/useful is YOU
    - you get to define a problem
    - write the software to take an idea and make it a reality
    - build things that matter to you.