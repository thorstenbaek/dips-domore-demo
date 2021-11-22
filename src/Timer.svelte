<script>
    import { onMount, onDestroy } from 'svelte'; 	    

    var timer = null;
    var countdown = 6;

    onMount(() => {
		timer = setInterval(() => {
			countdown -= 1;
	  }, 1000);
	})

    onDestroy(() => {
        if (timer) {
            clearInterval(timer);
        }
    })

    $: {
		if (countdown === 0) {
			clearInterval(timer);
			timer = null;
		}
	}
</script>

{#if countdown === 0}
    <slot/>
{/if}
