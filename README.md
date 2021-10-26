# Next.js + Netlify + Github Actions template

This intends to be the template repository [accompanying this blog post](https://awesome.red-badger.com/ruiramos/nextjs-github-netlify/).

It's a minimal setup of a Next.js website deployed to Netlify using Github Actions workflows. It also includes prettier and Jest installed/configured as dependencies.


## Usage

We're using [yarn]() for package management, so install that first:
```bash
npm install -g yarn
```

You'll then be able to install depedencies and having the site running locally:
```bash
yarn install
yarn dev
```

The website will be running on [http://localhost:3000](http://localhost:3000).

To enable Netlify deployments, two secrets are expected to be exposed to Github Actions runners:
 - `NETLIFY_SITE_ID`: which is shown on your site settings on Netlify as `API ID`
 - `NETLIFY_AUTH_TOKEN`: you can generate one from your [user
   page](https://app.netlify.com/user/applications) (they call it Personal
   Access Tokens)

Please have a look at the [blog post](https://awesome.red-badger.com/ruiramos/nextjs-github-netlify/) for more context.

Happy hacking!

