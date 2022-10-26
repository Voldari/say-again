<script lang="ts">
    import User from "$lib/User.svelte"
    import NewDictionary from "$lib/NewDictionary.svelte"
    import JoinDictionary from "$lib/JoinDictionary.svelte"
    import DictionaryList from "$lib/DictionaryList.svelte"
    import TermSearch from "$lib/TermSearch.svelte"
    import Term from "$lib/Term.svelte"
</script>


<div class="container">
    <User/>
    <NewDictionary/>
    <JoinDictionary/>
    <DictionaryList/>
    <TermSearch/>
    <Term/>
</div>

<style>
    .container {
        width: 100vw;
    
        display: grid;
        grid-template-columns: 1fr 1fr;
        grid-template-row: auto auto auto auto 1fr;
        
        background-color: var(--green)
    }
</style>


