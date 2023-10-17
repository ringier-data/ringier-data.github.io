# ringier-data.github.io

Current version: **v0.1.0**

Instructions for the new team members or business partners to enable the access to protected resources and information.

This repo as well as the produced website is publicly accessible from internet without login.

## Development

This website is built with [Hugo](https://gohugo.io/), a static site generator written in Go. And the rendered static HTML pages are
hosted on GitHub Pages.

For content authoring, you can use the [Hugo CLI](https://gohugo.io/commands/hugo/) to run a local server that will watch for changes.
1. Install `hugo`, run
   ```shell
   # with Homebrew
   brew install hugo
   
   # with MacPorts
   sudo port install hugo
   ```
2. At the root of this repo, run
   ```shell
   huge serve
   ```
3. The live preview of the document changes is at http://localhost:1313/ or whatever url the command tells you

Any commit made to `main` branch of this repo gets deployed by a GitHub Action to the website https://ringier-data.github.io.
