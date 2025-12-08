---
title: What Trails are closed outside of Durango
date: 2025-12-08T00:00:00.000Z
tags:
  - Trails
format:
  commonmark:
    df-print: kable
    variant: +yaml_metadata_block
    prefer-html: true
execute:
  echo: false
  message: false
  warning: false
  class-output: r
---


This analysis is a look at trails near Durango, Colorado. I wanted to
know what proportion of trails within 5 miles of Durango are closed
during the winter. I was starting to feel like the majority of trails
have wildlife closures on them in the winter and that as wildlfie
advocates we may want to stop closing areas because the public was
running out of recreational opportunities near durango. This analsyis
will show that is not the case.

<table>
<thead>
<tr>
<th style="text-align: left;">winter_closure</th>
<th style="text-align: right;">length</th>
<th style="text-align: right;">length_miles</th>
<th style="text-align: right;">perc</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align: left;">No</td>
<td style="text-align: right;">93988.42 [m]</td>
<td style="text-align: right;">58.40170 [miles]</td>
<td style="text-align: right;">0.6839389 [1]</td>
</tr>
<tr>
<td style="text-align: left;">Yes</td>
<td style="text-align: right;">43433.82 [m]</td>
<td style="text-align: right;">26.98852 [miles]</td>
<td style="text-align: right;">0.3160611 [1]</td>
</tr>
</tbody>
</table>

## Conclusion

Only about 30% of trails in Durango have winter closures on them. This
is fairly crude estimate given that the trail dataset I used does not
include trails on private property in Durango.

Need to add a map here:
