<script lang="ts">
    import { page } from '$app/state'
</script>

<style lang="scss">
    h1 {
        color: purple;
    }
</style>

<h1>Welcome to /{page.params.slug}</h1>
<p>Visit <a href="https://svelte.dev/docs/kit">svelte.dev/docs/kit</a> to read the documentation</p>
