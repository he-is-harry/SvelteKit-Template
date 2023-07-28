# Harry's `create-svelte` Template

Everything you need to build a Svelte project, powered by [`create-svelte`](https://github.com/sveltejs/kit/tree/master/packages/create-svelte).

## Creating a project

Follow the steps below to clone this specific branch for a SvelteKit template with compatibility with [PostCSS (Just In Time) Props](https://github.com/GoogleChromeLabs/postcss-jit-props).

If you are on Mac, you can run the following commands to copy in the template and remove all of the git files for the template repository.
```bash
# create a new project in the current directory with this specific postcss-open-props branch
git clone -b postcss-open-props --single-branch https://github.com/he-is-harry/SvelteKit-Template.git
# rename the repository name to your workspace name
mv SvelteKit-Template project-name
# enter your new workspace
cd project-name
# Then remove the current git repository from the project by running
rm -rf .git*
```
If you are on Windows, you can run these commands to accomplish the same thing.
```bash
# create a new project in the current directory with this specific postcss-open-props branch
git clone -b postcss-open-props --single-branch https://github.com/he-is-harry/SvelteKit-Template.git
# rename the repository name to your workspace name
ren SvelteKit-Template project-name
# enter your new workspace
cd project-name
# Then remove the current git repository from the project by running these two commands
rmdir /s /q .git
del /s /a .git*
```

Alternatively, if you are running in a existing workspace

```
git clone -b postcss-open-props --single-branch https://github.com/he-is-harry/SvelteKit-Template.git
```

Then you just need to delete the `SvelteKit-Template` folder which also deletes the Github repository that this refers to. On Mac, you can delete this by pressing Command-Option-Delete **(⌘⌥⌫)**. On Windows, you should use Shift-Delete **(⇧⌫)**.

That's it! You can now jumpstart right into your project.
In order for your project to feel more complete you may wish to modify the name of the project in your `package.json` file.

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
