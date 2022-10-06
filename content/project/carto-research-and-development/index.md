---
title: CARTO - Research and Development
subtitle: Multiple projects conducted between October 2016 to August 2017 at CARTO
date: 2022-10-06T00:11:48.222Z
draft: false
featured: false
tags:
  - GIS
  - Spatial-Statistics
image:
  filename: featured.png
  focal_point: Smart
  preview_only: false
---
### S﻿pace-time Autocorrelation using NYC taxi data (2015)

This project explores spatial and temporal autocorrelation. Open-source yellow taxi trip data for the year 2015 was aggregated to a 50m * 50m grid across NYC. This grid has aggregations of trip statistics for every hour of every day for every month of 2015. The idea is to explore spatial and temporal hotspots of activity across the city. The analysis uses PostGIS, PostgreSQL, Python (pysal package) and CARTO.

[![space-time](../../space-time.gif)](https://team.carto.com/u/mehak-carto/builder/ee115ed2-9aec-47c4-8cb1-25d238ab2ae1/embed?state=%7B%22map%22%3A%7B%22ne%22%3A%5B40.62984841250708%2C-74.14981842041017%5D%2C%22sw%22%3A%5B40.87769896474621%2C-73.51535797119142%5D%2C%22center%22%3A%5B40.75388918270174%2C-73.8325881958008%5D%2C%22zoom%22%3A12%7D%7D)

###### (﻿GIF is linked to original map embed)

(﻿Add more on space time moran's I)

### Exploring immigrant work visa reforms in USA

###### 
[Link to b﻿log post published by CARTO](https://carto.com/blog/examining-potential-impact-of-h-1b-reform-data-visualizations/)

[![h1b_visa](../../h1b_visa.PNG)](https://team.carto.com/u/mehak-carto/builder/c3f5efc4-0995-11e7-b8b8-0e233c30368f/embed?state=%7B%22map%22%3A%7B%22ne%22%3A%5B-58.813741715707806%2C-138.16406250000003%5D%2C%22sw%22%3A%5B68.2042121888185%2C133.24218750000003%5D%2C%22center%22%3A%5B10.574222078332806%2C-2.4609375000000004%5D%2C%22zoom%22%3A3%7D%7D)

###### (﻿Image is linked to original map embed)

This analysis explored possible ramifications for the tech industry, and the American economy more generally if the proposed H-1B program (responsible for hiring foreign workers in US) reforms (H.R.670) were to go into effect. Using open government data and analyzing patterns, this blog shows what these changes could mean.
This post was also published in [technical.ly brooklyn](https://technical.ly/civic-news/carto-tackles-h-1b-visa-issue-maps/).

[![h1b_2](../../h1b_2.PNG)](https://public.carto.com/builder/bc290bb1-b159-467c-b947-e6b7b05bbe75/embed?state=%7B%22map%22%3A%7B%22ne%22%3A%5B19.559790136497412%2C-130.07812500000003%5D%2C%22sw%22%3A%5B52.45600939264076%2C-64.68750000000001%5D%2C%22center%22%3A%5B37.80544394934274%2C-97.3828125%5D%2C%22zoom%22%3A5%7D%7D)

### Random Forest Regressor

As a part of developing new analysis tools within CARTO, this project involved exploring machine learning techniques suitable for spatial predictions and its implementation. We used gradient boosting to build an analysis tool that took feature variables as input to predict a target variable in a dataset. A second pass involved adding spatial lag to the technique to enhance prediction accuracy for spatially related features. The map is an example using this tool to predict WeWork desk prices using density and type of use in the area. The tool is currently internal only.[Pull request linked](https://github.com/CartoDB/crankshaft/pull/171)

[![gradient](../../gradient.PNG)](https://team.carto.com/u/mehak-carto/builder/b407d037-4144-43f8-a8fb-b62221109c15/embed)

T﻿he prediction map (linked to the image above) extends across the country covering many cities.

[![sfgradient](../../sfgradient.PNG)](https://team.carto.com/u/mehak-carto/builder/b407d037-4144-43f8-a8fb-b62221109c15/embed?state=%7B%22map%22%3A%7B%22ne%22%3A%5B37.609335991884876%2C-122.86216735839845%5D%2C%22sw%22%3A%5B38.024295124443995%2C-121.9365692138672%5D%2C%22center%22%3A%5B37.81710713079405%2C-122.39936828613283%5D%2C%22zoom%22%3A11%7D%2C%22widgets%22%3A%7B%22e7fcc176-9638-40aa-adc5-0e402d35b7ab%22%3A%7B%22normalized%22%3Atrue%7D%2C%221d15b03a-d628-46e5-b14f-6025586d5e8c%22%3A%7B%22normalized%22%3Atrue%7D%7D%7D)


