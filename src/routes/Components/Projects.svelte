<script>
 let people = [
   {name: 'computer', image: '/Illustrations.png', company: 'techminate', id: 1 },
   {name: 'computerd', image: '/Illustrations.png', company: 'techminatxe', id: 2 },
   {name: 'computer', image: '/Illustrations.png', company: 'techminategg', id: 3 },
   {name: 'computer', image: '/Illustrations.png', company: 'techminategg', id: 4 },
 ]
</script>
<!----card component-->
<main>
    <h1 class="text-center text-3xl py-6">Browse our projects</h1>
    <div class="grid grid-cols-1 sm:grid-cols-4 px-5 gap-4">
       <div class="card w-86 bg-base-100 shadow-xl">
            <figure class="px-5 pt-10">
                <img src="https://pim-img-psmt1.aeropost.com/n/4/8/9/4/4894364195beda2a4b838969c4e4e56b148fea27_ComputersTabletsAccessories_408709_01.png" alt="Shoes" class="rounded-xl" />
            </figure>
            <div class="card-body items-center text-center">
                <h2 class="card-title">{people[0].name}</h2>
                <p>{people[0].company}</p>
           </div>
       </div>
        <div class="card w-86 bg-base-100 shadow-xl">
            <figure class="px-5 pt-10">
                <img src="https://pim-img-psmt1.aeropost.com/n/4/8/9/4/4894364195beda2a4b838969c4e4e56b148fea27_ComputersTabletsAccessories_408709_01.png" alt="Shoes" class="rounded-xl" />
            </figure>
            <div class="card-body items-center text-center">
                <h2 class="card-title">{people[0].name}</h2>
                <p>{people[0].company}</p>
            </div>
       </div>
       <div class="card w-86 bg-base-100 shadow-xl">
            <figure class="px-5 pt-10">
                <img src="https://pim-img-psmt1.aeropost.com/n/4/8/9/4/4894364195beda2a4b838969c4e4e56b148fea27_ComputersTabletsAccessories_408709_01.png" alt="Shoes" class="rounded-xl" />
            </figure>
            <div class="card-body items-center text-center">
                <h2 class="card-title">{people[0].name}</h2>
                <p>{people[0].company}</p>
            
            </div>
       </div>
       <div class="card w-86 bg-base-100 shadow-xl">
        <figure class="px-5 pt-10">
            <img src="https://pim-img-psmt1.aeropost.com/n/4/8/9/4/4894364195beda2a4b838969c4e4e56b148fea27_ComputersTabletsAccessories_408709_01.png" alt="Shoes" class="rounded-xl" />
        </figure>
        <div class="card-body items-center text-center">
            <h2 class="card-title">{people[0].name}</h2>
            <p>{people[0].company}</p>
        
        </div>
   </div>
    </div>
</main>
<!----End card component-->