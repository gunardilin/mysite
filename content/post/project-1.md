---
date: 2023-04-02
description: "A tool to check if a stock is over-/undervalued"
featured_image: 'images/Project-1/Project-1_00.png'
tags: ["Python", "Plotly", "Dashboard"]
title: "Plotly Dashboard to Evaluate Stock Price"
---

# Description:
This project 
{{< rawhtml >}} 
  <a href="https://gunardi-dashboard.herokuapp.com" target="_blank"><img src="/images/siteimages/link_icon.png" style="width:20px;height:20px;"></a>
{{< /rawhtml >}}
aims to help calculating the fair value of a company stock. Therefore it could indicate if a stock is **over**- or **under**valued. Without this web app, the author would have to scour the internet to copy the financial datas and entering them manualy into calculator to get an estimation.

**Warning**: If the app is in sleep mode, it would take 30–45 seconds to reactivate, so have patience.

# Details:
This web app is built with *Python* and *plotly* library. After opening the web app
{{< rawhtml >}} 
  <a href="https://gunardi-dashboard.herokuapp.com" target="_blank"><img src="/images/siteimages/link_icon.png" style="width:20px;height:20px;"></a>
{{< /rawhtml >}}, it performs web scraping to get the up to date list of S&P500 company from Wikipedia. Furthermore it also retrieves list of foreign companies from multiple sources. The complete list of companies is shown as a dropdown menu:
{{< rawhtml >}} 
<center>
  <img style="border:2px solid black;" src="/images/Project-1/Project-1_01.png" width="210" height="200"/>
</center>
{{< /rawhtml >}}

The user can input one or multiple companies either by entering company name `Apple` or its stock ticker `aapl`. After selecting companies, the historical stock price is visualized and selected financial metrics are shown in table.
{{< rawhtml >}} 
<center>
  <img style="border:2px solid black;" src="/images/Project-1/Project-1_02.png" width="80%" height="80%"/>
</center>
{{< /rawhtml >}}

For the fair value calculation, the dashboard needs the following input parameters:
1. Assumption: Annual Inflation,
2. Tolerance: Margin of Safety,
3. Assumption: Annual EPS Growth Rate,
4. Assumption: PE-Ratio.

The **editable input parameters** are shown in the next screenshot:
{{< rawhtml >}} 
<center>
  <img style="border:2px solid black;" src="/images/Project-1/Project-1_04.png" width="100%" height="100%"/>
</center>
{{< /rawhtml >}}
These parameters influence the calculation if a stock is overvalued (sell) or undervalued (buy).

{{< rawhtml >}} 
<center>
  <img style="border:2px solid black;" src="/images/Project-1/Project-1_03.png" width="100%" height="80%"/>
</center>
{{< /rawhtml >}}