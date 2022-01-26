---
title: Install daisyUI as Tailwind CSS plugin
desc: 
thumbnail: https://api.lorem.space/image/album?w=500&h=500&hash=500B67FB
published: true
---

You need [Node.js](https://nodejs.org/en/download/) and [Tailwind CSS](https://tailwindcss.com/docs/installation) installed.

1. Install daisyUI:
  ```
  npm i daisyui
  ```
1. Then add daisyUI to your `tailwind.config.js` files:
  ```js
  module.exports = {
    plugins: [
      require('daisyui'),
    ],
  }
  ```