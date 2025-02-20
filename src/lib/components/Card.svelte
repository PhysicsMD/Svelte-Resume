<script lang="ts">
    export let CardIMG: string;
    export let CardTitle: string;
    export let CardDescription: string;
    export let CardHasLink: boolean = false;
    export let CardLink: string;
    export let CardLinkText: string = "More about this project";

    let isLoaded = false; // Variable to track image load state
</script>

<div class="card rounded-md border-2 shadow-lg shadow-black/50">
    <div class="w-72 h-86">
        <div class="center">
            <!-- Use "visibility: hidden" initially and show it when loaded -->
            <img
                src={CardIMG}
                alt=""
                class="lazy-image h-40 overflow-hidden"
                on:load={() => isLoaded = true}
                loading="lazy"
                style={isLoaded ? 'visibility: visible;' : 'visibility: hidden;'}
            />
        </div>
        <h2>{CardTitle}</h2>
        <div class="{CardHasLink ? 'h-23' : 'h-35'} descriptionscroll">
            <p class="card-description">{CardDescription}</p>
        </div>
        {#if CardHasLink}
        <div class="card-pagelink">
            <a href={CardLink} target="_blank">{CardLinkText}</a>
        </div>
        {/if}
    </div>
</div>

<style>
    .card {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        background-color: #333;
        overflow: hidden;
        margin: 10px;
        animation-name: offexample;
        animation-duration: .5s;
        border-color: #333;
    }
    .card:hover {
        animation-name: example;
        animation-duration: .5s;
        border-color: #888;
    }
    @keyframes example {
        from {border-color: #333;}
        to {border-color: #888;}
    }
    @keyframes offexample {
        from {border-color: #888;}
        to {border-color: #333;}
    }

    .center {
        display: flex;
        justify-content: center;
        background-color: black;
    }

    h2 {
        color: white;
        padding-top: 6px;
        padding-left: 15px;
        font-size: 25px;
        font-weight: bold;
    }

    .card-description {
        color: white;
        padding-left: 15px;
        font-size: 15px;
    }

    .card-pagelink {
        padding-top: 11px;
    }

    .card-pagelink a {
        margin-left: 16px;
        margin-top: 2px;
        padding: 7px;
        font-size: 15px;
        border: 2px solid;
        border-radius: 5px;
        color: #10c9cf;
        font-weight: 550;
    }

    .card-pagelink a:hover {
        font-size: 15px;
        border: 2px solid;
        border-radius: 5px;
        border-color: #10c9cf;
        color: white;
        background-color: #10c9cf;
        text-decoration: none;
    }

    .descriptionscroll {
        overflow-y: scroll;
        scrollbar-color: #555 #333;
        scrollbar-width: thin;
        scroll-behavior: smooth;
    }

    /* Optional: You can add a loading spinner or placeholder if needed */
    .lazy-image {
        visibility: hidden;
    }
</style>
