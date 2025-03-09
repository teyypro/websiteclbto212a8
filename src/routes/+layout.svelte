<script>
    import Taskbar from "../component/Taskbar.svelte";

</script>


<Taskbar/>
<main>
    <slot />
  </main>

  <style>
    main{
        top: 4rem;
    position: relative;
    }
  </style>