# Example of how to use 'Wagmi' and 'SvelteKit'.

This is an example of how to use [SvelteKit](https://svelte.dev/) with the [Wagmi/core](https://github.com/wevm/wagmi) library to create a wallet connector.

## Features.

It has been created:
- A wallet store with two functionalities `connect` and `disconnect`.
- Subscription to account changes.
- Reconnection to the defined connectors.

These features are located in the `src/lib/wallet/wallet.ts` file.

The use of these functionalities is made in `src/routes/+page.svelte`.