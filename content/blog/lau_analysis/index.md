---
title: Lynx Lau Analysis
date: 2025-07-03T00:00:00.000Z
format:
  commonmark:
    df-print: kable
    variant: +yaml_metadata_block
execute:
  echo: false
  message: false
  warning: false
  class-output: r
bibliography: references.bib
---


The San Juan National Forest just redrew it’s Lynx Analysis Units to
align with newly proposed critical habitat by the Fish and Wildlife
Service and new habitat mapping by Squires et al. (2024). Here is a
short analysis of the new mapping compared to the old mapping.

## New LAUs with Squires et. al. Habitat Mapping

<table>
<thead>
<tr>
<th style="text-align: left;">lau</th>
<th style="text-align: right;">Unlikely</th>
<th style="text-align: right;">Likely</th>
<th style="text-align: right;">Core</th>
<th style="text-align: right;">perc_unlikely</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align: left;">Anvil Mountain</td>
<td style="text-align: right;">18983.6</td>
<td style="text-align: right;">22577.5</td>
<td style="text-align: right;">12792.1</td>
<td style="text-align: right;">0.35</td>
</tr>
<tr>
<td style="text-align: left;">Bear Creek</td>
<td style="text-align: right;">36013.7</td>
<td style="text-align: right;">2715.0</td>
<td style="text-align: right;">0.0</td>
<td style="text-align: right;">0.93</td>
</tr>
<tr>
<td style="text-align: left;">Black Mesa</td>
<td style="text-align: right;">21819.6</td>
<td style="text-align: right;">10322.7</td>
<td style="text-align: right;">3.6</td>
<td style="text-align: right;">0.68</td>
</tr>
<tr>
<td style="text-align: left;">Chalk Mountain</td>
<td style="text-align: right;">34024.6</td>
<td style="text-align: right;">4992.3</td>
<td style="text-align: right;">0.0</td>
<td style="text-align: right;">0.87</td>
</tr>
<tr>
<td style="text-align: left;">East Dolores River</td>
<td style="text-align: right;">30085.5</td>
<td style="text-align: right;">0.0</td>
<td style="text-align: right;">0.0</td>
<td style="text-align: right;">1.00</td>
</tr>
<tr>
<td style="text-align: left;">East Fork San Juan River</td>
<td style="text-align: right;">48709.7</td>
<td style="text-align: right;">14670.9</td>
<td style="text-align: right;">92.5</td>
<td style="text-align: right;">0.77</td>
</tr>
<tr>
<td style="text-align: left;">Engineer</td>
<td style="text-align: right;">13941.5</td>
<td style="text-align: right;">11059.2</td>
<td style="text-align: right;">10778.1</td>
<td style="text-align: right;">0.39</td>
</tr>
<tr>
<td style="text-align: left;">Flat Top</td>
<td style="text-align: right;">5309.0</td>
<td style="text-align: right;">18588.6</td>
<td style="text-align: right;">11571.6</td>
<td style="text-align: right;">0.15</td>
</tr>
<tr>
<td style="text-align: left;">Fourmile-turkey</td>
<td style="text-align: right;">36689.8</td>
<td style="text-align: right;">6743.0</td>
<td style="text-align: right;">0.0</td>
<td style="text-align: right;">0.84</td>
</tr>
<tr>
<td style="text-align: left;">Junction Creek</td>
<td style="text-align: right;">20253.9</td>
<td style="text-align: right;">234.8</td>
<td style="text-align: right;">0.0</td>
<td style="text-align: right;">0.99</td>
</tr>
<tr>
<td style="text-align: left;">Lizard Head</td>
<td style="text-align: right;">18759.4</td>
<td style="text-align: right;">18627.8</td>
<td style="text-align: right;">1135.1</td>
<td style="text-align: right;">0.49</td>
</tr>
<tr>
<td style="text-align: left;">Lower Hermosa</td>
<td style="text-align: right;">29676.3</td>
<td style="text-align: right;">2053.1</td>
<td style="text-align: right;">0.0</td>
<td style="text-align: right;">0.94</td>
</tr>
<tr>
<td style="text-align: left;">Lower Pine River</td>
<td style="text-align: right;">19762.9</td>
<td style="text-align: right;">1775.6</td>
<td style="text-align: right;">0.0</td>
<td style="text-align: right;">0.92</td>
</tr>
<tr>
<td style="text-align: left;">Mancos</td>
<td style="text-align: right;">22556.1</td>
<td style="text-align: right;">24.9</td>
<td style="text-align: right;">0.0</td>
<td style="text-align: right;">1.00</td>
</tr>
<tr>
<td style="text-align: left;">Missionary - Florida</td>
<td style="text-align: right;">51449.6</td>
<td style="text-align: right;">2373.4</td>
<td style="text-align: right;">0.0</td>
<td style="text-align: right;">0.96</td>
</tr>
<tr>
<td style="text-align: left;">Needles</td>
<td style="text-align: right;">29469.9</td>
<td style="text-align: right;">25342.3</td>
<td style="text-align: right;">8337.1</td>
<td style="text-align: right;">0.47</td>
</tr>
<tr>
<td style="text-align: left;">Pagosa</td>
<td style="text-align: right;">30487.6</td>
<td style="text-align: right;">1305.9</td>
<td style="text-align: right;">0.0</td>
<td style="text-align: right;">0.96</td>
</tr>
<tr>
<td style="text-align: left;">Piedra River Headwaters</td>
<td style="text-align: right;">36988.7</td>
<td style="text-align: right;">18097.6</td>
<td style="text-align: right;">882.5</td>
<td style="text-align: right;">0.66</td>
</tr>
<tr>
<td style="text-align: left;">Rico</td>
<td style="text-align: right;">20592.0</td>
<td style="text-align: right;">19314.5</td>
<td style="text-align: right;">373.6</td>
<td style="text-align: right;">0.51</td>
</tr>
<tr>
<td style="text-align: left;">Rio Blanco</td>
<td style="text-align: right;">43585.8</td>
<td style="text-align: right;">6486.8</td>
<td style="text-align: right;">49.8</td>
<td style="text-align: right;">0.87</td>
</tr>
<tr>
<td style="text-align: left;">Upper Hermosa</td>
<td style="text-align: right;">13631.9</td>
<td style="text-align: right;">20730.7</td>
<td style="text-align: right;">3230.9</td>
<td style="text-align: right;">0.36</td>
</tr>
<tr>
<td style="text-align: left;">Upper Pine River</td>
<td style="text-align: right;">29751.0</td>
<td style="text-align: right;">22897.7</td>
<td style="text-align: right;">53.4</td>
<td style="text-align: right;">0.56</td>
</tr>
<tr>
<td style="text-align: left;">Vallecito Creek</td>
<td style="text-align: right;">40301.4</td>
<td style="text-align: right;">16314.9</td>
<td style="text-align: right;">8130.7</td>
<td style="text-align: right;">0.62</td>
</tr>
<tr>
<td style="text-align: left;">Weminuche</td>
<td style="text-align: right;">39262.4</td>
<td style="text-align: right;">4031.6</td>
<td style="text-align: right;">0.0</td>
<td style="text-align: right;">0.91</td>
</tr>
<tr>
<td style="text-align: left;">West Fork San Juan River</td>
<td style="text-align: right;">28801.0</td>
<td style="text-align: right;">13528.7</td>
<td style="text-align: right;">252.6</td>
<td style="text-align: right;">0.68</td>
</tr>
</tbody>
</table>

There are 25 LAUs proposed on the San Juan Naitonal Forest, the majority
of LAUs (n=13, 52%) on the San Juan are made up of less than 25% core
and likely as modeled by Squires et al. (2024). Eleven of the LAUs have
no core habitat and two LAUs have no lynx habitat at all.

## Old habitat mapping

## References

<div id="refs" class="references csl-bib-body hanging-indent"
entry-spacing="0">

<div id="ref-squiresAnthropogenicallyProtectedNaturally2024"
class="csl-entry">

Squires, John R., Lucretia E. Olson, Jacob S. Ivan, Peter M. McDonald,
and Joseph D. Holbrook. 2024. “Anthropogenically Protected but Naturally
Disturbed: A Specialist Carnivore at Its Southern Range Periphery.”
<https://doi.org/10.1007/s10531-024-02978-8>.

</div>

</div>
