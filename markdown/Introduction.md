[TOC]



### Introduction

The issue of "social segregation" , which refers to the segregation of the  social stratification in urban space, is a traditional focus of geography, sociology and economics. It is generally believed that severe social  segregation is primarily a phenomenon observed in the New World and the Third World and is not significant in East Asia, the former Soviet Union and Western Europe. However, this conclusion is based on the "static observation" of social segregation, which represents class agglomeration and division in the perspective of residential space such as the "brownstone district - slum" dichotomy. Therefore, we can explore whether the spatial pattern in the  "dynamic perspective" shows a different phenomenon of social segregation if the movement of people is considered on the basis of the static population distribution.

### Method and Data

1) The mobile data recorded the residents' live, visit, and work position in a week of 2019.
2) We use the  average housing price  of the housing estates to present every person's class in Beijing.
3) Inside every residential quarter, we recognized every resident's  destination of shopping malls in a week,  and use the per capita consumption of the shopping malls to distinguish every  resident's class .
4) We defined an  index $$ S $$ to describe the segregation level refers to Xu(2019). We use $$ s_{ij} $$ to describe the distance $$class_{i}$$ to $$class_{j}$$,  which is an asymmetric distance. $$ N $$, $$ N_{i} $$ is the total population and $$class_{i}$$ population in the statistical unit (AOI or housing estate) , A is the total number of people in the statistical unit who are less different from i than  $$ A $$.


$$
s_{ij}=1-\frac{A}{N-N_i}\tag{1}
$$

$$
A=\left\{x\ |\ \left|r_x-r_i\right|<\left|r_i-r_j\right|\right\}\tag{2}
$$


$$
S=\frac{\sum_{i=1}^{n-1}\sum_{j=0}^{n-1}{s_{ij}\ast N_i}}{\left(n-1\right)\ast N}\tag{3}
$$

5. In this way, we calculated the index $$ S $$  in three different levels:
   * **Segregation 1.0**, Division of streets, the traditional  issue of "Static Resident Segregation" ,with the street administrative district  as a statistics unit.
   * **Segregation 1.5**,  the  issue of "Dynamic Resident Segregation" , with every housing estate as a statistics unit.
   * **Segregation 2.0**, the  issue of "Dynamic AOI Segregation" , with every AOI as a statistics unit.



### Result

#####  Segregation 1.0

From the perspective of "Static Resident Segregation",  Beijing  has an obvious phenomenon of residential segregasion（P=0.001，z=78.9714，Moran I =0.376 ）, especially in the outer regions.

<center class="half">
    <img src="https://fsk-tuchaung.oss-accelerate.aliyuncs.com/img/1231123122.png" 
         width="300" height="300"/>
    <img src="https://fsk-tuchaung.oss-accelerate.aliyuncs.com/img/123eqewew.png" width="300" height="300"/>
        <br>
    <br>
    <div style="color:orange; border-bottom: 1px solid #d9d9d9;
    display: inline-block;
    color: #999;
    padding: 2px;">
       Figure1: Static Resident Segregation in Beijing.<br>
        (Left:Statistics in street administrative district units. Right:Global Moran's I )
    </div>
</center>



##### Segregation 1.5

Similarly,  the "Dynamic Resident Segregation" decreases outward from the center. It could be interpreted that there are a large number of villas in the outer ring of Beijing .On the contrary,the residential quarters in central city area have a more complex population sources.

<center class="half">
    <img src="https://fsk-tuchaung.oss-accelerate.aliyuncs.com/img/123321.png" 
         width="300" height="500"/>
            <br>
    <br>
    <div style="color:orange; border-bottom: 1px solid #d9d9d9;
    display: inline-block;
    color: #999;
    padding: 2px;">
       Figure2: Dynamic Resident Segregation in every housing estate.






##### Segregation 2.0

The type of place is related to the attributes and segregation of the visitor to some extent. Among the eight types of social places, Educational Institutions, Scopes and Enterprises have a higher degree of segregation, among which the Enterprises tend to be "low-class places" with lower economic attribute classes, while the Scopes have the characteristics of "high-class places". On the other hand, Caters , Hotels, Hospitals and Shopping malls  visitors have a lower degree of segregation, among which the  Caters and Hotels visitors show a higher average economic attribute classes.

<center class="half">
    <img src="https://fsk-tuchaung.oss-accelerate.aliyuncs.com/img/123123.png"width="300" height="300"/>
    <img src="https://fsk-tuchaung.oss-accelerate.aliyuncs.com/img/1232.png" width="300" height="300"/>
        <br>
    <br>
    <div style="color:orange; border-bottom: 1px solid #d9d9d9;
    display: inline-block;
    color: #999;
    padding: 2px;">
       Figure3: Dynamic AOI Segregation.<br>
        (Left:Statistics in AOI units. Right:statistics of AOI types)
    </div>
</center>






### Reference

Abramson, A. J., Tobin, M. S., & VanderGoot, M. R. (1995). The changing geography of metropolitan opportunity: The segregation of the poor in U.S. metropolitan areas, 1970 to 1990. Housing Policy Debate, 6(1), 45–72. https://doi.org/10.1080/10511482.1995.9521181

Deutsch, J., Flückiger, Y., & Silber, J. (1994). Measuring occupational segregation: Summary statistics and the impact of classification errors and aggregation. Journal of Econometrics, 61(1), 133–146. https://doi.org/10.1016/0304-4076(94)90080-9

Farber, S., Neutens, T., Miller, H. J., & Li, X. (2013). The Social Interaction Potential of Metropolitan Regions: A Time-Geographic Measurement Approach Using Joint Accessibility. Annals of the Association of American Geographers, 103(3), 483–504. https://doi.org/10.1080/00045608.2012.689238

Kang, C., Shi, L., Wang, F., & Liu, Y. (2020). How urban places are visited by social groups? Evidence from matrix factorization on mobile phone data. Transactions in GIS, 24(6), 1504–1525. https://doi.org/10.1111/tgis.12654

Lee, J. Y., & Kwan, M.-P. (2011). Visualisation of Socio-Spatial Isolation Based on Human Activity Patterns and Social Networks in Space-Time. Tijdschrift Voor Economische En Sociale Geografie, 102(4), 468–485. https://doi.org/10.1111/j.1467-9663.2010.00649.x

Li, F., & Wang, D. (2017). Measuring urban segregation based on individuals’ daily activity patterns: A multidimensional approach. Environment and Planning A: Economy and Space, 49(2), 467–486. https://doi.org/10.1177/0308518X16673213

Prestby, T., App, J., Kang, Y., & Gao, S. (2020). Understanding neighborhood isolation through spatial interaction network analysis using location big data. Environment and Planning A: Economy and Space, 52(6), 1027–1031. https://doi.org/10.1177/0308518X19891911

Reardon, S. F., & O’Sullivan, D. (2004). 3. Measures of Spatial Segregation. Sociological Methodology, 34(1), 121–162. https://doi.org/10.1111/j.0081-1750.2004.00150.x

Reardon, S. F., Yun, J. T., & Eitle, T. M. (2000). The changing structure of school segregation: Measurement and evidence of multiracial metropolitan-area school segregation, 1989–1995. Demography, 37(3), 351–364. https://doi.org/10.2307/2648047

Silm, S., & Ahas, R. (2014). The temporal variation of ethnic segregation in a city: Evidence from a mobile phone use dataset. Social Science Research, 47, 30–43. https://doi.org/10.1016/j.ssresearch.2014.03.011

Wang, D., Li, F., & Chai, Y. (2012). Activity Spaces and Sociospatial Segregation in Beijing. Urban Geography, 33(2), 256–277. https://doi.org/10.2747/0272-3638.33.2.256

Wong, D. W. S., & Shaw, S.-L. (2011). Measuring segregation: An activity space approach. Journal of Geographical Systems, 13(2), 127–145. https://doi.org/10.1007/s10109-010-0112-x

Xu, Y., Belyi, A., Santi, P., & Ratti, C. (2019). Quantifying segregation in an integrated urban physical-social space. Journal of The Royal Society Interface, 16(160), 20190536. https://doi.org/10.1098/rsif.2019.0536

Zhang, Chai, & Wang. (2019). Reside nearby, behave apart? Activity-space-based segregation among residents of various types of housing in Beijing, China. Cities, 88, 166–180. https://doi.org/10.1016/j.cities.2018.10.009