<script lang="ts">
    import { selected_pool } from './stores/stats.js'
</script>

        <div class="pb-8 pt-4 mx-auto max-w-6xl">
            <span
                id="Ravencoin"
                class="portal text-lg font-semibold"
                on:click={() => ($selected_pool = 'Dogecoin')}
                class:active={$selected_pool === 'Dogecoin'}
                class:~indigo={$selected_pool === 'Dogecoin'}
            >
                Ravencoin
            </span>

<!--
            <span
                id="Bitcoin"
                class="portal text-lg font-semibold"
                on:click={() => ($selected_pool = 'Bitcoin')}
                class:active={$selected_pool === 'Bitcoin'}
                class:~indigo={$selected_pool === 'Bitcoin'}
            >
                Bitcoin
            </span>
-->
        </div>

<style>
</style>
