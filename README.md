# French Aid To Navigation (ATONs/navaid)

https://tiles.atons.balisenav.com/styles/atons/#5/46.7/2.7

- Tileserver GL/Raster/WMTS/TileJSON
- GeoJSON dataset
- MBtiles dataset
- Sprites
- OpenLayers example

## Quickstart

*Requis: Docker, Port 8080*

```bash
$ ./start_tileserver.sh
```

- http://localhost:8080

## TODO

- [ ] Add FOGSIG to MBTiles + GL Style
- [ ] Add LIGHTS/sectors and enlu*.svg support to : NodeJS app + MBTiles + GL Style + OpenLayers
- [ ] Add GL-Style support to OpenLayers example
- [ ] Publish NodeJS app (SVG mapping, MBTiles generation, ...)
- [ ] Documentation

## Sources

- Data source : https://services.data.shom.fr/geonetwork/srv/fre/catalog.search#/metadata/BDML_BALISAGE.xml
- Data licence : Etalab Open Licence 2.0 (© Shom)
---
- Etalab / Entrepreneur d'intérêt général / Balisenav  : https://entrepreneur-interet-general.etalab.gouv.fr/defis/2018/balisenav.html
