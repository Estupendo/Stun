<script>
    import Header from "../../public/themes/one/header.svelte";
    import Footer from "../../public/themes/one/footer.svelte";
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
