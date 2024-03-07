<script>
import "../app.css";
import Nav from "$lib/nav.svelte";
import "@friendofsvelte/toggle/styles/Toggle.css";
</script>

<Nav/>
<slot />


<style>
        :global(.dark body) {
                @apply bg-gray-900 text-white;
        }
        :global(body) {
                @apply bg-gray-100 text-gray-900;
        }
</style>