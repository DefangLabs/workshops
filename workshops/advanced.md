# Advanced Level Workshop

A workshop for folks who are want to learn to build more complex cloud applications with Defang. In this workshop we'll talk about how to deploy a more complex application and how to use your own domain.

---SLIDE---

## Why should I deploy?

1. It's more fun! People can actually use your project.
2. If you ever want to launch the project, then you'll have to figure it out eventually. Why not take the easiest path to making it happen?
3. Setup a branded domain and get people recognizing your work.

---SLIDE---

## Defang Playground

1. Head to the [Defang Samples](https://defang.io/#samples) and use the 1-click deploy workflow. (use Next.js to start)
2. Edit your code (can use [github.dev](https://github.dev)) as an easy way to get started.
3. Can use [CodeSpaces](https://github.com/features/codespaces) as a way to work with the Defang CLI without having to install it.
4. Check your project in the [Defang Portal](https://portal.defang.dev).
5. Tear down your project using the Defang CLI.

---SLIDE---

## Okay, but now for real

1. The Playground is great, but let's deploy to our own account.
2. Before we can deploy to AWS, we need to setup our AWS credentials in the [AWS console](https://console.aws.amazon.com/).
3. Run `defang generate` and pick a more complex project or generate one using a prompt.
4. Check the code (pay attention to environment variables)
5. Run `defang compose up --provider aws` to deploy to AWS.

---SLIDE---

## Can I use my own domain?

1. Yes! Let's grab a domain.
2. Great, now let's added it to our `compose.yaml` file and redeploy (`defang compose up`)
3. Now run `defang cert generate`
4. Success!

---SLIDE---

## What's next?

1. Customize your project to your heart's content.
2. Check out the other Defang samples.
3. Don't forget to tear down your project when you're done! Save $$!
4. Join the [Defang Discord](https://s.defang.io/discord) community to ask questions and get help.
