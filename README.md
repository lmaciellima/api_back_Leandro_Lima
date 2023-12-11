# Cadastro de veículos API

O objetivo desse sistema e gerar para o usuário o sistema de cadastro de veiculos
Para facilictar o controle e a visualização do cadstro dos veículos em estoque

versão 01122023

## Como executar o programa
Será necessário ter todas as libs python listadas no `requirements.txt` instaladas.
Após clonar o repositório, é necessário ir ao diretório raiz, pelo terminal, para poder executar os comandos descritos abaixo.

> É fortemente indicado o uso de ambientes virtuais do tipo [virtualenv](https://virtualenv.pypa.io/en/latest/installation.html).


## Etapas de Ativação

 1 - Criação da Pasta env

```
(env)$ py -m venv env
```

 2 - Ativando o ambiente virtual
 ```
  .\env\Scripts\activate
 ```
 3 - Instalar as bibliotecas do ambiente virtual
 Este comando instala as dependências/bibliotecas, descritas no arquivo `requirements.txt`.
```
(env)$ pip install -r requirements.txt
```

 3.1 - Verifique as bibliotecas instaladas
 ```
 pip freeze
 ```




4 - Para executar a API  basta executar:

```
(env)$ flask run --host 0.0.0.0 --port 5000
```

Em modo de desenvolvimento é recomendado executar utilizando o parâmetro reload, que reiniciará o servidor
automaticamente após uma mudança no código fonte. 

```
(env)$ flask run --host 0.0.0.0 --port 5000 --reload
```

Abra o [http://localhost:5000/#/](http://localhost:5000/#/) no navegador para verificar o status da API em execução.
