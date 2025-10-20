<script lang="ts">
    const name = "Dylan Berutti";
    const asciiName = ``.trim();
</script>

<pre class="ascii-banner" aria-label="ascii-name">{asciiName}</pre>

<header class="site-header">
    <nav class="nav">
        <a href="/" class="home-link">Home</a>
        <a href="/about">About</a>
        <a href="/projects">Projects</a>
    </nav>
</header>

<main class="site-content">
    <slot />
</main>
