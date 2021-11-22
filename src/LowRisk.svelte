<script>
	import Banner from './Banner.svelte';    
    import Timer from './Timer.svelte';
</script>


    <div class="border">
        <img alt="Survival chart" src="./images/DIPS_Animate_LOWRISK.gif" />
    </div>
    <Timer>   
        <div class="border">
            <img alt="Survival chart" src="./images/DIPS_curve_LOWRISK.png" />
        </div>
        <Banner text="LOW RISK" color="#55752f"/>      
        <div class="border">
            <ul>
                <li>No cancer-specific death</li>
                <li>pN1, pT3, more than 12 examined lymph nodes => Intermediate risk and usually receives adjuvant chemotherapy in current clinical practice</li>
                <li>Add that DoMore-v1-CRC is Good prognosis => Low risk and recommended not to receive adjuvant chemotherapy</li>
            </ul>
        </div>
    </Timer>


<style>
    img {
        max-width: 100%;
        max-height: 100%;
    }      

    .border {
        display: block;
        padding: 5px;
    }

    
</style>    