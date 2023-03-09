# Nuxt3 Base

This repo serves as a Nuxt 3 base to be imported into newly created projects.

##### Installation

`git clone https://github.com/xDHILEx/nuxt3-base.git`

into a NEWLY created Nuxt 3 project, move everything except the `README.md` file into the `nuxt3-base` into the root directory as doing this will overwrite `app.vue` and `nuxt.config.ts`.

`npm i`

to install nuxt, there will be an error because this `nuxt.config.ts` includes `@nuxtjs/tailwindcss`, etc.

`npm i --save-dev @nuxtjs/tailwindcss`

to complete the installation process.
