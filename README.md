# Statistics_LinearRegression
Statistic project to determine the drivers of deforestation globally


Deforestation is a consistent and pressing issue in the world today. During the period of 2014-2019, 25% of tree cover loss occurred in areas where the dominant drivers of loss resulted in deforestation (GFW, 2020). As a result, the world has lost 37.32 million hectares of forest cover over that period, an average of 7.46 million hectares of forest cover per year. Forests provide a multitude of benefits to families and businesses, including clean water, food, disease and climate regulation, ecotourism, etc (TEEB,2010). Deforestation, defined as the permanent conversion of forest land to another land use (FAO, 2001), seriously damages both biodiversity and ecosystem services.

Our study sought to answer the question: Is there an association between impartial governance, as measured by impartial administration under democratic principles, and deforestation? Based on the literature and the unpredictability of government performance, we hypothesized that higher levels of impartial governance would be associated with deforestation (negative forest area change). Studies on the relationship between impartial governance and deforestation are scarce, in particular from the perspective of the performance of democracy. Therefore, the main objective in this paper is to explore the impact of impartial governance on deforestation in 148 countries for the period 2014-2019.


**METHODS

We initially tried using panel data from 2010-2020 to examine the association between impartial administration and deforestation. First we ran fixed effects and random effects models with the same control and explanatory variables outlined above, but with Global Forest Watch tree cover change data for response variable. We decided on panel data looking at the same countries (cross-sectional) each year (longitudinal). The control variables consisted of agricultural percent, population growth, mean years of schooling, total forest percent, and change in GDP per capita. The choice of control variables was determined to be consistent with previous studies Umemiya et al. (2010) and also aligned with findings from the literature (Hosonuma et al., 2012; Jha and Bawa, 2006; Crespo Cuaresma et al., 2017).

We did not find a statistically significant relationship between tree cover change and our governance indicators. However, the Global Forest Watch data measures tree cover change, not just forest cover change. Tree cover change also incorporates afforestation from agriculture to tree plantations and other tree cover, but not forest cover changes.

Next we used panel data from 2010-2020 using the same variables as above, but with the percent change in forest area from the prior year (calculated using World Bank Data) the explanatory variable.

We also subset our data frames by “deforestation” (i.e. filtering for observations where the forest area change was less than 0), in accordance with the methodology used by Umemiya et al. (2010). Using the panel data, we ran fixed effects and random effects models for all countries, all deforested countries, South American countries, tropical countries, and deforested tropical countries. However, we found no statistically significant relationship between forest area change and our governance indicator, the year-to-year differences were likely too granular, so the models didn’t pick up much of a change.

We ultimately settled on a cross-sectional approach, using % change in forest from 2014-2019 as our response variable. For our explanatory variables we used the target explanatory variable and the control variables outlined in the Description of the Variables section. We ran a multiple linear regression for all countries, all deforested countries, tropical countries, and deforested tropical countries. We chose to subset the data to deforested countries based on the findings of Umemiya et al. (2010), who found a statistically significant relationship between countries with negative forest change (positive deforestation rate) and governance indicators from 2000-2005.

