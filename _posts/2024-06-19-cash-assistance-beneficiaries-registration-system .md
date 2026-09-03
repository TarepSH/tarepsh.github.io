---
layout:     post
title:      "CASH Assistance Beneficiaries Registration system - SARC Syria"
date:       2022-03-26 
author:     "TarepSH"
header-img: "img/in-post/cash-app-icon.png"
lang: en
tags:
  - Data
  - Tech
---
A registration system for cash assistance at the Syrian Arab Red Crescent, built in two parts.

**The field app.** A customised version of ODK Collect that reads a person's ID by scanning the barcode with the volunteer's phone camera. It works offline and syncs when a connection is available, which matters in areas with poor coverage.

**The pipeline.** An ETL pipeline in Dataiku and Python that cleans, processes, analyses and stores the data, and makes it available to other programmes through an API.

As of the last update in 2023 the system held 24,779 registered people. About 34.5% of them (8,554) were registered using the barcode scanner: 4,811 with Syrian IDs and 696 family statements covering 5,835 people.

The code is on GitHub: [Syrian-Arab-Red-Crescent-SARC/collect](https://github.com/Syrian-Arab-Red-Crescent-SARC/collect).

![screenshot of odk app](/img/in-post/odk-screenshot.gif)

![screenshot of dataiku ETL](/img/in-post/dataiku-etl-screenshot.png)
