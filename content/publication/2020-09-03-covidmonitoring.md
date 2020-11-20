---
title: "Real-time monitoring of COVID-19 dynamics using automated trend fitting and anomaly detection"
author: Quentin Leclerc
date: '2020-09-03'
publication: "Wellcome Open Research"
publication_types: ["2"]
slug: covidbacktracing
categories: ["COVID-19", "preprint"]
tags: []
subtitle: ''
summary: ''
authors: ["Thibaut Jombart", "Stephane Ghozzi", "Dirk Schumacher", "**Quentin J. Leclerc**", "Mark Jit", "Stefan Flasche", "Felix Greaves", "Tom Ward", "Rosalind M. Eggo", "Emily Nightingale", "CMMID COVID-19 Working Group",  "Graham F. Medley", "Michael Hohle", "John Edmunds"]
lastmod: '2020-05-05T16:15:12+02:00'
featured: no
image:
  caption: ''
  focal_point: ''
  preview_only: no
projects: []
abstract: "
As several countries gradually release social distancing measures, rapid detection of new localised COVID-19 hotspots and subsequent intervention will be key to avoiding large-scale resurgence of transmission. We introduce ASMODEE (Automatic Selection of Models and Outlier Detection for Epidemics), a new tool for detecting sudden changes in COVID-19 incidence. Our approach relies on automatically selecting the best (fitting or predicting) model from a range of user-defined time series models, excluding the most recent data points, to characterise the main trend in an incidence. We then derive prediction intervals and classify data points outside this interval as outliers, which provides an objective criterion for identifying departures from previous trends. We also provide a method for selecting the optimal breakpoints, used to define how many recent data points are to be excluded from the trend fitting procedure. The analysis of simulated COVID-19 outbreaks suggest ASMODEE compares favourably with a state-of-art outbreak-detection algorithm while being simpler and more flexible. We illustrate our method using publicly available data of NHS Pathways reporting potential COVID-19 cases in England at a fine spatial scale, for which we provide a template automated analysis pipeline. ASMODEE is implemented in the free R package trendbreaker."
doi: "10.1101/2020.09.02.20186502"
---
