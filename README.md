# Classificação de Churn - Empresa de Telefonia

## Motivação

Testar meus conhecimentos sobre a resolução de problemas de negócios, análise de dados e aplicação de modelos preditivos, por meio de deste projeto feito sob mentoria no curso Jornada Cientista da Dados, do Let's Data

## Objeto de Estudo 

Um problema muito recorrente para muitas empresas é qual a melhor forma de reter seus clientes. Saber de antemão se um cliente vai cancelar os serviços é uma grande vantagem competitiva para qualquer empresa. A estratégia de marketing, CRM e as equipes de vendas podem se beneficiar muito se tiver informações de quais clientes tem mais chances de deixar de contratar os serviços de uma empresa.

Esse tipo de problema é chamado de previsão de churn (de churn rate, ou, % de clientes que deixam a empresa num determinado tempo). Para resolver esse tipo de problema precisamos ter uma base histórica com clientes que saíram e não saíram da empresa, bem como suas características. 

Bancos, telefônicas, varejo, qualquer empresa que presta algum tipo de serviços e possui informações sobre seus clientes pode se beneficiar de modelos preditivos similares aos que iremos construir.

Nesse projeto, vamos ajudar a Let's Talk (empresa fictícia de  telefônica da holding Let's Data) a manter seus clientes. Faremos isso criando modelos para classificar os clientes em "churn" ou "não churn", ou seja, se irão cancelar os serviços ou não.

## Base de Dados

A base utilizada pode ser obtida no [Kaggle](https://www.kaggle.com/blastchar/telco-customer-churn) e se trata de uma empresa telefônica fictícia com dados demográficos e de serviços contratados pelos  clientes com a informação se saiu ou não da empresa.

### Tópicos

- 1. Importando Bibliotecas e Configurando Pandas
- 2. Leitura e Exploração dos Dados
    - 2.1. Analisando a Base de Dados
    - 2.2. Dicionário de Dados
    - 2.3. Tratando Dados
- 3. Estatística descritiva
    - 3.1. Analisando a distribuição de tenure 
    - 3.2. Analisando a distribuição da cobrança mensal
    - 3.3. Analisando a variável target: churn
    - 3.4. Relação entre as features e a variável target
- 4. Codificação de Variáveis Categóricas
- 5. Determinando quem são variáveis preditoras e variável target
- 6. Separação de bases
- 7. Tratamento de dados faltantes (missing data)
- 8. Machine Learning
- 9. Feature Engineering
- 10. Modelo Campeão!
- 11. Comparação de desempenho
 
------------

## Requisitos e Replicações:

Neste projeto, foi utilizada a versão 3.9.13 do Python

A versão do pip utilizada é a 22.2.2

A versão do git utilizada é a 2.41.0

Demais requisitos se encontram no arquivo requirements.txt

<details>
  <summary>Para utilizar este projeto, siga as instruções abaixo:</summary>

  <details>
    <summary>Passo 1: Clonar o repositório</summary>

    git clone https://github.com/GSanner/Desafio_Indicium_Lighthouse.git

  </details>

  <details>
    <summary>Passo 2: Instalar os pacotes nas versões utilizadas</summary>

    pip install -r requirements.txt
    
  </details>

</details>
