---
date: 2023-04-02
description: "A tool to check if a stock is over-/undervalued"
featured_image: "/images/Project-1/project_home.png"
tags: ["Python", "Plotly", "Dashboard"]
title: "Plotly Dashboard to Evaluate Stock Price"
---

# Description:
This project 
{{< rawhtml >}} 
  <a href="https://gunardi-dashboard.herokuapp.com"><img src="/images/Project-1/link_icon.png" style="width:20px;height:20px;"></a>
{{< /rawhtml >}}
aims to help calculating the fair value of a company stock. Therefore it could indicate if a stock is **over-** or **under**valued. Without this app, the author would have to scour the internet to copy the financial datas and entering them manualy into calculator to get an estimation. 

# Details:

* Created a dashboard using Python and Plotly library.
* Can be accessed on: https://gunardi-dashboard.herokuapp.com
* When the dashboard is called, it scrapped list for S&P 500 company from Wikipedia and foreign companies from multiple sources.
* The input could be one or multiple companies either by entering company name ("Apple") or its stock ticker ("AAPL").
* The historical stock price is visualized and selected financial metrics are shown in table.
* Warning based on a list of criteria is shown.
* Further optional inputs are:
    * [Assumption] Annual Inflation
    * [Tolerance] Margin of Safety
    * [Assumption] Annual EPS Growth Rate
    * [Assumption] PE-Ratio
* The optional inputs influence the calculation if a stock is over-/undervalued, which could be seen in the right corner of last table. 

{{< figure src="/images/Project-1_01.png">}}
{{< figure src="/images/Project-1_02.png">}}