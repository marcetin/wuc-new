---
title: Bitcoin Price Chart
chart: true
charts:
  - priceUSD
  - priceEUR
  - priceCNY
---

<h2>{{ page.title }}</h2>
<h3>USD</h3>
<canvas id="price-chart-usd" class="chart" height="150" style="width:100%;"></canvas>

<h3>Euro</h3>
<canvas id="price-chart-eur" class="chart" height="150" style="width:100%;"></canvas>

<h3>CNY</h3>
<canvas id="price-chart-cny" class="chart" height="150" style="width:100%;"></canvas>

<a href="{{ site.baseurl }}/{{ page.lang }}/charts">Back to charts</a>
