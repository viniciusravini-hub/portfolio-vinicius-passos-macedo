# 🏢 Auditoria de Orçamentos Corporativos (Python)
 
[![Python Version](https://img.shields.io/badge/python-3.x-blue.svg)](https://www.python.org/)
[![Status](https://img.shields.io/badge/status-concluído-brightgreen.svg)]()
 
## 📖 Sobre o Projeto
Este projeto foi desenvolvido como parte da disciplina de Programação de computadores do curso de Ciência da computação. O objetivo do script é processar e calcular o orçamento de uma estrutura organizacional complexa (dicionários aninhados) de uma multinacional, aplicando regras de negócio dinâmicas e auditoria de execução.
 
A solução foi arquitetada utilizando conceitos avançados de Python para garantir flexibilidade, performance e rastreabilidade.
 
## 🚀 Funcionalidades
- **Cálculo Hierárquico:** Varredura completa da estrutura corporativa, independentemente do nível de profundidade.
- **Filtros Dinâmicos:** Capacidade de ignorar setores específicos e todos os seus subsetores na hora do cálculo financeiro.
- **Conversão de Câmbio:** Suporte a parâmetros opcionais para conversão de moedas em tempo de execução.
- **Sistema de Auditoria:** Monitoramento automatizado de tempo de execução e registro (logging) dos parâmetros utilizados na transação financeira.
 
## 🛠️ Tecnologias e Conceitos Aplicados
Este projeto foi construído utilizando Python puro (Standard Library), com foco nos seguintes paradigmas e recursos:
* **Funções Recursivas (Recursion):** Utilizadas para a navegação na árvore de dados (dicionários aninhados).
* **Decorators:** Implementação do `@auditor` para injetar comportamentos de log e cronometragem sem modificar a lógica de negócios.
* **Empacotamento de Argumentos (`*args` e `**kwargs`):** Utilizados tanto no decorator quanto na função principal para permitir a passagem dinâmica de departamentos a serem ignorados e taxas de câmbio.
 
## ⚙️ Como Executar
 
### Pré-requisitos
* Python 3.8 ou superior instalado.
 
### Passo a Passo
1. Clone este repositório:
   ```bash
   git clone [https://github.com/viniciusravini-hub](https://github.com/viniciusravini-hub.git)
   ```
2. Acesse a pasta do projeto:
   ```bash
   cd projeto_sistema_de_auditoria
   ```
3. Execute o script principal:
   ```bash
   sistema_de_auditoria main.py
   ```
 
## 🧠 Lógica e Estrutura do Código
Breve explicação de como o código foi organizado:
* `A ideia do programa foi criar uma forma automática de calcular os gastos da empresa sem precisar acessar cada setor manualmente. Para isso, a função vai navegando pelos dicionários até encontrar os valores dos orçamentos e somando tudo. Além disso, adicionei opções para ignorar alguns setores e alterar o valor final usando taxa de câmbio.`.
* **Dados:** Os dados simulados da empresa foram estruturados em... `JSON`.
 
## 👤 Autor
 
* **Vinicius Passos Macedo** * LinkedIn: https://www.linkedin.com/in/vin%C3%ADcius-passos-macedo-82264a407/
* E-mail: viniciusravini@gmail.com
 
---
*Projeto acadêmico com foco na aplicação prática de conceitos avançados da linguagem Python.*
