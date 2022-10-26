<script lang="ts">
    let selected = false
    
    function toggle() {
        selected = !selected
    }
</script>

<div class="toggle border" on:click={toggle}>
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
        grid-area: 2 / 1 / 3 / 2 ;
    }
    
    .container {
        grid-area: 3 / 1 / 4 / 3 ;
    }  
    
    .selected {
        background-color: var(--red);
    }
    
 </style> 
