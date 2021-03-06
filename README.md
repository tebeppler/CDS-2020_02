# CDS-2020_02
Requisito parcial para disciplina de período especial.
Estudantes:
Mariane R. S. Cassenote; 
Tamy Emily Beppler

Dataset (fake_job_postings.csv):

------ [Real or Fake] Fake JobPosting Prediction ------


https://www.kaggle.com/shivamb/real-or-fake-fake-jobposting-prediction


	18K job descriptions out of which about 800 are fake

Data:

	textual information and meta-information about the jobs.
	
The dataset can be used to answer the following questions:

    1- Create a classification model that uses text data features and meta-features and predict which job description are fraudulent or real.
    2- Identify key traits/features (words, entities, phrases) of job descriptions which are fraudulent in nature.
    3- Run a contextual embedding model to identify the most similar job descriptions.
    4- Perform Exploratory Data Analysis on the dataset to identify interesting insights from this dataset.
    
____________________________________________________________########____________________________________________________________    
Prática 3:
1) Que tipos de dados você tem, majoritariamente (atributos numéricos, textuais)?

O dataset possui 18 colunas, sendo 1 referente ao id da amostra, 4 colunas de atributos numéricos e 13 colunas de atributos textuais. 
As colunas são detalhadas abaixo:

Id:

	job_id

Numéricos:

	- telecommuting
	- has_company_logo
	- has_questions
	- fraudulent

Textuais:

	- title
	- location
	- department
	- salary_range
	- company_profile
	- description
	- requirements
	- benefits
	- employment_type
	- required_experience
	- required_education
	- industry
	- function

2) Qual seu objetivo com esse dataset?


O objetivo da análise do dataset é identificar anúncios de vagas de emprego fraudulentas, assim como as características comuns nesses anúncios maliciosos.


3) Seu dataset é rotulado de que maneira?


A coluna "fraudulent" identifica anúncios maliciosos como 1 e não-maliciosos como 0.


4) Como é a distribuição dos dados do dataset?


Esse dataset é altamente desbalanceado, o que torna difícil a tarefa de classificação.
Do total de 17880 amostras, temos 17014 anúncios reais e 866 anúncios maliciosos.
Também temos diversas amostras com valores nulos que terão de ser tratadas adequadamente:


	coluna          soma de NaNs
	job_id                     0
	title                      0
	location                 346
	department             11547
	salary_range           15012
	company_profile         3308
	description                1
	requirements            2695
	benefits                7210
	telecommuting              0
	has_company_logo           0
	has_questions              0
	employment_type         3471
	required_experience     7050
	required_education      8105
	industry                4903
	function                6455
	fraudulent                 0

5) Quais colunas/atributos você julga ser interessante manter e remover? Por quê?

Através da análise dos dados, optou-se por excluir a coluna job_id, que se refere somente ao número da amostra e a coluna salary_range, pois não contribui significativamente para a análise dos dados e por possuir muitas ocorrências de valores nulos (15.012 nulos entre 17.880).

Arquivos:

	Trabalho(w2v).ipynb    - Código com relatório após executar o word2vec para extração de atributos textuais
	Trabalho(w2v).py       - mesmo código
	Trabalho(w2v).pdf      - versão em pdf
	Trabalho-tfidf.ipynb   - Código com relatório após executar o TF-IDF para extração de atributos textuais
	trabalhp-tfidf.py      - mesmo código
	Trabalho-tfidf.pdf     - versão em pdf
	fake_job_postings.zip  - Dataset
	
Diretórios:

	Resultados-TF-IDF	- Imagens resultantes da execução do algoritmo usando TF-IDF
	Resultados-Word2vec	- Imagens resultantes da execução do algoritmo usando Word2Vec
