# 📚 Miniguia de Estudos Temático: Excel, Power BI, Power Query e SQL
Projeto de conclusão de desafio desenvolvido para a plataforma **DIO (Digital Innovation One)**, com foco no uso de Inteligência Artificial para aprendizagem activa e estruturação de conhecimento.

---

## 🎯 1. Contexto e Objetivos
Este caderno temático foi concebido com o objetivo de guiar uma jornada de aprendizado intensivo de 30 dias nas ferramentas mais demandadas da área de dados: **Excel, Power Query, Power BI e SQL**. 
O foco principal é construir uma base sólida partindo de fórmulas básicas até a consolidação de um mini-projeto prático integrado, simulando cenários reais do mercado de trabalho (como análise de movimentações bancárias e crédito).

---

## 🔍 2. Curadoria de Fontes
Para alimentar o contexto de estudos e garantir a acurácia técnica, foram selecionadas e mapeadas as seguintes fontes abertas e bases de dados:
1. **Dados Abertos do Banco Central (BACEN):** Séries temporais de concessão de crédito, taxas de juros, inadimplência e câmbio.
2. **Kaggle - Credit Card Fraud Detection:** Análise transacional e detecção de comportamentos suspeitos/fraudes.
3. **Kaggle - Loan Prediction Dataset:** Modelagem de concessão de crédito e perfil de risco de clientes.
4. **Documentação Oficial da Microsoft:** Guias de referência de funções DAX e Power Query.

---

## 🛠️ 3. Engenharia de Prompts e "Cicatrizes" (Troubleshooting)
Durante o desenvolvimento do plano, o principal desafio foi guiar o agente de IA para que saísse de respostas genéricas em inglês e adotasse rigorosamente o contexto do projeto em português, respeitando a estrutura local de arquivos.

### Prompts Testados & Evolução:
* **Prompt Inicial (Genérico):** *"Crie um plano de estudos de 30 dias sobre dados."*
  * *Resultado:* Resposta muito ampla, sem divisão clara de ferramentas por semana e menus/explicações gerados em inglês.
* **Prompt Estratégico (Com Contexto):** *"Por favor, leia as regras do meu projeto e responda a partir de agora apenas em português do Brasil. Estruture um cronograma separando por semanas: Semana 1 (Excel), Semana 2 (Power BI)..."*
  * *Resultado:* A IA realizou a varredura da pasta local (`README.md`, `cronograma.md`) e limitou o escopo exatamente ao que o projeto exigia.

### Cicatrizes (Troubleshooting):
* **Bloqueios de Segurança:** Durante a execução, o ambiente de desenvolvimento solicitou repetidas permissões de terminal (`Get-ChildItem -Force`). Foi necessário configurar a permissão de nível 3 (*"Yes, and always allow..."*) para garantir a fluidez do agente agêntico sem interrupções constantes.

---

## 📖 4. Miniguia de Estudo (Entrega Final)

### 📅 Resumo Estruturado do Cronograma (30 Dias)
* **Semana 1 — Excel:** Fórmulas básicas e avançadas (SOMA, MÉDIA, PROCV, XLOOKUP), Tabelas Dinâmicas e formatação de dados.
* **Semana 2 — Power BI:** Importação de dados (Exibição de Relatório, Dados e Modelo), conexões de fontes (Excel, CSV) e criação de primeiras visualizações (KPIs, barras, linhas).
* **Semana 3 — Power Query & Modelagem:** Relacionamentos entre tabelas, chaves primárias/estrangeiras, cardinalidade (1:N, N:N) e conceito de *Star Schema* (Tabela Fato vs. Tabelas Dimensão).
* **Semana 4 — SQL & Projeto Prático:** Consultas essenciais (SELECT, WHERE, JOINs) e consolidação do portfólio unindo as ferramentas com foco em dados de crédito/bancários.

### 🔤 Glossário de Conceitos-Chave
* **Tabela Fato:** Tabela que registra os eventos históricos ou transações quantificáveis (ex: vendas, movimentações bancárias).
* **Tabela Dimensão:** Tabela que contém os atributos de contexto que descrevem as entidades da Fato (ex: dados do cliente, produtos, calendário).
* **Power Query:** Ferramenta de conexão e tratamento de dados (ETL - Extração, Transformação e Carga) integrada ao Excel e Power BI.
* **Star Schema:** Modelo de organização de banco de dados onde uma tabela fato central se conecta a várias tabelas dimensão, formando o desenho de uma estrela.

### 🔄 Prompts Reutilizáveis para Revisão Futura
* **Para fixação prática:** *"Com base no cronograma da Semana [X], crie um exercício prático com dados fictícios para eu testar meu conhecimento em [Conceito]."*
* **Para revisão teórica:** *"Explique a diferença prática entre [Conceito A] e [Conceito B] usando uma analogia simples do cotidiano."*
