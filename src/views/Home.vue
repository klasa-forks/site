<template>
	<div class="container">
		<section class="section has-text-centered">
			<img rel="prefetch" class="logo" src="../assets/klasa.svg">
			<br>
			<br>
			<div class="tile is-ancestor">
				<div class="tile is-parent">
					<article class="tile is-child box content">
						<h5><strong>Install Stable</strong></h5>
						<pre v-highlightjs><code class="bash">npm install klasa</code></pre>
					</article>
				</div>
				<div class="tile is-parent">
					<article class="tile is-child box content">
						<h5><strong>Install Master</strong></h5>
						<pre v-highlightjs><code class="bash">npm install dirigeants/klasa#build</code></pre>
					</article>
				</div>
			</div>
			<div class="tile is-ancestor">
				<div class="tile is-parent">
					<article class="tile is-child box content has-text-left">
						<h5><strong>About:</strong></h5>
						<p>
							Klasa is an OOP discord.js bot framework which aims to be the most feature complete,
							while feeling like a consistent extension of <a href="https://discord.js.org/#/">
								discord.js
							</a>.
						</p>
						<p>
							Originally based on Komada, Klasa has become a <a href="https://en.wikipedia.org/wiki/Ship_of_Theseus">
								ship of Theseus
							</a> and so much more.
							You can only vaguely see similarities between the two frameworks anymore...
						</p>
					</article>
				</div>
				<div class="tile is-parent">
					<article class="tile is-child box content has-text-left">
						<h5><strong>Key Features:</strong></h5>
						<ul>
							<li>OOP and completely hot-reloadable (all commands, events, inhibitors, etc).</li>
							<li>Works with any database.</li>
							<li>Powerful and easy to configure permission levels system.</li>
							<li>Per Client/Guild/User settings, and possible to add more.</li>
							<li>Powerful command handler with: prompting, edits, argument resolving, flags, infinite args, custom args, and so much more...</li>
							<li>Fully customizable.</li>
						</ul>
					</article>
				</div>
			</div>
		</section>
	</div>
</template>

<style lang="scss" scoped>
.logo {
	width: 100%;
	max-width: 400px;
}
</style>
