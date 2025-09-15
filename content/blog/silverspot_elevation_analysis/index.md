---
title: Silverspot Elevation Analysis
date: 2025-09-09T00:00:00.000Z
tags:
  - Silverspot
format:
  commonmark:
    variant: +yaml_metadata_block
    df-print: tibble
execute:
  echo: false
  message: false
  warning: false
  class-output: r
bibliography: references.bib
knitr:
  opts_chunk:
    dev: ragg_png
---


There has been a bit of debate about where silverspot butterflies could
occur on the Columbine Ranger District. Colonies are known to occur up
to 8,300 feet but one individual was seen at 9,300 feet. The FWS wants
us to survey butterflies up to 9,300 feet, but we are skeptical that
they would occur so high given that there are no colonies known from
higher than 8,300 feet.

Here I look at the elevation ranges of *Speyeria nokomis* to inform
elevation ranges of *Speyeria nokomis nokomis* using citizen science
data from GBIF (“GBIF: The Global Biodiversity Information Facility”
2024) data using the rgbif package(Chamberlain, Oldoni, and Waller
2012).

![](index_files/figure-commonmark/unnamed-chunk-3-1.png)

So it looks like there are observations from 0 to 12,000 feet. However,
the vast majority of the observations are from about 9,200 feet to 4,500
feet. I noticed that a lot of points are old that are from unusual
elevations. Let me filter out very old observations, keeping anything
since the year 2010. These points are more likely to have accurate
location data.

![](index_files/figure-commonmark/unnamed-chunk-4-1.png)

There are fewer occurrences at very high elevations (i.e. \>11,000 feet)
but there is nothing here that demonstrates that they could not be found
up to 9,300 feet.

I want to double check that the high elevation occurrences are not
associated with lower latitudes so let’s map these out.

![](index_files/figure-commonmark/unnamed-chunk-5-1.png)

It does there are high elevation occurances both in Colorado and Mexico
so Latitude doesn’t have that much to do with it.

## Conclusion

After this analysis, I think there is reasonable evidence to suggest
that *Speyeria nokomis nokomis* could occur up to 9,300 feet in
elevation. While I don’t think that it is unlikely that we will find
butterflies above 8,300 feet it appears, from this analysis, that it
could happen.

## References

<div id="refs" class="references csl-bib-body hanging-indent"
entry-spacing="0">

<div id="ref-chamberlainRgbifInterfaceGlobal2012" class="csl-entry">

Chamberlain, Scott, Damiano Oldoni, and John Waller. 2012. “Rgbif:
Interface to the Global Biodiversity Information Facility API.”
<https://doi.org/10.32614/CRAN.package.rgbif>.

</div>

<div id="ref-GBIFGlobalBiodiversity2024" class="csl-entry">

“GBIF: The Global Biodiversity Information Facility.” 2024.
<https://www.gbif.org/what-is-gbif>.

</div>

</div>
