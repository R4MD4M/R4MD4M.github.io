---
title: Infos pratiques
layout: page
published: False
---

## Quand ?

Du 1<sup>er</sup> au 13 août.

## Où ?

16 Rue des Maçons, Lyon.

<link rel="stylesheet" href="http://openlayers.org/en/v3.17.1/css/ol.css" type="text/css">
<script src="http://openlayers.org/en/v3.17.1/build/ol.js"></script>
<script>
      var map = new ol.Map({
        layers: [
          new ol.layer.Tile({
            source: new ol.source.OSM()
          })
        ],
        target: 'map',
        controls: ol.control.defaults({
          attributionOptions: /** @type {olx.control.AttributionOptions} */ ({
            collapsible: false
          })
        }),
        view: new ol.View({
          center: [0, 0],
          zoom: 2
        })
      });

      document.getElementById('zoom-out').onclick = function() {
        var view = map.getView();
        var zoom = view.getZoom();
        view.setZoom(zoom - 1);
      };

      document.getElementById('zoom-in').onclick = function() {
        var view = map.getView();
        var zoom = view.getZoom();
        view.setZoom(zoom + 1);
      };
    </script>

## Combien ?

120€/12 jours ou 10€/jour.

## Que dois-je amener ?

- Couverture et matelas gonflable au cas où les places viendraient à manquer.
- Du matériel d'art : crayons, peinture, poscas, papier, etc...
- Instruments de musique.
- Décoration : guirlandes, etc...
- Tout ce que vous pensez utile ou pertinent (des nerf guns par exemple).

