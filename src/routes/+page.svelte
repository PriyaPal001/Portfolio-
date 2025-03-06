<script>
	import Skills from './../lib/component/skills.svelte';
	import Project from './../lib/component/project.svelte';
	import Experience from '$lib/component/experience.svelte';

</script>

<main class="container mx-auto my-10 p-4 bg-black text-white">
    <div>
        <div class="flex space-x-4">
            <h3 class=" text-3xl text-green-500">Hi, I'm Priya</h3>
            <!-- <div class=" space-x-4 place-content-end h-10 w-10 text-white">  
                <a href="https://github.com/PriyaPal001" class=""><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/github/github-original-wordmark.svg" alt="git" ></a>
            </div> -->
            
        </div>
        <p> Software Developer| Competitive coder | C++,Svelte, Data Structure  </p>
        <p>Completed degree in computer science, passinate about learning new technology and exploring them.
        As a passionate developer, I design and develop complex interfaces with expertise in Svelte and React .
        I look myself as a specialized in developing end-to-end applications that provide an optimal user experience</p>
    </div>
    <Skills></Skills>
    <Project></Project>
    <Experience></Experience>
</main>