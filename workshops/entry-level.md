# Entry Level Workshop

A workshop for folks who are just getting started with their cloud development journey. In this workshop we'll talk about why we deploy to the cloud with Defang and what are the easiest ways to get started.

## Why should I deploy?

1. It's more fun! People can actually use your project. 
2. If you ever want to launch the project, then you'll have to figure it out eventually. Why not take the easiest path to making it happen?
3. Setup a branded domain and get people recognizing your work.

## What's the easiest way?

1. Head to the [Defang Samples](https://defang.io/#samples) and use the 1-click deploy workflow. (use Next.js to start)
2. Edit your code (can use [github.dev](https://github.dev)) as an easy way to get started.
3. Can use [CodeSpaces](https://github.com/features/codespaces) as a way to work with the Defang CLI without having to install it.

## Okay, but how do we go from scratch?

1. First let's tear down our last project.
2. Let's install the Defang CLI (or use the [codespaces template](https://github.com/DefangLabs/codespaces))
3. Run `defang generate`
4. Use a prompt like `an express.js service which renders an html page with a random meme from the imgflip api`
5. Check the code (might need to remove some environment variables)
6. Run `defang compose up`

## Can I use my own domain?

1. Yes! Let's grab a domain.
2. Great, now let's added it to our `compose.yaml` file and redeploy (`defang compose up`)
3. Now run `defang cert generate`
4. Success!
