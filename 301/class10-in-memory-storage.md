# In memory storage

## Understanding the JavaScript Call Stack

What is a ‘call’?
**function invocation**
How many ‘calls’ can happen at once?
**Since the call stack is single, function(s) execution, is done, one at a time**
What does LIFO mean?
**Last In, First Out,it means that the last function that gets pushed into the stack is the first to be pop out, when the function returns.**
Draw an example of a call stack and the functions that would need to be invoked 
to generate that call stack.
****
What causes a Stack Overflow?
**A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point.**

## JavaScript error messages

What is a ‘reference error’?
**This is as simple as when you try to use a variable that is not yet declared you get this type os errors.**
What is a ‘syntax error’?
**his occurs when you have something that cannot be parsed in terms of syntax, like when you try to parse an invalid object using JSON.parse.**
What is a ‘range error’?
**Try to manipulate an object with some kind of length and give it an invalid length and this kind of errors will show up.**
What is a ‘type error’?
**Like the name indicates, this types of errors show up when the types (number, string and so on) you are trying to use or access are incompatible**
What is a breakpoint?
**The breakpoint can also be achieved by putting a debugger statement in your code in the line you want to break.**
What does the word ‘debugger’ do in your code?
**If the line you selected was run you will be able to see what has happened before that point and you can try and evaluate the next lines to check if everything is outputting what you are expecting.**