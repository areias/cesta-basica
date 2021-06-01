

# Como contribuir para Cesta Basica

Aqui seguem instruções de como contribuir ao projeto de Cesta Básica usando a webpage do Github. 


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






