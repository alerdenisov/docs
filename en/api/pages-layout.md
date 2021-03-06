---
title: "API: The layout Property"
description: Every file (first level) in the layouts directory will create a custom layout accessible with the layout property in the page component.
---

# The layout Property

> Every file (first level) in the layouts directory will create a custom layout accessible with the layout property in the page component.

- **Type:** `String` (default: `'default'`)

Use the `layout` key in your pages components to define which layout to use:

```js
export default {
  layout: 'blog'
}
```

In this example, Nuxt.js will include the `layouts/blog.vue` file as a layout for this page component.

Check the [demonstration video](https://www.youtube.com/watch?v=YOKnSTp7d38) to see it in action.

To understand how the layouts work with nuxt.js, take a look at the [layout documentation](/guide/views#layouts).
