---
title: "Real-time monitoring of COVID-19 dynamics using automated trend fitting and anomaly detection"
author: Quentin Leclerc
date: '2021-05-31'
publication: "Philosophical Transactions of the Royal Society B"
publication_types: ["2"]
slug: covidmonitoring
categories: ["COVID-19"]
tags: []
subtitle: ''
summary: ''
authors: ["Thibaut Jombart", "Stephane Ghozzi", "Dirk Schumacher", "Timothy J. Taylor", "**Quentin J. Leclerc**", "Mark Jit", "Stefan Flasche", "Felix Greaves", "Tom Ward", "Rosalind M. Eggo", "Emily Nightingale", "Sophie Meakin", "Oliver J. Brady", "CMMID COVID-19 Working Group",  "Graham F. Medley", "Michael Hohle", "W. John Edmunds"]
lastmod: '2021-06-01T06:15:12+02:00'
featured: no
image:
  caption: ''
  focal_point: ''
  preview_only: no
projects: []
abstract: "
As several countries gradually release social distancing measures, rapid detection of new localized COVID-19 hotspots and subsequent intervention will be key to avoiding large-scale resurgence of transmission. We introduce ASMODEE (automatic selection of models and outlier detection for epidemics), a new tool for detecting sudden changes in COVID-19 incidence. Our approach relies on automatically selecting the best (fitting or predicting) model from a range of user-defined time series models, excluding the most recent data points, to characterize the main trend in an incidence. We then derive prediction intervals and classify data points outside this interval as outliers, which provides an objective criterion for identifying departures from previous trends. We also provide a method for selecting the optimal breakpoints, used to define how many recent data points are to be excluded from the trend fitting procedure. The analysis of simulated COVID-19 outbreaks suggests ASMODEE compares favourably with a state-of-art outbreak-detection algorithm while being simpler and more flexible. As such, our method could be of wider use for infectious disease surveillance. We illustrate ASMODEE using publicly available data of National Health Service (NHS) Pathways reporting potential COVID-19 cases in England at a fine spatial scale, showing that the method would have enabled the early detection of the flare-ups in Leicester and Blackburn with Darwen, two to three weeks before their respective lockdown. ASMODEE is implemented in the free R package trendbreaker."
doi: "10.1098/rstb.2020.0266"
---
