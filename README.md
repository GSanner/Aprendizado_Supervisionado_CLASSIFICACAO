# Aprendizado_Supervisionado_CLASSIFICACAO

## Classificação usando Scikit Learn e XGBoost
Projeto feito no curso Let's Data - Jornada Cientista da Dados

## Motivação 

Muitos problemas da vida real na carreira de cientista de dados são modelados como classificação. Quando nossa variável dependente é discreta, temos uma classificação. As classes podem ser somente duas (variável dependente binária) ou problemas multiclasse.

Agora que você já criou seu primeiro modelo, sabe como separar a base, sabe que selecionar modelo é só na validação, vamos aumentar um pouquinho o nível! Criar o modelo, treinar, validar e testar é a parte mais "fácil". Escolher a melhor forma de tratar dados faltantes (missing data), realizar uma boa engenharia de features (feature engineering) e selecionar a melhor métrica para cada projeto são partes essenciais e que requerem uma certa "criatividade" de nossa parte.

## Objeto de Estudo 

Um problema muito recorrente para muitas empresas é qual a melhor forma de retenr seus clientes. Saber de antemão se um cliente vai cancelar os serviços é uma grande vantagem competitiva para qualquer empresa. A estratégia de marketing, CRM e as equipes de vendas podem se beneficiar muito se tiver informações de quais clientes tem mais chances de deixar de contratar os serviços de uma empresa.

Esse tipo de problema é chamado de previsão de churn (de churn rate, ou, % de clientes que deixam a empresa num determinado tempo). Para resolver esse tipo de problema precisamos ter uma base histórica com clientes que saíram e não saíram da empresa, bem como suas características.

Bancos, telefônicas, varejo, qualquer empresa que presta algum tipo de serviços e possui informações sobre seus clientes pode se beneficiar de modelos preditivos similares aos que iremos construir.

Nesse projeto, vamos ajudar a Let's Talk (empresa telefônica da holding Let's Data) a manter seus clientes. Faremos isso criando modelos para classificar os clientes em "churn" ou "não churn", ou seja, se irão cancelar os serviços ou não.

A base utilizada pode ser obtida no Kaggle e se trata de uma empresa telefônica fictícia com dados demográficos e de serviços contratados pelos clientes com a informação se saiu ou não da empresa.

## Instalação das dependências

Para instalar as dependências do projeto, certifique-se de ter o Python instalado. Em seguida, execute o seguinte comando no terminal ou prompt de comando: pip install -r requirements.txt

Este comando irá instalar todas as bibliotecas e suas versões especificadas no arquivo `requirements.txt`, garantindo que o ambiente esteja configurado corretamente.

## Executando o projeto

Para executar o projeto, siga os passos abaixo:

1. Clone este repositório para o seu ambiente local.
2. Navegue para o diretório do projeto no terminal ou prompt de comando.
3. Certifique-se de que as dependências estejam instaladas (consulte a seção "Instalação das dependências" acima).
4. Execute o seguinte comando: python main.py
5. Isso iniciará o aplicativo e você poderá interagir com ele através da interface do usuário.
