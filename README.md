<p align="center">
    <img width="250"
        src="./images/tawk-vue-logo.png"
        alt="Tawk Vue logo">
</p>

## General
- The only purpose of this forked is supporting Typescript
- Just only tested in framework Nuxt3 with Typescript
- This fork was published in npm 

## Installation

```bash
# Node
npm install tawk-messenger-vue-3-ts

# Yarn
yarn add tawk-messenger-vue-3-ts
```

<br/>

## Quickstart SSR for Nuxt3

Create a file **tawk-messenger.client.ts** in **plugins/** directory in your project, and add the
code below.

```js
import TawkMessengerVue from 'tawk-messenger-vue-3-ts'

export default defineNuxtPlugin((nuxtApp) => {
  nuxtApp.vueApp.use(TawkMessengerVue, {
    propertyId: 'property id',
    widgetId: 'widget id',
  })
})

```
