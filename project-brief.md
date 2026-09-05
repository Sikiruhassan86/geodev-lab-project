# My project brief

## The question
How much has the built-up area of Greater Ibadan (the 11 local government areas making up Ibadan) expanded since 2015, and where is that growth concentrated?

## Why it matters
Ibadan's historic core (Ibadan North, North-East, North-West, South-East, South-West) is already close to fully built-up, so new growth is being pushed into surrounding LGAs — Akinyele, Egbeda, Ona Ara, Oluyole, Lagelu, and Ido. A local planning office or the Oyo State Ministry of Physical Planning could use this to see where roads, schools, and services need to catch up with where people are actually settling.

## The data I need
- LGA administrative boundaries for the 11 Ibadan LGAs — FAO GAUL (via Google Earth Engine) — vector, small
- Built-up surface area, 2015 — JRC Global Human Settlement Layer (GHSL), GHS-BUILT-S — raster, ~100m resolution
- Built-up surface area, latest available epoch (2020) — JRC GHSL, GHS-BUILT-S — raster, ~100m resolution

## Where each dataset comes from
- LGA boundaries: FAO GAUL 2015 Level 2, accessed via Google Earth Engine (`FAO/GAUL/2015/level2`)
- Built-up surface (2015 and 2020): JRC Global Human Settlement Layer, accessed via Google Earth Engine (`JRC/GHSL/P2023A/GHS_BUILT_S`)

## What I would build
A map showing where built-up area expanded across Greater Ibadan between 2015 and 2020, highlighting that growth is concentrated in the peripheral LGAs rather than the already-saturated core. Over the year, this becomes a system that can be re-run automatically as new GHSL epochs are published, tracking urban expansion for the region without needing to redo the analysis by hand each time.

## First result
- Total built-up area, 2015: **560.4 km²**
- Total built-up area, 2020: **656.0 km²**
- Growth: **95.6 km² (+17.1%)** over 5 years, concentrated in the peripheral LGAs

Built over twelve months with GeoDev Lab Africa, Cohort One.
