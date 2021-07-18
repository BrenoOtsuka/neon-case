# Neon Pagamentos | Case Técnico - Analista de Dados Pleno

**Case de análise de dados para descobrir quantas pessoas nos EUA não usam internet em banda larga**

Não é novidade que vivemos em um mundo conectado pela internet. Temos acesso fácil e rápido a informação, podemos assistir nossas séries preferidas no Netflix, ouvir nossas músicas no Spotify, conversar com nossos amigos e familiares pelo Zoom ou WhatsApp. Mas enquanto alguns têm tudo isso na palma da mão, outros sofrem sem acesso à internet com o mínimo de qualidade.

Na pandemia que estamos enfrentando, essa diferença ficou ainda mais evidente. Hoje, muitos dependem de uma boa conectividade para trabalhar, estudar ou acessar algum serviço necessário. 

Nesse cenário, a análise de dados pode contribuir para o aumento da cobertura da banda larga. Sendo assim, tenho o objetivo de definir uma estratégia para promover a expansão da banda larga. E, para tanto, os seguintes objetivos específicos foram cumpridos:

1) Descobrir onde estão as pessoas sem acesso à banda larga;
2) Estimar quantas pessoas estão sem acesso à banda larga em um determinado CEP.

## Base de Dados

[United States Broadband Usage Percentages Dataset](https://github.com/microsoft/USBroadbandUsagePercentages): Dados coletados pela Microsoft sobre a distribuição da banda larga nos Estados Unidos.

[United States Census](https://www.kaggle.com/census/census-bureau-usa) Dados baixados da plataforma Kaggle sobre população dos Estados Unidos em 2010 separadas por idade, genero e CEP.

[Population Density by County](https://github.com/camillol/cs424p3/blob/master/data/Population-Density%20By%20County.csv) Dados sobre a densidade populacional por condado nos Estados Unidos publicados em 2011


### Dependências

* Python 3.8
* Pip 20.0.2
* VS Code

## Set Up

Primeiro clone o projeto em sua máquina. Para isso, no terminal, excute o comando

```
git clone https://github.com/BrenoOtsuka/neon-case.git
```

Em seguida, crie um ambiente virtual e instale as bibliotecas requeridas

```
python3 -m venv venv
source venv/bin/activate
pip3 install -r requirements.txt 
```

Abra o projeto no VS code ou outro de sua preferência.

1) O notebook exploratory_data_analysis contem as análises para as questões 1 e 3.
2) O notebool training_model contem o treinamento do modelo solicitado na questão 2.

**IMPORTANTE** Ao abrir um notebook, verifique se o kernel Python 3.8 (venv) está selecionado. O Kernel fica no canto superior direito do Notebook.

**SUGESTÃO** Caso não queria instalar o VS Code, outra opção é executar o projeto no Jupyter Lab
