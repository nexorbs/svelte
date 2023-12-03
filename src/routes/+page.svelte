<script>
    import Layout from '../layouts/Layout.svelte';
</script>

<Layout>

    <!-- DELETE THIS & GO -->
    <div class="bg-[#090909] text-white min-h-screen">
        <h1 class='text-center font-bold text-5xl pt-4'>Welcome to <span class="sveltegradient">SvelteKit</span> with <span class="tailgradient">Tailwind</span></h1>
        <br>
        <p class='text-center text-2xl'>Visit <a class='text-blue-500 hover:underline' href='https://kit.svelte.dev'>kit.svelte.dev</a> to read the documentation</p>
        <br>
        <p class='text-center text-2xl'>Visit <a class='text-blue-500 hover:underline' href='https://tailwindcss.com/docs/installation'>tailwindcss.com/docs/</a> to read the documentation</p>
        <p class="absolute bottom-0 text-zinc-900">Maked with NexOrbs</p>
    </div>

</Layout>
<style>
    .sveltegradient {
        background: -webkit-linear-gradient(0deg, rgba(255,110,1,1) 0%, rgba(255,255,255,1) 100%);
        background-clip: text;
        -webkit-text-fill-color: transparent;
    }
    .tailgradient{
        background: -webkit-linear-gradient(0deg, rgba(1,19,255,1) 0%, rgba(255,255,255,1) 100%);
        background-clip: text;
        -webkit-text-fill-color: transparent;
    }
</style>

