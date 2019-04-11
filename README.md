

# Data Science Challenge #

Esse desafio tem o objetivo de testar algumas habilidades em Data Science.

## O desafio

O desafio consiste em desenvolver a solução para três problemas de Data Science, Regressão, Classificação e Clusterização.

### REGRESSÃO

Usando uma lista de (cliente, loja, valor da compra) para treinar seu algoritmo, predizer o valor das próximas compras de um cliente em uma loja. 

**INPUT** cliente, loja 

**OUTPUT** valor previsto para a compra 

Seu algoritmo deve estar preparado para receber uma lista de clientes, loja para teste. 

Base para treinamento: [base_regressao.csv](bases/base_regressao.csv) 
Descrição das colunas: 
- cliente: número inteiro identificador do cliente 
- loja: número inteiro identificador da loja 
- valor: número real com o valor da compra 


### CLASSIFICAÇÃO

Usando uma lista com data de nascimento, sexo e um label de classificação de persona para treinamento, seu algoritmo deve responder a novas entradas com a persona correspondente 

**INPUT** data de nascimento, sexo 

**OUTPUT** persona 

Seu algoritmo deve estar preparado para receber uma lista de data de nascimento e sexo para teste.

Base para treinamento: [base_classificacao.csv](bases/base_classificacao.csv) 
Descrição das colunas: 
- dt_nascimento: data no formato YYYY-MM-DD 
- sexo: letra representando o sexo do cliente 
- persona: número inteiro representando a persona que o cliente se encaixa 


### CLUSTERIZAÇÃO

Usando uma lista com o cliente, frequência de uso do cartão, valor médio e número de compras, gerar uma clusterização para separar os perfis de cliente 

**INPUT** lista com cliente, freq. do uso de cartão, valor médio e num. de compras 

**OUTPUT** lista de cada cliente e seu cluster 

Base para treinamento: [base_clusterizacao.csv](bases/base_clusterizacao.csv) 
Descrição das colunas: 
- cliente: número identificador do cliente 
- %cartao: número inteiro representando a porcentagem de uso do cartão nas compras 
- gasto_medio: número real com a média dos valores de compras 
- qtd_compras: número inteiro com a quantidade de compras feitas 


## Instruções ##

- Crie um arquivo INSTRUCOES.txt com as instruções para replicar e executar sua solução.
- A sua solução deve estar autocontida.
- Assim que concluído o desafio, envie um email para [tecnologia@spotmetrics.com](mailto:tecnologia@spotmetrics.com) intitulado ```Desafio DataScience``` com uma pasta compactada com seus arquivos de solução (caso esteja tendo problemas em anexar o arquivo, pode-se usar um servidor de transferência, como por exemplo o [WeTransfer](https://wetransfer.com/)).


## Considerações Gerais

- Crie um arquivo COMENTARIOS.txt na sua pasta para registrar suas reflexões, decisões, escolhas e os porquês.
- Comente o código.
- Você é livre para definir a modelagem e organização das features a serem implementadas.
- Use ferramentas e bibliotecas open source, documente as decisões e os porquês.
- Todo o projeto deve ser autocontido.
- Deve ser enviado instruções para executar o projeto.
- Lembre-se, não tenha pressa! Iremos avaliar a qualidade da sua solução, mesmo incompleto. Em caso de dúvida, mande um e-mail para [tecnologia@spotmetrics.com](mailto:tecnologia@spotmetrics.com).


## O que será avaliado ##

- Organização do projeto.
- Simplicidade da implementação.
- Modelagem do Problema.
- Você é livre para usar softwares nas soluções, mas soluções que forem implementadas em alguma linguagem terão pontos extras.  
- Em caso de dúvida, envie um email para [tecnologia@spotmetrics.com](mailto:tecnologia@spotmetrics.com).

Boa sorte!
