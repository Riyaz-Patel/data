Description
-----------

Ce fichier fournit des données sur les salaires nets horaires issus des
bases Tous salariés (fichier salariés au lieu de résidence). Les
indicateurs sont repartis selon le sexe, l’âge, la catégorie
socioprofessionnelle (hors agriculture).

Preview
-------

    salary = read.csv2("/Users/riyazpatel/Desktop/cc_bases-tous-salaries_2019_DEP.csv")

    head(salary)

    ##   CODGEO           SNHM19          SNHMC19          SNHMP19          SNHME19
    ## 1     01 14.6570229627526  25.319887312681 15.5317771052947 11.3419515469029
    ## 2     02 13.4905125349157    23.7635445629  15.344498541774 10.9072834458772
    ## 3     03 13.1239077124887  23.340957341506 14.8584668084949   10.62652297448
    ## 4     04 13.5921113834959 23.0909559984362 15.0595235030281 10.7243589610648
    ## 5     05  12.940012872305 21.6206288800456 14.5461599893458 10.7533490313591
    ## 6     06 15.4859395700169  26.757142616657 15.8089382470029  11.474006495603
    ##            SNHMO19          SNHMF19         SNHMFC19         SNHMFP19
    ## 1 11.9281510787151 13.0440694256039  22.075824193883 14.1746895296058
    ## 2 11.9126473112789 12.1958948047631 20.7417549936199 13.9960138246849
    ## 3 11.5827152975374 12.0094641885839  20.410012366146 13.8308104531655
    ## 4 11.5225580522525 12.2591212828577 20.6273204660378 13.5949496004067
    ## 5 11.5131625382955 12.0001757787983 19.7679638273198 13.5377074210606
    ## 6 11.8731874839597 13.8928846396804 23.3042439255981 14.8571075710857
    ##           SNHMFE19         SNHMFO19          SNHMH19         SNHMHC19
    ## 1  11.113294512777 10.5561945158104 15.8023000449807 26.8338568789919
    ## 2 10.6744367352397 10.5130599343192 14.2372947590571 25.0957152116407
    ## 3  10.438576411279 10.8277890236909 13.8988749353358 24.8029785243431
    ## 4 10.5141727039865 9.94909408139973 14.5625427555787 24.3466837456031
    ## 5 10.5863147070872 9.54563474227486 13.6589332263753 22.6708565058161
    ## 6 11.2842313363997 10.2426024630851 16.7611325925993 28.6478192241555
    ##           SNHMHP19         SNHMHE19         SNHMHO19         SNHM1819
    ## 1 16.6252326920412 12.0053897356736 12.2874728408852 10.3249562036716
    ## 2 16.2749398359237 11.4236376786252  12.193226569829 10.1237431990757
    ## 3 15.6115155906297 11.1433716186273 11.7574075028338 10.0121219679732
    ## 4 16.2570350723558 11.1901053950943 11.8198365104117 9.81216206817589
    ## 5 15.5126108259848 11.0983222265855 11.7964943204658 9.81435206962009
    ## 6 16.7868293141032 11.8113153321657 12.1836189432504 10.4998336845397
    ##           SNHM2619         SNHM5019        SNHMF1819        SNHMF2619
    ## 1 14.6244630709919 16.6087885161802   9.861072093152 13.1747509309214
    ## 2  13.331644521705 15.1875903772828 9.71929220050481    12.1655625558
    ## 3  12.914569139897 14.8271691447742 9.67749546319862 11.9169935078815
    ## 4 13.3023151947479 15.6344479740314 9.56128425023282 12.1657287391055
    ## 5 12.6973704642363 14.7798080412152 9.51740333404221 11.8199259419043
    ## 6 15.2404130027592 18.0389273786141 10.0372473442059 13.9444613405235
    ##          SNHMF5019        SNHMH1819        SNHMH2619        SNHMH5019
    ## 1  14.093497823017 10.6537058612481 15.6442359810382 18.4367082129828
    ## 2 13.3363197037339 10.3969551293351 13.9910394115404 16.2414600848757
    ## 3 13.1308964133636 10.2508050144977 13.5934643015481 16.0513159655771
    ## 4 13.4513849015229 10.0021080140727 14.0998272450392 17.3268244091692
    ## 5 13.3705401401024 10.0379276251794 13.3519899132543  15.926695971616
    ## 6 15.3509375064662 10.8978932022784 16.2498112363926 20.2637776034625

Dataset Characteristics
-----------------------

-   100 lignes (1 ligne par departement)
-   25 colonnes
-   41 ko

Variables
---------

<table>
<thead>
<tr class="header">
<th style="text-align: right;">Variables</th>
<th style="text-align: left;">Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="text-align: right;">COD_VAR</td>
<td style="text-align: left;">LIB_VAR</td>
</tr>
<tr class="even">
<td style="text-align: right;">SNHM19</td>
<td style="text-align: left;">Salaire net horaire moyen en 2019</td>
</tr>
<tr class="odd">
<td style="text-align: right;">SNHMC19</td>
<td style="text-align: left;">Salaire net hor. Moy. Cadres sup. en 2019</td>
</tr>
<tr class="even">
<td style="text-align: right;">SNHMP19</td>
<td style="text-align: left;">Salaire net hor. moy. prof inter. en 2019</td>
</tr>
<tr class="odd">
<td style="text-align: right;">SNHME19</td>
<td style="text-align: left;">Salaire net hor. moy. employés en 2019</td>
</tr>
<tr class="even">
<td style="text-align: right;">SNHMO19</td>
<td style="text-align: left;">Salaire net hor. moy. ouvriers en 2019</td>
</tr>
<tr class="odd">
<td style="text-align: right;">SNHMF19</td>
<td style="text-align: left;">Salaire net horaire moyen F en 2019</td>
</tr>
<tr class="even">
<td style="text-align: right;">SNHMFC19</td>
<td style="text-align: left;">Salaire net hor. moy. F cadres sup. en 2019</td>
</tr>
<tr class="odd">
<td style="text-align: right;">SNHMFP19</td>
<td style="text-align: left;">Salaire net hor. moy. F prof inter. en 2019</td>
</tr>
<tr class="even">
<td style="text-align: right;">SNHMFE19</td>
<td style="text-align: left;">Salaire net hor. moy. F employées en 2019</td>
</tr>
<tr class="odd">
<td style="text-align: right;">SNHMFO19</td>
<td style="text-align: left;">Salaire net hor. moy. F ouvriers en 2019</td>
</tr>
<tr class="even">
<td style="text-align: right;">SNHMH19</td>
<td style="text-align: left;">Salaire net horaire moyen H en 2019</td>
</tr>
<tr class="odd">
<td style="text-align: right;">SNHMHC19</td>
<td style="text-align: left;">Salaire net hor. moy. H cadres sup. en 2019</td>
</tr>
<tr class="even">
<td style="text-align: right;">SNHMHP19</td>
<td style="text-align: left;">Salaire net hor. moy. H prof inter. en 2019</td>
</tr>
<tr class="odd">
<td style="text-align: right;">SNHMHE19</td>
<td style="text-align: left;">Salaire net hor. moy. H employés en 2019</td>
</tr>
<tr class="even">
<td style="text-align: right;">SNHMHO19</td>
<td style="text-align: left;">Salaire net hor. moy. H ouvriers en 2019</td>
</tr>
<tr class="odd">
<td style="text-align: right;">SNHM1819</td>
<td style="text-align: left;">Salaire net horaire moyen 18-25 ans en 2019</td>
</tr>
<tr class="even">
<td style="text-align: right;">SNHM2619</td>
<td style="text-align: left;">Salaire net horaire moyen 26-50 ans en 2019</td>
</tr>
<tr class="odd">
<td style="text-align: right;">SNHM5019</td>
<td style="text-align: left;">Salaire net horaire moyen 18-25 ans en 2019</td>
</tr>
<tr class="even">
<td style="text-align: right;">SNHMF1819</td>
<td style="text-align: left;">Salaire net horaire moyen F 18-25 ans en 2019</td>
</tr>
<tr class="odd">
<td style="text-align: right;">SNHMF2619</td>
<td style="text-align: left;">Salaire net horaire moyen F 26-50 ans en 2019</td>
</tr>
<tr class="even">
<td style="text-align: right;">SNHMF5019</td>
<td style="text-align: left;">Salaire net horaire moyen F plus de 50 ans en 2019</td>
</tr>
<tr class="odd">
<td style="text-align: right;">SNHMH1819</td>
<td style="text-align: left;">Salaire net horaire moyen H 18-25 ans en 2019</td>
</tr>
<tr class="even">
<td style="text-align: right;">SNHMH2619</td>
<td style="text-align: left;">Salaire net horaire moyen H 26-50 ans en 2019</td>
</tr>
<tr class="odd">
<td style="text-align: right;">SNHMH5019</td>
<td style="text-align: left;">Salaire net horaire moyen H plus de 50 ans en 2019</td>
</tr>
</tbody>
</table>

Exemples d’utilisation / Intérêt
--------------------------------

-   Lien entre le taux de vaccination par departement et le revenu
-   Analyse des soins, diagnostics, prescription médicament, santé des
    enfants, mortalité, par departement selon le revenu

Licence
-------

Les données issues des Bases Tous Salariés sont soumises au secret
statistique. Aucune statistique n’est diffusée pour les zones de moins
de 2 000 habitants. Pour quelques zones de 2 000 habitants ou plus, qui
ne respectent pas les seuils, il n’est pas non plus possible de diffuser
des résultats. À savoir, chaque case du tableau doit comporter au moins
5 salariés et aucun salarié ne doit représenter plus de 80% de la masse
salariale de la case.

Source
------

<a href="https://www.insee.fr/fr/statistiques/2021266" class="uri">https://www.insee.fr/fr/statistiques/2021266</a>
(Paru le : 26/08/2021)

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

    names(salary) = c("Code_dep", "Salaire_net_h", "Cadres_sup" ,"Profession_intermediaire","employés",
                       "ouvriers", "Femmes",  "F_cadre_sup", "F_prof_int","F_employées",
                       "F_ouvriers", "Hommes","H_cadre_sup", "H_prof_int",  "H_employés", 
                       "H_ouvriers","18_25", "26_50","+50", "F_18_25", "F_26_50",  "F_+50",
                       "H_18_25",  "H_26_50", "H_+50")

    salary = sapply(salary, function(x) {
        if(is.character(x)) as.numeric(as.character(x)) else x
      })

    ## Warning in FUN(X[[i]], ...): NAs introduits lors de la conversion automatique

    salary_clean=as.data.frame(salary)

Statistiques descriptives
-------------------------

    salary_hf = salary_clean%>%
      select (Femmes, Hommes)
    library(ggplot2)
    ggplot(stack(salary_hf), aes(x = ind, y = values, color=ind)) +
      geom_boxplot()

![Rplot01](https://user-images.githubusercontent.com/74362276/138365784-301845da-4093-492f-935c-5c6741bc7c87.png)


![](Salary_2019_files/figure-markdown_strict/unnamed-chunk-3-1.png)

    salary_f = salary_clean%>%
      select(F_cadre_sup, F_prof_int, F_employées, F_ouvriers)

    ggplot(stack(salary_f), aes(x = ind, y = values, color=ind)) +
      geom_boxplot()
![Rplot](https://user-images.githubusercontent.com/74362276/138365836-b7d7b104-fbe4-4fdb-a57d-a7ebdacf2e14.png)


![](Salary_2019_files/figure-markdown_strict/unnamed-chunk-3-2.png)

    salary_h = salary_clean%>%
      select (H_cadre_sup, H_prof_int, H_ouvriers, H_employés)

    ggplot(stack(salary_h), aes(x = ind, y = values, color=ind)) +
      geom_boxplot()

![Rplot02](https://user-images.githubusercontent.com/74362276/138365591-873196d9-2c6e-4d5d-a395-c8cda68eb943.png)



![](Salary_2019_files/figure-markdown_strict/unnamed-chunk-3-3.png)

    salary_hf_cadre = salary_clean%>%
      select(F_cadre_sup, H_cadre_sup)

    ggplot(stack(salary_hf_cadre), aes(x = ind, y = values, color=ind)) +
      geom_boxplot()


![Rplot03](https://user-images.githubusercontent.com/74362276/138365606-0fb86123-cc89-499a-8241-161812c2f79a.png)



![](Salary_2019_files/figure-markdown_strict/unnamed-chunk-3-4.png)

    salary_hf_ouvriers = salary_clean%>%
      select(F_ouvriers, H_ouvriers)

    ggplot(stack(salary_hf_ouvriers), aes(x = ind, y = values, color=ind)) +
      geom_boxplot()
      
 ![Rplot04](https://user-images.githubusercontent.com/74362276/138365663-35ec1ce8-9ba4-48fd-b075-fef13c8ca52a.png)



![](Salary_2019_files/figure-markdown_strict/unnamed-chunk-3-5.png)
