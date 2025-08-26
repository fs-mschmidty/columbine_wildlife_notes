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

The vast majority of LAUs on the San Juan have No Lynx habitat as
modeled by Squires et al. (2024).

## Old habitat mapping

<table>
<colgroup>
<col style="width: 26%" />
<col style="width: 9%" />
<col style="width: 9%" />
<col style="width: 11%" />
<col style="width: 12%" />
<col style="width: 21%" />
<col style="width: 9%" />
</colgroup>
<thead>
<tr>
<th style="text-align: left;">lau</th>
<th style="text-align: right;">Alpine</th>
<th style="text-align: right;">Suitable</th>
<th style="text-align: right;">Unsuitable</th>
<th style="text-align: right;">total_acres</th>
<th style="text-align: right;">perc_not_hab_all_lau</th>
<th style="text-align: right;">perc_hab</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align: left;">Anvil Mountain</td>
<td style="text-align: right;">9386.88</td>
<td style="text-align: right;">29670.57</td>
<td style="text-align: right;">3072.35</td>
<td style="text-align: right;">54341.22</td>
<td style="text-align: right;">0.45</td>
<td style="text-align: right;">0.91</td>
</tr>
<tr>
<td style="text-align: left;">Bear Creek</td>
<td style="text-align: right;">665.36</td>
<td style="text-align: right;">25306.29</td>
<td style="text-align: right;">3229.89</td>
<td style="text-align: right;">38815.20</td>
<td style="text-align: right;">0.35</td>
<td style="text-align: right;">0.89</td>
</tr>
<tr>
<td style="text-align: left;">Black Mesa</td>
<td style="text-align: right;">311.61</td>
<td style="text-align: right;">21506.15</td>
<td style="text-align: right;">1166.77</td>
<td style="text-align: right;">32245.29</td>
<td style="text-align: right;">0.33</td>
<td style="text-align: right;">0.95</td>
</tr>
<tr>
<td style="text-align: left;">Chalk Mountain</td>
<td style="text-align: right;">2769.68</td>
<td style="text-align: right;">11174.26</td>
<td style="text-align: right;">123.89</td>
<td style="text-align: right;">39168.89</td>
<td style="text-align: right;">0.71</td>
<td style="text-align: right;">0.99</td>
</tr>
<tr>
<td style="text-align: left;">East Dolores River</td>
<td style="text-align: right;">348.93</td>
<td style="text-align: right;">21855.14</td>
<td style="text-align: right;">686.93</td>
<td style="text-align: right;">30291.47</td>
<td style="text-align: right;">0.28</td>
<td style="text-align: right;">0.97</td>
</tr>
<tr>
<td style="text-align: left;">East Fork San Juan River</td>
<td style="text-align: right;">4304.83</td>
<td style="text-align: right;">32900.78</td>
<td style="text-align: right;">1795.41</td>
<td style="text-align: right;">63542.95</td>
<td style="text-align: right;">0.48</td>
<td style="text-align: right;">0.95</td>
</tr>
<tr>
<td style="text-align: left;">Engineer</td>
<td style="text-align: right;">16896.05</td>
<td style="text-align: right;">11492.87</td>
<td style="text-align: right;">229.70</td>
<td style="text-align: right;">35814.34</td>
<td style="text-align: right;">0.68</td>
<td style="text-align: right;">0.98</td>
</tr>
<tr>
<td style="text-align: left;">Flat Top</td>
<td style="text-align: right;">2976.05</td>
<td style="text-align: right;">23694.23</td>
<td style="text-align: right;">74.23</td>
<td style="text-align: right;">35447.73</td>
<td style="text-align: right;">0.33</td>
<td style="text-align: right;">1.00</td>
</tr>
<tr>
<td style="text-align: left;">Fourmile-turkey</td>
<td style="text-align: right;">153.89</td>
<td style="text-align: right;">12613.36</td>
<td style="text-align: right;">2342.59</td>
<td style="text-align: right;">43601.04</td>
<td style="text-align: right;">0.71</td>
<td style="text-align: right;">0.84</td>
</tr>
<tr>
<td style="text-align: left;">Junction Creek</td>
<td style="text-align: right;">1907.01</td>
<td style="text-align: right;">11906.77</td>
<td style="text-align: right;">73.65</td>
<td style="text-align: right;">20679.70</td>
<td style="text-align: right;">0.42</td>
<td style="text-align: right;">0.99</td>
</tr>
<tr>
<td style="text-align: left;">Lizard Head</td>
<td style="text-align: right;">744.73</td>
<td style="text-align: right;">25296.68</td>
<td style="text-align: right;">140.76</td>
<td style="text-align: right;">38501.98</td>
<td style="text-align: right;">0.34</td>
<td style="text-align: right;">0.99</td>
</tr>
<tr>
<td style="text-align: left;">Lower Hermosa</td>
<td style="text-align: right;">257.85</td>
<td style="text-align: right;">18721.83</td>
<td style="text-align: right;">3344.34</td>
<td style="text-align: right;">32596.13</td>
<td style="text-align: right;">0.43</td>
<td style="text-align: right;">0.85</td>
</tr>
<tr>
<td style="text-align: left;">Lower Pine River</td>
<td style="text-align: right;">2414.08</td>
<td style="text-align: right;">10220.07</td>
<td style="text-align: right;">600.56</td>
<td style="text-align: right;">21778.57</td>
<td style="text-align: right;">0.53</td>
<td style="text-align: right;">0.94</td>
</tr>
<tr>
<td style="text-align: left;">Mancos</td>
<td style="text-align: right;">397.38</td>
<td style="text-align: right;">17030.68</td>
<td style="text-align: right;">201.26</td>
<td style="text-align: right;">22756.82</td>
<td style="text-align: right;">0.25</td>
<td style="text-align: right;">0.99</td>
</tr>
<tr>
<td style="text-align: left;">Missionary - Florida</td>
<td style="text-align: right;">10557.85</td>
<td style="text-align: right;">24308.03</td>
<td style="text-align: right;">2632.14</td>
<td style="text-align: right;">54212.26</td>
<td style="text-align: right;">0.55</td>
<td style="text-align: right;">0.90</td>
</tr>
<tr>
<td style="text-align: left;">Needles</td>
<td style="text-align: right;">23673.24</td>
<td style="text-align: right;">22622.43</td>
<td style="text-align: right;">649.32</td>
<td style="text-align: right;">63089.56</td>
<td style="text-align: right;">0.64</td>
<td style="text-align: right;">0.97</td>
</tr>
<tr>
<td style="text-align: left;">Pagosa</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">13.31</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">32372.85</td>
<td style="text-align: right;">1.00</td>
<td style="text-align: right;">NA</td>
</tr>
<tr>
<td style="text-align: left;">Piedra River Headwaters</td>
<td style="text-align: right;">7672.97</td>
<td style="text-align: right;">30176.07</td>
<td style="text-align: right;">1797.68</td>
<td style="text-align: right;">56025.05</td>
<td style="text-align: right;">0.46</td>
<td style="text-align: right;">0.94</td>
</tr>
<tr>
<td style="text-align: left;">Rico</td>
<td style="text-align: right;">1570.95</td>
<td style="text-align: right;">28365.84</td>
<td style="text-align: right;">74.14</td>
<td style="text-align: right;">40253.45</td>
<td style="text-align: right;">0.30</td>
<td style="text-align: right;">1.00</td>
</tr>
<tr>
<td style="text-align: left;">Rio Blanco</td>
<td style="text-align: right;">2159.33</td>
<td style="text-align: right;">19564.50</td>
<td style="text-align: right;">463.21</td>
<td style="text-align: right;">50307.66</td>
<td style="text-align: right;">0.61</td>
<td style="text-align: right;">0.98</td>
</tr>
<tr>
<td style="text-align: left;">Upper Hermosa</td>
<td style="text-align: right;">785.48</td>
<td style="text-align: right;">28984.30</td>
<td style="text-align: right;">2108.82</td>
<td style="text-align: right;">37579.71</td>
<td style="text-align: right;">0.23</td>
<td style="text-align: right;">0.93</td>
</tr>
<tr>
<td style="text-align: left;">Upper Pine River</td>
<td style="text-align: right;">13444.28</td>
<td style="text-align: right;">29076.66</td>
<td style="text-align: right;">903.55</td>
<td style="text-align: right;">52797.98</td>
<td style="text-align: right;">0.45</td>
<td style="text-align: right;">0.97</td>
</tr>
<tr>
<td style="text-align: left;">Vallecito Creek</td>
<td style="text-align: right;">20109.49</td>
<td style="text-align: right;">22336.65</td>
<td style="text-align: right;">1792.23</td>
<td style="text-align: right;">64844.28</td>
<td style="text-align: right;">0.66</td>
<td style="text-align: right;">0.93</td>
</tr>
<tr>
<td style="text-align: left;">Weminuche</td>
<td style="text-align: right;">4825.45</td>
<td style="text-align: right;">27323.53</td>
<td style="text-align: right;">2916.70</td>
<td style="text-align: right;">43353.35</td>
<td style="text-align: right;">0.37</td>
<td style="text-align: right;">0.90</td>
</tr>
<tr>
<td style="text-align: left;">West Fork San Juan River</td>
<td style="text-align: right;">7586.69</td>
<td style="text-align: right;">9859.31</td>
<td style="text-align: right;">17633.77</td>
<td style="text-align: right;">42701.59</td>
<td style="text-align: right;">0.77</td>
<td style="text-align: right;">0.36</td>
</tr>
</tbody>
</table>

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
