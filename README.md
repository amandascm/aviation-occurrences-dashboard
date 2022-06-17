# Aviation Occurrences Dashboard

A project developed by [Amanda Moraes](https://github.com/amandascm) and [Washington Igor](https://github.com/Washhh) to practice the development process of data visualizations.

## Goals

- Describe the investigations performed on the data to identify curiosities
- Build a dashboard with visualizations based on the result of the initial exploration
- Describe the facts learned from the visualizations about the data

## Data

The database initially proposed for the development of the dashboard was the [Aviation occurrences data recorded by ANAC in Brazil](https://dados.gov.br/dataset/ocorrencias-aeronauticas-da-aviacao-civil-brasileira), but it was combined with a second database to include additional attributes to help defining an analysis scope, the [List of Brazilian municipalities and additional information](http://blog.mds.gov.br/redesuas/lista-de-municipios-brasileiros/).

## Investigation and tasks

- Understand the spatial distribution of aviation occurrences in Brazil
- Investigate patterns and/or trends about occurences locations
- Identify relationships between location attributes and occurrences

### Main questions

- Where do aviation occurrences take place in Brazil?
- What characterizes a place with many occurrences?

## Dashboard

[A set of related data visualizations developed with Tableau Public](https://public.tableau.com/app/profile/amanda7266/viz/Ocorrencias_aereas/proj).

## Results

### Where do aviation occurrences take place in Brazil?
- When analyzing the frequency of occurrences by location, mainly according to the 'Aviation occurrences by city' chart (translated from 'Ocorrências aéreas por cidade'), it is possible to identify the cities that dispute the highest absolute number of records, such as São Paulo, Rio de Janeiro and Belo Horizonte, some of the Brazilian capitals.
- The cities that lead the count of occurrences are part of federative units (UF) that are also at the top of the ranking of occurrences in Brazil, as represented in the 'Occurrences and population by UF' charts (translated from 'Ocorrências e população por UF'). Some of the leading federative units are: São Paulo, Minas Gerais, Rio de Janeiro, Paraná and Rio Grande do Sul (all of them located in the south/southeast of Brazil).

### What characterizes a place with many occurrences?
- When analyzing some of the visualizations (mainly 'Aviation occurrences by city size', 'Aviation occurrences by city' and 'Occurrences by capitals and non-capitals' charts), it can be seen that the cities with the most occurrences correspond to capitals, metropolises or large cities.
- When analyzing the visualizations 'Occurrences and population by UF' and 'Count of occurrences by regions of Brazil', it is noticeable that the federative units that lead the records of aviation occurrences have in common the regions to which they belong and most of them are populous (the 'Occurrences and population by UF' vis makes a parallel between the behavior of the Occurrences by UF and Population by UF charts).
- The Sudeste Brazilian region comprises more than 40% of the absolute value of registered occurrences (see 'Count of occurrences by regions of Brazil'), and this trend can be confirmed by checking the '% of occurrences by UF in Brazil' chart.

## Conclusion

This short project report summarizes essential steps in the data visualization development process. Behind the resulting dashboard there is an iterative sequency of procedures as exploratory data analysis, scope and attributes selection, curiosity and question gathering, choice of appropriate visual channels and visualization composition, which combined help to achieve a successful communication with users.
