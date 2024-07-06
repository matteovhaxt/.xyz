<script>
	import { Github, Linkedin, Twitter } from 'lucide-svelte';
</script>

<footer class="footer footer-center text-base-content rounded p-10">
	<nav>
		<div class="flex gap-4">
			<a href="https://github.com/matteovhaxt">
				<Github />
			</a>
			<a href="https://twitter.com/matteovhaxt">
				<Twitter />
			</a>
			<a href="https://www.linkedin.com/in/matteovhaxt/">
				<Linkedin />
			</a>
		</div>
	</nav>
	<aside>
		<p>© {new Date().getFullYear()} - Matteo von Haxthausen</p>
	</aside>
</footer>
