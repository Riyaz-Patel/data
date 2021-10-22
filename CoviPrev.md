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

    knitr::kable(head(covi))

<table>
<colgroup>
<col style="width: 3%" />
<col style="width: 6%" />
<col style="width: 2%" />
<col style="width: 3%" />
<col style="width: 3%" />
<col style="width: 2%" />
<col style="width: 3%" />
<col style="width: 3%" />
<col style="width: 2%" />
<col style="width: 3%" />
<col style="width: 3%" />
<col style="width: 2%" />
<col style="width: 3%" />
<col style="width: 3%" />
<col style="width: 2%" />
<col style="width: 3%" />
<col style="width: 3%" />
<col style="width: 2%" />
<col style="width: 3%" />
<col style="width: 3%" />
<col style="width: 3%" />
<col style="width: 4%" />
<col style="width: 4%" />
<col style="width: 1%" />
<col style="width: 2%" />
<col style="width: 2%" />
<col style="width: 2%" />
<col style="width: 3%" />
<col style="width: 3%" />
<col style="width: 0%" />
<col style="width: 1%" />
<col style="width: 1%" />
</colgroup>
<thead>
<tr class="header">
<th style="text-align: left;">age</th>
<th style="text-align: left;">semaine</th>
<th style="text-align: right;">anxiete</th>
<th style="text-align: right;">anxiete_inf</th>
<th style="text-align: right;">anxiete_sup</th>
<th style="text-align: right;">depression</th>
<th style="text-align: right;">depression_inf</th>
<th style="text-align: right;">depression_sup</th>
<th style="text-align: right;">pbsommeil</th>
<th style="text-align: right;">pbsommeil_inf</th>
<th style="text-align: right;">pbsommeil_sup</th>
<th style="text-align: right;">hyg4mes</th>
<th style="text-align: right;">hyg4mes_inf</th>
<th style="text-align: right;">hyg4mes_sup</th>
<th style="text-align: right;">dist3mes</th>
<th style="text-align: right;">dist3mes_inf</th>
<th style="text-align: right;">dist3mes_sup</th>
<th style="text-align: right;">nbmoy7mes</th>
<th style="text-align: right;">nbmoy7mes_inf</th>
<th style="text-align: right;">nbmoy7mes_sup</th>
<th style="text-align: right;">nbmoy4mesHyg</th>
<th style="text-align: right;">nbmoy4mesHyg_inf</th>
<th style="text-align: right;">nbmoy4mesHyg_sup</th>
<th style="text-align: right;">dist1m</th>
<th style="text-align: right;">dist1m_inf</th>
<th style="text-align: right;">dist1m_sup</th>
<th style="text-align: right;">portmasque</th>
<th style="text-align: right;">portmasque_inf</th>
<th style="text-align: right;">portmasque_sup</th>
<th style="text-align: left;">X</th>
<th style="text-align: left;">X.1</th>
<th style="text-align: left;">X.2</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="text-align: left;">18-24 ans</td>
<td style="text-align: left;">Vague 1 : 23-25 mars</td>
<td style="text-align: right;">33.1</td>
<td style="text-align: right;">26.8</td>
<td style="text-align: right;">40.0</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: left;">NA</td>
<td style="text-align: left;">NA</td>
<td style="text-align: left;">NA</td>
</tr>
<tr class="even">
<td style="text-align: left;">25-34 ans</td>
<td style="text-align: left;">Vague 1 : 23-25 mars</td>
<td style="text-align: right;">37.5</td>
<td style="text-align: right;">32.2</td>
<td style="text-align: right;">43.1</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: left;">NA</td>
<td style="text-align: left;">NA</td>
<td style="text-align: left;">NA</td>
</tr>
<tr class="odd">
<td style="text-align: left;">35-49 ans</td>
<td style="text-align: left;">Vague 1 : 23-25 mars</td>
<td style="text-align: right;">32.0</td>
<td style="text-align: right;">28.1</td>
<td style="text-align: right;">36.2</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: left;">NA</td>
<td style="text-align: left;">NA</td>
<td style="text-align: left;">NA</td>
</tr>
<tr class="even">
<td style="text-align: left;">50-64 ans</td>
<td style="text-align: left;">Vague 1 : 23-25 mars</td>
<td style="text-align: right;">21.4</td>
<td style="text-align: right;">18.0</td>
<td style="text-align: right;">25.2</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: left;">NA</td>
<td style="text-align: left;">NA</td>
<td style="text-align: left;">NA</td>
</tr>
<tr class="odd">
<td style="text-align: left;">65 ans et plus</td>
<td style="text-align: left;">Vague 1 : 23-25 mars</td>
<td style="text-align: right;">17.0</td>
<td style="text-align: right;">13.9</td>
<td style="text-align: right;">20.7</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: left;">NA</td>
<td style="text-align: left;">NA</td>
<td style="text-align: left;">NA</td>
</tr>
<tr class="even">
<td style="text-align: left;">18-24 ans</td>
<td style="text-align: left;">Vague 2 : 30 mars-1 avr</td>
<td style="text-align: right;">22.5</td>
<td style="text-align: right;">16.8</td>
<td style="text-align: right;">29.5</td>
<td style="text-align: right;">16.5</td>
<td style="text-align: right;">11.7</td>
<td style="text-align: right;">22.9</td>
<td style="text-align: right;">68.5</td>
<td style="text-align: right;">61.1</td>
<td style="text-align: right;">75</td>
<td style="text-align: right;">38</td>
<td style="text-align: right;">31</td>
<td style="text-align: right;">45.6</td>
<td style="text-align: right;">55.9</td>
<td style="text-align: right;">48.4</td>
<td style="text-align: right;">63.2</td>
<td style="text-align: right;">5.13</td>
<td style="text-align: right;">4.84</td>
<td style="text-align: right;">5.42</td>
<td style="text-align: right;">2.8</td>
<td style="text-align: right;">2.62</td>
<td style="text-align: right;">2.99</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">NA</td>
<td style="text-align: right;">13.7</td>
<td style="text-align: right;">9.3</td>
<td style="text-align: right;">19.9</td>
<td style="text-align: left;">NA</td>
<td style="text-align: left;">NA</td>
<td style="text-align: left;">NA</td>
</tr>
</tbody>
</table>

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
           
 ![Rplot11](https://user-images.githubusercontent.com/74362276/138417280-770c124b-cd11-4131-ad9f-4ba41f8e1476.png)


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

![Rplot01](https://user-images.githubusercontent.com/74362276/138417363-c7959a9e-ecf7-47a2-8745-e2e741987275.png)



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
    
    ![Rplot55](https://user-images.githubusercontent.com/74362276/138417345-1a2293f0-a3c1-40d3-837a-bd638f2a6ce6.png)

    
    
   

![](CoviPrev_files/figure-markdown_strict/unnamed-chunk-3-3.png)
