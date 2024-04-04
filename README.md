# Human traficking, population, and GNI per capita

## Problem statement
Human trafficking is often defined as the coercion of a person into labor, servitude, slavery, commercial sex, or organ removal. It is a global problem that impacts victims from all ages and socioeconomic backgrounds.
<br>
In this notebook, we use world development statistics from [Gapminder](https://www.gapminder.org/about/) and the [Counter Trafficking Data Collaborative](https://www.ctdatacollaborative.org/) to answer two questions:
* Is a victim’s economic background connected to the way they were recruited?
* Is a victim’s majority at entry connected to the country of exploitation’s population?

## Findings
* Almost all victims recruited by intimate partners are citizens of wealthier countries.
* The majority of victims recruited by friends and "other" recruiters are citizens of poorer countries.
* Victims recruited by family members are very common in poorer countries and not uncommon in wealthier countries.
* Reportedly, most victims entering trafficking as minors are exploited in the U.S.
* Most victims entering trafficking as adults are exploited in countries with lower populations.

## Data dictionaries

### Dataset: The Global K-anonymized Dataset
The CTDC provides a data dictionary for its 60+ columns dataset: [The Global K-anonymized Data Dictionary](https://www.ctdatacollaborative.org/sites/g/files/tmzbdl2011/files/CTDC%20Global%20K-anon%20Dataset%20DATA%20DICTIONARY%20version%2020210825.xlsx).

### Dataset: GNI per capita, Atlas method
|Feature|Type|Description|
|---|---|---|
|**country**|*string*|The name of the country.| 
|**2002**|*float*|The GNI per capita value for the year 2002.|
|**2003**|*float*|The GNI per capita value for the year 2003.|
|...|...|...|
|**2021**|*float*|The GNI per capita value for the year 2021.|

### Dataset: Population
|Feature|Type|Description|
|---|---|---|
|**country**|*string*|The name of the country.| 
|**2002**|*float*|The population value for the year 2002.|
|**2003**|*float*|The population value for the year 2003.|
|...|...|...|
|**2021**|*float*|The population for the year 2021.|

## References
[1] Counter Trafficking Data Collaborative, "The Global K-anonymized Dataset". 2023. https://www.ctdatacollaborative.org/sites/g/files/tmzbdl2011/files/The%20Global%20K-anon%20Dataset%2015%20July%202021.xlsx.
<br>
[2] Counter Trafficking Data Collaborative, "Counter Trafficking Data Collaborative (CTDC) K-anonymized Data Codebook". 2021. https://www.ctdatacollaborative.org/sites/g/files/tmzbdl2011/files/CTDCk_codebook_v7_1.pdf.
<br>
[3] Counter Trafficking Data Collaborative, "The Global K-anonymized Data Dictionary". 2021. https://www.ctdatacollaborative.org/sites/g/files/tmzbdl2011/files/CTDC%20Global%20K-anon%20Dataset%20DATA%20DICTIONARY%20version%2020210825.xlsx.
<br>
[4] C. Fraser, "An analysis of the emerging role of social media in human trafficking: Examples from labour and human organ trading," International Journal of Development Issues, vol. 15, no. 2, pp. 98-112, 2016. https://doi.org/10.1108/IJDI-12-2015-0076.
<br>
[5] UNODC, Global Report on Trafficking in Persons 2020. 2020. https://www.unodc.org/documents/data-and-analysis/tip/2021/GLOTiP_2020_Chapter5.pdf.
<br>
[6] UNODC, Global Report on Trafficking in Persons 2022. 2020. https://www.unodc.org/documents/data-and-analysis/glotip/2022/GLOTiP_2022_web.pdf.
<br>
[7] P. Campana, "Online and technology-facilitated trafficking in human beings", Council of Europe. 2022. https://rm.coe.int/online-and-technology-facilitated-trafficking-in-human-beings-summary-/1680a5e10c.
