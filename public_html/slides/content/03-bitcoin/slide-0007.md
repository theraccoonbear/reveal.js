## Bitcoin: Scaling Solutions

<ul>
	<li class="fragment smaller">
		<strong>SegWit</strong><span class="fragment"> - segregated witness removes cryptographic signatures from the actual block data.  Signatures account for ~90% of the block data</span>
		<ul>
			<li class="fragment">BIP 91: signaling for SegWit (locked July 2017)</li>
			<li class="fragment">BIP 141: the actual SegWit proposal </li>
			<li class="fragment">Also fixes a bug: transaction maleability</li>
		</ul>
	</li>
	<li class="fragment smaller">
		1MB block size
		<ul>
			<li class="fragment">Blocks are at capacity; <a href="https://blockchain.info/unconfirmed-transactions" target="_blank">transaction backlog</a></li>
			<li class="fragment">Fees climb higher to get included</li>
			<li class="fragment">Users want low fees, miners high</li>
		</ul>
	</li>
</ul>
