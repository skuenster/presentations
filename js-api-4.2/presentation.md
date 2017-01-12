<!-- .slide: class="title" -->

## ArcGIS API for JavaScript 4.2 und Web AppBuilder

![separator](images/separator.png)

`Stephan Künster, Simon Geigenberger`

---

## Agenda

- A
- B
- C

---

<!-- .slide: class="section" -->

# Section 1

---

## Slide 1

- text
- [Link](//www.arcgis.com) with text after
- [`Link highlighted`](//www.arcgis.com)

---

<!-- .slide: class="section" -->

# Section 2

---

## Slide 1

text
- `highlighted text`

---

## Slide 2

- text
 - subtext
 
![Picture-text](images/esri-startup-program.jpg)

---

## Slide 3

- text _"text"_
- text **_text_**-text, text `text()`

---

## Slide 4

```js
var view = new MapView({ map: map });

// watch for view center updates
view.watch('center', function(value) {
  log("center set to:", value.longitude, value.latitude);
});

// watch for basemap title updates
map.watch('basemap.title', function(value) {
  log("basemap is now: ", value);
});
```

---

## Questions?

**Text** Text

Author ([@twitter-account](https://twitter.com/twitter-account))

Slides: [github.com/[Author]/presentations](https://github.com/[Author]/presentations)

