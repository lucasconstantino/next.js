[![Deploy to now](https://deploy.now.sh/static/button.svg)](https://deploy.now.sh/?repo=https://github.com/zeit/next.js/tree/master/examples/with-google-sign-in)

# Example app with Google Sign-In

## How to use

### Using `create-next-app`

Execute [`create-next-app`](https://github.com/segmentio/create-next-app) with [Yarn](https://yarnpkg.com/lang/en/docs/cli/create/) or [npx](https://github.com/zkat/npx#readme) to bootstrap the example:

```bash
npx create-next-app --example with-google-sign-in with-google-sign-in-app
# or
yarn create next-app --example with-google-sign-in with-google-sign-in-app
```

### Download manually

Download the example:

```bash
curl https://codeload.github.com/zeit/next.js/tar.gz/canary | tar -xz --strip=2 next.js-canary/examples/with-google-sign-in
cd with-google-sign-in
```

Install it and run:

```bash
npm install
npm run dev
# or
yarn
yarn dev
```

## The idea behind the example

Configuring proper [Google Sign-In](https://developers.google.com/identity/) with all the oAuth flow can be a burden. This examples connects all the needed pieces to have a simple Google authentication flow based on a sign-in button.
