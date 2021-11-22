<script>
	import Banner from './Banner.svelte';
    import Timer from './Timer.svelte';    
</script>


    <div class="border">
        <img alt="Survival chart" src="./images/DIPS_Animate_HIGHRISK.gif" />
    </div>
    <Timer>   
        <div class="border">
            <img alt="Survival chart" src="./images/DIPS_curve_HIGHRISK.png" />
        </div>
        <Banner text="HIGH RISK" color="#90353b"/>
        <div class="border">
            <ul>
                <li>Cancer-specific death</li>
                <li>pN1, pT3, 12 or less examined lymph nodes => Intermediate risk and usually receives adjuvant chemotherapy in current clinical practice, but usually a mild variant (e.g. single agent or shorter duration)</li>
                <li>Add that DoMore-v1-CRC is Poor prognosis => High risk and recommended to receive more comprehensive adjuvant chemotherapy</li>
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