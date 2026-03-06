# Projeto Integrador

## Descrição do Projeto

Este repositório contém o desenvolvimento do Projeto Integrador da disciplina de Projeto de Extensão.
O objetivo do projeto é desenvolver uma aplicação que permita a gestão de usuários e informações dentro de uma plataforma digital.

## Problema

Muitas aplicações precisam de sistemas simples e seguros para gerenciamento de usuários, autenticação e controle de informações.
A ausência dessas funcionalidades pode causar dificuldades no acesso e na organização dos dados.

## Público-alvo

* Usuários que necessitam acessar um sistema com autenticação
* Pequenas aplicações ou plataformas digitais
* Usuários que precisam gerenciar seus próprios dados dentro de um sistema

## Objetivo

Desenvolver um sistema que permita autenticação de usuários, gerenciamento de perfil e controle básico de acesso, garantindo segurança e boa experiência de uso.

## Requisitos do Sistema

### Requisitos Funcionais (RF)

**RF01 — Login do usuário**
O sistema deve permitir que o usuário realize login com e-mail e senha.

**RF02 — Recuperar senha**
O sistema deve permitir que o usuário solicite recuperação de senha por e-mail.

**RF03 — Atualização de perfil**
O usuário pode alterar nome, foto e dados pessoais.

### Requisitos Não Funcionais (RNF)

**RNF01 — Tempo de resposta**
O sistema deve carregar telas principais em até 2 segundos.

**RNF02 — Segurança**
As senhas devem ser armazenadas usando hash seguro (ex.: bcrypt).

**RNF03 — Compatibilidade**
O sistema deve funcionar nos navegadores Chrome, Edge e Firefox.

### Regras de Negócio (RN)

**RN01 — Maioridade**
Para criar uma conta, o usuário deve ter mais de 18 anos.

**RN02 — Bloqueio por inatividade**
Usuários inativos por mais de 90 dias devem ser marcados como inativos.

**RN03 — Limite de tentativas de login**
Após 5 tentativas inválidas, a conta deve ser temporariamente bloqueada.

## Tecnologias

As tecnologias do projeto serão definidas durante o desenvolvimento.

## Integrantes do Grupo

* Hugo Palmiro Bento Francisco
* Paulos Bastos Nicioli de Albuquerque
* Gustavo Miranda Rodrigues
* Weverton Alves Nascimento
* Guilherme Silva Zavan Sampaio
