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

# CRUD HEVY - Etapa 1

nome = ""
grupo = ""
series = 0
repeticoes = 0
carga = 0.0
cadastrado = False
opcao = 0

while opcao != 5:
    print("\n===== HEVY =====")
    print("1 - Cadastrar")
    print("2 - Listar")
    print("3 - Atualizar")
    print("4 - Excluir")
    print("5 - Sair")

    opcao = int(input("Opcao: "))

    if opcao == 1 or opcao == 3:
        if opcao == 1 and cadastrado:
            print("Exercicio ja cadastrado.")
        elif opcao == 3 and not cadastrado:
            print("Nenhum exercicio cadastrado.")
        else:
            nome = input("Nome: ")
            while nome.strip() == "":
                nome = input("Nome obrigatorio: ")

            grupo = input("Grupo muscular: ")
            series = int(input("Series: "))
            repeticoes = int(input("Repeticoes: "))
            carga = float(input("Carga em kg: "))

            while series <= 0 or repeticoes <= 0 or carga < 0:
                print("Valores invalidos.")
                series = int(input("Series: "))
                repeticoes = int(input("Repeticoes: "))
                carga = float(input("Carga em kg: "))

            cadastrado = True
            print("Operacao realizada com sucesso!")

    elif opcao == 2:
        if cadastrado:
            print(nome, "-", grupo)
            print("Series:", series, "| Repeticoes:", repeticoes)
            print("Carga:", carga, "kg")
        else:
            print("Nenhum exercicio cadastrado.")

    elif opcao == 4:
        if cadastrado:
            nome = ""
            grupo = ""
            series = 0
            repeticoes = 0
            carga = 0.0
            cadastrado = False
            print("Exercicio excluido.")
        else:
            print("Nenhum exercicio cadastrado.")

    elif opcao == 5:
        print("Sistema encerrado.")

    else:
        print("Opcao invalida.")

