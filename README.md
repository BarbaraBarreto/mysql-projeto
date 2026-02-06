# MySQL - Projeto
Sistema de vendas em MySQL simulando ambiente de produção, com foco em modelagem relacional, procedures, transações, performance e monitoramento.

## 🛠️ Tecnologias
- MySQL 8
- SQL
- Git / GitHub

---

## 🧱 Estrutura do projeto
- `ddl/` – Criação de tabelas, constraints e índices  
- `dml/` – Carga de dados simulados  
- `procedures/` – Regras de negócio  
- `performance/` – Análises e otimizações  
- `monitoramento/` – Scripts de saúde do banco  
- `docs/` – Decisões técnicas  

---

## ▶️ Como executar
1. Executar os scripts da pasta `ddl`
2. Executar os scripts da pasta `dml`
3. Executar as stored procedures conforme necessário
4. 

---

## 📁 Estrutura de pastas usada

```text
mysql-projeto/
├── ddl/                     # Scripts de definição do banco (DDL)
│   ├── 01_tables.sql        # Criação das tabelas principais do sistema
│   ├── 02_constraints.sql   # Chaves primárias, estrangeiras e integridade
│   └── 03_indexes.sql       # Índices para performance
│
├── dml/                     # Scripts de carga de dados simulados
│   └── carga_fake.sql       # Inserts de clientes, produtos e pedidos
│
├── procedures/              # Stored procedures do sistema
│   ├── sp_cria_pedido_json.sql   # Criação de pedidos com transação
│   ├── sp_processa_pagamento.sql # Processamento de pagamentos
│   ├── sp_baixa_estoque.sql      # Controle de estoque
│   └── sp_log_execucao.sql       # Logs de execução
│
├── performance/             # Análise e otimização de consultas
│   ├── queries_lentas.sql
│   ├── queries_otimizadas.sql
│   └── explain.md
│
├── monitoramento/           # Scripts de saúde do banco
│   └── health_check.sql
│
├── docs/                    # Documentação técnica
│   └── decisoes_tecnicas.md
│
└── README.md                # Documentação geral do projeto
```

---

## 👩‍💻 Autora
Barbara Barreto  
Analista de Dados / DBA
