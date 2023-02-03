# 💻 Projeto de automação web para busca de preços e coleta de links de compra 

<img src="https://cdn.discordapp.com/attachments/965066624556232737/983442947326509098/Captura_de_tela_de_2022-06-06_15-50-28.png">

## 📄 Descrição do projeto:

O projeto foi feito no curso Python Impressionador da Hashtag Treinamentos
<br>
<br>
O projeto consiste em um código que é capaz de navegar na web e coletar o preço e o link de compra dos produtos determinados na base de dados podendo ter um número indeterminado de produtos.
<br>
<br>
Como o bot do selenium é executado em uma nova janela do navegador é possível fazer outras coisas no computador desde que não interfira na janela que foi criada pelo bot.
<br>
<br>
Foram criadas duas funções, uma para cada loja onde serão feitas as buscas, estas funções são encarregadas de buscar, coletar e tratar os dados dos produtos que correspondem com o preço máximo e mínimo determinado pela base de dados, e os que correspondem ao nome do produto da base de dados, por fim as funções retornam listas com tuplas que contém os resultados filtrados.
<br>
<br>
Ao final da execução do código é retornado as listas das funções com os nomes, preços, data e links dos produtos, esta lista é transformada em um dataframe que por sua vez é exportado para sua respectiva pasta de seu respectivo produto.
<br>
<br>
São criadas pastas no executar do programa, uma pasta principal que vai abrigar varias outras pastas que correspondem a cada um dos produtos onde dentro destas são armazenadas as planilhas excel com os nomes,preços,data e links dos seus respectivos produtos.
<br>
<br>
Por fim o programa comprime a pasta principal que foi criada possibilitando o envio por e-mail.




## 🎯 Foi utilizado a linguagem de programação python com as bibliotecas:

- Selenium (Para a automação de uma nova janela do navegador com um bot)
- Pandas (Para manipulação,importação e exportação de Dataframes e planilhas excel)
- Shutil (Para de uma pasta comprimida)
- Path (Para a criação automática de pastas no computador)
- Date (Para fornecer a data do dia em que o código for executado)
- Sleep (Para fazer o código para por tempo determinado)



## 📽 Vídeo demonstrativo:

[![Watch the video](https://cdn.discordapp.com/attachments/965066624556232737/983443621485363250/Captura_de_tela_de_2022-06-06_15-53-25.png)](https://drive.google.com/file/d/1wsCGIYJP0uCYhl9jCK1KRSqmG4rBmqpA/view?usp=sharing)
