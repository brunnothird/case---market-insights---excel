# 🎓 Case Customer Insights: Diagnóstico de Acolhimento do Calouro (Grupo Cogna)

## 📌 Sobre o Projeto
Este repositório contém a análise estatística e preditiva dos dados de onboarding de alunos ingressantes nas instituições de Ensino Superior do grupo Cogna Educação. O objetivo central deste projeto foi converter dados brutos de pesquisa de experiência do cliente (CX/UX) em direcionamentos estratégicos de negócio, identificando os principais gargalos e fatores de sucesso na retenção de alunos nas primeiras semanas da jornada acadêmica.

O projeto avalia o desempenho de grandes marcas educacionais, tais como **Anhanguera, Unopar, Pitágoras, Uniderp, Unic e Unime**, mapeando a percepção de valor por modalidade de ensino e discriminando os componentes da régua de comunicação institucional.

---

## 🛠️ Tecnologias, Ferramentas e Boas Práticas
* **Excel Avançado & Tabelas Dinâmicas:** Estruturação de matrizes multidimensionais, cruzamentos por segmentação de mercado e cálculo automatizado de indicadores de lealdade.
* **Data Cleaning (Tratamento de Nulos e Textos):** Tratamento de dados nulos nas colunas de métricas centrais e padronização de variáveis de texto categóricas para valores numéricos contínuos via recursos de transformação e fórmulas lógicas (`SE`, `OU`, `VALOR`, `ÉERROS`).
* **Customer Experience Metrics:** Implementação prática e cálculo de frameworks globais de mercado:
    * **NPS (Net Promoter Score)**
    * **CSAT (Customer Satisfaction Score)**
* **Storytelling com Dados:** Estruturação da apresentação executiva orientada a tomadores de decisão (C-Level).

---

## 📊 Principais Resultados Obtidos
Após o saneamento e higienização da base de dados (composta por **2.549 registros válidos**), os seguintes indicadores-chave de performance (KPIs) foram consolidados:

### 1. Indicadores Macro (Geral)
* **NPS Geral:** `39.3` (Zona de Aperfeiçoamento)
    * *Share de Clientes:* **58.8%** Promotores | **21.7%** Neutros | **19.5%** Detratores
* **Média Geral CSAT (Satisfação Geral - P2):** `8.4 / 10`

### 2. Visão por Marca (Matriz de Desempenho)
| Marca | Share de Base | % Promotores | % Neutros | % Detratores | NPS Final |
| :--- | :---: | :---: | :---: | :---: | :---: |
| **Unopar** | 27.2% | 64.8% | 20.5% | 14.7% | **50.1** *(Benchmark)* |
| **Pitágoras** | 1.2% | 58.1% | 25.8% | 16.1% | **41.9** |
| **Anhanguera** | 68.1% | 57.0% | 21.7% | 21.3% | **35.7** |
| **Uniderp** | 1.3% | 50.0% | 35.3% | 14.7% | **35.3** |
| **Unic** | 1.0% | 38.5% | 42.3% | 19.2% | **19.2** |
| **Unime** | 1.1% | 50.0% | 17.9% | 32.1% | **17.9** *(Ponto Crítico)* |

### 3. Diagnóstico por Atributo (Médias de Satisfação da Régua)
* **Recepção na Unidade:** `4.60 / 5.0`
* **Aula Inaugural:** `4.42 / 5.0`
* **Acesso ao Portal Digital do Aluno (PDA):** `4.40 / 5.0`
* **Acesso ao Ambiente Virtual de Aprendizagem (AVA):** `4.38 / 5.0`
* **Volume de Comunicações Recebidas:** `4.30 / 5.0` *(Menor nota - Saturação de canal)*

---

## 💡 Principais Insights e Recomendações Estratégicas
1.  **Gargalo Financeiro no Onboarding:** A análise qualitativa dos comentários de alunos detratores apontou recorrentes surpresas negativas e inconsistências no valor do primeiro boleto de mensalidade gerado pelas unidades, gerando atritos imediatos de confiança.
2.  **Fadiga de Comunicação:** O atributo de menor avaliação foi a quantidade de comunicações enviadas (`4.30`). Recomenda-se a imediata orquestração de canais para unificar e centralizar os disparos (E-mail, SMS, WhatsApp), mitigando o spam institucional.
3.  **Replicação de Práticas de Sucesso:** A marca **Unopar** desponta na Zona de Qualidade (`NPS 50.1`). É imperativo conduzir uma auditoria de processos (*internal benchmark*) para replicar sua esteira de atendimento e acolhimento humano para as marcas **Unime** e **Unic**, que sofrem com alta taxa de detratores.

---

## 🤖 Declaração de Uso Ético de Inteligência Artificial
Em total conformidade com os pré-requisitos estabelecidos no processo seletivo, declara-se que este projeto utilizou soluções de **Inteligência Artificial de forma ética e assistida** atuando estritamente como um copiloto analítico. 

A tecnologia foi empregada nas seguintes frentes:
1.  **Saneamento de Dados:** Auxílio no mapeamento lógico e desenho estrutural da fórmula de higienização de nulos e conversão de textos mistos (`Muito satisfeito5` / `Pouco satisfeito1`) no ecossistema do Excel.
2.  **Storytelling:** Estruturação e ordenação do fluxo narrativo lógico da apresentação de slides para garantir concisão, clareza e foco em dados de negócio.
3.  **Refinamento Técnico:** Revisão de semântica técnica de CX e garantia de consistência metodológica entre o tratamento estatístico da base bruta e os resultados finais apresentados.

---

## 📂 Estrutura do Repositório
* `README.md`: Documentação técnica principal do projeto.
* `BD_Acolhimento_Teste - Case.xlsx`: Pasta contendo a base de dados em formato de planilha Excel higienizada.
* `Jornada do Calouro 2023 - Insights Acadêmicos - Case`: Apresentação executiva final em formato PDF/HTML contendo os slides e visualizações para a banca avaliadora.
