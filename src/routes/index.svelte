<script>
  import Hero from './Components/Hero.svelte';
  import About from './Components/About.svelte';
 let people = [
   {name: 'computer', image: '/Illustrations.png', company: 'techminate', id: 1 },
   {name: 'computer', image: '/Illustrations.png', company: 'techminate', id: 2 },
   {name: 'computer', image: '/Illustrations.png', company: 'techminate', id: 3 },
 ]
</script>
<!--hero section-->
 
<Hero />
<!--hero section-->
<!---about-->
<About />
<!---about-->


  <div class="overflow-x-auto" data-theme="light">
    <!-- The button to open modal -->
   <label for="my-modal" class="btn modal-button">open modal</label>
    <!-- Put this part before </body> tag -->
    <input type="checkbox" id="my-modal" class="modal-toggle">
      <div class="modal">
        <div class="modal-box">
          <h3 class="font-bold text-lg">Congratulations random Interner user!</h3>
          <p class="py-4">You've been selected for a chance to get one year of subscription to use Wikipedia for free!</p>
          <div class="modal-action">
            <label for="my-modal" class="btn">Yay!</label>
          </div>
        </div>
      </div>
  </div>

  
 <style>

 </style>