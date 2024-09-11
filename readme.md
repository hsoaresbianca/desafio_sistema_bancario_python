# Desafio Criando Um Sistema Bancário
- Este projeto foi desenvolvido na [Formação Python Developer DIO](https://www.dio.me/bootcamp/formacao-python-developer).
- Acesse o [REPOSITÓRIO DA TRILHA PYTHON DIO](https://github.com/digitalinnovationone/trilha-python-dio/tree/main).

# DESAFIO 1
## Objetivo Geral:
- Criar um sistema bancário com a linguagem Python.
- Implementar as operações: sacar, depositar e visualizar extrato.

## Depósito:
- Deve ser possível depositar apenas valores positivos para a conta bancária.
- Todos os depósitos devem ser armazenados em uma variável e exibidos na operação de extrato.

## Saque:
- O sistema deve permitir realizar 3 saques diários com o limite de R$ 500,00 por saque.
- Todos os saques devem ser armazenados em uma variável e exibidos na operação de extrato.

## Extrato:
- Essa operação deve listar todos os depósitos e saques realizados na conta.
- No fim da listagem deve ser exibido o saldo atual da conta.
- Os valores devem ser exibidos utilizando o formato R$ xxx.xx

# DESAFIO 2
## Objetivo Geral:
- Otimizar o Sistema Bancário previamente desenvolvido com o uso de funções Python.
- Tornar as operações existentes de saque, depósito e extrato em funções.
- Criar duas novas funções: cadastrar usuário (cliente) e cadastrar conta bancária.
- Refatorar o código existente, dividindo-o em funções reutilizáveis, facilitando a manutenção e o entendimento do sistema como um todo.

## Funções:
- Criar funções para todas as operações do sistema.
- Cada função vai ter uma regra na passagem de argumentos.

## Função Saque:
- Deve receber os argumentos apenas por nome (keyword only).

## Função Depósito:
- Deve receber os argumentos apenas por posição (positional only).

## Função Extrato:
- Deve receber os argumentos por posição e nome.

## Criar Novas Funções:
- Função "criar usuário (cliente)".
- Função "criar conta corrente".

## Função Criar Usuário (cliente):
- O programa deve armazenar os usuários em uma lista.
- Um usuário é composto por: nome, data de nascimento, CPF e endereço.
- O endereço é uma string com o formato: logradouro, número, bairro, cidade/UF.
- Deve ser armazenado somente os números do CPF.
- Não pode ser possível cadastrar 2 usuários com o mesmo CPF.

## Função Criar Conta Corrente:
- O programa deve armazenar contas em uma lista.
- Uma conta é composta por: agência, número da conta e usuário.
- O número da conta é sequencial, iniciando em 1.
- O número da agência é fixo: "0001".
- O usuário pode ter mais de uma conta, mas uma conta pertence a somente um usuário.

## Dica para o desafio 2:
- Para vincular um usuário a uma conta, filtre a lista de usuários buscando o numero do CPF informado para cada usuário da lista.

# DESAFIO 3
## Objetivo Geral:
 - Atualizar a implementação do sistema bancário, para armazenar os dados de clientes e contas bancárias em objetos ao invés de dicionários.
 - Iniciar a modelagem do sistema bancário em Programação Orientada a Objetos (POO).
 - Adicionar classes para cliente e para as operações bancárias depósito e saque.
 - O código deve seguir o modelo de classes UML. ![Imagem de referência](https://academiapme-my.sharepoint.com/personal/renato_dio_me/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Frenato%5Fdio%5Fme%2FDocuments%2FDigital%20Innovation%20One%2Fslides%20aulas%20diversas%2FTrilhas%2FPython%20Developer%2FTrilha%20Python%20%2D%20desafio%2Epng&parent=%2Fpersonal%2Frenato%5Fdio%5Fme%2FDocuments%2FDigital%20Innovation%20One%2Fslides%20aulas%20diversas%2FTrilhas%2FPython%20Developer&ga=1)

## Desafio extra:
- Após concluir a modelagem das classes e a criação dos métodos. Atualizar os métodos que tratam as opções do menu, para funcionarem com as classes modeladas.