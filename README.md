# Next + Netlify + Github Actions Starter

[![Netlify Status](https://api.netlify.com/api/v1/badges/2d40592a-96c3-4110-b5ae-10c6664b921d/deploy-status)](https://app.netlify.com/sites/next-netlify-github-actions-starter/deploys)

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app) and set up to be deployed on Netlify using Github Actions.

> This template is related to the article: [How to deploy your Next.js app on Netlify using Github Actions](https://dev.to/thedaviddias/how-to-deploy-your-next-js-app-on-netlify-using-github-actions-14bn)

## Quick start

Install the dependencies

```bash
npm install
```

Check your project is working properly launching the dev mode:

```bash
npm run dev
```

A new tab should automatically open in your browser.

If not, go to [http://localhost:3000](http://localhost:3000) with your browser to see the result.
### Environment variables

Go to your Github project settings and setup the following environment variables.

| Actions secret name  | Comments                                                                                                                       |
|----------------------|--------------------------------------------------------------------------------------------------------------------------------|
| `NETLIFY_AUTH_TOKEN` | Request your token [here](https://app.netlify.com/user/applications#personal-access-tokens)                                    |
| `NETLIFY_SITE_ID`    | The site to where deploy your site (get it from the API ID on your Site Settings)                                              |

### Open a pull request

The current Github Action only works when you open a new PR to main / master. Feel free to change to `push` instead of `pull_request` if you want to trigger on push.
## Deploy in one-click

You can use this button below to create a new repo with the current project and automatically deploy to Netlify.

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/thedaviddias/next-netlify-github-actions-starter)
