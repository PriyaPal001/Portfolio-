<script>
    let repos =[
        {
            id: 1,
            img:'https://i.pinimg.com/474x/77/b5/2a/77b52a0a2fe2210beed8039017c5b5b7.jpg',
            name:'Dragon game',
            date:'2021-09-01',
            description:'A project that I made for fun. It is a game where you can fight a dragon. It is made with HTML, CSS, and JavaScript.',
        },
        {
            id: 2,
            img:'https://i.pinimg.com/474x/e9/bf/45/e9bf455e42cbb5c763a897ba3b5f98b1.jpg',
            name:'Resume builder',
            date:'2021-09-01',
            description:'Users can create their resume by filling out a form. It is made with HTML, CSS, and JavaScript.',
        },
        {
            id: 3,
            img:'https://i.pinimg.com/474x/e1/4e/bd/e14ebd1396c089ca5d97d0e53a6cd3c5.jpg',
            name:'chat bot',
            date:'2021-09-01',
            description:'A chat bot that can answer questions. Helping users to find information. ',
        },
        {
            id: 1,
            img:'https://i.pinimg.com/474x/77/b5/2a/77b52a0a2fe2210beed8039017c5b5b7.jpg',
            name:'Dragon game',
            date:'2021-09-01',
            description:'A project that I made for fun. It is a game where you can fight a dragon. It is made with HTML, CSS, and JavaScript.',
        },
        {
            id: 2,
            img:'https://i.pinimg.com/474x/e9/bf/45/e9bf455e42cbb5c763a897ba3b5f98b1.jpg',
            name:'Resume builder',
            date:'2021-09-01',
            description:'Users can create their resume by filling out a form. It is made with HTML, CSS, and JavaScript.',
        },
        {
            id: 3,
            img:'https://i.pinimg.com/474x/e1/4e/bd/e14ebd1396c089ca5d97d0e53a6cd3c5.jpg',
            name:'chat bot',
            date:'2021-09-01',
            description:'A chat bot that can answer questions. Helping users to find information. ',
        },
    ]
</script>


<div class="container my-4 ">
<p class="text-3xl text-green-500 pt-5">Projects</p>
<div role="list" class="grid grid-cols-2 gap-x-4 gap-y-8 sm:grid-cols-3 sm:gap-x-6 lg:grid-cols-4 xl:gap-x-8 my-4">
  
  {#each repos as project}
    <div class="relative">
      <div class="group overflow-hidden rounded-lg bg-gray-100 h-56 w-56 focus-within:ring-2 focus-within:ring-indigo-500 focus-within:ring-offset-2 focus-within:ring-offset-gray-100">
        <img src={project.img} alt="" >
        
      </div>
      <p class="pointer-events-none mt-2 block truncate text-sm font-medium text-white">{project.name}</p>
      <p class="pointer-events-none block text-sm font-medium text-green-500">{project.date}</p>
        <p class="pointer-events-none block text-sm font-medium text-gray-500">{project.description}</p>
    </div>
  
    {/each}
  </div>
</div>


  