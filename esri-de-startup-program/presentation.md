<!-- .slide: class="title" -->

## Esri-DE Startup Program

Stephan Künster

---

<!-- .slide: class="agenda" 

## Agenda

- A
- B
- C

---
-->

<!-- .slide: class="section" -->

# Section 1

---

## Slide 1

- text
- new [Link](//www.arcgis.com) with text

---

## Slide 2

- text 2

---

## Slide 3

- text 3

---

<!-- .slide: class="section" -->

# Section 2

---

## Slide 1

- text

---

## Slide 2

Classes
- `esri/core/Accessor`
- `esri/core/Promise`
- `esri/core/Loadable`
- `esri/core/Collection`

---

## Slide 3

- text
 - subtext

---

## Slide 4

- text _"just need to know what properties for a class"_

- no more **_property_**-change events, use `watch()`
- in 3.x, listen for [`extent-change`](https://developers.arcgis.com/javascript/jsapi/map-amd.html#event-extent-change) event.
- in 4.0 `extent` watchers will be call very often

---

## Slide 5


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

Stephan Künster ([@skuenster](https://twitter.com/skuenster))

Slides: [github.com/skuenster/skuenster.github.io/presentations](https://github.com/skuenster/skuenster.github.io/presentations)

---


<!-- .slide: class="end" -->
