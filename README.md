# Blog

## What is this about ?

This is the blog of `pacotheai` where we hope to write our discoveries
while learning more about creating an AI. The blog is available at:

[https://pacotheai.github.io/blog/](https://pacotheai.github.io/blog/)

## Generate the site

The jBake content can be found in `src/jbake` and you can build the
site using:

```shell
./gradlew bake
```

Your site will be generated in `build/jbake`.

## Startup locally

You can start a local server with your generated content using:

```shell
./gradlew appStart
```

Then open your browser at `http://localhost:8080`

## Publish to gitpages

When you are ready to publish the site to your GitHub-Pages, run:

```shell
./gradlew publish
```
