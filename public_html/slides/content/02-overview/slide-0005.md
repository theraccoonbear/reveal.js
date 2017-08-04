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

<p class="fragment">This is an example using JSON.  Bitcoin represents blocks using DER ASN.1</p>