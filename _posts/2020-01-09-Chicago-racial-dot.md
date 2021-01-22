---
layout: post
title: Chicago Racial Dot Map
description:  # Add post description (optional)
img: chicago-sky.jpg # Add image post (optional)
fig-caption: # Add figcaption (optional)
tags: []
---

Dustin Cable's <a href="https://demographics.coopercenter.org/racial-dot-map">racial dot map</a> is an American snapshot; it provides an accessible visualization of geographic distribution, population density, and racial diversity of the American people in every neighborhood in the entire country. I decided to recreate a version for Chicago using the most recent American Community Survey 5-Year Estimates.

We decided to use this idea for a project at my current job with the City of Chicago OIG that was evaluating the City's <a href="https://igchicago.org/wp-content/uploads/2020/02/OIG-JISC-Audit.pdf">Juvenile Intervention Support Center (JISC)</a>. In that report, we wanted to to visually show the demographics of the area that the JISC was serving. Below is the racial dot map utilized.

![Chicago Racial Dot Map]({{site.baseurl}}/assets/img/chicago_racial_dot/chicago_racial_dot.png)

The map was created with QGIS. To create this map, population counts at the census tract level for different racial groups from the 2017 American Community Survey 5-Year Estimates were divided by 100, therefore each dot on the map represents 100 residents. In QGIS dots for the corresponding racial groups were randomly plotted within each census tract. This map does leave out data from other racial groups that is collected in the American Community Survey because of very low counts in Chicago.