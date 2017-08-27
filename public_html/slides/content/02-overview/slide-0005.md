## So "Blocks" Are?
<h4 class="fragment" data-fragment-index="1">Just a bundle of transactions</h4>
<pre class="fragment" data-fragment-index="2">
	<code>
	{
		"transactions": [
			{ "from": "Alice", "to": "Jacques", "amount": 3.4 },
			{ "from": "Jacques", "to": "Bob", "amount": 2 }
		],
		...
	}
	</code>
</pre>

<small class="fragment" data-fragment-index="2">These examples use JSON.  Bitcoin represents blocks using <a href="https://en.wikipedia.org/wiki/Abstract_Syntax_Notation_One#Example_encoded_in_DER" target="_blank" rel="noopener noreferrer">DER ASN.1</a></small>