# Svelte Todo

Made with Svelte and PocketBase

Everything you need to build a Svelte project, powered by [`sv`](https://github.com/sveltejs/cli).

Ensure you have the correct version on pocketbase installed. I developed on apple silicon, if you have another computer, delete the ```pocketbase``` file and replace it with the correct one from the [PocketBase documentation](https://pocketbase.io/docs/)

## Developing

Once you've created a project and installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

Then start the PocketBase server:

```bash
./pocketbase serve
```

## Building

To create a production version of your app:

```bash
npm run build
```

You can preview the production build with `npm run preview`.

> To deploy your app, you may need to install an [adapter](https://svelte.dev/docs/kit/adapters) for your target environment.
