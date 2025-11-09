<script>
	import Logo from "$lib/components/Logo.svelte";

    const name = 'Hello World';
    const fullname = "John Doe";

    const src = '/logo-removebg-preview.png';
</script>

<style>
    h1 {
        size: 100px;
        color: rgb(255, 0, 0);
        font-family: Papyrus, sans-serif;
    }
</style>

<h1>{name}</h1>

<p>Nama Lengkap {fullname.toUpperCase()}</p>

<Logo/>