# Simple 8-bit Assembler Simulator
A simulator which provides a simplified assembler syntax (based on NASM) and is simulating a x86 like cpu. Press Help inside the simulator to see an overview about the supported instructions.  

**This repository is a fork off [Schweigi/assembler-simulator](https://github.com/Schweigi/assembler-simulator)**  

---

### Changes that I have done  

- Documented the code. Put in some comments.  
- In the example code I put a mention: ```You can also write in lowercase symbols```  
- Changed the repository link (Fork me on GitHub) in the ```index.html``` to this repository.  
- Changed the ```README.md```  
- Added a clear button for clearing the code-input-field.  
- I added new commands:  
  - SQ (sq) : squares the content of the given register.  
  ```asm
    mov a, 3
    sq a ; after that the register A contains 9
  ```
  - POW (pow) : computes the power x^n  
  ```asm
    ; for example
    mov a, 2
    pow a, 3 ; after that the register A contains 8
  ```

---

[TRY IT](http://christianbender.github.io/assembler-simulator)  

---

### Features
- 8-bit CPU
- 4 general purpose registers
- 256 bytes of memory
- Console output

---

### How to build
Make sure you have <a href="http://www.gruntjs.com/" target="_blank">Grunt</a> installed to compile the `asmsimulator.js` script.
Run `grunt` to build the project.

---

### Background
A technical introduction is available on my blog: [www.mschweighauser.com](https://www.mschweighauser.com/make-your-own-assembler-simulator-in-javascript-part1/).  

---

### Orginal author of this repository  

[Marco Schweighauser](https://github.com/Schweigi)  

I use this repository as exercise for make me fit of open source projects.  


