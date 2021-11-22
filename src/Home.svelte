<script>
	import HiRisk from './HiRisk.svelte';
    import LowRisk from './LowRisk.svelte';

    const urlParams = new URLSearchParams(window.location.search);
    const patientId = urlParams.get('patientId');   
</script>

<main>  
    {#if patientId == "2012466"}
        <HiRisk/>    
    {:else}
        <LowRisk/>    
    {/if}
</main>



