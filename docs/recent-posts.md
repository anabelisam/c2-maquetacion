## Recent-Posts Component

This html component layout represent the last four posts for the site. Follow the instructions to add the component to your own layouts.

### Prerequisites

You must have an html document with a root element, like `<body />` or `<app />`.

### Usage

Create the layout on your root component

```html
<section class="recent-posts"> <!-- Recent posts component -->
  <h2 class="recent-posts__title">Posts Recientes</h2>
  <div class="recent-posts__container">
      <!-- Recent posts items -->
  </div>
</section>
```

Create the recent-post items and add them inside the recent-posts container, example item:

```html
<div class="recent-posts__container-item">
  <img src="..." alt="imagenpreview">
  <h3>Title</h3>
  <p>Recent post preview. </p>
</div>
```

The result should look like:

```html
<section class="recent-posts"> <!-- Recent posts component -->
  <h2 class="recent-posts__title">Posts Recientes</h2>
  <div class="recent-posts__container">
    <div class="recent-posts__container-item">
      <img src="..." alt="imagenpreview">
      <h3>Title</h3>
      <p>Recent post preview. </p>
    </div>
    <!-- More posts items ... -->
  </div>
</section>
```

Use the different css classes provided in the ./styles/recent-posts.css to add your own style, for example:

```css
.recent-posts__container-item {
  border: 1px solid #ccc;
}
```

### Contributing

You have to be one of the 7Masters to contribute to this project.

### Authors

* **Raúl Romo** - [rromomx](https://github.com/rromomx)

### License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details