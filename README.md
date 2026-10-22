# PowderWeGo — tuiles de carte

Tuiles vectorielles et raster (format PMTiles) du domaine de l'Espace Killy (Tignes, Val d'Isère), lues par la carte du site https://www.powderwego-val-d-isere.com.

## Fichiers
- `espace-killy.pmtiles` : fond de carte
- `espace-killy-ski.pmtiles` : pistes et remontées
- `espace-killy-contours.pmtiles` : courbes de niveau
- `espace-killy-hillshade.pmtiles` : ombrage du relief
- `espace-killy-poi.pmtiles` : points d'intérêt de la carte d'hiver (couche vectorielle `ski_poi`, zooms 12 à 15) ; propriété `kind` = restaurant, snow_park, stade, luge ou freeride ; propriétés `name`, `ele` (altitude en m) et, quand OpenStreetMap les a, `name:fr`, `name:en`, `name:de`
- `espace-killy-pentes.pmtiles` : pentes de plus de 30° (tuiles raster PNG, zooms 11 à 15) ; rouge de plus en plus soutenu pour 30–35°, 35–40° et plus de 40° ; transparent sous 30°
- `glyphs/Noto Sans Regular/{plage}.pbf` : polices du style (une seule pile, « Noto Sans Regular », 256 plages 0-255 à 65280-65535) ; licence dans `glyphs/OFL.txt`

## Sources et attributions
- © contributeurs OpenStreetMap, données sous licence ODbL : https://www.openstreetmap.org/copyright
- © OpenMapTiles : https://openmaptiles.org
- Relief : produit à partir de Copernicus WorldDEM-30 © DLR e.V. 2010-2014 et © Airbus Defence and Space GmbH 2014-2018, fourni dans le cadre de COPERNICUS par l'Union européenne et l'ESA.
- Pentes : calculées à partir du même relief Copernicus WorldDEM-30 (mêmes mentions que ci-dessus).
- Couche POI : © contributeurs OpenStreetMap, licence ODbL (voir ci-dessus).
- Police Noto Sans : licence SIL Open Font License 1.1 ; glyphes PBF issus de https://github.com/openmaptiles/fonts (release v2.0, `noto-sans.zip`).
- Mise en forme : données de PowderWeGo.
