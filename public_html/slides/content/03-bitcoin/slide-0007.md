## Bitcoin: Scaling Solutions

<ul>
	<li class="fragment smaller">
		<strong>SegWit</strong><span class="fragment"> - segregated witness removes cryptographic signatures from the actual block data and bumps max. block size to 2 MB.  Signatures account for ~50% of the block data</span>
		<ul>
			<li class="fragment">BIP 91: signaling for SegWit (locked July 2017)</li>
			<li class="fragment">BIP 141: the actual SegWit proposal (activated August 2017)</li>
			<li class="fragment">Also fixes a bug: transaction maleability</li>
		</ul>
	</li>
	<li class="fragment smaller">
		<strong>Bitcoin Cash</strong><span class="fragment"> - increase the maximum block size to 8MB and incorporate SegWit.</span>
		<ul>
			<li class="fragment">A deliberate hard fork to a new currency</li>
			<li class="fragment">Not part of a BIP</li>
			<li class="fragment">An overtly political change amidst otherwise mundane tech upgrades</li>
		</ul>
	</li>
	<li class="fragment smaller">
		<strong>Lightning Network</strong><span class="fragment"> - a new layer to accomodate faster transactions and substantially lower fees.</span>
		<ul>
			<li class="fragment">Would be atop Bitcoin, not part of it</li>
			<li class="fragment">Current BTC: ~7 tx/s, VISA: ~2,000 tx/s, PayPal: ~100 tx/s, LN: > 1,000,000 tx/s</li>
		</ul>
	</li>
</ul>
