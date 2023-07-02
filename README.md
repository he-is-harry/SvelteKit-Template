# Harry's `create-svelte` Template

Everything you need to build a Svelte project, powered by [`create-svelte`](https://github.com/sveltejs/kit/tree/master/packages/create-svelte).

## Creating a project

If you're seeing this, you've probably already done this step. Congrats!

```bash
# create a new project in the current directory
git clone https://github.com/he-is-harry/SvelteKit-Template.git
# Then remove the current git repository from the project by running
rm -rf .git*
```
Alternatively, if you are running in a existing workspace

```
git clone https://github.com/he-is-harry/SvelteKit-Template.git
```

Then you just need to delete the `SvelteKit-Template` folder which also deletes the Github repository that this refers to. On Mac, you can delete this by pressing Command-Option-Delete **(⌘⌥⌫)**. On Windows, you should use Shift-Delete **(⇧⌫)**.

## Developing

Once you've created a project and installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```
**Note:** You may want to initially run this command so that you create a `./.svelte-kit` folder for your `tsconfig.json`.

## Building

To create a production version of your app:

```bash
npm run build
```

You can preview the production build with `npm run preview`.

> To deploy your app, you may need to install an [adapter](https://kit.svelte.dev/docs/adapters) for your target environment.
