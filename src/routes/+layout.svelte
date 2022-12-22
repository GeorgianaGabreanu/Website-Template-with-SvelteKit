<script>
	import Header from "$lib/uiSections/Header.svelte";
    import "../tailwind.css";

</script>



<div class="bg-emerald-900 dark:bg-zinc-800">    
    


    <!--Responsive Container with Max-width -->
    <div class="container mx-auto flex flex-col min-h-screen">
      
        <Header/>
      <!--Main content-->
      <main class="bg-zinc-50 dark:bg-zinc-900 rounded-xl flex-grow">
        <slot></slot>
      </main>
  
    </div>
  
  </div>