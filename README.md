# Projeto de Data Warehouse e Analytics 🚀

Bem-vindo ao repositório do **Projeto de Data Warehouse e Analytics**!  
Este projeto demonstra uma solução abrangente de ponta a ponta, desde a construção de um Data Warehouse robusto até a geração de insights acionáveis. Como um projeto de portfólio, ele destaca as melhores práticas do setor em engenharia e análise de dados.

---

## 🚀 Requisitos do Projeto

### 🛠️ Construção do Data Warehouse (Engenharia de Dados)

**Objetivo:** Desenvolver um Data Warehouse moderno utilizando **SQL Server** para consolidar dados de vendas, permitindo relatórios analíticos e tomadas de decisão fundamentadas.

**Especificações Técnicas:**
* **Fontes de Dados:** Importação de dados de dois sistemas distintos (ERP e CRM), fornecidos em formato CSV.
* **Qualidade de Dados (Data Quality):** Processos de limpeza e resolução de inconsistências (Nulos, duplicatas, espaços indesejados) antes da análise.
* **Integração:** Consolidação das fontes em um modelo de dados único e intuitivo (**Star Schema**), otimizado para performance em consultas.
* **Escopo:** Foco no estado atual dos dados (Latest Dataset); sem necessidade de historização (SCD) neste estágio.
* **Documentação:** Documentação clara do modelo de dados para suporte a stakeholders e times técnicos.

### 📊 BI: Analytics & Relatórios (Análise de Dados)

**Objetivo:** Utilizar SQL avançado para extrair insights estratégicos que permitam entender:
* **Comportamento do Cliente:** Identificação de padrões e perfis de compra.
* **Performance de Produtos:** Análise de vendas por categorias e rentabilidade.
* **Tendências de Vendas:** Monitoramento de métricas ao longo do tempo.

Esses insights capacitam os tomadores de decisão com métricas de negócios essenciais (KPIs).

---

## 🛠️ Como Executar o Projeto

1. **Clonar o repositório:** `git clone https://github.com/seu-usuario/nome-do-repo.git`
2. **Configurar o Banco de Dados:** Execute os scripts da pasta `/scripts` no seu SQL Server.
3. **Ajuste de Caminhos:** > **Nota:** Antes de executar a *stored procedure* `bronze.load_bronze`, certifique-se de atualizar os caminhos dos arquivos CSV nos comandos `BULK INSERT` para o diretório local onde você clonou este repositório.
4. **Execução:** Execute `EXEC bronze.load_bronze` para iniciar a carga dos dados.

---

## 👨‍💻 Sobre Mim

Olá! Eu sou o **Pedro Tibúrcio**! 👋

Sou **Analista de Dados** com certificação **Google Data Analytics**. Minha trajetória anterior como **Engenheiro de Software** me conferiu uma base sólida em SQL e raciocínio lógico, permitindo-me abordar desafios de dados com rigor técnico e eficiência.

---

## 🛠️ Tecnologias Utilizadas
* **Banco de Dados:** SQL Server
* **Linguagem:** T-SQL (Transact-SQL)
* **Ferramentas:** SQL Server Management Studio (SSMS)
* **Metodologia:** Camadas Bronze, Silver e Gold (Medallion Architecture)

---
*Desenvolvido por Pedro Tibúrcio – Conecte-se comigo no [LinkedIn](https://www.linkedin.com/in/pedro-tiburcio/)*
