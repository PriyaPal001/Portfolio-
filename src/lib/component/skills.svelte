<script>
    let talent=[
        {
            img:'https://camo.githubusercontent.com/75aa77d9823348b78543f3939647a26bd0d66e0f8c91782ab557d8a391b357e8/68747470733a2f2f75706c6f61642e77696b696d656469612e6f72672f77696b6970656469612f636f6d6d6f6e732f312f31622f5376656c74655f4c6f676f2e737667',
            name:'svelte'
        },
        {
            img:'https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg',
            name:'TypeScript'
        },
        {
            img:'https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg',
            name:'JavaScript'
        },
        {
            img:'https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg',
            name:'React'
        },
        {
            img:'https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg',
            name:'CSS'
        },
        {
            img:'https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg',
            name:'HTML'
        },
        {
            img:'https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg',
            name:'Java'
        },
        {
            img:'https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg',
            name:'C++'
        },
      
    
    ]
</script>

<div>
    <p class="text-3xl text-green-500 mt-4">Skills</p>
    <div role="list" class="grid grid-cols-4 gap-x-7 gap-y-8 sm:grid-cols-3 sm:gap-x-8 lg:grid-cols-8 xl:gap-x-8 my-4 ">
        {#each talent as skill}
        <div class="inline-flex pb-1">
            <img src={skill.img} alt="" class="h-6 w-6">
            <p class="text-xl text-white mx-2">{skill.name}</p>
            </div>
       
        {/each}
  </div>
</div>