Download Link: https://assignmentchef.com/product/solved-express-the-complexity-of-these-functions-using-the-big-o-notation
<br>
<strong> </strong>

<ol>

 <li><strong> Express the complexity of these functions using the big-O notation: a. T(n) = 2n2 + 3n3</strong></li>

 <li><strong> T(n) = 5 + n</strong></li>

</ol>

<strong> </strong>

<ol start="2">

 <li><strong> Use the definition of big-O to show that T(n) = 5 + n3 </strong><strong></strong><strong> O(n3)</strong></li>

</ol>

<strong> </strong>

<ol start="3">

 <li><strong> Write down the running time function of the following Python function. Then describe it in terms of O and </strong><strong></strong></li>

</ol>

<strong> </strong>

<strong>def h(a_list)</strong>

<strong>n = len(a_list) i = n-1</strong>

<strong>sum = 0</strong>

<strong>while i&gt;=0 do:</strong>

<strong>i = i </strong><strong>–</strong><strong> 1 j = 0</strong>

<strong>while j&lt;n do:</strong>

<strong>j = j*2</strong>

<strong>sum = sum + a_list[i] + a_list[j]</strong>

<strong> </strong>

<ol start="4">

 <li><strong> Write down the running time function of the following Python function. Then describe it in terms of O and </strong><strong></strong><strong>.</strong></li>

</ol>

<strong> </strong>

<strong>def g(a_list)</strong>

<strong>n = len(a_list) sum = 0</strong>

<strong>for i in range(n):</strong>

<strong>for j in range(n*n):</strong>

<strong>for k in range(j):</strong>

<strong>sum = i + j + a_list[i]</strong>

<strong> </strong>

<ol start="5">

 <li><strong> Write down the running time function of the following Python function. Then describe it in terms of O and </strong><strong></strong><strong>. (Assume that the running time of function foo is n*log(n).)</strong></li>

</ol>

<strong> </strong>

<strong>def bar(a_list)</strong>

<strong>n = len(a_list) sum = 0</strong>

<strong>for i in range(n):</strong>

<strong>sum = sum + a_list[i] value = 1</strong>

<strong>for j in range(n*n):</strong>

<strong>value = value * j</strong>

<strong>foo(sum, value)</strong>