# NLP_Surnames_generator
This Repository is for the assignment 2 of NLP classes. 
Portuguese dataset and python file are available here.

The Portuguese dataset ("sobrenomes_pt_br"):
It was createb by extracting manually the data from https://censo2022.ibge.gov.br/nomes/rankings.
That is an official Brazilian`s government website containing census data from 2022, ranking names and surnames by frequency across national statistics.
It contains the most frequent 5000 surnames in the ranking. 
All entries were lowercased and the special portuguese language characters such as "ç", "ã", "é", "ê", "õ"... were preserved.

The Spanish dataset ("apellidos_es"): It was created extracting manually the data from https://www.ine.es/apellidos/inicio.do
It is an official Spanish' government website, Instituto Nacional de Estadistica.
It contains the most frequent 5000 surnames in the ranking.
All entries were lowercased. The character "ñ" was preserved. The acentuation mark "´" was ignored, since the official source also ignored it.
