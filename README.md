# Installing stuff

To get started, make sure you have the following installed on your system:

1. node (I'm using v7.10.0)
2. npm (I'm using 4.2.0)

(re the versions - as I'm writing this project across 2 machines, they vary - just make sure you have the latest).

Then install the project's dependencies, i.e. run this at the root of the project (where the `package.json` file is):

`npm i`

Finally, install the hexo cli globally: `npm i -g hexo-cli` (this will allow you to run the `server`, a shortcut to create new posts, deploying etc…)

Run `hexo --help` to view the top level Hexo cli docs.

# Running the server locally

Note that we will eventually `hexo generate` to generate the static files and then upload them (deploy them) to our (hopefully free) hosting service of choice.

However, to develop locally, we spin up a Hexo server to generate content while we create it (note that not everything can be generated on the fly. If you're editing themes and new content doesn't show up when you refresh the browser, try restarting the server).

To start the Hexo server, run the following in root directory:

`hexo server`

Run `hexo server --help` to view the doc for this subcommand.
