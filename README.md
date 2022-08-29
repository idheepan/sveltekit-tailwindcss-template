# sveltekit-tailwindcss-template

A simple skeleton page that saves a ton of time in setting up [Svelte](https://svelte.dev/), [SvelteKit](https://kit.svelte.dev/) and [Tailwindcss](https://tailwindcss.com/).

I found most templates were not updated to SvelteKit 1.0 and there were a few manual steps I kept repeating while setting up tailwind 3 for Sveltekit and typescript. This repo is a solution to that problem.

## Creating a project

You can either clone this repo or use degit. 

```bash
# create a copy from github repo
npx degit idheepan/sveltekit-tailwindcss-template

# install dependencies
npm install

# open page in a new browser
npm run dev -- --open

# build app for deployment
npm build
```

> To deploy your app, you may need to install an [adapter](https://kit.svelte.dev/docs/adapters) for your target environment.
