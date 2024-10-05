# Open Source AI Models

A workshop for folks who are ready to dive into some more advanced Defang features and want to host their own LLM models.

---SLIDE---

## Why host your own model

1. It can be less expensive
2. You can experiment with a wide variety of models
3. Can fulfil legal requirements

---SLIDE---

## What is Ollama?

[Ollama](https://ollama.com/) is a tool that helps you easily manage and run open source (or open weight) llms.

---SLIDE---

## What's the easiest way?

1. Head to the [Defang Samples](https://defang.io/#samples) and use the 1-click deploy workflow for Ollama
2. Edit your code (can use [github.dev](https://github.dev)) as an easy way to get started.
3. Can use [CodeSpaces](https://github.com/features/codespaces) as a way to work with the Defang CLI without having to install it.

---SLIDE---

## Diving deeper...

1. Install the Defang CLI
2. Clone the repo
3. Run `docker compose -f compose.dev.yaml up`
4. Update, and deploy:
    a. `git push`
    b. `defang compose up`


---SLIDE---

## Can I use my own domain?

1. Yes! Let's grab a domain.
2. Great, now let's added it to our `compose.yaml` file and redeploy (`defang compose up`)
3. Now run `defang cert generate`
4. Success!
