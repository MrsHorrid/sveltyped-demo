<script lang="ts">
	import { Typewriter } from 'sveltyped';
    let words = ['Sveltyped' , 'An aweosme typewriter library', "For Svelte!","This is a demonstration of the Typewriter library."]
</script>

<div class="p-20 flex flex-col">
    <h1 class="font-bold text-4xl capitalize text-center mt-10 text-[#000000]">Demos</h1>
    <h2 class="text-center py-5 mt-8">
        <Typewriter
            phrases = {words}
            loop= {true}
        />
    </h2>
    <h2 class="text-center py-5 font-mono capitalize font-bold text-2xl text-gray-700">
        <Typewriter
            phrases = {words}
            typeSpeed = {100}
            loop= {true}
        />
    </h2>
    <h2 class="text-center py-5 font-serif text-3xl first-letter:">
        <Typewriter
            phrases = {words}
            typeSpeed = {50}
            loop= {true}
        />
    </h2>
    <h2 class="text-center py-5 first-letter:text-red-600 font-bold uppercase text-3xl">
        <Typewriter
            phrases = {words}
            loop= {true}
        />
    </h2>
</div>
