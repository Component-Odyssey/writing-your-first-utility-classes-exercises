# Writing Your First Utility Classes: Exercises

The companion repo to the corresponding lesson from [Component Odyssey](https://component-odyssey.com).

## Getting started

Clone this repo using:

`git clone https://github.com/Component-Odyssey/writing-your-first-utility-classes-exercises.git`

Open the folder in VSCode

Navigate to the directory of the first exercise:

`cd ./starter`

Install the dependencies:

`npm i`

Start the server:

`npm run start`

The README within `starter` has more details about the exercises, so be sure to read the instructions.

## Troubleshooting

### "NPM warns me of vulnerabilities when I install dependencies, is something wrong?"

While it may be concerning to install some dependencies only to be told that they contain vulnerabilities. NPM audit often raises false positives, as it doesn't understand the context with which we use the installed package.

We're using @web/dev-server to run a dev server for our code. The vulnerability that NPM audit flags for that package is Server-Side Request Forgery (SSRF). This may be a concern if we're running a remote server with private resources, but that's not the case for us, as we'll only be running our code locally.

If you're interested in learning more about the difficulties with [NPM audit, then please check out this article](https://overreacted.io/npm-audit-broken-by-design/)

If you have any problems, then please reach out in the Discord.
