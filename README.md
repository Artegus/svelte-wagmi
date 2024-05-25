# Example of how to use 'Wagmi' and 'svelte kit'.

This is an example of how to use Svelte-kit with the Wagmi/core library to create a wallet connector.

## Features.

It has been created:
- A wallet store with two functionalities `connect` and `disconnect`.
- Subscription to account changes.
- Reconnection to the defined connectors.

These features are located in the `src/lib/wallet/wallet.ts` file.

The use of these functionalities is made in `src/routes/+page.svelte`.