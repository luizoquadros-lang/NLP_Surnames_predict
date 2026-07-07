# NLP_Surnames_generator

A Natural Language Processing (NLP) project that explores character-based language models for surname generation in Portuguese and Spanish.

This repository contains the source code and datasets used to train and evaluate two independent language models:

    ex2_es_model – a model trained on the Spanish language dataset available in this repository.

    ex2_pt_model – a model trained on the Portuguese language dataset also available here.

These models were trained to generate surnames in their respective training languages.
Additionally, they were tested interchangeably in order to evaluate how well they could generate words in a language on which they were not trained.

# Portuguese Dataset (sobrenomes_pt_br)

The dataset was created by manually extracting data from: https://censo2022.ibge.gov.br/nomes/rankings
This is an official Brazilian government website containing 2022 census data, which ranks names and surnames by frequency across national statistics.
The dataset contains the 5,000 most frequent surnames in the ranking.
All entries were converted to lowercase, and Portuguese special characters such as ç, ã, é, ê, õ, etc., were preserved.

# Spanish Dataset (apellidos_es)

This dataset was created by manually extracting data from: https://www.ine.es/apellidos/inicio.do
This is an official Spanish government website maintained by the Instituto Nacional de Estadística (INE).
The dataset contains the 5,000 most frequent surnames in the ranking.
All entries were converted to lowercase, while the character ñ and accent marks (´) were preserved.


