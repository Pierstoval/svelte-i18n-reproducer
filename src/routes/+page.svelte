<script>
    import { _ } from 'svelte-i18n'
</script>

<h1>{$_('page.home.title')}</h1>

<nav>
    <a>{$_('page.home.nav', { default: 'Home' })}</a>
    <a>{$_('page.about.nav', { default: 'About' })}</a>
    <a>{$_('page.contact.nav', { default: 'Contact' })}</a>
</nav>

<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
