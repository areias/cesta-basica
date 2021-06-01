

# Criando um Índice de Cesta Basica de forma Colaborativa 

O íntuito deste projeto é seguir o espirito da [metodologia definida pelo DIEESE](https://www.dieese.org.br/metodologia/metodologiaCestaBasica2016.pdf) para o calculo do custo médio da cesta básica de alimentos usando dados coletados de forma automatizada da internet usando Python. 

Vale mencionar que o [mais recente relatorio mensal do DIEESE](https://www.dieese.org.br/analisecestabasica/2021/202103cestabasica.pdf) menciona que:

>O tempo  médio  necessário  para  adquirir  os  produtos  da  cesta,  em março,ficou  em 109 horas e 18 minutos,menor do que em fevereiro,quando foi de 110 horas e 22 minutos.


Vamos a trabalhar no google Colaboratory assim não será necessário instalar Python no computador.

Vamos aprender a utilizar os seguintes pacotes Python:

* [requests](https://docs.python-requests.org/en/master/user/quickstart/)
* urllib
* [Beautiful Soup](https://beautiful-soup-4.readthedocs.io/en/latest/#quick-start)
* json
* [pandas](https://pandas.pydata.org/docs/getting_started/tutorials.html)
* numpy
* [re](https://docs.python.org/3/howto/regex.html)

Não esquecer de o recurso mais importante de todos, [Stackoverflow!](https://stackoverflow.com/questions/tagged/data-science)

E como bonus, vamos aprender o workflow de como contribuir a um projeto usando Github pela webpage, sem a necessidade de trabalhar na linha de comando.

Aqui seguem instruções de como contribuir:


1. Criar conta no Github.

2. Dar um **Fork** no repositório cesta-basica para criar uma copia do repositorio na tua conta Github.

3. Abrir o arquivo cesta-basica.ipynb no Google colab.

4. Navegar ate o fim do documento e addicionar um titulo com o produto que vais escolher em um markdown cell, por exemplo: 

`## 2. Bananas`

5. Scrape e processar os dados do seu produto escolhido da forma que temos feito ate agora para calcular o preço médio do produto, comforme definido pela nota metodológica. Por exemplo, para Bananas e o preço medio de uma duzia.

Faça tambem um histogram dos precos.

6. Load os datos coletados até agora direto do repositorio central em um dataframe para poder append os seus e salvar com o mesmo nome.

```
df=pd.read_csv("https://raw.githubusercontent.com/areias/cesta-basica/main/data/cesta-basica.csv")   
df=df.append(teu_df)  
df.to_csv("cesta-basica.csv")  
```

7. Uma vez satisfeita com o seu codigo escolher no menu do Colab notebook **File > Save Copy to Github.**

8. Como os arquivos salvos dentro do Google colab sao efémeros e desaparecem quando o runtime desativar, faça o upload da versão atualizada do cesta-basica.csv na pasta correspondente do teu repositorio Github.

9. Finalmente, tendo salvo tanto teu cesta_basica.ipynb modificado e o cesta-basica.csv atualizado, pode fazer o **Pull request** para que eu integre as suas contribuicoes ao repositorio central!

10. Sempre que for começar a trabalhar na sua versão de cesta_basica.ipynb, vale checar se houve mudanças no repositorio central e integra-las ao seu repositorio, clicando no botão **Fetch upstream**. Assim vc estará trabalhando com a versão mais recente do código. 

Qualquer dúvida entre em contato pelo canal Slack ou WhatsApp.






