<script lang="ts">
    const name: string = "Harry";
</script>

<div class="two-columns">
    <div class="center-columns green-border">
        <h1>Hello {name}, to SvelteKit!</h1>
        <p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
    </div>

    <div class="center-columns orange-border">
        <h1>Hello {name}, to SvelteKit!</h1>
        <p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
    </div>
</div>

<style>
    .two-columns {
        display: flex;
    }

    
    .center-columns {
        text-align: center;
        border: 5px solid;
        margin: 10px;
        width: 50%;
    }

    .orange-border {
        border-color: var(--orange-7);
    }

    .green-border {
        border-color: var(--green-8);
    }
</style>
