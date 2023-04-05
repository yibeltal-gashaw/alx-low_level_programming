<html>
<h1>C - Recursion</h1>
<p>Recursion is the process of repeating items in a self-similar way. In programming languages, if a program allows you to call a function inside the same function, then it is called a recursive call of the function.</p>
<p>void recursion() {<br>
   recursion(); /* function calls itself */<br>
}<br>

int main() {<br>
   recursion();<br>
}</p>
<p>The C programming language supports recursion, i.e., a function to call itself. But while using recursion, programmers need to be careful to define an exit condition from the function, otherwise it will go into an infinite loop.

Recursive functions are very useful to solve many mathematical problems, such as calculating the factorial of a number, generating Fibonacci series, etc.</p>
</html>
