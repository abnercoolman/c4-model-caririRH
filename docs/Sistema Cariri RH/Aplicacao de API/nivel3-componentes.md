# Acesso rápido

* [**Nível 1 | Contexto | Visão Geral**](/docs/nivel1-context.md)
* [**Nível 2 | Contêineres | Sistema Cariri RH**](/docs/Sistema%20Cariri%20RH/nivel2-conteiner.md)
* [**Nível 4 | Códigos | Services e Controllers**](/docs/Sistema%20Cariri%20RH/Aplicacao%20de%20API/Diagrama%20de%20Classes/nivel4-codes.md)
---

# Nível 3 | Componentes | API Application

## Visão Geral

O diagrama de componentes mostra como o contêiner da API é composto por vários componentes, detalhando suas responsabilidades e interações. Este nível de documentação é essencial para entender a estrutura interna da API e como ela se comunica com outros elementos do sistema.

## Escopo e Elementos

**Escopo**: Contêiner da API do Sistema Cariri RH.

**Elementos principais**: 
- Componentes dentro do contêiner da API
- Interações entre componentes
- Tecnologias utilizadas (Express.JS, Node.JS)

**Público-alvo**: Arquitetos de software e desenvolvedores.

## Componentes da API

A API do Sistema Cariri RH é composta pelos seguintes componentes principais:

1. **Deletar Dados Funcionário**: Componente responsável por excluir registros de funcionários do banco de dados.
2. **Login Administrador**: Gerencia autenticação, login e alteração de senha para administradores.
3. **Ler Dados Funcionário**: Realiza consultas e leitura de dados dos funcionários.
4. **Cadastro de Funcionário**: Responsável pela aquisição e registro de novos dados de funcionários.
5. **Atualizar Dados Funcionário**: Gerencia a atualização de informações existentes de funcionários.

## Tecnologias Utilizadas

- **Backend**: Express.JS (Node.JS)
- **Comunicação**: JSON/HTTPS
- **Banco de Dados**: MongoDB

## Diagrama de Componentes

![Diagrama de Componentes do Sistema Cariri RH](nivel3-componentes.png)