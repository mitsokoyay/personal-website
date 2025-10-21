<script lang="ts">
    import "../app.css";
    const name = "Dylan Berutti";
    const asciiName = ``.trim();
</script>

<section class="home" style="text-align:center; padding: 2rem;">
    <div class="navbar">
        <a class="active" href="home">Home</a>
        <a href="contact">Contact</a>
        <a href="about">About</a>
    </div>
</section>

<main class="site-content">
    <slot />
</main>
