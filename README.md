# aasm
This is a simple x86_64 assembler written in Ruby. 


* This is a tool aimed to be developed in a couple days.So, it may not follow principles of Software Engineering. 
* Main aim is to read the Intel Manual and understand the wide range of instructions present. 
* Then write code to asssemble instructions. 

This doesn't assembly files into object files. It just gives the machine equivalent of 1 or more assembly instructions seperated by a **;**

Inspiration: 

1. rasm2 is awesome!
2. This [talk](https://www.youtube.com/watch?v=eunYrrcxXfw) - This dude XlogicX has written a tool called [irasm](https://github.com/XlogicX/irasm) which shows that assembly-machine code mapping is not 1:1. 
3. And I have never written a tool like this before. So, thought of writing this!


# Note!

Realized that writing an assembler takes time. 

So, I wrote **nasmshell** - A simple python3 wrapper for **nasm** and **ndisasm** tools. Do check it out!
