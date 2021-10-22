## Description

Ce fichier fournit des données sur les salaires nets horaires issus des
bases Tous salariés (fichier salariés au lieu de résidence). Les
indicateurs sont repartis selon le sexe, l’âge, la catégorie
socioprofessionnelle (hors agriculture).

## Preview

    salary = read.csv2("/Users/riyazpatel/Desktop/cc_bases-tous-salaries_2019_DEP.csv")
    knitr::kable(head(salary))

<table style="width:100%;">
<colgroup>
<col style="width: 1%" />
<col style="width: 4%" />
<col style="width: 4%" />
<col style="width: 4%" />
<col style="width: 4%" />
<col style="width: 4%" />
<col style="width: 4%" />
<col style="width: 4%" />
<col style="width: 4%" />
<col style="width: 4%" />
<col style="width: 4%" />
<col style="width: 4%" />
<col style="width: 4%" />
<col style="width: 4%" />
<col style="width: 4%" />
<col style="width: 4%" />
<col style="width: 4%" />
<col style="width: 4%" />
<col style="width: 4%" />
<col style="width: 4%" />
<col style="width: 4%" />
<col style="width: 4%" />
<col style="width: 4%" />
<col style="width: 4%" />
<col style="width: 4%" />
</colgroup>
<thead>
<tr class="header">
<th style="text-align: left;">CODGEO</th>
<th style="text-align: left;">SNHM19</th>
<th style="text-align: left;">SNHMC19</th>
<th style="text-align: left;">SNHMP19</th>
<th style="text-align: left;">SNHME19</th>
<th style="text-align: left;">SNHMO19</th>
<th style="text-align: left;">SNHMF19</th>
<th style="text-align: left;">SNHMFC19</th>
<th style="text-align: left;">SNHMFP19</th>
<th style="text-align: left;">SNHMFE19</th>
<th style="text-align: left;">SNHMFO19</th>
<th style="text-align: left;">SNHMH19</th>
<th style="text-align: left;">SNHMHC19</th>
<th style="text-align: left;">SNHMHP19</th>
<th style="text-align: left;">SNHMHE19</th>
<th style="text-align: left;">SNHMHO19</th>
<th style="text-align: left;">SNHM1819</th>
<th style="text-align: left;">SNHM2619</th>
<th style="text-align: left;">SNHM5019</th>
<th style="text-align: left;">SNHMF1819</th>
<th style="text-align: left;">SNHMF2619</th>
<th style="text-align: left;">SNHMF5019</th>
<th style="text-align: left;">SNHMH1819</th>
<th style="text-align: left;">SNHMH2619</th>
<th style="text-align: left;">SNHMH5019</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="text-align: left;">01</td>
<td style="text-align: left;">14.6570229627526</td>
<td style="text-align: left;">25.319887312681</td>
<td style="text-align: left;">15.5317771052947</td>
<td style="text-align: left;">11.3419515469029</td>
<td style="text-align: left;">11.9281510787151</td>
<td style="text-align: left;">13.0440694256039</td>
<td style="text-align: left;">22.075824193883</td>
<td style="text-align: left;">14.1746895296058</td>
<td style="text-align: left;">11.113294512777</td>
<td style="text-align: left;">10.5561945158104</td>
<td style="text-align: left;">15.8023000449807</td>
<td style="text-align: left;">26.8338568789919</td>
<td style="text-align: left;">16.6252326920412</td>
<td style="text-align: left;">12.0053897356736</td>
<td style="text-align: left;">12.2874728408852</td>
<td style="text-align: left;">10.3249562036716</td>
<td style="text-align: left;">14.6244630709919</td>
<td style="text-align: left;">16.6087885161802</td>
<td style="text-align: left;">9.861072093152</td>
<td style="text-align: left;">13.1747509309214</td>
<td style="text-align: left;">14.093497823017</td>
<td style="text-align: left;">10.6537058612481</td>
<td style="text-align: left;">15.6442359810382</td>
<td style="text-align: left;">18.4367082129828</td>
</tr>
<tr class="even">
<td style="text-align: left;">02</td>
<td style="text-align: left;">13.4905125349157</td>
<td style="text-align: left;">23.7635445629</td>
<td style="text-align: left;">15.344498541774</td>
<td style="text-align: left;">10.9072834458772</td>
<td style="text-align: left;">11.9126473112789</td>
<td style="text-align: left;">12.1958948047631</td>
<td style="text-align: left;">20.7417549936199</td>
<td style="text-align: left;">13.9960138246849</td>
<td style="text-align: left;">10.6744367352397</td>
<td style="text-align: left;">10.5130599343192</td>
<td style="text-align: left;">14.2372947590571</td>
<td style="text-align: left;">25.0957152116407</td>
<td style="text-align: left;">16.2749398359237</td>
<td style="text-align: left;">11.4236376786252</td>
<td style="text-align: left;">12.193226569829</td>
<td style="text-align: left;">10.1237431990757</td>
<td style="text-align: left;">13.331644521705</td>
<td style="text-align: left;">15.1875903772828</td>
<td style="text-align: left;">9.71929220050481</td>
<td style="text-align: left;">12.1655625558</td>
<td style="text-align: left;">13.3363197037339</td>
<td style="text-align: left;">10.3969551293351</td>
<td style="text-align: left;">13.9910394115404</td>
<td style="text-align: left;">16.2414600848757</td>
</tr>
<tr class="odd">
<td style="text-align: left;">03</td>
<td style="text-align: left;">13.1239077124887</td>
<td style="text-align: left;">23.340957341506</td>
<td style="text-align: left;">14.8584668084949</td>
<td style="text-align: left;">10.62652297448</td>
<td style="text-align: left;">11.5827152975374</td>
<td style="text-align: left;">12.0094641885839</td>
<td style="text-align: left;">20.410012366146</td>
<td style="text-align: left;">13.8308104531655</td>
<td style="text-align: left;">10.438576411279</td>
<td style="text-align: left;">10.8277890236909</td>
<td style="text-align: left;">13.8988749353358</td>
<td style="text-align: left;">24.8029785243431</td>
<td style="text-align: left;">15.6115155906297</td>
<td style="text-align: left;">11.1433716186273</td>
<td style="text-align: left;">11.7574075028338</td>
<td style="text-align: left;">10.0121219679732</td>
<td style="text-align: left;">12.914569139897</td>
<td style="text-align: left;">14.8271691447742</td>
<td style="text-align: left;">9.67749546319862</td>
<td style="text-align: left;">11.9169935078815</td>
<td style="text-align: left;">13.1308964133636</td>
<td style="text-align: left;">10.2508050144977</td>
<td style="text-align: left;">13.5934643015481</td>
<td style="text-align: left;">16.0513159655771</td>
</tr>
<tr class="even">
<td style="text-align: left;">04</td>
<td style="text-align: left;">13.5921113834959</td>
<td style="text-align: left;">23.0909559984362</td>
<td style="text-align: left;">15.0595235030281</td>
<td style="text-align: left;">10.7243589610648</td>
<td style="text-align: left;">11.5225580522525</td>
<td style="text-align: left;">12.2591212828577</td>
<td style="text-align: left;">20.6273204660378</td>
<td style="text-align: left;">13.5949496004067</td>
<td style="text-align: left;">10.5141727039865</td>
<td style="text-align: left;">9.94909408139973</td>
<td style="text-align: left;">14.5625427555787</td>
<td style="text-align: left;">24.3466837456031</td>
<td style="text-align: left;">16.2570350723558</td>
<td style="text-align: left;">11.1901053950943</td>
<td style="text-align: left;">11.8198365104117</td>
<td style="text-align: left;">9.81216206817589</td>
<td style="text-align: left;">13.3023151947479</td>
<td style="text-align: left;">15.6344479740314</td>
<td style="text-align: left;">9.56128425023282</td>
<td style="text-align: left;">12.1657287391055</td>
<td style="text-align: left;">13.4513849015229</td>
<td style="text-align: left;">10.0021080140727</td>
<td style="text-align: left;">14.0998272450392</td>
<td style="text-align: left;">17.3268244091692</td>
</tr>
<tr class="odd">
<td style="text-align: left;">05</td>
<td style="text-align: left;">12.940012872305</td>
<td style="text-align: left;">21.6206288800456</td>
<td style="text-align: left;">14.5461599893458</td>
<td style="text-align: left;">10.7533490313591</td>
<td style="text-align: left;">11.5131625382955</td>
<td style="text-align: left;">12.0001757787983</td>
<td style="text-align: left;">19.7679638273198</td>
<td style="text-align: left;">13.5377074210606</td>
<td style="text-align: left;">10.5863147070872</td>
<td style="text-align: left;">9.54563474227486</td>
<td style="text-align: left;">13.6589332263753</td>
<td style="text-align: left;">22.6708565058161</td>
<td style="text-align: left;">15.5126108259848</td>
<td style="text-align: left;">11.0983222265855</td>
<td style="text-align: left;">11.7964943204658</td>
<td style="text-align: left;">9.81435206962009</td>
<td style="text-align: left;">12.6973704642363</td>
<td style="text-align: left;">14.7798080412152</td>
<td style="text-align: left;">9.51740333404221</td>
<td style="text-align: left;">11.8199259419043</td>
<td style="text-align: left;">13.3705401401024</td>
<td style="text-align: left;">10.0379276251794</td>
<td style="text-align: left;">13.3519899132543</td>
<td style="text-align: left;">15.926695971616</td>
</tr>
<tr class="even">
<td style="text-align: left;">06</td>
<td style="text-align: left;">15.4859395700169</td>
<td style="text-align: left;">26.757142616657</td>
<td style="text-align: left;">15.8089382470029</td>
<td style="text-align: left;">11.474006495603</td>
<td style="text-align: left;">11.8731874839597</td>
<td style="text-align: left;">13.8928846396804</td>
<td style="text-align: left;">23.3042439255981</td>
<td style="text-align: left;">14.8571075710857</td>
<td style="text-align: left;">11.2842313363997</td>
<td style="text-align: left;">10.2426024630851</td>
<td style="text-align: left;">16.7611325925993</td>
<td style="text-align: left;">28.6478192241555</td>
<td style="text-align: left;">16.7868293141032</td>
<td style="text-align: left;">11.8113153321657</td>
<td style="text-align: left;">12.1836189432504</td>
<td style="text-align: left;">10.4998336845397</td>
<td style="text-align: left;">15.2404130027592</td>
<td style="text-align: left;">18.0389273786141</td>
<td style="text-align: left;">10.0372473442059</td>
<td style="text-align: left;">13.9444613405235</td>
<td style="text-align: left;">15.3509375064662</td>
<td style="text-align: left;">10.8978932022784</td>
<td style="text-align: left;">16.2498112363926</td>
<td style="text-align: left;">20.2637776034625</td>
</tr>
</tbody>
</table>

## Dataset Characteristics

-   100 lignes (1 ligne par departement)
-   25 colonnes
-   41 ko

## Variables

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

## Exemples d’utilisation / Intérêt

-   Lien entre le taux de vaccination par departement et le revenu
-   Analyse des soins, diagnostics, prescription médicament, santé des
    enfants, mortalité, par departement selon le revenu

## Licence

Les données issues des Bases Tous Salariés sont soumises au secret
statistique. Aucune statistique n’est diffusée pour les zones de moins
de 2 000 habitants. Pour quelques zones de 2 000 habitants ou plus, qui
ne respectent pas les seuils, il n’est pas non plus possible de diffuser
des résultats. À savoir, chaque case du tableau doit comporter au moins
5 salariés et aucun salarié ne doit représenter plus de 80% de la masse
salariale de la case.

## Source

<https://www.insee.fr/fr/statistiques/2021266> (Paru le : 26/08/2021)

## Datamanagement

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

## Statistiques descriptives

    salary_hf = salary_clean%>%
      select (Femmes, Hommes)
    library(ggplot2)
    ggplot(stack(salary_hf), aes(x = ind, y = values, color=ind)) +
      geom_boxplot()
      
![unnamed-chunk-3-1](https://user-images.githubusercontent.com/74362276/138416895-882813c0-2271-4c52-9fbb-50f0bc9a4846.png)

![](Salary_2019_files/figure-markdown_strict/unnamed-chunk-3-1.png)

    salary_f = salary_clean%>%
      select(F_cadre_sup, F_prof_int, F_employées, F_ouvriers)

    ggplot(stack(salary_f), aes(x = ind, y = values, color=ind)) +
      geom_boxplot()
![unnamed-chunk-3-2](https://user-images.githubusercontent.com/74362276/138416937-6780767b-af76-4f85-9e56-cdeb843c61f0.png)



![](Salary_2019_files/figure-markdown_strict/unnamed-chunk-3-2.png)

    salary_h = salary_clean%>%
      select (H_cadre_sup, H_prof_int, H_ouvriers, H_employés)

    ggplot(stack(salary_h), aes(x = ind, y = values, color=ind)) +
      geom_boxplot()
![unnamed-chunk-3-3](https://user-images.githubusercontent.com/74362276/138416956-f0d0c32a-f61d-4949-b654-e3cfb2101eee.png)



![](Salary_2019_files/figure-markdown_strict/unnamed-chunk-3-3.png)

    salary_hf_cadre = salary_clean%>%
      select(F_cadre_sup, H_cadre_sup)

    ggplot(stack(salary_hf_cadre), aes(x = ind, y = values, color=ind)) +
      geom_boxplot()
      
      
   ![unnamed-chunk-3-4](https://user-images.githubusercontent.com/74362276/138416974-9724fa5e-64d5-4bf2-851a-5c4371801405.png)

  

![](Salary_2019_files/figure-markdown_strict/unnamed-chunk-3-4.png)

    salary_hf_ouvriers = salary_clean%>%
      select(F_ouvriers, H_ouvriers)

    ggplot(stack(salary_hf_ouvriers), aes(x = ind, y = values, color=ind)) +
      geom_boxplot()

![unnamed-chunk-3-5](https://user-images.githubusercontent.com/74362276/138417001-324e28ca-7e25-4818-8f4b-cf2d46bff744.png)



![](Salary_2019_files/figure-markdown_strict/unnamed-chunk-3-5.png)
