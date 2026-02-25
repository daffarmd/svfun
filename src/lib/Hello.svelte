<script>
  import Logo from "./Logo.svelte";

    // Hello
    alert('Hello, World!');

    // Text Expresion
    const name = 'Text Expresion';

    // Dynamic Attribute
    const src = 'https://upload.wikimedia.org/wikipedia/commons/thumb/4/46/Bitcoin.svg/3840px-Bitcoin.svg.png';

    // HTML Tag
    const content = '<h1> Hello </h1>';
</script>

<style>
    h1 {
        color: rgb(0, 166, 255);
    }

    img {
        width: 200px;
    }
</style>

<!-- Hello -->
<h1> Hello </h1>

<!-- Text Expresion -->
<h1> Hello {name.toLowerCase()} </h1>

<!-- Dynamic Attribute -->
<img {src} alt="www">

<!-- Nested Component -->
<Logo />

<!-- HTML Tag -->
{@html content}