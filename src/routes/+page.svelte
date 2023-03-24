<script lang="ts">
	import { onMount } from 'svelte';
	import { Typewriter } from 'sveltyped';
    let words = ['Sveltyped' , 'An aweosme typewriter library', "For Svelte!"]

    
</script>


<div class="flex items-center justify-center mt-[15rem] p-5 flex-col"> 
	<h1 class="font-bold text-4xl text-center">
		<Typewriter
			phrases={words}
			loop={true}
		/>
	</h1>
    <p class="py-4">Simply nest in a HTML element!</p>
    <div class="bg-black text-white p-3 rounded-md">
        <p>npm i sveltyped</p>
    </div>
</div>
