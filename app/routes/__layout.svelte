<script>
    import Header from "$lib/themes/one/header.svelte";
    import Footer from "$lib/themes/one/footer.svelte";
</script>

<svelte:head>
    <link rel="stylesheet" href="/static/app.css">
</svelte:head>

<Header />

<main>
    <slot />
</main>

<Footer />

<style>
</style>
