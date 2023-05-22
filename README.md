# New Estonian NER dataset

The dataset is a collection of Estonian news and social media texts annotated with named entities. 

## Dataset statistics

The dataset is divided into training, development and test sets. The annotations can be hierarchical, meaning that there can be one named entity inside another. The maximum number of levels in the hierarchical annotations is three. 

|                 | Train  | Dev   | Test  | Total  |
|-----------------|--------|-------|-------|--------|
| Documents       | 78     | 16    | 15    | 109    |
| Sentences       | 7001   | 882   | 890   | 8773   |
| Tokens          | 111858 | 13130 | 14686 | 139674 |
|1-level entities	| 7480	 | 497	 | 938	 | 8915   |
|2-level entities	| 571    | 44	   | 59	   | 674    |
|3-level entities	| 27	   | 0	   | 1	   | 28     |

## Annotated entities

The dataset is annotated with the following entities: 
* PER - person names
*	GPE - geopolitical entities
* LOC - geographical locations
* ORG - organizations
* PROD - products, things, works of art
* EVENT - events
* DATE - dates
* TIME - times
* TITLE - titles and professions
* MONEY - monetary expressions
* PERCENT - percentages

### Level 1 entities

|         | Train | Dev | Test  | Total |
|---------|-------|-----|-------|-------|
| PER	    | 2601	| 109	| 299	  | 3009  |
| ORG	    | 1177	| 85	| 150	  | 1412  | 
| LOC	    | 449	  | 31	| 35	  | 515   |
| GPE	    | 1253	| 129	| 231	  | 1613  |
| TITLE   | 702	  | 19 	| 59	  | 772   |
| PROD	  | 624	  | 60	| 117	  | 801   |
| EVENT	  | 230	  | 15	| 26	  | 271   |
| DATE	  | 746	  | 64	| 77	  | 887   |
| TIME	  | 103	  | 6	  | 6	    | 115   |
| PERCENT	| 75	  | 11	| 1	  | 87    |
| MONEY	  | 118	  | 12 	| 1	  | 131   |
| Total   | 8078	| 541	| 994   | 9613  |

### Level 2 entities

|         | Train | Dev | Test  | Total |
|---------|-------|-----|-------|-------|
| PER	    | 108   | 1	  | 14	  | 123   |
| ORG	    | 92	  | 8	  | 6	    | 106   |
| LOC	    | 25	  | 1 	| 0	    | 26    |
| GPE	    | 379	  | 35	| 42	  | 456   |
| TITLE	  | 3	    | 0	  | 0	    | 3     |
| PROD    | 4	    | 0	  | 0	    | 4     |
| EVENT	  | 1	    | 0	  | 0	    | 1     |
| DATE	  | 10	  | 0	  | 0	    | 10    |
| TIME	  | 0	    | 0	  | 0     | 0     |
| PERCENT	| 0	    | 0	  | 0	    | 0     |
| MONEY   | 0   	| 0	  | 0	    | 0     |
| Total	  | 622	  | 45	| 62	  | 729   |


### Level 3 entities

|         | Train | Dev | Test  | Total |
|---------|-------|-----|-------|-------|
| PER	    | 1     | 0	  | 0	    | 1     |
| ORG	    | 0	    | 0	  | 0	    | 0     |
| LOC	    | 1	    | 0 	| 0	    | 1     |
| GPE	    | 25	  | 0	  | 1	    | 26    |
| TITLE	  | 0	    | 0	  | 0	    | 0     |
| PROD    | 0	    | 0	  | 0	    | 0     |
| EVENT	  | 0	    | 0	  | 0	    | 0     |
| DATE	  | 0	    | 0	  | 0	    | 0     |
| TIME	  | 0	    | 0	  | 0     | 0     |
| PERCENT	| 0	    | 0	  | 0	    | 0     |
| MONEY   | 0   	| 0	  | 0	    | 0     |
| Total	  | 27	  | 0	  | 1	    | 28    |


Shield: [![CC BY 4.0][cc-by-shield]][cc-by]

This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg


