# Metadata reference

- [Package ID](#package)
- [Data Sets](#dataSets)
- [Data Elements](#dataElements)
- [Data Element Groups](#dataElementGroups)
- [Category Combos](#categoryCombos)
- [Categories](#categories)
- [Category Options](#categoryOptions)
- [Category Option Combos](#categoryOptionCombos)
- [Category Option Group Sets](#categoryOptionGroupSets)
- [Category Option Groups](#categoryOptionGroups)
- [Option Sets](#optionSets)
- [Options](#options)
- [Validation Rules](#validationRules)
- [Validation Rule Groups](#validationRuleGroups)
- [Indicators](#indicators)
- [Indicator Groups](#indicatorGroups)
- [Indicator Types](#indicatorTypes)
- [Dashboards](#dashboards)
- [Charts](#charts)
- [Report Tables](#reportTables)
- [Maps](#maps)
- [User Groups](#userGroups)

<h1 id="#package"> Package info</h1>
| **Property** | Value |
| --- | --- |
| **Code** | COVID19 |
| **Type** | COMPLETE |
| **Version** | V2.0 |
| **DHIS2 version** |DHIS2.33 |
| **Created** | 2020-10-12T15:17 |
| **Identifier** | COVID19_COMPLETE_V2.0_DHIS2.33_2020-10-12T15:17 |

<h1 id="#dataSets"> Data sets</h1>

### COVID19 - Aggregate Weekly Surveillance

| **Property** | Value |
| --- | --- |
| **Name:** | COVID19 - Aggregate Weekly Surveillance |
| **Custom form:** | No |
| **Sections:** | Yes |
| **Last updated** | 2020-09-17 |
| **UID:** | uKtOZwDnIpM |

#### Sections

| **Section**                       | **Last updated** | **UID**     |
| --------------------------------- | ---------------- | ----------- |
| New confirmed and probable cases  | 2020-10-26       | i9rpQqB3Hfh |
| New probable and confirmed deaths | 2020-10-26       | WpkRkdnPvjU |
| Health worker infection and death | 2020-10-26       | DFZ530AsisR |
| Hospitalisation and discharges    | 2020-10-26       | LsTxlZ01Cxn |
| Tests conducted                   | 2020-10-26       | r6tjZBmD6UQ |
| Transmission classification       | 2020-10-26       | GTFXasEGT2O |

#### Data Set Section - Data Element

| **Data Set Section**              | **Data Element**                                     |
| --------------------------------- | ---------------------------------------------------- |
| New confirmed and probable cases  | COVID19 - New Confirmed Cases                        |
| New confirmed and probable cases  | COVID19 - New Probable Cases                         |
| New probable and confirmed deaths | COVID19 - New Probable Deaths                        |
| New probable and confirmed deaths | COVID19 - New Confirmed Deaths                       |
| Health worker infection and death | COVID19 - New Cases Among HW (Confirmed + Probable)  |
| Health worker infection and death | COVID19 - New Deaths Among HW (Confirmed + Probable) |
| Hospitalisation and discharges    | COVID19 - New Discharged Cases                       |
| Hospitalisation and discharges    | COVID19 - New Hospitalized Cases                     |
| Tests conducted                   | COVID19 - Tested                                     |
| Tests conducted                   | COVID19 - Tested with PCR Assay                      |
| Transmission classification       | COVID19 - Transmission Classification                |

<h1 id="#dataElements">Data Elements</h1>

| **Name** | **Shortname** | **Code** | **Description** | **Categorycombo** | **Last updated** | **UID** |
| --- | --- | --- | --- | --- | --- | --- |
| COVID19 - New Cases Among HW (Confirmed + Probable) | New Cases Among HW (Confirmed + Probable) | CV19\_NEW\_CONF\_PROB\_HW\_CASES || default | 2020-10-06 | SU1j9CmCuW9 |
| COVID19 - New Confirmed Cases | New Confirmed Cases | CV19\_NEW\_CONF\_CASES ||Age and sex (COVID-19) | 2020-09-17 | bmbNyNoJcXP|
| COVID19 - New Confirmed Deaths | New Confirmed Deaths | CV19\_NEW\_CONF\_DEATHS || Age and sex (COVID-19) | 2020-09-17 | rBw83gVQLHK |
| COVID19 - New Deaths Among HW (Confirmed + Probable) | New Deaths Among HW (Confirmed + Probable) | CV19\_NEW\_CONF\_PROB\_HW\_DEATHS| | default | 2020-10-06 | DI9JgEJ3t8v |
| COVID19 - New Discharged Cases | New Discharged Cases | CV19\_NEW\_CONF\_PROB\_DISCHARGED ||default | 2020-09-17 | fJ7Qi1zcdAR |
| COVID19 - New Hospitalized Cases | New Hospitalized Cases | CV19\_NEW\_CONF\_PROB\_HOSPITALIZED ||default | 2020-09-17 | cW0odY9vhrd |
| COVID19 - New Probable Cases | New Probable Cases | CV19\_NEW\_PROB\_CASES ||Age and sex (COVID-19) | 2020-09-17 | VnkErE22ELJ |
| COVID19 - New Probable Deaths | New Probable Deaths | CV19\_NEW\_PROB\_DEATHS ||Age and sex (COVID-19) | 2020-09-17 | N59eghaBpM7 |
| COVID19 - Tested | Tested | CV19\_TESTED ||default|  2020-09-17 | E1pXvzyZzKB |
| COVID19 - Tested with PCR Assay | Tested with PCR Assay | CV19\_TESTED\_PCR ||default | 2020-09-17 | pZtyMNtYPLM |
| COVID19 - Transmission Classification | Transmission Classification | CV19\_TRANS\_CLASS ||default |2020-09-17 | sWCFbUawFDa |

<h1 id="#dataElementGroups">Data Element Groups</h1>

| **Name** | **Shortname** | **Last updated** | **UID** |
| --- | --- | --- | --- |
| COVID-19 | COVID-19 | 2020-09-17 | TIo5wZmgN8F |

### Data Element Groups - Data Elements

| **Data Element Group** | **Data Element** |
| --- | --- |
| COVID-19 | COVID19 - Transmission Classification |
| COVID-19 | COVID19 - New Confirmed Cases |
| COVID-19 | COVID19 - New Confirmed Deaths |
| COVID-19 | COVID19 - New Probable Cases |
| COVID-19 | COVID19 - Tested with PCR Assay |
| COVID-19 | COVID19 - New Probable Deaths |
| COVID-19 | COVID19 - New Hospitalized Cases |
| COVID-19 | COVID19 - Tested |
| COVID-19 | COVID19 - New Cases Among HW (Confirmed + Probable) |
| COVID-19 | COVID19 - New Discharged Cases |
| COVID-19 | COVID19 - New Deaths Among HW (Confirmed + Probable) |

<h1 id="#categoryCombos"> Category Combinations</h1>

| **Name** | **Last updated** | **UID** | **Categories** |
| --- | --- | --- | --- |
| Age and sex (COVID-19) | 2020-09-17 | UPxdJOxz2I7 | Age (COVID19); Sex (with unknown) |
| default | 2020-05-11 | bjDvmb4bfuf | default |

<h1 id="#categories"> Data Element Categories</h1>

| **Name** | **Last updated** | **UID** | **Category options** |
| --- | --- | --- | --- |
| Age (COVID19) | 2020-10-06 | RrZWSJ6CsLs | 0-4 years; 5-9 years; 10-14 years; 15-19 years; 20-29 years; 30-39 years; 40-49 years; 50-59 years; 60-64 years; 65-69 years; 70-74 years; 75-79 years; 80+ years; Unknown age |
| default | 2020-10-01 | GLevLNI9wkl | default |
| Sex (with unknown) | 2020-09-22 | b7peexUktxt | Male; Female; Unknown Sex |

<h1 id="#categoryOptions"> Data Element Category Options</h1>

| **Name** | **Last updated** | **UID** |
| --- | --- | --- |
| 0-14 years | 2019-07-03 | IoqDBYr0rH5 |
| 0-4 years | 2020-09-17 | UPvKbcqTEY3 |
| 10-14 years | 2020-09-17 | ftXCKvbuGgj |
| 15-19 years | 2020-09-17 | dENFBee17Oi |
| 20-29 years | 2020-09-17 | GERCWxK3mvz |
| 30-39 years | 2020-09-17 | bY3NyagrzeD |
| 40-49 years | 2020-09-17 | tTmsWzvoEUv |
| 5-9 years | 2020-09-17 | J205eXYNH7q |
| 50-59 years | 2020-09-17 | BOCPEdURsYX |
| 60-64 years | 2020-09-17 | TEBfAmuOSJk |
| 65-69 years | 2020-09-17 | gHA96noC0iO |
| 70-74 years | 2020-09-17 | Po7T5dd3tQs |
| 75-79 years | 2020-09-17 | xWXUBYNycnE |
| 80+ years | 2020-09-17 | c2hLbh0drQI |
| default | 2018-05-30 | xYerKDKCefk |
| Female | 2020-09-17 | FFA9e1yIXCT |
| Male | 2020-09-17 | MP15bHaQh2x |
| Unknown age | 2020-09-17 | WNPpyVkVaL3 |
| Unknown Sex | 2020-09-17 | kuP5EmQRFke |

<h1 id="#categoryOptionCombos">Category Option Combination</h1>

| **Name** | **Last updated** | **UID** |
| --- | --- | --- |
| 0-4 years, Female | 2020-09-17 | X7SGUlfmJa5 |
| 0-4 years, Male | 2020-09-17 | d1XzGx028Z8 |
| 0-4 years, Unknown Sex | 2020-09-17 | Ter1Z3EGkQM |
| 10-14 years, Female | 2020-09-17 | vvpjmqp0psR |
| 10-14 years, Male | 2020-09-17 | SV1RvPdmAkj |
| 10-14 years, Unknown Sex | 2020-09-17 | XUXU9zyHXN9 |
| 15-19 years, Female | 2020-09-17 | F9pPSHdgzwj |
| 15-19 years, Male | 2020-09-17 | sx3u16x80nV |
| 15-19 years, Unknown Sex | 2020-09-17 | CTWSo1P4qyZ |
| 20-29 years, Female | 2020-09-17 | SIxMfxXNBVo |
| 20-29 years, Male | 2020-09-17 | bB5hQrGwaD1 |
| 20-29 years, Unknown Sex | 2020-09-17 | EjYC7RAtkkQ |
| 30-39 years, Female | 2020-09-17 | GiRwR3FD86i |
| 30-39 years, Male | 2020-09-17 | S17lTK4VVeE |
| 30-39 years, Unknown Sex | 2020-09-17 | bAO3xBqTyUk |
| 40-49 years, Female | 2020-09-17 | JepUukzD91g |
| 40-49 years, Male | 2020-09-17 | MysvJzZ0ADY |
| 40-49 years, Unknown Sex | 2020-09-17 | ejldVLyrIy7 |
| 5-9 years, Female | 2020-09-17 | g5XAclU6mWm |
| 5-9 years, Male | 2020-09-17 | bm2siOxEk6w |
| 5-9 years, Unknown Sex | 2020-09-17 | S7DctIRHOH4 |
| 50-59 years, Female | 2020-09-17 | cfJ88kcKfs2 |
| 50-59 years, Male | 2020-09-17 | Hqno1sfL72D |
| 50-59 years, Unknown Sex | 2020-09-17 | nux1VokaZmF |
| 60-64 years, Female | 2020-09-17 | ABYB6U68hMU |
| 60-64 years, Male | 2020-09-17 | vsG6W671YoN |
| 60-64 years, Unknown Sex | 2020-09-17 | YUMOQHnN8pn |
| 65-69 years, Female | 2020-09-17 | SZ9ccMeGlS6 |
| 65-69 years, Male | 2020-09-17 | H0mzaMCOq2e |
| 65-69 years, Unknown Sex | 2020-09-17 | llEP85jmlnN |
| 70-74 years, Female | 2020-09-17 | D0g8d1tsNnv |
| 70-74 years, Male | 2020-09-17 | oEsLwo2ah7U |
| 70-74 years, Unknown Sex | 2020-09-17 | JC2mJwkcXQ2 |
| 75-79 years, Female | 2020-09-17 | Lic97hqxsNP |
| 75-79 years, Male | 2020-09-17 | PgmLRiqPKgd |
| 75-79 years, Unknown Sex | 2020-09-17 | byqkmEDJ42u |
| 80+ years, Female | 2020-09-17 | RzvnXjQu1cm |
| 80+ years, Male | 2020-09-17 | zjOFUnSP4cf |
| 80+ years, Unknown Sex | 2020-09-17 | P6caJBLkaq9 |
| default | 2020-03-26 | HllvX50cXC0 |
| Female, 0-14 years | 2020-09-17 | GHDbaPccoPh |
| Male, 0-14 years | 2020-09-17 | KMTXoNkoiAc |
| Unknown age, Female | 2020-09-17 | w1W0eGecUME |
| Unknown age, Male | 2020-09-17 | BAJrVjxh8K9 |
| Unknown age, Unknown Sex | 2020-09-17 | meAnvpEpz8M |

<h1 id="#categoryOptionGroupSets"> Category Option Group Sets</h1>

| **Name** | **Last updated** | **UID** |
| --- | --- | --- |
| Age in years for COVID-19(0-4,5-9,10-14,15-19,20-29,30-39,40-49,50-59,60-64,65-69,70-74,75-79,80+,Unk) | 2020-09-17 | nd6HGxbW3D5 |
| Sex (with unknown) | 2020-09-17 | XxEFGdwxOJ0 |

<h1 id="#categoryOptionGroups">Category Option Groups</h1>

| **Name** | **Shortname** | **Last updated** | **UID** |
| --- | --- | --- | --- |
| 0-4 years | 0-4 y | 2020-09-17 | yuathFHLjNe |
| 10-14 years | 10-14 y | 2020-09-17 | RoYZKp6iDnH |
| 15-19 years | 15-19 y | 2020-09-17 | qiaJA9sMzj2 |
| 20-29 years | 20-29 y | 2020-09-17 | p84eezwJhMd |
| 30-39 years | 30-39 y | 2020-09-17 | u87kL0SUYZa |
| 40-49 years | 40-49 y | 2020-09-17 | nuU9qXctcQE |
| 5-9 years | 5-9 y | 2020-09-17 | Mcv3dvoK2iM |
| 50-59 years | 50-59 y | 2020-09-17 | IpuKFEXhtUJ |
| 60-64 years | 60-64 y | 2020-09-17 | JrQqLgsGgFr |
| 65-69 years | 65-69 y | 2020-09-17 | Bap549vCg8U |
| 70-74 years | 70-74 y | 2020-09-17 | t1JMgMVyoac |
| 75-79 years | 75-79 y | 2020-09-17 | FplLHwIitbU |
| 80+ years | 80+ y | 2020-09-17 | v1e6orGTL3f |
| Female | Female | 2020-09-17 | bqoVhX2RfG4 |
| Male | Male | 2020-09-17 | EVYKU2fIc6G |
| Unknown Sex | Unk Sex | 2020-09-17 | SZJNeRyrh22 |

### Category Option Group Sets - Category Option Groups

| **Category Option Group Sets** | **Category Option Groups** |
| --- | --- |
| Age in years for COVID-19(0-4,5-9,10-14,15-19,20-29,30-39,40-49,50-59,60-64,65-69,70-74,75-79,80+,Unk) | 0-4 years |
| Age in years for COVID-19(0-4,5-9,10-14,15-19,20-29,30-39,40-49,50-59,60-64,65-69,70-74,75-79,80+,Unk) | 5-9 years |
| Age in years for COVID-19(0-4,5-9,10-14,15-19,20-29,30-39,40-49,50-59,60-64,65-69,70-74,75-79,80+,Unk) | 10-14 years |
| Age in years for COVID-19(0-4,5-9,10-14,15-19,20-29,30-39,40-49,50-59,60-64,65-69,70-74,75-79,80+,Unk) | 15-19 years |
| Age in years for COVID-19(0-4,5-9,10-14,15-19,20-29,30-39,40-49,50-59,60-64,65-69,70-74,75-79,80+,Unk) | 20-29 years |
| Age in years for COVID-19(0-4,5-9,10-14,15-19,20-29,30-39,40-49,50-59,60-64,65-69,70-74,75-79,80+,Unk) | 30-39 years |
| Age in years for COVID-19(0-4,5-9,10-14,15-19,20-29,30-39,40-49,50-59,60-64,65-69,70-74,75-79,80+,Unk) | 40-49 years |
| Age in years for COVID-19(0-4,5-9,10-14,15-19,20-29,30-39,40-49,50-59,60-64,65-69,70-74,75-79,80+,Unk) | 50-59 years |
| Age in years for COVID-19(0-4,5-9,10-14,15-19,20-29,30-39,40-49,50-59,60-64,65-69,70-74,75-79,80+,Unk) | 60-64 years |
| Age in years for COVID-19(0-4,5-9,10-14,15-19,20-29,30-39,40-49,50-59,60-64,65-69,70-74,75-79,80+,Unk) | 65-69 years |
| Age in years for COVID-19(0-4,5-9,10-14,15-19,20-29,30-39,40-49,50-59,60-64,65-69,70-74,75-79,80+,Unk) | 70-74 years |
| Age in years for COVID-19(0-4,5-9,10-14,15-19,20-29,30-39,40-49,50-59,60-64,65-69,70-74,75-79,80+,Unk) | 75-79 years |
| Age in years for COVID-19(0-4,5-9,10-14,15-19,20-29,30-39,40-49,50-59,60-64,65-69,70-74,75-79,80+,Unk) | 80+ years |
| Age in years for COVID-19(0-4,5-9,10-14,15-19,20-29,30-39,40-49,50-59,60-64,65-69,70-74,75-79,80+,Unk) | Unknown Sex |
| Sex (with unknown) | Female |
| Sex (with unknown) | Male |
| Sex (with unknown) | Unknown Sex |

<h1 id="#optionSets">Option Sets</h1>

| **Name** | **Last updated** | **UID** | **Options** |
| --- | --- | --- | --- |
| Transmission Classification | 2020-09-17 | QLANS0Gen0m | No cases; Sporadic; Clusters; Community |

<h1 id="#options">Options</h1>

| **Name** | **Code** | **Last updated** | **UID**|
| --- | --- | --- | --- | --- |
| Transmission Classification | Clusters | CLUSTERS | 2020-09-17 | NzPq5MlxCmh |
| Transmission Classification | Community | COMMUNITY | 2020-09-17 | zUdhwKZdpT8 |
| Transmission Classification | No cases | NO\_CASES | 2020-09-17 | mF5r1p7sKcq |
| Transmission Classification | Sporadic | SPORADIC | 2020-09-17 | AXl3Z9rLjLi |

<h1 id="#validationRules"> Validation Rules</h1>

| **Name** | **Instruction** | **Left side** | **Operator** | **Right side** | **Last updated** | **UID** |
| --- | --- | --- | --- | --- | --- | --- |
| COVID19 - New Cases hospitalised \&lt;= All New Cases | New Cases hospitalised should be less than or equal to All new cases reported | New Cases hospitalised | less\_than\_or\_equal\_to | All New Cases | 2020-10-06 | bO8rXNzj0iR |
| COVID19 - PCR tests \&lt;= tested | Test with PCR should be less than or equal to tested | Tested with PCR | less\_than\_or\_equal\_to | Tested | 2020-10-06 | gZwUbrTOa0g |

<h1 id="#validationRuleGroups">Validation Rule Groups</h1>

| Name | Last updated | UID |
| --- | --- | --- |
| **COVID-19** | 2020-10-06 | WY7h5pKok2I |

### Validation Rule Groups - Validation Rules

| Validation Rule Group | Validation Rule |
| --- | --- |
| **COVID-19** | COVID19 - PCR tests \&lt;= tested |
| **COVID-19** | COVID19 - New Cases hospitalised \&lt;= All New Cases |

<h1 id="#indicators"> Indicators</h1>

| Name | Shortname | Code | Description | Numerator | Denominator | Type | Last updated | UID |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| **COVID19 - Active cases** | Active cases | CV19\_ACTIVE\_CASES ||Active Cases | 1 | Numerator only (number) | 2020-10-06 | ZTklbd8JtLn |
|**COVID19 - Case fatality rate (%)** | Case Fatality rate (%) |CV19\_CASE\_FATALITY\_RATE ||Death (Confirmed + Probable) | All cases (Confirmed + Probable) | Percentage | 2020-10-05 | LeNVLm6SL1x|
| **COVID19 - Case fatality rate among HW (%)** | Case fatality rate HW (%)|CV19\_CASE\_FATALITY\_RATE\_HW || New Deaths Among HW (Confirmed + Probable) | New Cases Among HW (Confirmed + Probable) | Percentage | 2020-10-06 | NP88sGFKpCQ|
| **COVID19 - Closed cases** | Closed cases | CV19\_CLOSED\_CASES || Closed cases | 1 | Numerator only (number) | 2020-10-06 | VJHMO9gHkV5 |
| **COVID19 - New Confirmed cases** | New Confirmed cases |CV19\_NEW\_CONF\_CASES || New Confirmed cases | 1 | Numerator only (number) | 2020-09-17 | TmKNBHtBx6D |
| **COVID19 - New Confirmed Deaths** | New Confirmed Deaths | CV19\_NEW\_CONF\_DEATHS || New Confirmed Deaths | 1 | Numerator only (number) | 2020-09-17 | yzyWxXoSCny |
| **COVID19 - New Discharged Cases** | New Discharged Cases | CV19\_NEW\_CONF\_PROB\_DISCHARGED || New Discharged Cases | 1 | Numerator only (number) | 2020-09-17 | U89bOzPbFyA |
| **COVID19 - New Hospitalized Cases** | New Hospitalized Cases | CV19\_NEW\_CONF\_PROB\_HOSPITALIZED || New Hospitalized Cases | 1 | Numerator only (number) | 2020-09-17 | DnleIypnqxJ |
| **COVID19 - Positivity rate (%)** | Positivity rate (%) | CV19\_POSITIVITY\_RATE || New Confirmed cases | Tested | Percentage | 2020-10-05 | C6A59SObXV6 |
| **COVID19 - Proportion of HW amongst reported cases (%)** | HW among confirmed cases (%) | CV19\_%\_HW\_AMONGST\_REPORTED\_CASES || New Cases Among HW (Confirmed + Probable) | New Confirmed Cases | Percentage | 2020-10-06 | x6IelBioEX1 |
| **COVID19 - Proportion of PCR tests (%)** | Proportion of PCR tests | CV19\_%\_PCR\_TESTS || Tested with PCR Assay | Tested | Percentage | 2020-10-05 | cJZS7kSFFGl|
| **COVID19 - Recovery rate (%)** | Recovery rate (%) | CV19\_RECOVERY\_RATE || New Discharged Cases | All cases (Confirmed + Probable) | Percentage | 2020-10-05 | K2JqazsxhvP |
| **COVID19 - Tested** | Tested | CV19\_TESTED || Tested | 1 | Numerator only (number) | 2020-09-17 | pxqFjCNLkzD |
| **COVID19 - Tested with PCR Assay** | Tested with PCR Assay | CV19\_TESTED\_PCR || Tested with PCR Assay | 1 | Numerator only (number) | 2020-09-17 | jgyO0rV708H |

<h1 id="#indicatorGroups">Indicator Groups</h1>

| Name | Shortname | Last updated | UID |
| --- | --- | --- | --- |
| **COVID19** |
| 2020-10-06 | UGXgY58CxjG |

### Indicator Groups - Indicators

| Indicator Group | Indicator |
| --- | --- |
| **COVID19** | COVID19 - New Confirmed Deaths |
| **COVID19** | COVID19 - Active cases |
| **COVID19** | COVID19 - Closed cases |
| **COVID19** | COVID19 - New Confirmed cases |
| **COVID19** | COVID19 - Proportion of HW amongst reported cases (%) |
| **COVID19** | COVID19 - Recovery rate (%) |
| **COVID19** | COVID19 - Case fatality rate among HW (%) |
| **COVID19** | COVID19 - New Hospitalized Cases |
| **COVID19** | COVID19 - Tested |
| **COVID19** | COVID19 - Tested with PCR Assay |
| **COVID19** | COVID19 - Positivity rate (%) |
| **COVID19** | COVID19 - New Discharged Cases |
| **COVID19** | COVID19 - Proportion of PCR tests (%) |
| **COVID19** | COVID19 - Case fatality rate (%) |

<h1 id="#indicatorTypes">Indicator types</h1>

| Name | Factor | Last updated | UID |
| --- | --- | --- | --- |
| **Numerator only (number)** | 1 | 2020-09-09 | kHy61PbChXr |
| **Percentage** | 100 | 2018-01-16 | hmSnCXmLYwt |

<h1 id="#dashboards"> Dashboards</h1>

### COVID19 - Aggregate Weekly Surveillance

| Property | **Value** |
| --- | --- |
| Name: | COVID19 - Aggregate Weekly Surveillance |
| Last updated: | 2020-10-12 |
| UID: | GdRQEdWJEMH |

#### Dashboard items

| Content/item type | Content name | Content UID | Last updated | Dashboard Item UID |
| --- | --- | --- | --- | --- |
| **Pivot table** | COVID19 - Tested, tests with PCR and positivity rate by subnational level this year | jTGq07MlmMp | 2020-10-12 | btrkVNdRwnO |
| **Chart** | COVID19 - HW amongst reported cases this year | oaBx9hR7FFR | 2020-10-12 | jmn7HoMmBHC |
| **Chart** | COVID19 - Fatality rate amongst HW | BGGBmj9Yuu7 | 2020-10-12 | JNHOYQEIN3V |
| **Chart** | COVID19 - New confirmed cases and deaths in the last 12 weeks | eha82bnB8N1 | 2020-10-12 | P7syfXG9dNm |
| **Chart** | COVID19 - Cumulative tests conducted, cases reported, hospitalised, discharged and deaths | E6w4iwPkaRM | 2020-10-12 | IeZQZcgmAfV |
| **Map** | COVID19 - Cumulative confirmed cases by subnational | AwrThZVBW5g | 2020-10-12 | KWM5EsM8hYR |
| **Chart** | COVID19 - Deaths by age groups last weeks | WcRHBfw09Iq | 2020-10-12 | qTkvVnIP5Ri |
| **Chart** | COVID19 - Confirmed cases by sex in the last 14 weeks | E94X1H21okK | 2020-10-12 | KMsy5gLLUWr |
| **Chart** | COVID19 - Closed and active cases at subnational last months | neIuzgRUO0N | 2020-10-12 | JZ4Jt9JxsVh |
| **Chart** | COVID19 - Case recovery and fatality rates last 12 weeks | pQ6jw6r59Op | 2020-10-12 | YocjDGUCP18 |
| **Chart** | COVID19 - Active and Closed Cases last 12 weeks | Sf2KIcQRyMj | 2020-10-12 | dbn6GloPaRP |

<h1 id="#charts"> Charts</h1>

| Name | Description | Last updated | UID |
| --- | --- | --- | --- |
| COVID19 - Active and Closed Cases last 12 weeks || 2020-10-05 | Sf2KIcQRyMj |
| **COVID19 - Case recovery and fatality rates last 12 weeks** || 2020-10-05 | pQ6jw6r59Op |
| **COVID19 - Closed and active cases at subnational last months** || 2020-10-05 | neIuzgRUO0N |
| **COVID19 - Confirmed cases by sex in the last 14 weeks** || 2020-10-06 | E94X1H21okK |
| **COVID19 - Cumulative tests conducted, cases reported, hospitalised, discharged and deaths** || 2020-10-05 | E6w4iwPkaRM |
| **COVID19 - Deaths by age groups last weeks** || 2020-10-05 | WcRHBfw09Iq |
| **COVID19 - Fatality rate amongst HW** || 2020-10-05 | BGGBmj9Yuu7 |
| **COVID19 - HW amongst reported cases this year** || 2020-10-05 | oaBx9hR7FFR |
| **COVID19 - New confirmed cases and deaths in the last 12 weeks** || 2020-10-05 | eha82bnB8N1 |

<h1 id="#reportTables"> Report tables</h1>

| Name | Description | Last updated | UID |
| --- | --- | --- | --- |
| **COVID19 - Tested, tests with PCR and positivity rate by subnational level this year** || 2020-10-05 | jTGq07MlmMp |

<h1 id="#maps"> Maps</h1>

| Name | Description | Last updated | UID |
| --- | --- | --- | --- |
| **COVID19 - Cumulative confirmed cases by subnational** || 2020-10-05 | AwrThZVBW5g |

### Map views

| Parent map name | Parent map UID | Last updated | UID |
| --- | --- | --- | --- |
| **COVID19 - Cumulative confirmed cases by subnational** | AwrThZVBW5g | 2020-10-05 | BigUFwCduUF |
| **COVID19 - Cumulative confirmed cases by subnational** | AwrThZVBW5g | 2020-10-05 | y9n0wxeewlR |

<h1 id="#userGroups"> User Groups</h1>

| Name | Last updated | UID |
| --- | --- | --- |
| **COVID19 access** | 2020-04-24 | DoYehxUvmwT |
| **COVID19 admin** | 2020-09-21 | w4iJeNKy9br |

<h1 id="#users">Users</h1>

| Username | Last updated | UID |
| --- | --- | --- |
| **covid19** | 2020-10-12 | F0YhCM0Pi73 |
```

```