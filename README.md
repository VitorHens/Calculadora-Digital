# 🧮 Calculadora Digital

Aplicação web desenvolvida em **PHP** para praticar **Programação Orientada a Objetos**, formulários HTML, rotas com Slim Framework e estilização com Bootstrap.

O projeto reúne diferentes módulos em uma única aplicação, cada um resolvendo um problema específico.

## 🚀 Funcionalidades

- 🧍 **IMC:** calcula e classifica o Índice de Massa Corporal a partir de peso e altura
- 📦 **Estoque:** registra produtos, entradas e saídas e calcula quantidades e valores
- 🎓 **Média escolar:** calcula a média de notas e apresenta a situação do aluno
- 💰 **Salário:** calcula o salário considerando horas trabalhadas e horas extras
- 📐 **Triângulos:** valida os lados, classifica o triângulo e calcula perímetro e área

## 🛠️ Tecnologias

- PHP
- HTML5
- Bootstrap
- Slim Framework 4
- Composer
- Programação Orientada a Objetos

## 🧠 Conceitos praticados

- Classes e objetos
- Encapsulamento
- Atributos e métodos
- Validação de dados
- Formulários HTML
- Rotas HTTP com `POST`
- Separação da lógica em classes

## 📁 Estrutura principal

```text
├── public/          # Formulários e ponto de entrada da aplicação
├── src/             # Classes PHP com a lógica dos módulos
├── composer.json    # Dependências do projeto
└── composer.lock    # Versões das dependências
```

## ▶️ Como preparar o projeto

Com PHP e Composer instalados, execute:

```bash
composer install
```

Depois execute a aplicação em um servidor PHP/Apache apontando o diretório público para a pasta `public/`.

> Dependendo do ambiente local utilizado, pode ser necessário ajustar o `basePath` configurado em `public/index.php`.

## 🎯 Objetivo

Praticar a integração entre **interface web e lógica orientada a objetos**, utilizando PHP para processar os dados enviados pelos formulários.

---

Desenvolvido por **Vitor Hens**.
