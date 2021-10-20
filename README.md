![Logo](https://svietimas.vilnius.lt/new/subsystems/darzeliai/layout/images/new_style/home_icon.png)
# About Dataset

Duomenys iš vaikų darželio https://svietmas.vilnius.lt sistemos.

Data for kindergartens and children going to them

## About Data collection methodology

Periodinės užduotis atrenka duomenis ir patalpina į šią talpiklą tokiu periodiškumu:
```
lankomumo_ziniarasciai -  kas menesį
-darzeliai_grupes.csv - kas savaite
-lankanciu_vaiku_ataskaita_pagal_grupes.csv - kas savaite
-laukianciuju_eileje_ataskaita.csv - kas savaite
```
Daily data select from svietimias.vilnius.lt DB and push to github.

### Description of the data

Duomenų rinkiniai

Data is stored in all the files
```
Root Dir/
  -data/
    -darzeliai_grupes.csv 
    -lankanciu_vaiku_ataskaita_pagal_grupes.csv
    -laukianciuju_eileje_ataskaita.csv
  -Other_data/ # old archived data
  darzeliai_grupes2.csv 
    -group_age.csv
    -group_age_type.csv
    -grupes.csv
    -lankanciu_vaiku_ataskaita_pagal_grupes_2014-09-23.csv
    -lankanciu_vaiku_ataskaita_pagal_grupes_2014-10-27.csv
    -visi_prasymai.csv
  -lankomumo_ziniarasciai/
      -Lankomumo_ziniarasciai_pamenesiui
      
  -README.md

```

istaigu_sarasas.csv - list of pre-school institutions;

lankanciu_vaiku_ataskaita_pagal_grupes.csv - children that are going to the kindergartens by groups;

lankomumo_ziniarasciai_(datefrom)-(dateto).csv - report of childrens attendance per specifed date range;

laukianciuju_eileje_ataskaita.csv - children that are waiting for the kindergartens in queue;


## Online Repository link

* [DataRepository](https://github.com/vilnius/darzeliai) - Link to the data repository.

## Authors

* **ITG** - *Initial work* - [AtvirasVilnius](https://github.com/vilnius)

# More Data
You can find more data set at https://open.vilnius.lt

Please contact us via email atviras@vilnius.lt if you require any further information or specific data and/or dataset.

