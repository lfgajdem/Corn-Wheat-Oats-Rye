# Corn, wheat, oats, and rye yield in Argentina (kg/ha)

*Domain* Agroindustry\
*Period 1923-2020*

**Research Question**\
What was the average yield in kilograms per hectare (kg/ha) for corn, wheat, oats and rye in Argentina between 1923 and 2020? Has productivity increased over the last 30 years?

**Datasets**\
 \- [Corn](https://github.com/lfgajdem/Corn-Wheat-Oats-Rye/blob/main/assets/maiz-serie-1923-2019.csv
) - [Wheat](https://github.com/lfgajdem/Corn-Wheat-Oats-Rye/blob/main/assets/trigo-serie-1923-2020-anual.csv
) - [Oats](https://github.com/lfgajdem/Corn-Wheat-Oats-Rye/blob/main/assets/avena-serie-1923-2020.csv
) - [Rye](https://github.com/lfgajdem/Corn-Wheat-Oats-Rye/blob/main/assets/centeno-serie-1923-2020.csv
)

**Screenshot**
<figure>
   <img src="./images/crops01.png" 
   alt="The yield (in kilograms per hectare) in 1972 was..." 
   title="yield (kg/ha) year 1972"
   width=70%
   height=auto >
</figure>

**Discussion**\
From 1946 to 1965, wheat yields were higher than corn yields.\
From 1923 to 1937, corn yields declined and then stabilized. A slow increase in corn yields began in 1957 and continued until 1975, when there was a very pronounced increase that set corn yields apart from those of other crops.\
Oats had similar yields until 1981, when a sustained increase began.\
Rye had similar yields until 1998, when a sustained increase began.\
All crops suffered a sharp decline (greatest in corn) between 2007 and 2009 due to a drought.

---
## Alberto Cairo's principles. Design choices.
- `'truthfulness'` A specific function was performed to clean the data frames. The average yield per year was calculated for each crop after discarding the NANs. The graph starts in 1923 and shows an average yield of 0 (with a scale of every 1,000 kg/ha).

