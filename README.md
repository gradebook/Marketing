# Gradebook Marketing

This is the code that powers the Gradebook Marketing site.

We ask that you don't clone the content of the site, but you are free to get inspiration from the project - if you find the project architecture, design, etc. interesting, we welcome you to use it!

## Getting Started

Gradebook uses the latest version of Node LTS. Please ensure you have this installed to ensure maximum compatibility

1. Clone the repository

1. Install dependencies - run `yarn install`

1. Copy `.env.example` to `.env` and update the environment variables as needed


## Development

The commands you need to run are dependent on what you're trying to do.

 - For all tasks, you need eleventy to run - `yarn dev`

 - For *js* and *css* tasks (e.g. svelte or styling), you also need to have rollup running - `yarn rollup -c -w`