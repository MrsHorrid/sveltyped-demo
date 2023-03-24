<script>
    import { Typewriter } from 'sveltyped';
    import src from '/src/images/me.png'
    let words = ["About Creator.", "About Shaked.", "About Shelly."]
</script>

<div class="flex flex-col items-center p-20">
    <h1 class="font-bold text-4xl capitalize text-center mt-10 text-[#ce4141]">
        <Typewriter
          phrases = {words}
          typeSpeed = {120}
          loop = {true}
        />
    </h1>
    <img {src} alt="" class="w-[15rem] py-10">
    <p class="text-center break-words max-w-lg text-[1.2rem] capitalize">Hi im Shaked or Shelly and im a software developer. I make webapps , games , and tutorials for the youtube channel SuccessSprint to find out more about my work visit the git repo link.</p>
</div>

