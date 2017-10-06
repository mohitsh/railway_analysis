## Comparison between SL and 3A classes based on season and train
Supervisor: Prof. Vinod Vasudevan  
Presented By: Mohit Shukla  
Dual-Degree Student  
Department Of Civil Engineering IIT Kanpur 


Content
========================================================


* Literature Review  
* Clustering
* Seasonal Variation 
* Train wise comparison 
* References
         


Literature Review 
========================================================
1. **Heterogeneity in Perceptions of Service Quality among Groups of Railway Passengers**   
        > Study is done in Milan, Italy to analyze the different perception among groups regarding 
        transit service quality. Proposed methodology is CART to identify the most influencial 
        service quality.
        
2. **Evaluating the Impact of Rail-Trails: A Methodology for Assessing Travel Demand and Economic Impacts**   
        > This study explores methods to measure the travel demand and economic impact of developing a rail trail. A methodology is proposed to identify the demand and need for rail-trails and their economic impacts and benefits in Buffalo Valley Rail Trail, Pennsylvania. 

Literature Review 
========================================================
3. **An integrated Bayesian approach for passenger flow assignment in metro networks**   
        > This papere proposed a Bayesian Statistical Inference method to characerize passenger flow assignment model in complex metro networks. They used likelihood of observing passenger travel times provided by smart card data and their prior knowledge about the studied metro network.
        
4. **Analysis of the Mobility of Railway Passenger Transport in Small Urban Areas**   
        > Main purpose behind the railway network is to provide better mobility to passengers. This paper analyses the mobility of passengers by railway in the area of the small town of Varazdin (Croatia).  

Clustering
========================================================
* task of grouping a set of objects in such a way that objects in the same group are more similar to each other than to those in other groups.
*  Hierarchical clustering seeks to build a hierarchy of clusters based on Agglomerative approach.
* Euclidean distance is used for matrix formation
* Ward's minimum variance criterion minimizes the total within-cluster vairance. Include pair of clusters that leads to minimum increase in total within-cluster variance after merging.
        
Seasonal Variation 
========================================================
**Data recorded for JAN-15 01-10** 


```
  CLASS OccCurrY OccLastY
1    1A    86.56    91.68
2    2A   109.43   114.57
3    2S    92.28    86.37
4    3A   111.57   113.72
5    CC    80.89    80.92
6    EC    53.02    60.05
```
Seasonal Variation 
=================================================================
**Class Clusters based on occupational status**


```
  CLASS OccCurrY OccLastY
1    1A    86.56    91.68
3    2S    92.28    86.37
  CLASS OccCurrY OccLastY
2    2A   109.43   114.57
4    3A   111.57   113.72
  CLASS OccCurrY OccLastY
5    CC    80.89    80.92
  CLASS OccCurrY OccLastY
6    EC    53.02    60.05
  CLASS OccCurrY OccLastY
8    SL   132.12   136.12
```

Seasonal Variation
========================================================
**Cluster Visualization**
![plot of chunk unnamed-chunk-3](thesis-figure/unnamed-chunk-3-1.png) 

Seasonal Variation
========================================================
**Data recorded for MAY-15 01-10** 

```
  CLASS OccCurrY OccLastY
1    1A   106.90   106.61
2    2A   130.00   131.89
3    2S   117.12   112.44
4    3A   131.65   134.52
5    CC   105.74   105.40
6    EC   103.96   110.38
```
Seasonal Variation
=================================================================
**Class Clusters based on occupational status**


```
  CLASS OccCurrY OccLastY
1    1A   106.90   106.61
5    CC   105.74   105.40
  CLASS OccCurrY OccLastY
2    2A   130.00   131.89
4    3A   131.65   134.52
  CLASS OccCurrY OccLastY
3    2S   117.12   112.44
  CLASS OccCurrY OccLastY
6    EC   103.96   110.38
  CLASS OccCurrY OccLastY
7    SL    159.1    173.3
```

Seasonal Variation
========================================================
**Cluster Visualization**

![plot of chunk unnamed-chunk-6](thesis-figure/unnamed-chunk-6-1.png) 


Train wise comparison
==========================================================
**Comparison of 3A and SL classes of 4 selected trains of Central Railway**

* Coimbatore Exp  (Mumbai to Bangalore)
* Kushinagar Exp   (Mumbai to Gorakhpur)
* Jhelum Express   (Jammu to Pune)
* Kolkata Mail   (Mumbai to Howrah)  

Train wise comparison
========================================================
**Class clustering**    

```
  passengers utilization            tclass
1        143       43.46 COIMBATORE EXP 2A
2        681       45.27 COIMBATORE EXP 3A
   passengers utilization            tclass
3        2071       55.07 COIMBATORE EXP SL
13        529       58.77 JHELUM EXPRESS 2A
41        299       58.51   KOLKATA MAIL 2A
42       1027       63.94   KOLKATA MAIL 3A
   passengers utilization            tclass
5         350       77.77 KUSHINAGAR EXP 2A
6        1194       82.91 KUSHINAGAR EXP 3A
14       2465       68.47 JHELUM EXPRESS 3A
43       5111       69.32   KOLKATA MAIL SL
   passengers utilization            tclass
7       10648       79.40 KUSHINAGAR EXP SL
15       7421       87.71 JHELUM EXPRESS SL
```

Train wise comparison
========================================================
**Cluster Visualization**
![plot of chunk unnamed-chunk-8](thesis-figure/unnamed-chunk-8-1.png) 

References
==========================================================
* ['International Journal of Sustainable Transportation Volume 9, Issue 7,2015'](http://www.tandfonline.com/doi/abs/10.1080/15568318.2013.825035)
* ['International Journal of Sustainable Transportation Volume 9, Issue 8, 2015'](http://www.tandfonline.com/doi/abs/10.1080/15568318.2013.849318?journalCode=ujst20#.VaP8o_mqqko)
* ['An integrated Bayesian approach for passenger flow assignment in metro networks'](http://www.sciencedirect.com/science/article/pii/S0968090X15000030)
* ['Analysis Of The Mobility Of Railway Passenger Transport In Small Urban Areas'](http://www.witpress.com/elibrary/wit-transactions-on-the-built-environment/146/34126)
* ['R
eserved passenger data warehouse of Indian Railway'](http://www.dw.indianrail.gov.in/)



