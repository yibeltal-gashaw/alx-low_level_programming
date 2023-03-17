<h1>C - Variables, if, else, while <h1>
  
<h6>C is a powerful general-purpose programming language. It can be used to develop software like operating systems, databases, compilers,<h6>
<h2> Control of flow</h2>
  
<h3>The if statement</h3>
  
The if statement has two forms:<br>
<i>if(expression) statement<i>

<i>if(expression) statement1
else statement2<i>
  
  In the first form, if (and only if) the expression is non-zero, the statement is executed. If the expression is zero, the statement is ignored. Remember that the statement can be compound; that is the way to put several statements under the control of a single if.

The second form is like the first except that if the statement shown as statement1 is selected then statement2 will not be, and vice versa.<br>
  <h2> while and do statements<h2>
    <h3>while is simple:<h3>
      <i>while(expression)<br>
           statement<i>
        
 <h6>The statement is only executed if the expression is non-zero. After every execution of the statement, the expression is evaluated again and the process repeats if it is non-zero. What could be plainer than that? The only point to watch out for is that the statement may never be executed, and that if nothing in the statement affects the value of the expression then the while will either do nothing or loop for ever, depending on the initial value of the expression.
