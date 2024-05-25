<script lang="ts" >
    import { walletStore } from "$lib/wallet";

</script>

{#if $walletStore.isConnected}
    <p>Connected</p>
    <div>
        <p>Address: {$walletStore.address}</p>
        <p>Connected on: {$walletStore.chain?.name}</p>
    </div>
{:else}
    <button on:click={walletStore.connect}>
        Connect wallet
    </button>
{/if}