

# Como contribuir para Cesta Basica

1. Criar conta no github

2. Dar um "fork" no cesta-basica repository para criar uma copia do repositorio na tua conta

3. Abrir o arquivo cesta-basica.ipynb no Google colab 

4. Navegar ate o fim do documento e addicionar um titulo com o produto que vais escolher em um markdown cell, por exemplo: 

`## 2. Bananas`

5. Scrape e processar os dados do seu produto escolhido da forma que temos feito ate agora para calcular o preco medio do produto, comforme definido pela nota metodologica. Por exemplo, para Bananas e o preco medio de uma duzia.
Faca tambem um histogram dos precos.

6. Load os datos coletados ate agora direto do repositorio central em um dataframe para poder append os seus e salvar com o mesmo nome.

`
df=pd.read_csv("https://raw.githubusercontent.com/areias/cesta-basica/main/data/cesta-basica.csv")   

df=df.append(teu_df)  

df.to_csv("cesta-basica.csv")  
`

7. Uma vez satisfeita com o seu codigo escolher no menu File > Save Copy to Github.

8. Como os arquivos salvos dentro do Google colab sao ephemereos e desaparecem quando o runtime desativar, upload a versao atualizada do cesta-basica.csv na pasta correspondente do teu repositorio github.

9. Finalmente, tendo salvo tanto teu codigo adicionado e o cesta-basica.csv atualizado, pode fazer o "pull request" para que eu integre as suas contribuicoes ao repositorio central!


