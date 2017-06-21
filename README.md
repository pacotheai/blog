# blog.pacotheai.com

## Blog

This is the blog of pacotheai.com where we hope to write our
discoveries while learning more about creating an AI.

## How to generate the site

The jBake content can be found in `src/jbake` and you can build the
site using:

```shell
./gradlew bake
```

Your site will be generated in `build/jbake`. You can start a local
server with your generated content using:

```shell
./gradlew appStart
```

When you are ready to publish the site to your GitHub-Pages, run:

```shell
./gradlew publish
```
