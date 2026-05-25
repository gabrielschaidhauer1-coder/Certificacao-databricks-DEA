# 📚 Curso de Preparação - Databricks Data Engineer Associate (DEA)

Material de estudo para a certificação **Databricks Certified Data Engineer Associate**, com foco em ambientes **Azure Databricks**.

---

## 🎯 Objetivo

Este repositório contém documentação, exemplos práticos e anotações organizadas por tópico para preparação completa para o exame de certificação DEA.

A certificação valida a capacidade de utilizar a **Databricks Data Intelligence Platform** para realizar tarefas de engenharia de dados, incluindo compreensão da arquitectura, execução de ETL com Apache Spark SQL e PySpark, e orquestração de workloads com Databricks Workflows.

---

## 📋 Conteúdo Programático

| Pasta | Tópico | Descrição |
|-------|--------|-----------|
| `01` | Introdução ao Curso | Boas vindas e introdução |
| `02` | Criando Conta Free na Azure |Criando conta Azure com bonus de $200 |
| `03` | Componentes Databricks | Arquitectura, clusters, workspaces |
| `04` | Introdução ao Unity Catalog | Governança, metastore, namespaces |
| `05` | Databricks Lakehouse | Delta Lake, arquitectura medallion |
| `06` | ETL e Processamento Spark | Transformações, DataFrames, SQL |
| `07` | Spark Structured Streaming | Streaming, triggers, checkpoints |
| `08` | Pipelines Declarativos - DLT | Delta Live Tables, expectations |
| `09` | Databricks Jobs | Orquestração, triggers, task values |
| `10` | Databricks SQL | Warehouses, dashboards, alertas |
| `11` | Governança de Dados | Permissões, GRANT/REVOKE, security |
| `12` | Simulado Certificação | Simulado de Perguntas Certificação |
| `13` | Condideração Final| Encerramento do treinamento |
---

## 🎓 Sobre o Exame

| Aspecto | Detalhe |
|---------|---------|
| **Tipo** | Proctored (supervisionado) |
| **Questões** | 45 questões pontuadas |
| **Duração** | 90 minutos |
| **Formato** | Múltipla escolha |
| **Taxa de Registo** | $200 USD |
| **Idiomas** | English, 日本語, Português BR, 한국어 |
| **Modalidade** | Online ou centro de testes |
| **Pré-requisitos** | Python e SQL nível básico |
| **Experiência Recomendada** | 6+ meses hands-on |
| **Validade** | 2 anos |
| **Recertificação** | Refazer exame na versão actual |

---

## 📊 Distribuição de Tópicos no Exame

| Domínio | Peso |
|---------|------|
| Databricks Intelligence Platform | 10% |
| Development and Ingestion | 30% |
| Data Processing & Transformations | 31% |
| Productionizing Data Pipelines | 18% |
| Data Governance & Quality | 11% |

```
Data Processing & Transformations  ████████████████████████████████  31%
Development and Ingestion          ██████████████████████████████    30%
Productionizing Data Pipelines     ██████████████████                18%
Data Governance & Quality          ███████████                       11%
Databricks Intelligence Platform   ██████████                        10%
```

---

## 🛠️ Estrutura do Material

Cada pasta contém:

- **Documentação em Markdown** — Resumos focados em pontos de certificação
- **Notebooks** — Exemplos práticos para execução no Databricks
- **Cenários de Exame** — Questões típicas e como responder

---

## 📖 Como Usar

1. **Estudo sequencial** — Seguir a numeração das pastas (01 → 12)
2. **Revisão por tópico** — Focar em áreas específicas de dificuldade
3. **Prática hands-on** — Executar notebooks no ambiente Azure Databricks
4. **Revisar Exam Guide** — Identificar gaps no conhecimento

---

## 📝 Passos para Preparação (Recomendado pela Databricks)

1. ✅ Revisar o [Exam Guide oficial](https://www.databricks.com/sites/default/files/2026-01/databricks-certified-data-engineer-associate-exam-guide-nov-30-2025-000.pdf)
2. ✅ Completar treino relacionado
3. ✅ Registar para o exame
4. ✅ Verificar [requisitos técnicos](https://kryterion.my.site.com/support/s/article/Online-Testing-Requirements?language=en_US) para exame online
5. ✅ Executar [system check](https://www.kryterion.com/systemcheck/)
6. ✅ Identificar gaps e estudar
7. ✅ Fazer o exame!

> **Nota:** O código no exame é fornecido em SQL quando possível. Nos demais casos, será em Python.

---

## ✅ Checklist de Preparação

### Databricks Intelligence Platform (10%)
- [ ] Compreender arquitectura do workspace
- [ ] Diferenciar clusters All-Purpose vs Job Clusters
- [ ] Conhecer SQL Warehouses e seus tipos

### Development and Ingestion (30%)
- [ ] Dominar leitura de múltiplos formatos (JSON, CSV, Parquet)
- [ ] Entender Auto Loader e ingestão incremental
- [ ] Trabalhar com dados complexos (arrays, structs, JSON)

### Data Processing & Transformations (31%)
- [ ] Dominar Spark SQL e PySpark transformations
- [ ] Implementar UDFs (SQL e Python)
- [ ] Operações Delta Lake (MERGE, UPDATE, DELETE)
- [ ] Higher-order functions e manipulação de nested data

### Productionizing Data Pipelines (18%)
- [ ] Configurar e agendar Jobs
- [ ] Entender Delta Live Tables e expectations
- [ ] Structured Streaming (triggers, checkpoints)
- [ ] Task orchestration e dependencies

### Data Governance & Quality (11%)
- [ ] Unity Catalog e hierarquia de objectos
- [ ] Permissões (GRANT, REVOKE, USAGE)
- [ ] Data quality com expectations

---

## 📚 Recursos Oficiais

- [Página da Certificação](https://www.databricks.com/learn/certification/data-engineer-associate)
- [Exam Guide (PDF)](https://www.databricks.com/sites/default/files/2026-01/databricks-certified-data-engineer-associate-exam-guide-nov-30-2025-000.pdf)
- [Registo para Exame](http://webassessor.com/databricks)
- [Databricks Academy](https://www.databricks.com/learn/training/login)
- [Documentação Azure Databricks](https://learn.microsoft.com/pt-pt/azure/databricks/)
- [FAQ da Certificação](https://www.databricks.com/learn/certification/faq)

---

## 📁 Pasta Arquivos

Contém ficheiros de dados utilizados nos notebooks práticos (CSV, JSON, Parquet) para simulação de cenários reais de ingestão e transformação.

---

## ⚠️ Notas Importantes

- **Conteúdo não pontuado:** O exame pode incluir questões para fins estatísticos que não afetam a nota
- **Materiais permitidos:** Nenhum (closed book)
- **Código:** SQL é preferido, Python quando necessário

---

**Boa sorte na certificação!** 🚀