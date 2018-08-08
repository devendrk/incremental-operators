# incremental-operators

Description 
THis snippet is to learn how the js machine executes the operator.The operators  goes form left to right and following BOADMAS rule in Maths.


* main learning objective  
to understand how the operators excutes in javasscript machine.

the code :
```
let input = 0;
(String(++input) + String(input++)) + Number(String(input++) + String(++input));

```



exercises & study links.  
[replit](https://repl.it/@colevandersWands/snippets-day-3)
[pytut]
	sketches you made
  

review
	* things I struggled with:
  I struggled with input updates. I thought that when input value was changed to string,
  then the original input will be turned to string. But its not the case.
  
	* things I learned:
   ++input and input++ was entirely different,
  ++input will addup first and then update to input but input++ works entirely different.
  
	* vocab
  
	next steps

helpful link.  urls to good online resources that cover this feature of js

example: https://github.com/elewa-academy/block-scope-let-vs-var#index
