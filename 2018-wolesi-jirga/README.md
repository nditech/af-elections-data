# 2018 Wolesi Jirga

## Data & Sources

### Voter Registration Data
**Source**: http://www.iec.org.af/pdf/vr-list-1397/

Processing: 
1. Extracted voter registration data as CSV from PDF using [Tabula](https://tabula.technology/)
2. Cross-referenced Dari polling center/district name with [IEC's Dari polling center list](http://www.iec.org.af/pdf/pclist-2018/allpc1397.pdf) to add polling center/district id to each row
3. Looked up id in [IEC's English polling center list](http://www.iec.org.af/pdf/pclist-2018/allpc1397-en.pdf) to add polling center/district name to each row


### Observer data
**Source:** [NDI Data](https://docs.google.com/spreadsheets/d/1N0_16dQyz17xitYTrGjQEMaEeLm4MgZH57eMBFSehN8/edit?usp=sharing)\
**Processing:** Summed each organizations' counts of observers at province polling centers and stations\
**Columns:**\
`| provinceId | provinceName | Total | Men | Women | totalPollingCenters | totalCoveredPollingStations | Women Polling Stations |`

Where men = male observers, women = women observers, and polling station genders = sex-segregated polling stations
