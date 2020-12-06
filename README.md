# Getting a taste of Vue JS

### Section 1 - 2.1

We have a blog section with 2 static html articles which we'll make dynamic with Vue.

### Link to vue CDN

In our script tag we link to the vue cdn

```html
<script src="https://unpkg.com/vue@next"></script>
```

We also link to our custom js file below this.

```html
  <script src="https://unpkg.com/vue@next"></script>
  <script src="./script.js"></script>
```

### Allowing Vue to control parts of the HTML file

#### Create a new vue instance

```js
// we want to mount to part of the file
// blog section has id of blog, this is section we want vue to control
// can create multiple vue instances, we can control header with vue as well.
Vue.createApp().mount('header');
Vue.createApp().mount('#blog');
```

## 2.2 Data and Lists