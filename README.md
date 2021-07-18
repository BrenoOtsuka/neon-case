# Neon Pagamentos | Case Técnico - Analista de Dados Pleno

**Caso de análise de dados para descobrir quantas pessoas nos EUA não usam internet em banda larga**

O case aborda o problema do acesso à internet nos Estados Unidos. 

No território norte-americano, por exemplo, reuniões do conselho municipal ou de processos judiciais tornaram-se quase inacessíveis para qualquer pessoa cuja conexão não
possa suportar uma chamada no Zoom. Alguns distritos escolares começaram a fornecer pontos de acesso Wi-Fi para alunos sem uma conexão doméstica confiável. Em outros distritos, as crianças se instalam nos estacionamentos do McDonald's apenas para obter um sinal confiável o suficiente para fazer o dever de casa.

Além da questão do acesso, ainda existe o problema da qualidade do sinal. Para ser considerada banda larga a velocidade mínima de download é de 25Mbps, limite ainda considerado baixo para internet de alta qualidade.

## Objetivo

Propor uma solução para aumentar o número de pessoas com acesso à banda larga nos Estados Unidos

**Objetivos específicos:**

* Descobrir onde estão as pessoas sem acesso à banda larga e por que elas não têm acesso;
* Encontrar CEPs que não têm informações de acesso à banda larga e estimar quantas pessoas nestes CEPs estão sem acesso.


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
