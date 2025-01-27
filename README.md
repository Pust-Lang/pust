<p align="center">
  
![Banner](https://github.com/user-attachments/assets/2ef510d5-33f5-4969-bf53-5b2c19f243bf)


</p>
<h4 align="center">
  
  [Website](https://pust-lang.github.io/web/)
  
</h4>
<hr>
<p align="center">
  <b>Pust</b> – A Rust-inspired programming language <br> 
  This program is in alpha. The full code is still under development.
</p>


<br>

## What is Pust?

Pust is a new low-level programming language inspired by Rust.  
Our goal is to offer powerful, safe, and concurrent programming capabilities with an easier learning curve.  
Think **Rust**, but with **Pust** simplicity and elegance!

---

## Features (Work in Progress)

- **Easy to use**: Pust is easy to use, like, pln, iln, fn, wo, if_stmt and cv!
- **Usefull**: Pust is written it so that its easy to code for bigginers, it might also be usefull
- **Software**: Building software is slowly being implemented, and you can create windows and message boxes

---
## How to program
- **Mainspace**: Mainspace is where you can code without using the ps. , like this: p.fn("main", ['pln("my coding space")']), functions cannot be created in mainspace, but mainspace can run functions <br> <br>
- **Print**: To print in Pust in use pln("") or ps.pln("") if it isnt in mainspace <br> <br>
- **Input**: If you want user input, use iln("") or add the ps. if not in mainspace, and this is how to give an input a variable to add in an if statement or print: cv("variable", "put anything you want, it wont be used") = iln("Hello: "), and it'll take the user input and save it into the variable <br> <br>
- **if_stmt**: to use an if statement, use ```ps.if_stmt("variable", "value", ['pln("Hello!")'], ['pln("Bye!")'])```, this part "variable", "value", you could say if variable is value then pln("Hello!") else pln("Bye!"), else is optinal. ```ps.if_stmt(if > "variable", is > "value", then > ['pln("Hello!")'], else > ['pln("Bye!")'])```. <br> <br>
- **Button**: To create a button use ```cb("parent", "130,150 position", "150,30 size", "name")```, at you've created a button! under here you'll see how to run something with a button <br> <br>
- **Button Click**: to register a click on a button, use ```bc("button name", ["fn(FuncName)"])```, it can only run functions, so use p.fn. <br> <br>
- **Functions**: Currently sometimes functions does not work in Mainspace, so you have to use with p. : ```ps.fn("MyFunc", """code""")```, functions cannot be created in mainspace, but mainspace can run functions <br> <br>
- **Py**: Basicly runs python code whatever you put in, ```py("py code")``` <br> <br>
- **Os**: It will run bash scripts on your computer when used, ```os("bash code")``` <br> <br>
- **Load**: Load any raw link, ```load("raw link")``` <br> <br>
- **Loops**: To loop something use ```loop("Code", 0)```, its that easy! <br> <br>
- **Variables**: Variables, to create a variable, use cv("VariableName", "Value"), to print or Input a variable, use pln("VariableName") and input, if its outside of Mainspace use variable = ps.iln("Type Hello: ") like in basic python. <br> <br>
- **Message Box**: Message boxes, like those info, warning and error messages, well now you can program them to show up! simply use ```ps.ms("type", "title", "text/message")```, type options: info, warning and error . This is one of the first things of software, or the beginning. <br> <br>
- **Window**: To create a window, use ```cv("mywindow", cw("Name", "400x300"))```, and to make the window show up, use ```wl("mywindow")```. <br> <br>
- **Copy Paste**: mainspace ``` ps.fn("main", [' code here ']) ```, print ``` ps.pln('Hello World!') ```, input ``` ps.iln('Type somthing: ') ```, variables ``` ps.cv('VName', 'Vvalue') ```, if statement ```ps.if_stmt("variable", "value", ['pln("Hello!")'], ['pln("Bye!")'])```, web open ```ps.wo('url')```, message box ```ps.ms("type", "title", "text/message")```, functions ```ps.fn("MyFunc", """code""")```. <br> <br>

## Useful Info
**Importing Functions**: To import a function, use python's import system. ```import file``` thats it, run the function with ```fn("funcname")``` <br> <br>

## Getting Started
Download [python](https://python.org) before downloading! <br>
Clone with git: <br>

Clone the repository: <br> <br>
  clone repo:

   ```bash
   git clone https://github.com/Pust-Lang/Pust
   ```
   <br>
Clone ide (Recommended):
   <br> <br>
   
   ```bash
   git clone https://github.com/Pust-Lang/pustIDE.git
   ```
   
   <br><br>
3. Run the files <br>
   Run and open the file named 'main.py', you'll be seeing "ps.fn("main", """"""). In between the """""" is where you code, you may also not use Mainspace, but you need to add ps. , like this: ps.pln("Hello World!") <br>
   To learn Pust, go in our website and click on "cource" (still in development!) <br>
<hr>

**Supports**: Linux, Windows, Mac.
