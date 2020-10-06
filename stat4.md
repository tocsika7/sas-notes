# Statisztika 4. óra 

## Hipotézis vizsgálat 

+ **Analyze** -> T-test -> One Sample 
+ Ho: célérték
+ **Analyzis**: Confidence level beállítása 
+ **Plot**: Confidence, Normal Q-Q , Summary
+ Ha a Pr 0,5 alatt van elutasítjuk ha nagyobb elfogadjuk. 

## Normális eloszlás vizsgálata 

+ Describe: Distribution Analysis 
+ Summary: Normal
+ Plots: Histogram, Box, Probability
+ Inset: Tests for normality 
+ Inset-Browse: Numeric - BESTXw.d 7 2 
+ Ha a Shapiro-Wilk vagy Kolmogorov-Smirnov p nagyobb mint 0,05 akkor normál eloszlású 

## Kétmintás t-próba 
+ Analyze - T-test 
+ Type: Two Sample 
+ Analyzis Ho = 0 
+ Plot Summary + Utolsó 2 
+ Equality of Variences tábla 
+ Ha a Pr érték nagyobb mint 0,05 elfogadjuk 
+ Ha a variancia megyezik Pooled ha nem Satterthwaite ha itt a P nagyobb mint 0,05 elfogadjuk 
+ Plotokon meg kell nézni hogy normális eloszlásúak az értékek 


## Variancia Analízis 
+ Describe: Summary Statistics
+ Plot Box and Whisker
+ Statistics Basic: Maximum Decimal: 3
+ SST = SSM + SSE
+ Az értékekeket kivonjuk a teljes minta átlagából négyzetre emeljük és összegezzük 
+ SSM = SUM(Yi - Y)^2 
+ SSE = SUM(SUM(Yij - Yi))^2

## Determinációs együttható 
+ ANOVA - Linear Models
+ Model - Main 
+ Mode Options - Type1, Show Parameters
+ Post Hoc Tests - Least Squares - Add 
  + Comparrisson Show p-values All pairwise differences
  + Adjustment method Turkey 
+ Arithmetics 
  + Class effect use true 
  + Homogenity Levene (square residual)
+ Futás után 
  + F hez tartozó p érték ha nagyobb mint 0,05 elfogadjuk 
  + R-négyzet a modellben a változékonyságot magyarázza, ha közelebb áll a nullához kevésbé magyarázza 
