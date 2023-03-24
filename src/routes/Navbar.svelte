<script lang="ts">
	let navToggle = false;
	import src from '../images/burger.png';

	export const toggleNav = () => {
		if (navToggle) {
			navToggle = false;
		} else {
			navToggle = true;
		}
	};
</script>

<!-- when in mobile sizes , hamburger menu when in medium and above normal nav -->
<nav class="flex justify-between px-8 py-4">
	<a href="/" class="text-2xl font-bold ">Sveltyped.</a>
	<ul class="hidden md:flex gap-4">
		<a class="hover:font-bold ease-in-out duration-300 hover:text-orange-500" href="https://github.com/MrsHorrid/Sveltyped" target="_blank">Git Repo</a>
		<a class="hover:font-bold ease-in-out duration-300 hover:text-orange-500" href="https://www.npmjs.com/package/sveltyped" target="_blank">NPM site</a>
		<a class="hover:font-bold ease-in-out duration-300 hover:text-orange-500" href="/demos">Demos</a>
		<a class="hover:font-bold ease-in-out duration-300 hover:text-orange-500" href="/about">About Creator</a>
	</ul>
</nav>

<div class="px-5 underline underline-offset-4">
    <ul class="mt-20 flex items-center text-[15px] gap-4 text-center justify-center mx-auto  md:hidden ">
		<a class="hover:font-bold" href="https://github.com/MrsHorrid/Sveltyped">Git Repo</a>
		<a class="hover:font-bold" href="https://www.npmjs.com/package/sveltyped">NPM site</a>
		<a class="hover:font-bold" href="/demos">Demos</a>
		<a class="hover:font-bold" href="/about">About Creator</a>
	</ul>
</div>
