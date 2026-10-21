# CRUD HEVY — Gerenciamento de Fichas de Treino

Projeto desenvolvido em Python para a disciplina de Algoritmos e Programação e documentado para a disciplina de Gestão Ágil de Projetos.

Objetivo: desenvolver um sistema de terminal inspirado no aplicativo HEVY para registrar e administrar informações de exercícios físicos, facilitando a organização das fichas de treino e o acompanhamento das atividades realizadas na academia.

# Tipos de dados

Nome do exercício  str
Grupo muscular     str 
Quantidade de séries int 
Repetições por série int 
Carga em kg float

## Funcionalidades do CRUD

Cadastrar: registrar um exercício e suas informações.
Listar: consultar os dados do exercício cadastrado.
Atualizar: modificar as informações de um exercício.
Excluir: remover o exercício registrado.

## Requisitos funcional


RF01 — O sistema deve permitir cadastrar exercícios e suas respectivas informações.
RF02 — O sistema deve permitir consultar os dados do exercício cadastrado.
RF03 — O sistema deve permitir atualizar as informações de um exercício.
RF04 — O sistema deve permitir excluir um exercício cadastrado.


## Regras de negócio

RN01 — O nome do exercício não pode ficar vazio. Caso isso aconteça, o sistema deve informar que é necessário preencher o nome.
RN02 — A quantidade de séries deve ser maior que zero. Caso contrário, o sistema deve informar que o valor é inválido.
RN03 — A quantidade de repetições deve ser maior que zero. Caso contrário, o sistema deve solicitar um valor válido.
RN04 — A carga utilizada deve ser igual ou superior a zero quilograma. Caso seja informado um valor negativo, o sistema deve apresentar uma mensagem de erro.
RN05 — O sistema só deve permitir consultar, atualizar ou excluir um exercício quando houver um registro cadastrado.


## Requisitos não funcional


RNF01 — O sistema deve ser executado por meio do terminal.
RNF02 — O sistema deve possuir uma interface textual simples e fácil de utilizar.
RNF03 — O sistema deve funcionar sem necessidade de conexão com a internet.
RNF04 — O sistema deve ser desenvolvido utilizando a linguagem Python.



# ETAPA 1 

