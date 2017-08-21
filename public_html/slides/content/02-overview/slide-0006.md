## And The "Chain"?
<h4 class="fragment">A series of blocks, linked by their hashes</h4>
<pre class="fragment">
	<code>
	{
		"transactions": [ ... ],
		"prevHash": "0000dfc85ae45a95330209c0834c59876011aa587be693354cbd1f40bf637fcd",
		"hash": "0000fb1ce99aef3ab068afbaabae8f21fd9b9f02d3a9442e364fa92c0b3eeef0",
		"nonce": "123456"
	}
	</code>
</pre>
<small class="fragment">This is basically how a <a href="https://en.wikipedia.org/wiki/Merkle_tree" target="_blank">Merkle Tree</a> works</small>