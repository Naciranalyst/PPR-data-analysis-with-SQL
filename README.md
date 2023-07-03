# PPR-data-analysis-with-SQL
Insight of Peste des petits ruminants disease worldwide. Distribution, vaccination coverage,  mortality, morbidity and fatality rates, affected species and animal categories were calculated and determined.

###### * In this project, two datsets were used:
1. First dataset: Peste des petits ruminants disease worldwide
source: https://wahis.woah.org/#/dashboards/qd-dashboard  excracted in 26/06/2023. It contains  11 785 rows and 17 columns.
​
2. Second dataset: small ruminants number etracted from https://www.fao.org/livestock-systems/global-distributions/en/ . Two tables of number of sheep and goats per country.
​
**Definition of data: dataset of notified foci, cases and outbreaks of PPR from 2005-2023 worldwide. Exctracted from
 the database WAHIS of the World organisation for Animal Health (OIE).

**Peste des Petits Ruminants (PPR), also known as sheep and goat plague, is a highly contagious animal disease 
affecting domestic and wild small ruminants. It is caused by a virus belonging to the genus Morbillivirus,
 family Paramixoviridae. Once newly introduced, the virus can infect up to 90 percent of an animal heard, 
and the disease kills anywhere up to 70 percent of infected animals. The PPR virus does not infect humans(FAO, 2023).

​
** Steps of analysing the data
​
1) Data imported in excel format
2) Cleaning: * converting numbers from french to english by converting comma to point 
              * replacing empty cells and - by NA
2) Exportation to microsofot server sql
3) 
** The table of PPR called [PPR_worldwide].[dbo].[PPRW]
   
** The table of goat number called [PPR_worldwide].[dbo].[goat]

** The table of sheep number called [PPR_worldwide].[dbo].[sheep]

   In the text file named SQL.PPR, I have run some queries to get relevant information aboiut the disease 
