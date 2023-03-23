# estatistica-parte-1

![Badge em Desenvolvimento](http://img.shields.io/static/v1?label=STATUS&message=FINALIZADO&color=GREEN&style=for-the-badge)

![Badge code size](https://img.shields.io/github/languages/code-size/fab-souza/estatistica-parte-1)
![Badge de Atualização](https://img.shields.io/github/last-commit/fab-souza/estatistica-parte-1)

| :placard: Vitrine.Dev |    |
| -------------  | --- |
| :sparkles: Nome        | **Estatística com Python parte 1: frequências e medidas**
| :label: Tecnologias | python
| :rocket: URL         | Notebook no [Kaggle](https://www.kaggle.com/code/fabianadesouza/estatistica-parte-1)
| :fire: Desafio     | Conteúdo do 3º [curso](https://www.alura.com.br/curso-online-estatistica-distribuicoes-e-medidas) da formação [Data Science](https://www.alura.com.br/formacao-data-science)

![](https://user-images.githubusercontent.com/67301805/222568832-1c2ad53b-1ce2-4297-ad48-cfa5a6b8a9dc.jpg#vitrinedev)

# Sobre o curso 📚

Este é o terceiro curso da formação Data Science, na @Alura. Sim, você não leu errado. O último projeto era sobre o primeiro e este é sobre o terceiro. Eu decidi pular o segundo curso, porque ele está presente tanto nesta formação, quanto na formação de [Python para Data Science](https://www.alura.com.br/formacao-python-data-science), que é um curso que já elaborei um projeto para pôr em prática o que aprendi e não vi vantagem em criar um novo.

Se quiser conferir, [este](https://github.com/fab-souza/python-pandas-tratando-dados) é o projeto que criei sobre o curso [Python Pandas](https://www.alura.com.br/curso-online-introducao-python-pandas).

Voltando a falar sobre este curso, ele é o primeiro dedicado exclusivamente a estatística, com foco em apresentar ao aluno conceitos sobre frequência e medidas, ao fazer uma análise descritiva do dataset da [Pesquisa Nacional por Amostra de Domicílio](https://www.ibge.gov.br/estatisticas/sociais/populacao/19897-sintese-de-indicadores-pnad2.html?=&t=microdados), que são provenientes do IBGE. Eu já havia estudado estatística durante a graduação, mas quis fazer o curso para retomar e reforçar conceitos.

A base de dados utilizada continha informações sobre as seguintes variáveis:

![image](https://user-images.githubusercontent.com/67301805/222787934-a44f74a3-452f-460b-b2ff-1494263c7651.png)

Após a apresentação das variáveis e observações sobre o tratamento previamente realizado no dataset, por exemplo a eliminação dos registros que não haviam informação sobre a renda e adição da variável **Altura**, o instrutor [Rodrigo Dias](https://www.linkedin.com/in/rodrigo-fernando-dias-118181120/) mostrou como são classificados os tipos das variáveis, a fazer o cálculo da distribuição de frequência, identificar as medidas de tendência, o que são as medidas separatrizes e medidas de dispersão.

![image](https://user-images.githubusercontent.com/67301805/224794909-759a16a5-3ecf-4810-a799-bbc0cdf00c46.png)

![image](https://user-images.githubusercontent.com/67301805/224795179-cd09be6b-44a1-4f30-aa52-c62f2021b8ec.png)

**Obs.:** Não houve uma abordagem mais aprofundada, pois na plataforma há uma formação inteira dedicada à [estatística](https://www.alura.com.br/formacao-estatistica-python), em que este curso é o primeiro deles. 

# Minha prática 👩🏻‍💻

Diante os tópicos apresentados no curso, eu decidi trabalhar com um dataset que já utilizei em um projeto anterior, referente aos empreendimentos de geração de energia elétrica presentes no país. Ele foi desenvolvido de forma independente, ou seja, eu não estava seguindo nenhum roteiro de curso, bootcamp ou imersão. Eu fiz o projeto, porque eu queria saber até onde poderia chegar e por em prática o que havia aprendido até então. 

Escolhi trabalhar com os dados da [Agência Nacional de Energia Elétrica](https://dadosabertos.aneel.gov.br/dataset/siga-sistema-de-informacoes-de-geracao-da-aneel), por causa da minha graduação na área e porque eu queria sanar uma dúvida que eu tinha sobre a geração de energia renovável. Caso tenha curiosidade, este é o link para o [meu projeto](https://github.com/fab-souza/meu-projeto-energia).

Na época, eu abordei mais a visualização do que a análise descritiva, porque os resultados foram tão discrepantes, que não vi a necessidade de apresentar resultados estatísticos.

![image](https://user-images.githubusercontent.com/67301805/224802757-f1a04e9a-3e1a-4ca0-924a-a5430bf114ce.png)

Ao utilizar este dataset, eu não teria à disposição todos os tipos de dados (qualitativa ordinal e nominal, quantitativa discreta e contínua), mas desenvolver este projeto me possibilitou mostrar as informações de outra forma e dados que não havia explorado anteriormente. Por exemplo, entre os 24.439 registros no dataset, um pouco mais do que 89% deles encontra-se em operação, enquanto as demais usinas estão em fase de construção, ou ainda não saíram do papel.

![image](https://user-images.githubusercontent.com/67301805/225739406-64805bec-feaf-492b-979d-7505864d3e10.png)

Entre os *tipos de combustível* utilizados (Biomassa, Eólica, Fóssil, Hídrica, Nuclear e Solar), temos a eólica e solar com os maiores números de usinas tanto em *fase de construção*, quanto em *construção não iniciada*. Esta informação me deixou contente, pois mostra que estas fontes estão conseguindo uma maior fatia de participação na Matriz Elétrica brasileira, e que usinas de fontes não renováveis possuem um dos menores números nas duas fases de construção, 26 usinas em fase de construção e 15 usinas que ainda não tiveram sua construção iniciada. 

![image](https://user-images.githubusercontent.com/67301805/225739516-fbcd3905-42e7-467d-a41c-75614db922ed.png)

Durante o curso, através da renda dos entrevistados, foi possível determinar a classe social que eles se enquadram e plotar um gráfico de distribuição. No caso deste projeto, eu poderia fazer algo similar ao dividir as usinas hidrelétricas pela potência. Essa divisão já é padronizada pela ANEEL, em que hidrelétricas de até 1 MW de potência instalada são classificadas como **Centrais Geradoras Hidrelétricas**, as que tiverem entre 1,1 MW a 30 MW de potência instalada são denominadas **Pequenas Centrais Hidrelétricas** e as que tiverem potência superior são **Usina Hidrelétrica de Energia**. 

Fonte: [Catálogo de Metadados da ANA](https://metadados.snirh.gov.br/geonetwork/srv/api/records/d0886b5c-f94c-4573-941b-febad5a990f3#:~:text=A%20Ag%C3%AAncia%20Nacional%20de%20Energia,com%20mais%20de%2030%20MW)

### **Detalhe:** 

Potência instalada não é a mesma coisa do que potência outorgada, ou fiscalizada. Mas eu utilizei a classificação ANEEL, porque queria pôr em prática o que aprendi. Caso tenha curiosidade em entender a diferença entre as potências, essa página do [energês](https://energes.com.br/o-que-e-potencia-outorgada-fiscalizada-e-instalada/) trás uma explicação, que até para quem não é da área consegue entender.

Essa divisão já estava presente no dataset, na variável *SigTipoGeracao*, mas eu queria averiguar se as duas classificações seriam compatíveis. Ao fazer a classificação, respeitando as potências que encontrei no site do governo, gerei a seguinte tabela:

![image](https://user-images.githubusercontent.com/67301805/226001714-f5a81a2f-9576-4fda-aeab-5662d4ab469a.png)

Ao conferir com a classificação presente no dateset, encontrei as seguintes informações:

![image](https://user-images.githubusercontent.com/67301805/226001950-f8b84066-e51c-4278-884b-64ea183bc0cb.png)

Eu já esperava que os valores fossem diferentes. Acredito que isso tenha acontecido, porque os mínimos e máximos presentes no dataset, para cada tipo de hidrelétrica, não estão compatíveis com a classificação da ANEEL.

![image](https://user-images.githubusercontent.com/67301805/226403609-6d194fc0-b6c7-45a2-bf6a-a93931b9554f.png)
![image](https://user-images.githubusercontent.com/67301805/226403684-f21309a6-ca67-413f-ac6d-16adb2385427.png)

Para finalizar, verifiquei as medidas de dispersão das usinas eólicas. Escolhi esta fonte, porque ela apresentou um box-plot com menos outliers (com exceção das usinas hídricas e nuclear). 

Criei um dataset composto por estas usinas, classificadas como em *Operação* e adicionei a média da *Potência Outorgada*, o desvio e desvio médio absoluto para calcular a variância e o desvio padrão. Conclui com o uso dos métodos de cada medida de dispersão, fiz a variância de cada tipo de usina e plotei seus box-plot, mostrando que posso trazer a mesma informação de formas diferentes.

![image](https://user-images.githubusercontent.com/67301805/226986549-ea82f74a-f270-490b-afc3-798d24a86b7b.png)
![image](https://user-images.githubusercontent.com/67301805/226986632-5f6eb4d7-7f1a-4e8d-a759-82553bdf853b.png)


# Conclusão  🏁

Fazer a exploração descritiva, me proporcionou identificar algumas inconsistências que não tinha reparado, por exemplo:

- no projeto anterior, trabalhei apenas com as usinas classificadas em fase de *Operação*. Neste projeto, inicialmente, eu não fiz esta delimitação e vi que algumas usinas classificadas como *Construção não iniciada* tinham datas inusitadas na variável *DatEntradaOperacao*. 

![image](https://user-images.githubusercontent.com/67301805/226005483-a27739c7-c7ce-4567-b760-d01d5e7c10ad.png)

### Obs.:
Eu não quis ir ‘muito além’ do que foi passado no curso, porque ainda há mais conteúdo de estatística que quero elaborar um projeto.

---

Muito obrigada por chegar até aqui e até a próxima 🤗


## Ferramentas utilizadas 🧰 
<p> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> 
    <a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="pandas" width="40" height="40"/>
    <a href="https://numpy.org/" target="_blank" rel="noreferrer"> <img src="https://numpy.org/images/logo.svg" alt="numpy" width="40" height="40"/>
    <a href="https://seaborn.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" alt="seaborn" width="40" height="40"/>
    </p>
