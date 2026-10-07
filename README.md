# 🏎️ Porsche Sales Dashboard

Dashboard interativa desenvolvida como parte de um desafio prático da **DIO**, com o objetivo de transformar uma base de vendas da Porsche em uma experiência visual para análise de dados publicada na web.

O projeto utiliza **HTML, CSS e JavaScript** em um único arquivo, permitindo explorar os dados por meio de indicadores, gráficos e filtros interativos.

## 🎯 Objetivo

O objetivo foi transformar uma planilha contendo 100 registros de vendas da Porsche em uma dashboard capaz de responder perguntas de negócio de forma visual e interativa.

Mais do que simplesmente apresentar gráficos, a proposta foi criar uma narrativa baseada nos dados:

**O que vende → O que gera receita → Como os clientes pagam.**

## 📊 Perguntas de negócio

### 1. Quais modelos Porsche são mais vendidos?

Essa análise permite identificar quais veículos possuem maior volume de vendas dentro da base.

A informação é apresentada por meio de um gráfico de barras com o ranking dos modelos.

### 2. Quais modelos geram mais receita?

Nem sempre o modelo com maior quantidade de vendas é aquele que gera o maior faturamento.

Por isso, a segunda análise compara a receita gerada pelos diferentes modelos Porsche.

### 3. Como os clientes pagam?

A terceira análise busca entender a distribuição dos métodos de pagamento utilizados nas vendas.

O gráfico permite visualizar a participação de opções como transferência bancária, cartão de crédito, financiamento e pagamento em dinheiro.

## 📈 Indicadores

A dashboard apresenta quatro KPIs principais:

- Total de vendas;
- Receita total;
- Ticket médio;
- Modelo mais vendido.

Todos os indicadores são recalculados automaticamente quando um filtro é aplicado.

## 🔎 Filtros interativos

Foram implementados filtros para:

- Modelo Porsche;
- Model Year;
- Estado;
- Cidade;
- Método de pagamento.

Os filtros trabalham de maneira integrada e atualizam os indicadores e gráficos da dashboard.

Também foi incluída uma opção para limpar os filtros e retornar à visão geral dos dados.

## 🧹 Tratamento da base

A base utilizada contém 100 registros e apresenta os campos originais juntamente com suas respectivas versões sanitizadas.

Para a construção da dashboard, foram priorizadas as colunas sanitizadas:

- `SaleDateSanitized`
- `PorscheModelSanitized`
- `ModelYearSanitized`
- `SalesPriceSanitized`
- `VehicleMileageSanitized`
- `PayMethodSanitized`
- `CitySanitized`
- `StateSanitized`
- `DeliveryStatusSanitized`

Durante a análise da base, foram encontrados registros `INVALID` no campo de data sanitizada.

Como as perguntas de negócio escolhidas não dependiam diretamente da data da venda, o **Model Year** foi utilizado como um dos principais filtros temporais da dashboard.

Os campos numéricos também foram preparados para permitir cálculos de receita, ticket médio e demais indicadores.

## 🤖 Utilização de Inteligência Artificial

O **ChatGPT** foi utilizado como apoio durante o desenvolvimento do projeto.

O processo não se limitou à geração inicial da dashboard. A solução foi refinada por meio de linguagem natural, avaliando o resultado e solicitando alterações de estrutura, visualização e experiência de uso.

Entre os principais refinamentos realizados estiveram:

- definição das perguntas de negócio;
- escolha dos KPIs;
- definição dos filtros;
- criação dos gráficos;
- melhoria da interatividade;
- reorganização da apresentação;
- adoção de uma identidade visual inspirada na Porsche;
- criação de uma capa em estilo automotivo premium;
- utilização de fundo escuro e elementos de alto contraste.

## 💬 Prompt utilizado

Um dos prompts utilizados durante o desenvolvimento foi:

> Crie uma dashboard interativa em HTML utilizando a base sanitizada de vendas da Porsche.
>
> A dashboard deve possuir filtros por modelo Porsche, Model Year, cidade, estado e método de pagamento.
>
> Inclua indicadores de total de vendas, receita total, ticket médio e modelo mais vendido.
>
> Responda visualmente às seguintes perguntas de negócio:
>
> 1. Quais modelos Porsche são mais vendidos?
> 2. Quais modelos geram mais receita?
> 3. Quais métodos de pagamento são mais utilizados?
>
> Todos os filtros devem atualizar os indicadores e gráficos automaticamente.
>
> Utilize uma identidade visual premium inspirada na Porsche, com fundo preto, cards em tons escuros, tipografia moderna, detalhes em vermelho e uma imagem de um Porsche em destaque na capa.
>
> O resultado deve ser responsivo, visualmente semelhante a uma dashboard profissional e funcionar como um único arquivo HTML.

## 🎨 Evolução do projeto

A primeira versão priorizava a organização dos dados e a funcionalidade dos gráficos.

Após analisar o resultado, o prompt foi refinado para melhorar principalmente a experiência visual.

A versão final recebeu uma interface escura inspirada na identidade da Porsche, uma área de abertura com destaque para o veículo, cards de indicadores e uma apresentação mais próxima de dashboards corporativas e ferramentas de Business Intelligence.

Esse processo mostrou a importância de **iterar sobre o resultado gerado pela IA**, em vez de considerar a primeira resposta como produto final.

## 🛠️ Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript
- Visualização de dados
- Inteligência Artificial Generativa
- Git
- GitHub
- GitHub Pages

## 📷 Dashboard

### Visão geral

> Inserir aqui o print da dashboard.

### Exemplo com filtros aplicados

> Inserir aqui um print da dashboard com um ou mais filtros selecionados.

## 🌐 Dashboard publicada

Acesse a versão online:

**[Inserir aqui o link do GitHub Pages]**

## 📁 Repositório

O código-fonte e os arquivos utilizados no desenvolvimento deste projeto estão disponíveis neste repositório.

---

### 👩‍💻 Autora

**Ingrid Gabriela Alves Ferreira**

Projeto desenvolvido para fins educacionais e de portfólio durante os estudos em tecnologia e análise de dados.
