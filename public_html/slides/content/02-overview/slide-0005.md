## So "Blocks" Are?
<h4 class="fragment">Just a bundle of transactions</h4>
<pre class="fragment">
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

<small class="fragment">These examples use JSON.  Bitcoin represents blocks using DER ASN.1</small>