# Modelando e Visualizando Dados de Email
Tarefa final da Trilha de Honras da minha especialização ''Python For Everybody'' da Universidade de Michigan. Nesse projeto, trabalho para recuperar e analisar dados de e-mails do projeto de código open-source Sakai.
Além disso, o projeto inclui duas visualizações essenciais: uma nuvem de palavras para visualizar a distribuição de frequência e uma linha do tempo que mostra como os dados se modificam ao longo do tempo.
Na construção do projeto, são utilizadas tecnologias como Python, SQLite e Web Scraping. Certificado de Conclusão (Com Honras): https://www.coursera.org/account/accomplishments/certificate/ELZCSB9P93R8

![GmaneMap](https://github.com/jvictorlopez/ModelandoEVisualizandoDadosDeEmail/assets/124679867/defda317-8c4b-4efa-b812-ff561a68eea0)


# Passo a Passo
1. Seguindo as instruções do mapa demonstrado acima, executo primeiramente o código gmane.py, e peço que o programa processe 1000 mensagens. O processo leva cerca de 10 minutos. Após isso, posso visualizar content.sqlite no DB Browser (Visualizador de SQLite).

![gmane.py](https://github.com/jvictorlopez/ModelandoEVisualizandoDadosDeEmail/assets/124679867/ac062e6e-ade7-43f8-a64f-9a3e7f0989bc)
![Visualizando'content.sqlite'](https://github.com/jvictorlopez/ModelandoEVisualizandoDadosDeEmail/assets/124679867/963c7743-6a22-44f7-860d-6d139a5107c2)


2. Agora, executo gmodel.py, produzindo o Banco de Dados index.sqlite. Essa etapa é de suma importância, pois recolhe os dados do primeiro banco de dados e faz a limpeza, mantendo apenas os dados necessários para trabalhar. Logo após, abro o novo banco de dados.

![gmodel.py](https://github.com/jvictorlopez/ModelandoEVisualizandoDadosDeEmail/assets/124679867/5bd215b1-1e32-4d3c-b099-b44664c68035)
![Visualizando'index.sqlite'](https://github.com/jvictorlopez/ModelandoEVisualizandoDadosDeEmail/assets/124679867/1f2f13b6-7b99-465c-b428-bb100eb33407)


3. Executo o código gbasic.py, requisitando o retorno dos Top 10 emails e organizações com mais enviados.

![gbasic.py](https://github.com/jvictorlopez/ModelandoEVisualizandoDadosDeEmail/assets/124679867/1f070a06-c5dc-4f0a-a78a-ce2a9e53bf7f)


4. Produzo a primeira visualização de dados ao executar gwords.htm, obtendo a nuvem de palavras mais usadas nos e-mails.

![VisualizaçãoEmNuvens](https://github.com/jvictorlopez/ModelandoEVisualizandoDadosDeEmail/assets/124679867/512838d6-4660-4b45-882e-dacf506f98fe)


5. Finalmente, executo gline.py, e em seguida, gline.htm, visualizando as mensagens recebidas por organização, em função de meses. Com o processamento de 1000 mensagens, as linhas são curtas. Caso tivese processado números significativamente maiores (ex: 50k),
a visualização seria proporcionalmente mais longeva e densa em dados.


![VisualizaçãoEmLinhas](https://github.com/jvictorlopez/ModelandoEVisualizandoDadosDeEmail/assets/124679867/bb3b2e72-cf76-415a-8607-5d0a17f2c076)







