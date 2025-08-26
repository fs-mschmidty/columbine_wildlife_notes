---
title: FS Veg vs Landfire, and FIA excercise.
date: 2025-07-01T00:00:00.000Z
tags: []
format:
  commonmark:
    df-print: kable
    variant: +yaml_metadata_block
execute:
  echo: false
  message: false
  warning: false
  class-output: r
---


The Forest Service developed a polygon based system called FSVeg. It is
an amazing product. But it relies heavily on by-hand interpretation of
aerial imagery. Raster based products that are remotely sensed with
computer models have since been developed such and LandFire. A debate
about what to use has occured on the San Juan National Forest. I’ve been
a proponent of LandFire. But many are skepticle. Almost all current
products rely on FSVeg.

This grey paper will use FIA data to evaluate both FSVeg and Landfire
for species occurrence and cover metrics.

## Is basal area correlated to canopy cover

Here we look at if canopy cover of FSVeg, NLCD and Landfire correlate to
FIA basal area. In short they really don’t. Basal area probably isn’t a
great metric to test against canopy cover.

It is interesting to see that the canopy cover metrics do correlate to
one another a bit and it is good to see that landfire and nlcd correlate
to one another.

<table>
<thead>
<tr>
<th style="text-align: left;"></th>
<th style="text-align: right;">fia_ba</th>
<th style="text-align: right;">fs_veg_cc</th>
<th style="text-align: right;">nlcd_cc</th>
<th style="text-align: right;">lf_cc_avg</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align: left;">fia_ba</td>
<td style="text-align: right;">1.0000000</td>
<td style="text-align: right;">0.1998669</td>
<td style="text-align: right;">0.1739695</td>
<td style="text-align: right;">0.2600609</td>
</tr>
<tr>
<td style="text-align: left;">fs_veg_cc</td>
<td style="text-align: right;">0.1998669</td>
<td style="text-align: right;">1.0000000</td>
<td style="text-align: right;">0.4927437</td>
<td style="text-align: right;">0.4724324</td>
</tr>
<tr>
<td style="text-align: left;">nlcd_cc</td>
<td style="text-align: right;">0.1739695</td>
<td style="text-align: right;">0.4927437</td>
<td style="text-align: right;">1.0000000</td>
<td style="text-align: right;">0.6932432</td>
</tr>
<tr>
<td style="text-align: left;">lf_cc_avg</td>
<td style="text-align: right;">0.2600609</td>
<td style="text-align: right;">0.4724324</td>
<td style="text-align: right;">0.6932432</td>
<td style="text-align: right;">1.0000000</td>
</tr>
</tbody>
</table>

## Dominant Forest Type

Here we check the tree species with the greatest basal area in FIA to
see if the dominant veg type matches LOCAL_TYPE in FS_VEG and EVT_GP_N
in Landfire. Honestly I’m fairly surprised at how well these match given
that the FIA points are just points and both FSVeg and LandFire data are
averages of larger areas.

<table>
<colgroup>
<col style="width: 9%" />
<col style="width: 20%" />
<col style="width: 22%" />
<col style="width: 46%" />
</colgroup>
<thead>
<tr>
<th style="text-align: right;">fia_ba</th>
<th style="text-align: left;">fia_cn</th>
<th style="text-align: left;">fsveg</th>
<th style="text-align: left;">lf_evg_gp</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align: right;">1.9799111</td>
<td style="text-align: left;">Gambel oak</td>
<td style="text-align: left;">Mountain Shrublands</td>
<td style="text-align: left;">Aspen Forest, Woodland, and Parkland</td>
</tr>
<tr>
<td style="text-align: right;">8.0855005</td>
<td style="text-align: left;">blue spruce</td>
<td style="text-align: left;">Riparian</td>
<td style="text-align: left;">Western Riparian Woodland and
Shrubland</td>
</tr>
<tr>
<td style="text-align: right;">15.9852922</td>
<td style="text-align: left;">Engelmann spruce</td>
<td style="text-align: left;">Spruce-fir</td>
<td style="text-align: left;">Aspen Forest, Woodland, and Parkland</td>
</tr>
<tr>
<td style="text-align: right;">13.4109497</td>
<td style="text-align: left;">Engelmann spruce</td>
<td style="text-align: left;">Aspen w Conifer</td>
<td style="text-align: left;">Douglas-fir-Grand Fir-White Fir Forest and
Woodland</td>
</tr>
<tr>
<td style="text-align: right;">17.1202696</td>
<td style="text-align: left;">Douglas-fir</td>
<td style="text-align: left;">Warm-dry Mixed Conifer</td>
<td style="text-align: left;">Douglas-fir-Grand Fir-White Fir Forest and
Woodland</td>
</tr>
<tr>
<td style="text-align: right;">22.1380587</td>
<td style="text-align: left;">ponderosa pine</td>
<td style="text-align: left;">Ponderosa pine</td>
<td style="text-align: left;">Ponderosa Pine Forest, Woodland and
Savanna</td>
</tr>
<tr>
<td style="text-align: right;">10.6879856</td>
<td style="text-align: left;">Douglas-fir</td>
<td style="text-align: left;">Cool-moist Mixed Conifer</td>
<td style="text-align: left;">Douglas-fir-Grand Fir-White Fir Forest and
Woodland</td>
</tr>
<tr>
<td style="text-align: right;">4.6307187</td>
<td style="text-align: left;">corkbark fir</td>
<td style="text-align: left;">Spruce-fir</td>
<td style="text-align: left;">Spruce-Fir Forest and Woodland</td>
</tr>
<tr>
<td style="text-align: right;">9.2389124</td>
<td style="text-align: left;">quaking aspen</td>
<td style="text-align: left;">Aspen w Conifer</td>
<td style="text-align: left;">Aspen-Mixed Conifer Forest and
Woodland</td>
</tr>
<tr>
<td style="text-align: right;">21.1652287</td>
<td style="text-align: left;">ponderosa pine</td>
<td style="text-align: left;">Pinyon-juniper</td>
<td style="text-align: left;">Aspen Forest, Woodland, and Parkland</td>
</tr>
<tr>
<td style="text-align: right;">15.3320666</td>
<td style="text-align: left;">quaking aspen</td>
<td style="text-align: left;">Spruce-fir</td>
<td style="text-align: left;">Spruce-Fir Forest and Woodland</td>
</tr>
<tr>
<td style="text-align: right;">9.2698911</td>
<td style="text-align: left;">Engelmann spruce</td>
<td style="text-align: left;">Mountain Shrublands</td>
<td style="text-align: left;">Aspen Forest, Woodland, and Parkland</td>
</tr>
<tr>
<td style="text-align: right;">0.3798166</td>
<td style="text-align: left;">corkbark fir</td>
<td style="text-align: left;">Spruce-fir</td>
<td style="text-align: left;">Spruce-Fir Forest and Woodland</td>
</tr>
<tr>
<td style="text-align: right;">1.8044559</td>
<td style="text-align: left;">Utah juniper</td>
<td style="text-align: left;">Pinyon-juniper</td>
<td style="text-align: left;">Ponderosa Pine Forest, Woodland and
Savanna</td>
</tr>
<tr>
<td style="text-align: right;">16.5336919</td>
<td style="text-align: left;">Engelmann spruce</td>
<td style="text-align: left;">Spruce-fir</td>
<td style="text-align: left;">Spruce-Fir Forest and Woodland</td>
</tr>
<tr>
<td style="text-align: right;">12.7657960</td>
<td style="text-align: left;">subalpine fir</td>
<td style="text-align: left;">Mountain Shrublands</td>
<td style="text-align: left;">Spruce-Fir Forest and Woodland</td>
</tr>
<tr>
<td style="text-align: right;">18.2253046</td>
<td style="text-align: left;">ponderosa pine</td>
<td style="text-align: left;">Ponderosa pine</td>
<td style="text-align: left;">Ponderosa Pine Forest, Woodland and
Savanna</td>
</tr>
<tr>
<td style="text-align: right;">0.4320113</td>
<td style="text-align: left;">Rocky Mountain juniper</td>
<td style="text-align: left;">Ponderosa pine</td>
<td style="text-align: left;">Ponderosa Pine Forest, Woodland and
Savanna</td>
</tr>
<tr>
<td style="text-align: right;">11.5877320</td>
<td style="text-align: left;">ponderosa pine</td>
<td style="text-align: left;">Ponderosa pine</td>
<td style="text-align: left;">Ponderosa Pine Forest, Woodland and
Savanna</td>
</tr>
<tr>
<td style="text-align: right;">11.3211405</td>
<td style="text-align: left;">ponderosa pine</td>
<td style="text-align: left;">Spruce-fir</td>
<td style="text-align: left;">Douglas-fir-Grand Fir-White Fir Forest and
Woodland</td>
</tr>
</tbody>
</table>

## Conclusion

I think this needs further investigation but for now I have to say I’m
at least a little more supportive of FSVeg. I’m not sure if I want to
use it but I’m at least a bit more supportive of it than I was prior to
these checks.
