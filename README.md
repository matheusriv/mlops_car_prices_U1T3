# Utilizando boas práticas no Guided Project: Predicting Car Prices do Dataquest.

Projeto da disciplina de MLOps da UFRN que tem como objetivo principal colocar em prática o conteúdo referente a Semana 03 da matéria, focado nos princípios de código limpo para ciência de dados e aprendizado de máquina.

## Requisitos

Verifique se você atende a todos os requisitos a seguir:
* Ter uma máquina com ` Windows | Linux | Mac `.
* Ter o [`Python 3.9`](https://www.python.org/downloads/) instalado na sua máquina.
* Ter o pylint instalado:
```
pip install pylint
```

## Começando

Para começar a usar este projeto, basta clonar o repositório:

Opção HTTP:
```
git clone https://github.com/matheusriv/mlops_car_prices_U1T3.git
```

Opção SSH:
```
git clone git@github.com:matheusriv/mlops_car_prices_U1T3.git
```

## 💻 Etapas do Projeto

* A primeira parte do trabalho foi adquirir o jupyter notebook (arquivo.ipynb) referente ao Projeto Guiado [Guided Project: Predicting Car Prices do Dataquest](https://app.dataquest.io/c/36/m/155/guided-project%3A-predicting-car-prices/1/introduction-to-the-data-set). O notebook tem título de Mission155Solutions.

* A segunda parte do trabalho foi validar o arquivo gerado no passo 1) através da sua execução no [Google Colaboratory](https://colab.research.google.com/), ambiente de notebook Jupyter gratuito que roda na nuvem e armazena seus notebooks no Google Drive.

* Após isso se gerou um arquivo python (script.py) referente ao item 1).

* Por último foi avaliado a aderência das boas práticas do código limpo em relação ao último passo executando em terminal o comando [Pylint](https://pylint.pycqa.org/en/latest/), ferramenta de análise para a linguagem de programação Python que analisa código-fonte, bug e qualidade de códigos, seguindo o estilo recomendado pelo PEP 8. O objetivo final alcançado foi conseguir uma nota 10/10 através do pylint.

Você pode simplesmente executar o script usando:
```
python3 script_refatorado.py
```

Você pode verificar se todas as técnicas de práticas recomendadas de codificação foram aplicadas executando:
```
pylint script_refatorado.py
```
