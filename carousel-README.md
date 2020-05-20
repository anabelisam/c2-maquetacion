## Carousel
This section of the page is to show 5 featured posts of the week.

### Size
Height is always 500px and the width depends on the viewport.

### Display
Carousel is 100% responsive and touch-friendly. Each slide has a right margin to create a separation between slides.

### Placement
The carousel is placed immediately below the navigation.

### Styling
```css
.carousel {
  display: flex;
  height: 500px;
  margin-bottom: 20px;
  overflow-x: auto;
  scroll-snap-type: x mandatory;
  width: 100%;
}
.carousel__slide {
  align-items: center;
  background-color: #005082;
  color: white;
  display: flex;
  font-family: system-ui, sans-serif;
  font-size: 50px;
  height: 500px;
  justify-content: center;
  margin-right: 15px;
  min-width: 100%;
  scroll-snap-align: start;
}
```
