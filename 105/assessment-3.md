Im enjoying the pace of the program. I already had some experience with coding, so i've wanted it to be a little faster to get to new material. But not everyone has experience with coding and the whole class needs to be on the same page. I know eventually we will be getting to new material soon.

Functions are very useful and should be used whenever possible. I always thought of functions as sub-programs inside of the main program that you can call and use whenever needed. It helps greatly with seperating different ideas of the full program. It especially helps with organizing the code and making it easier to read and understand. 

Scopes in java refer to where a certain binding can be seen in other parts of the code. There are global scopes that can be seen anywhere in the code, these are either defined outside of any loops or paths the code can take, or defined with the word global. For example. 

```
let globalScope = "this is in the global scope because it was defined here, outside of any loops or paths."
if (true) {
   let internalScope = 'this binding is only seen inside this If statement and it cannot leave this if statement.'
   global globalInternalScope= 'this binding CAN be seen outside of if statement becuase it was defined with 'global' and not let.'
   
   console.log(internalScope); // this will output perfectly fine
   console.log(globalInternalScope); // this will also output perfectly fine
}

console.log(internalScope); // this will display a error message claiming that internalScope has not been defined. because it hasent been in this part of code.
console.log(globalInternalScope); // this will display perfectly, It was defined with 'global' and allowed to expand past the local scope of the if statement.
```
