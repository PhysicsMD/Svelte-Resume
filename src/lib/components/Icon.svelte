<script lang="ts">

    export let IconImg: string;
    export let IconTitle: string;
	
</script>

<div class="card" title={IconTitle}>
    <div class="w-30 h-30">
        <img src={IconImg} alt="icon" class="m-auto w-23 drop-shadow-xl shadow-black/50">
    </div>
</div>

<style>
    .card {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        background-color: transparent;
        overflow: hidden;
        height: 8em;
        margin: 0px;
        border-color: transparent;
    }
    .card div{
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        background-color: transparent;
        border-color: transparent;
    }
    .card div img{
        display: block;
        height: 5em;
        width: auto;
        padding: .2em;
        margin: 0px;
        background-color: transparent;
        filter: drop-shadow(0px 0px 4px white);
    }

</style>