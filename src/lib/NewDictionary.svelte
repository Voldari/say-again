<script lang="ts">
    let selected = false
    
    function toggle() {
        selected = !selected
    }
</script>

<div class="toggle" on:click={toggle}>
    {#if selected}
        Cancel
    {:else}
        New
    {/if}
</div>

{#if selected}
    <div class="border container">  
        howdy
    </div>  
{/if}

<style> 

    .toggle {
        grid-area: 1 / 2 / 2 / 3 ;
    }
    
    .container {
        grid-area: 1 / 3 / 3 / 4 ;
    }  
    
    .selected {
        background-color: var(--red);
    }
    
 </style> 
