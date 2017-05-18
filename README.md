# map-component
[Demo here](https://dariuszignaciuk.github.io/map-component/ "map-component demo")
#### Embed google map in your site with few lines of code.

#### Since this component uses Shadow Dom, Import and Custom Element technologies - this component only works on Chrome and Opera. 
Stay tuned for wider support and styling updates.
***
### All you need to do in your HTML file:


- Inside `<head>` add import link: 
```
<head>
<link rel="import" href="map-component.html">
</head>
```

- Add `<map-component>` tag inside `<body>`: 
```
  <map-component>
    <div id="map"></div>
    <div id="directions"></div>
    <div id="your-destination">Rynek Kosciuszki, Bialystok</div>
  </map-component>
```

Inside `#your-destination` div put your desired destination.
Divs `#map` and `#directions` are optional, chose what you need. `#map` shows Google map, `#direction` shows driving directions to your desired location.
