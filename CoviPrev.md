Description
-----------

Depuis le 23 mars 2020, Santé publique France a lancé avec la société
d’étude et de conseil BVA, l’enquête CoviPrev.

Celle-ci a pour objectif de suivre l’évolution des comportements et de
la santé mentale ainsi que leurs principaux déterminants face à
l’épidémie de Covid-19 et depuis les mesures gouvernementales de
confinement du 16 mars 2020.

Pour tous les indicateurs, un intervalle de confiance à 95% est indiqué.
Questionnaires auto-administrés Echantillons de 2 000 personnes de 18
ans et plus résidant en France

Preview
-------

    covi = read.csv2("/Users/riyazpatel/Desktop/coviprev-age.csv")

    head(covi)

    ##              age                 semaine anxiete anxiete_inf anxiete_sup
    ## 1      18-24 ans    Vague 1 : 23-25 mars    33.1        26.8        40.0
    ## 2      25-34 ans    Vague 1 : 23-25 mars    37.5        32.2        43.1
    ## 3      35-49 ans    Vague 1 : 23-25 mars    32.0        28.1        36.2
    ## 4      50-64 ans    Vague 1 : 23-25 mars    21.4        18.0        25.2
    ## 5 65 ans et plus    Vague 1 : 23-25 mars    17.0        13.9        20.7
    ## 6      18-24 ans Vague 2 : 30 mars-1 avr    22.5        16.8        29.5
    ##   depression depression_inf depression_sup pbsommeil pbsommeil_inf
    ## 1         NA             NA             NA        NA            NA
    ## 2         NA             NA             NA        NA            NA
    ## 3         NA             NA             NA        NA            NA
    ## 4         NA             NA             NA        NA            NA
    ## 5         NA             NA             NA        NA            NA
    ## 6       16.5           11.7           22.9      68.5          61.1
    ##   pbsommeil_sup hyg4mes hyg4mes_inf hyg4mes_sup dist3mes dist3mes_inf
    ## 1            NA      NA          NA          NA       NA           NA
    ## 2            NA      NA          NA          NA       NA           NA
    ## 3            NA      NA          NA          NA       NA           NA
    ## 4            NA      NA          NA          NA       NA           NA
    ## 5            NA      NA          NA          NA       NA           NA
    ## 6            75      38          31        45.6     55.9         48.4
    ##   dist3mes_sup nbmoy7mes nbmoy7mes_inf nbmoy7mes_sup nbmoy4mesHyg
    ## 1           NA        NA            NA            NA           NA
    ## 2           NA        NA            NA            NA           NA
    ## 3           NA        NA            NA            NA           NA
    ## 4           NA        NA            NA            NA           NA
    ## 5           NA        NA            NA            NA           NA
    ## 6         63.2      5.13          4.84          5.42          2.8
    ##   nbmoy4mesHyg_inf nbmoy4mesHyg_sup dist1m dist1m_inf dist1m_sup portmasque
    ## 1               NA               NA     NA         NA         NA         NA
    ## 2               NA               NA     NA         NA         NA         NA
    ## 3               NA               NA     NA         NA         NA         NA
    ## 4               NA               NA     NA         NA         NA         NA
    ## 5               NA               NA     NA         NA         NA         NA
    ## 6             2.62             2.99     NA         NA         NA       13.7
    ##   portmasque_inf portmasque_sup  X X.1 X.2
    ## 1             NA             NA NA  NA  NA
    ## 2             NA             NA NA  NA  NA
    ## 3             NA             NA NA  NA  NA
    ## 4             NA             NA NA  NA  NA
    ## 5             NA             NA NA  NA  NA
    ## 6            9.3           19.9 NA  NA  NA

Dataset Characteristics
-----------------------

-   80 lignes
-   30 colonnes
-   12 ko

Variables
---------

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th style="text-align: right;">Variables</th>
<th style="text-align: left;">Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="text-align: right;">age</td>
<td style="text-align: left;">age</td>
</tr>
<tr class="even">
<td style="text-align: right;">semaine</td>
<td style="text-align: left;">Salaire net horaire moyen en 2019</td>
</tr>
<tr class="odd">
<td style="text-align: right;">anxiete</td>
<td style="text-align: left;">prévalences de l’anxiété</td>
</tr>
<tr class="even">
<td style="text-align: right;">anxiete_inf</td>
<td style="text-align: left;">prévalences de l’anxiété moyenne inf.</td>
</tr>
<tr class="odd">
<td style="text-align: right;">anxiete_sup</td>
<td style="text-align: left;">prévalences de l’anxiété moyenne sup.</td>
</tr>
<tr class="even">
<td style="text-align: right;">depression</td>
<td style="text-align: left;">prévalences de la dépression</td>
</tr>
<tr class="odd">
<td style="text-align: right;">pbsommeil</td>
<td style="text-align: left;">prévalence des problèmes de sommeil</td>
</tr>
<tr class="even">
<td style="text-align: right;">hyg4mes</td>
<td style="text-align: left;">prévalence de l’adoption systématique des 4 mesures d’hygiène</td>
</tr>
<tr class="odd">
<td style="text-align: right;">dist3mes</td>
<td style="text-align: left;">prévalences de l’adoption systématique des 3 mesures de distanciation physique</td>
</tr>
<tr class="even">
<td style="text-align: right;">nbmoy7mes</td>
<td style="text-align: left;">nombre moyen de mesures de prévention adoptées systématiquement</td>
</tr>
<tr class="odd">
<td style="text-align: right;">nbmoy4mesHyg</td>
<td style="text-align: left;">nombre moyen de mesures d’hygiène adoptées systématiquement</td>
</tr>
<tr class="even">
<td style="text-align: right;">dist1m</td>
<td style="text-align: left;">prévalence de l’adoption systématique de la distance d’un mètre</td>
</tr>
<tr class="odd">
<td style="text-align: right;">portmasque</td>
<td style="text-align: left;">prévalences de l’adoption systématique du port du masque en public</td>
</tr>
</tbody>
</table>

Exemples d’utilisation / Intérêt
--------------------------------

-   suivre l’adoption des mesures de protection et de la santé de la
    population pendant la période de confinement et de déconfinement
-   recueillir les informations nécessaires à l’orientation et à
    l’ajustement des mesures de prévention
-   surveiller les inégalités de santé (identifier les segments de
    population les plus vulnérables)

Source
------

<a href="https://www.santepubliquefrance.fr/etudes-et-enquetes/coviprev-une-enquete-pour-suivre-l-evolution-des-comportements-et-de-la-sante-mentale-pendant-l-epidemie-de-covid-19#block-242829" class="uri">https://www.santepubliquefrance.fr/etudes-et-enquetes/coviprev-une-enquete-pour-suivre-l-evolution-des-comportements-et-de-la-sante-mentale-pendant-l-epidemie-de-covid-19#block-242829</a>
<a href="https://www.data.gouv.fr/fr/datasets/donnees-denquete-relatives-a-levolution-des-comportements-et-de-la-sante-mentale-pendant-lepidemie-de-covid-19-coviprev/" class="uri">https://www.data.gouv.fr/fr/datasets/donnees-denquete-relatives-a-levolution-des-comportements-et-de-la-sante-mentale-pendant-lepidemie-de-covid-19-coviprev/</a>

Datamanagement
--------------

    #data management

    library(dplyr)

    ## 
    ## Attaching package: 'dplyr'

    ## The following objects are masked from 'package:stats':
    ## 
    ##     filter, lag

    ## The following objects are masked from 'package:base':
    ## 
    ##     intersect, setdiff, setequal, union

    library(tidyr)
    library(ggplot2)
    covi_clean = covi %>%
      separate(col = "semaine",
               into = paste0("Vague", 1:2), sep = ":",
               extra = "merge")

    ## Warning: Expected 2 pieces. Missing pieces filled with `NA` in 8 rows [81, 82,
    ## 83, 84, 85, 86, 87, 88].

    covi_clean2 = covi_clean %>%
      separate(col = "Vague1",
               into = paste0("Date", 1:2), sep = " ",
               extra = "merge")

    ## Warning: Expected 2 pieces. Missing pieces filled with `NA` in 8 rows [81, 82,
    ## 83, 84, 85, 86, 87, 88].

    covi_clean2 = covi_clean2 [,-2]
    colnames(covi_clean2)[2] <- 'date'  

    covi_clean2$date = as.numeric(covi_clean2$date)
    #*4
    covi_clean2 <- covi_clean2[-81,]
    covi_clean2 <- covi_clean2[-81,]
    covi_clean2 <- covi_clean2[-81,]
    covi_clean2 <- covi_clean2[-81,]
    covi_clean2 <- covi_clean2[-81,]
    covi_clean2 <- covi_clean2[-81,]
    covi_clean2 <- covi_clean2[-81,]
    covi_clean2 <- covi_clean2[-81,]

Statistiques descriptives
-------------------------

    ggplot(covi_clean2, aes(x = date, y= anxiete, color = age)) +
             geom_line()+
      geom_rect(aes(xmin = 0, xmax = 14, ymin = -Inf, ymax = Inf),
                fill = "blue", alpha = 0.005) +
      geom_rect(aes(xmin = 14, xmax = 16, ymin = -Inf, ymax = Inf),
                fill = "pink", alpha = 0.008)+
      labs(title = "Evolution de l'anxiété selon l'âge",
           subtitle = "Premiere vague : 23 Mars - 26 Aout
           Deuxième vague : à partir du 21 Septembre")

![Rplot11](https://user-images.githubusercontent.com/74362276/138376205-b75251a0-47bd-4767-b840-41ca9d5cc574.png)



![](CoviPrev_files/figure-markdown_strict/unnamed-chunk-3-1.png)

    ggplot(covi_clean2, aes(x = date, y= portmasque, color = age)) +
      geom_line()+
      geom_rect(aes(xmin = 0, xmax = 14, ymin = -Inf, ymax = Inf),
                fill = "blue", alpha = 0.005) +
      geom_rect(aes(xmin = 14, xmax = 16, ymin = -Inf, ymax = Inf),
                fill = "pink", alpha = 0.008)+
      labs(title = "Evolution de l'adoption du port du masque en public  selon l'âge",
           subtitle = "Premiere vague : 23 Mars - 26 Aout
           Deuxième vague : à partir du 21 Septembre")

    ## Warning: Removed 5 row(s) containing missing values (geom_path).

![Rplot01](https://user-images.githubusercontent.com/74362276/138376229-7b3dc338-6847-4c9f-8945-8746617894f3.png)



![](CoviPrev_files/figure-markdown_strict/unnamed-chunk-3-2.png)

    ggplot(covi_clean2, aes(x = date, y= depression, color = age)) +
      geom_line()+
      geom_rect(aes(xmin = 0, xmax = 14, ymin = -Inf, ymax = Inf),
                fill = "blue", alpha = 0.005) +
      geom_rect(aes(xmin = 14, xmax = 16, ymin = -Inf, ymax = Inf),
                fill = "pink", alpha = 0.008)+
      labs(title = "Evolution de la drepression selon l'âge",
           subtitle = "Premiere vague : 23 Mars - 26 Aout
           Deuxième vague : à partir du 21 Septembre")

    ## Warning: Removed 5 row(s) containing missing values (geom_path).
    
![Rplot55](https://user-images.githubusercontent.com/74362276/138376235-fc436193-919a-4343-9b39-cd92ac067f31.png)

    

![](CoviPrev_files/figure-markdown_strict/unnamed-chunk-3-3.png)


![Figure_mesures_prevention_CoviPrev_Vague28](https://user-images.githubusercontent.com/74362276/138376270-347fb746-a2e6-47e7-9088-82f504ed2aaa.jpeg)

![Tab_Le point sur_CoviPrev_V28](https://user-images.githubusercontent.com/74362276/138376307-19cf937d-6827-4c2c-835e-c4d5f6758573.jpeg)



