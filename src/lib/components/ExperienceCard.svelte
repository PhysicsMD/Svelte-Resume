<script lang="ts">
    export let ShardIMG: string;
    export let ShardCompany: string;
    export let ShardRole: string;
    export let ShardDescription: string;
    export let ShardDates: string;
    export let ShardLocation: string;

    let isLoaded = false; // Variable to track image load state
</script>

<div class="rounded-md border-2 shadow-lg shadow-black/50 w-full m-3">
    <div class="w-100% container">
        <div class="imgcontainer">
            <!-- Use visibility: hidden until the image is loaded -->
            <img 
                src={ShardIMG} 
                alt={ShardCompany} 
                class="lazy-image"
                on:load={() => isLoaded = true} 
                loading="lazy"
                style={isLoaded ? 'visibility: visible;' : 'visibility: hidden;'}
            />
        </div>
        <div class="textcontainer">
            <div class="headcont">
                <div class="expcompany">{ShardCompany}</div>
                <div class="expdates">{ShardDates}</div>
            </div>
            <div class="exprole">{ShardRole}</div>
            <div class="explocation">{ShardLocation}</div>
            <div class="expdesc">
                {#each ShardDescription.split("\n").filter(line => line.trim() !== "") as line, index}
                    <p>{line}</p>
                {/each}       
            </div>
        </div>
    </div>
</div>

<style>
    .container {
        display: block;
        background-color: #333;
        overflow: hidden;
    }

    .imgcontainer {
        float: left; /* Allows text to wrap around */
        max-width: 15em;
        max-height: 10em;
        border-width: 1px;
        background-color: white;
        border-top-left-radius: 5px;
        border-color: #222;
        padding: 10px;
        margin-right: 15px; /* Space between image and text */
    }

    .textcontainer {
        margin: 10px;
    }

    .headcont {
        display: flex;
        justify-content: space-between;
        align-items: center;
    }

    .expcompany {
        color: white;
        font-weight: 800;
        font-size: larger;
    }

    .exprole {
        color: white;
        font-weight: 600;
    }

    .expdates {
        color: white;
        font-weight: 600;
    }

    .explocation {
        color: white;
        font-weight: 400;
    }

    .expdesc {
        color: white;
        text-indent: 1.5em;
        font-size: medium;
        font-family: Arial, Helvetica, sans-serif;
    }

    .lazy-image {
        visibility: hidden; /* Initially hide the image */
    }
</style>
