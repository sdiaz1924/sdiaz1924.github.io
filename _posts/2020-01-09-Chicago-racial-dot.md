---
layout: post
title: Chicago Racial Dot Map
description:  # Add post description (optional)
img: chicago-sky.jpg # Add image post (optional)
fig-caption: # Add figcaption (optional)
tags: []
---
The map below depicts where different racial groups are concentrated in the City of Chicago. By looking at the map you can see that White populations tend to be concentrated on the north, northwest, and southwest sides of the City. Black populations are highly concentrated on the south and west sides of the city. Latino/Hispanic populations are most concentrated on the northwest and southwest sides of the city. Lastly, Asian populations are most concentrated just south of downtown Chicago as well as on parts of the north side. Chicago has a history of racial segregation and none of this information should come as a surprise to anyone.

![Chicago Racial Dot Map]({{site.baseurl}}/assets/img/chicago_racial_dot/chicago_racial_dot.png)

The map was created using QGIS. To create this map, raw counts from the 2017 American Community Survey 5-Year Estimates were aggregated at the census tract level. Those aggregates were divided by 100, therefore each dot on the map represents 100 residents. In QGIS dots for the corresponding racial groups were randomly plotted within each census tract. This map does leave out data from other racial groups that is collected in the American Community Survey because of very low counts in Chicago.