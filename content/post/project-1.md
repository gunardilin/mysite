---
date: 2023-04-02
description: "A tool to check if a stock is over-/undervalued"
featured_image: "/images/Project-1_00.png"
tags: ["Python", "Plotly", "Dashboard"]
title: "Project 1: Plotly Dashboard to Evaluate Stock Price"
---

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