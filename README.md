# ArgumentsOptional

<h2>Arguments Optional</h2>

<p>Create a function that sums two arguments together. If only one argument is provided, then return a function that expects one argument and returns the sum.</p>
<p>For example, addTogether(2, 3) should return 5, and addTogether(2) should return a function.</p>
<p>Calling this returned function with a single argument will then return the sum:</p>
<p>var sumTwoAnd = addTogether(2);

sumTwoAnd(3) returns 5.

If either argument isn't a valid number, return undefined.</p>
<ul>
<li>addTogether(2, 3) should return 5.</li>
<li>addTogether(2)(3) should return 5.</li>
<li>addTogether("http://bit.ly/IqT6zt") should return undefined.</li>
<li>addTogether(2, "3") should return undefined.</li>
<li>addTogether(2)([3]) should return undefined.</li>