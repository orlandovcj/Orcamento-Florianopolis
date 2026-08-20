# Análise da LOA 2026 de Florianópolis — Orçamento e Finanças Governamentais

Estudo de caso para a disciplina **Orçamento e Finanças Governamentais**, do curso de
**Especialização em Gestão Pública Estratégica** do Instituto Federal de Educação, Ciência
e Tecnologia do Amazonas (IFAM) — *Campus* Presidente Figueiredo.

| | |
|---|---|
| **Componente Curricular** | Orçamento e Finanças Governamentais (30h) |
| **Curso** | Especialização em Gestão Pública Estratégica |
| **Instituição** | IFAM – Campus Presidente Figueiredo |
| **Ministrante** | Prof. Dr. Jackson Pantoja Lima |
| **Discente** | Orlando Vieira de Castro Junior |
| **Ano/Semestre** | 2026/1 |
| **Avaliação** | 03 (período 03 a 21.08) — 10 pontos |

## Tema

Rigidez Fiscal, Discricionariedade e Eficiência Alocativa: Análise Crítica da LOA 2026 de
Florianópolis.

## Sobre o projeto

Este repositório contém um **notebook Jupyter** que analisa a Lei Orçamentária Anual (LOA)
2026 do município de Florianópolis/SC, a partir da base de receitas e despesas consolidadas.
A análise é organizada em seções que exploram:

1. **Configurações visuais e bibliotecas** — padrão acadêmico/profissional para os gráficos.
2. **Carga de dados** — leitura da base `loa_2026_florianopolis_consolidada.csv`.
3. **Autonomia tributária** — composição da arrecadação própria (IPTU, ISSQN, ITBI, IRRF etc.).
4. **Composição das receitas correntes** — autonomia *vs.* dependência (FPM/ICMS/FUNDEB).
5. **Rigidez de despesa** — peso de pessoal, custeio, juros, investimentos e reserva.
6. **Conformidade com a LRF** — simulação dos limites legais de gasto com pessoal para
   municípios (alerta 54%, prudencial 57% e máximo 60% da RCL).

Os totais e subtotais de cada categoria são calculados no próprio notebook, a partir das
rubricas de detalhe da base, evitando a dupla contagem de linhas de total.

## Arquivos

| Arquivo | Descrição |
|---|---|
| `orcamento.ipynb` | Notebook com as análises e simulações. |
| `loa_2026_florianopolis_consolidada.csv` | Base de dados da LOA 2026 de Florianópolis. |
| `Estudo de Caso - Orlando Castro.pdf` | Estudo de caso com as conclusões apoiadas nos resultados deste notebook. |

## Como executar

1. Instale as dependências:

   ```bash
   pip install pandas matplotlib numpy jupyter
   ```

2. Abra o notebook:

   ```bash
   jupyter notebook orcamento.ipynb
   ```

3. Execute as células em ordem (Kernel → Restart & Run All).

> As conclusões e a discussão acadêmica completas estão no arquivo
> `Estudo de Caso - Orlando Castro.pdf`.