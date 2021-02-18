# hackerrank-javascript-intermediate-1
You want to rename a certain file on your computer. However, because of a glitch, you can't rename it to whatever you want—you can only delete characters from the old file name. In other words, the new file name must be a subsequence of the original file name. Given the original file name, as well as the file name you'd like to change it to, how many ways are there to create the new file name by just removing characters?


<p><em>Note: Because the number of ways may be large, return the answer modulo 10<sup>9</sup>+7.</em></p>

<p>For example, let's say you want the new file name to be <em>newName = "aba"</em>. Currently, the <em>oldName = "ababa"</em>. There are a total of 4 subsequences within the old file name that would form the new file name:</p>

<ul>
	<li>
	<p>"aba<strike>ba</strike>"</p>
	</li>
	<li>
	<p>"ab<strike>ab</strike>a"</p>
	</li>
	<li>
	<p>"<strike>ab</strike>aba"</p>
	</li>
	<li>
	<p>"a<strike>ba</strike>ba"</p>
	</li>
</ul>
<p>Therefore, the answer is 4 modulo 10<sup>9</sup>+7</p>
