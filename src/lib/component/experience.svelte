<script>
    let work=[
        {
            title:'Software Developer',
            company:'TCS',
            date:'2021-2023',
            description:'Developed and maintained the front end of the website using Svelte and React. Worked with the team to develop the website and mobile application. '
        },
        {
            title:'Software Developer',
            company:'Bank of America',
            date:'2021-2023',
            description:'Developed and maintained the front end of the website using Svelte and React. Worked with the team to develop the website and mobile application. '
        },
        {
            title:'Software Developer',
            company:'DevTown',
            date:'2021-2023',
            description:'Developed and maintained the front end of the website using Svelte and React. Worked with the team to develop the website and mobile application. '
        }
    ]

</script>

<p class="text-3xl text-green-500 pt-5">Experience</p>
{#each work as exp}
<ul role="list" class="space-y-6">
    <li class="relative flex pt-3 gap-x-4">
      <p class="flex-auto  text-sm text-gray-300"><span class="font-medium text-white text-2xl">{exp.company}</span> {exp.title}</p>
      <time datetime="2023-01-23T10:32" class="flex-none py-0.5 pt-4 text-xs/5 text-gray-500">{exp.date}</time>
    </li>
   
  </ul>
  <p class="text-gray-500">{exp.description}</p>
{/each}
  
