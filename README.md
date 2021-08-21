### Análise de Dados com Python

#### Biblioteca Pandas

Projeto desenvolvido para estudo de análise de dados utilizando a linguagem Python e a biblioteca Pandas durante o Bootcamp Banco Carrefour Data Engineer na plataforma Digital Innovation One.



Para realizar a atividade foi utilizado o Google Colab: https://colab.research.google.com/ 

O projeto contém uma pasta com os datasest utilizados para aprendizado.



##### Introdução a Biblioteca Pandas

Neste arquivo estão informações básicas de como utilizar a biblioteca Pandas.

Para importar o dataset nesse arquivo optei por utilizar o menu lateral do Google Colab, clicando sobre o ícone de uma pasta e em seguida fazendo o upload do arquivo clicando sobre o ícone com o desenho de uma folha de papel com uma setinha em seu interior.

Ao clicar sobre o ícone surgirá uma nova tela para escolher o dataset que será utilizado.

Para a utilização do dataset foi digitada a seguinte linha de código:

```
df = pd.read_csv("/Gapminder.csv", error_bad_lines=False, sep=";" )
```

error_bad_lines=False auxilia no carregamento evitando algum possível erro em alguma linha do dataset.

sep="; " indica que o separador de dados do dataset será ponto e vírgula.

Cada execução no arquivo possui comentários para auxiliar no entendimento.



##### Trabalhando com Planilhas Excel

Foram utilizadas as bibliotecas Panda e Matplotlib

Para importar o dataset nesse arquivo optei por utilizar o menu lateral do Google Colab, clicando sobre o ícone de uma pasta e em seguida fazendo o upload do arquivo clicando sobre o ícone com o desenho de uma folha de papel com uma setinha em seu interior.

Ao clicar sobre o ícone surgirá uma nova tela para escolher o dataset que será utilizado.

Para a utilização das planilhas foram digitadas as seguintes linhas de códigos.

```
#Leitura dos arquivos
df1 = pd.read_excel("Aracaju.xlsx")
df2 = pd.read_excel("Fortaleza.xlsx")
df3 = pd.read_excel("Natal.xlsx")
df4 = pd.read_excel("Recife.xlsx")
df5 = pd.read_excel("Salvador.xlsx")
```

Cada execução no arquivo possui comentários para auxiliar no entendimento.

Nesse arquivo há exemplos de análise com datas e visualização gráfica.



### Análise Exploratória

Foram utilizadas as bibliotecas Panda, Matplotlib (estilo seaborn) e math.

Para importar o dataset nesse arquivo foi utilizado o seguinte código:

```
#Upload do arquivo
from google.colab import files
arq = files.upload()
```

Cada execução no arquivo possui comentários para auxiliar no entendimento.

Nesse arquivo há exemplos de análise com datas e visualização gráfica.



qualquer dúvida podem me contatar através do meu Linkedin [linkedin.com/in/sandro-marcos-campos-910294106](https://www.linkedin.com/in/sandro-marcos-campos-910294106)

