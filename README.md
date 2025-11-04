# 💻 Laboratório 02 – Exercício 01: GitHub Actions

Este repositório contém os arquivos e configurações do exercício 01 do Laboratório 02 da Web Academy. O objetivo é aprender a configurar e utilizar **GitHub Actions** para automatizar tarefas em projetos de desenvolvimento.

## 📌 Objetivos do exercício

- Criar um workflow básico com GitHub Actions
- Automatizar tarefas
- Entender a estrutura de arquivos `.yml` usados nas Actions

## 🛠️ Estrutura do projeto
.github/ └── workflows/ └── build.yml   #Arquivo de configuração do workflow

## 🚀 Como funciona o workflow

O arquivo `build.yml` define um fluxo de trabalho que é executado automaticamente quando há um `push` ou `pull request` no branch `main`. Ele pode incluir etapas como:

- Instalar dependências
- Rodar testes
- Gerar builds

## 📂 Como usar

1. Clone o repositório:
   ```bash
   git clone https://github.com/Danielevs/WACAD015-Fundamentos-de-integracao-continua---lab02

2. Faça alterações e envie para o GitHub

git add .

git commit -m "Atualiza workflow"

git push

