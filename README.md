# incremental-operators

Description 
THis snippet is to learn how the js machine executes the operator.The operators  goes form left to right and following BOADMAS rule in Maths.


* main learning objective  
to understand how the operators excutes in javasscript machine.

* the code :

```
let input = 0;
(String(++input) + String(input++)) + Number(String(input++) + String(++input));

```



exercises & study links.  
[replit](https://repl.it/@colevandersWands/snippets-day-3)
[pytut]  
* sketches you made
![snippet-image](https://github.com/devendrk/incremental-operators/blob/master/WIN_20180808_13_23_55_Pro.jpg?raw=true)
	
  

review
	* things I struggled with:
  I struggled with input updates. I thought that when input value was changed to string,
  then the original input will be turned to string. But its not the case.
  * things I learned:
  ++input and input++ was entirely different,
  ++input will addup first and then update to input but input++ works entirely different.
  
  * vocab
  next steps

helpful link

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Operator_Precedence

example:
