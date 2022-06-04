# tile-boundaries
![tile-boundaries](https://thumbs.gfycat.com/ShortOrnateGyrfalcon-size_restricted.gif)


tile-boundaries.js is a helper script that adds tile boundaries to your Leaflet map.

In order to use this helper script you can add the script tag below to your html 

    <script src="https://clockworkmicro.github.io/tile-boundaries.js"></script>

Then call the below function with a Leaflet map object

    addTileBoundaries(map)


## Customization

`addTileBoundaries(map, opts)` function takes an optional `opts` parameter to customize the tile boundaries.

`border-width`, `font-size`, `border-color`, `text-color`, `text-stroke-color` can be customized like this



    addTileBoundaries(map, {
        "border-width": 8,
        "font-size": 24,
        "border-color": "ff0000",
        "text-color": "ffffff",
        "text-stroke-color": "00ff00"
    })



See `index.html` for an example usage.
