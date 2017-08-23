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

<small class="fragment" data-fragment-index="2">These examples use JSON.  Bitcoin represents blocks using DER ASN.1</small>