
# Desafio de Análise de Dados Financeiros Pessoais

[![Status - Em andamento](https://img.shields.io/badge/Status-Em%20andamento-yellow)](#9-prazo-de-entrega)
[![Nível - Básico](https://img.shields.io/badge/N%C3%ADvel-B%C3%A1sico-blue)](#1-contexto)
[![Ferramenta - Google Sheets](https://img.shields.io/badge/Ferramenta-Google%20Sheets-success)](#5-etapa-2--importa%C3%A7%C3%A3o-e-tratamento-no-google-sheets)
[![Foco - Dados Pessoais](https://img.shields.io/badge/Foco-Dados%20Financeiros%20Pessoais-orange)](#1-contexto)

---

## Visão geral rápida

| Pilar                | Descrição                                                                                             |
|----------------------|-------------------------------------------------------------------------------------------------------|
| Ferramenta           | Google Sheets                                                                                         |
| Duração dos dados    | Trimestre: Outubro/2025, Novembro/2025, Dezembro/2025                                                |
| Habilidades foco     | Coleta, tratamento, análise, visualização de dados e storytelling analítico                         |
| Entrega principal    | Dashboard financeiro interativo + apresentação de até 30 minutos                                     |
| Tipo de dado         | Dados financeiros pessoais (extratos bancários e/ou cartão)                                          |

---

## Sumário

1. [Contexto](#1-contexto)
2. [Termo de aceite](#2-termo-de-aceite)
3. [Objetivo do desafio](#3-objetivo-do-desafio)
4. [Etapa 1 – Coleta dos dados](#4-etapa-1--coleta-dos-dados)
5. [Etapa 2 – Importação e tratamento no Google Sheets](#5-etapa-2--importa%C3%A7%C3%A3o-e-tratamento-no-google-sheets)
6. [Etapa 3 – Análises com tabelas dinâmicas](#6-etapa-3--an%C3%A1lises-com-tabelas-din%C3%A2micas)
7. [Etapa 4 – Criação do dashboard](#7-etapa-4--cria%C3%A7%C3%A3o-do-dashboard-no-google-sheets)
8. [Apresentação do dashboard](#8-apresenta%C3%A7%C3%A3o-do-dashboard)
9. [Prazo de entrega](#9-prazo-de-entrega)
10. [Entregáveis finais](#10-entreg%C3%A1veis-finais)

---

## 1. Contexto

Este desafio foi criado para que você exercite, na prática, habilidades de **coleta, tratamento, análise e visualização de dados**, utilizando seus **próprios dados financeiros** como base. A ideia é que, além de treinar aspectos técnicos, você desenvolva **criatividade e senso analítico**, gerando **insights reais** sobre sua vida financeira.

> Pense neste desafio como um mini-projeto real de analytics, só que com um "cliente" muito especial: você mesmo(a).

---

## 2. Termo de aceite

A participação neste desafio **envolve o uso de dados pessoais e financeiros seus** (por exemplo, extratos bancários).

Por isso, antes de iniciar, você precisa me enviar um **aceite formal** por escrito, confirmando que:

- Está ciente de que utilizará seus próprios dados financeiros;
- Autoriza o uso desses dados **apenas para fins de estudo**;
- Compromete-se a **proteger a confidencialidade** dos seus dados, não compartilhando arquivos ou prints sensíveis com outras pessoas além do contexto combinado.

> **Ação obrigatória**: Enviar uma mensagem de aceite explícito (por exemplo, por e-mail ou chat) antes de começar o desafio.

---

## 3. Objetivo do desafio 🎯

O objetivo principal é que você:

- Exercite a **criatividade analítica**, escolhendo formas interessantes de enxergar seus dados;
- Desenvolva **insights sobre seu próprio comportamento financeiro**;
- Pratique **tratamento de dados**, **uso de fórmulas**, **tabelas dinâmicas** e **gráficos** no Google Sheets;
- Construa um **dashboard** claro, visual e objetivo para apresentar seus resultados.

> No final, você deve ser capaz de contar a história do seu trimestre financeiro com dados, gráficos e indicadores claros.

---

## 4. Etapa 1 – Coleta dos dados

Você deverá extrair seus **extratos bancários** (conta corrente e/ou cartão, conforme fizer sentido para você) referentes aos **três últimos meses fechados**:

- Outubro/2025  
- Novembro/2025  
- Dezembro/2025  

### Requisitos desta etapa

- Extrair os dados em formato que permita importação no Google Sheets (CSV, XLSX ou similar);
- Garantir que os dados contenham, no mínimo:
  - Data da transação
  - Descrição / estabelecimento / tipo de transação
  - Valor
  - Tipo (crédito/receita ou débito/despesa), se existir
- Se necessário, fazer **ajustes manuais posteriores** no Google Sheets para complementar ou padronizar a informação.

> Dica: deixe todos os arquivos organizados em uma pasta única, com nomes padronizados (por exemplo: `extrato_conta_out_2025.csv`, `cartao_dez_2025.xlsx`).

---

## 5. Etapa 2 – Importação e tratamento no Google Sheets

Todo o trabalho deverá ser feito **exclusivamente no Google Sheets**.

### Passos esperados

1. **Importar os extratos** dos três meses para uma ou mais abas no Google Sheets;
2. **Padronizar e tratar os dados**, por exemplo:
   - Padronizar nomes de estabelecimentos;
   - Criar uma coluna de **categoria** (ex.: Alimentação, Moradia, Transporte, Lazer, Saúde, Educação, Investimentos, etc.);
   - Identificar se é **receita** ou **despesa**;
   - Tratar sinais de valor (positivo/negativo);
   - Ajustar datas, formatos numéricos e textos;
3. Utilizar **fórmulas** e/ou **ajustes manuais** conforme necessário, desde que o resultado final fique **limpo, coerente e utilizável** para análise.

> Objetivo desta etapa: transformar extratos "crus" em uma base analítica organizada.

---

## 6. Etapa 3 – Análises com tabelas dinâmicas

Com os dados tratados, você deverá criar **tabelas dinâmicas** no Google Sheets para responder a alguns pontos mínimos. Você pode (e é desejável que você) crie análises adicionais além das listadas abaixo.

### Análises mínimas obrigatórias

Crie tabelas dinâmicas (e, se necessário, colunas auxiliares) para obter pelo menos:

1. **Média de receitas mensais** no trimestre (out/25, nov/25, dez/25);  
2. **Média de gastos mensais** no trimestre;
3. **Top 5 maiores gastos por categoria** no trimestre;
4. **Top 5 maiores gastos por estabelecimento/comércio/serviço** no trimestre;
5. **Total de transações realizadas no trimestre** (quantidade de linhas/lançamentos);
6. **Volume total movimentado no trimestre** (somatório de receitas + despesas, ou detalhando separadamente, se preferir);
7. **Volume investido ou poupado no trimestre, em %**  
   - Caso você tenha feito investimentos ou reservas, estime:  
     - Quanto do total de receitas foi investido/poupado (em percentual).

Você pode ajustar nomes, formatos e detalhes dessas análises desde que a **essência das informações** acima esteja presente.

> Priorize métricas que ajudem a responder perguntas como: "Onde mais gasto?", "Quanto consigo guardar?", "Quais meses foram mais críticos?".

---

## 7. Etapa 4 – Criação do dashboard no Google Sheets

Com base nas tabelas dinâmicas e nas análises geradas, você deverá construir um **dashboard** em uma aba específica do Google Sheets.

### Requisitos do dashboard

- O dashboard deve ser **claro, visual e focado em insights**;
- Deve conter **no mínimo** os seguintes tipos de gráficos:
  - **1 gráfico de barras**;
  - **1 gráfico de colunas**;
  - **1 gráfico de pizza**;
- Deve incluir um **gráfico comparativo do trimestre**, com:
  - Uma série representando os **gastos** por mês (por exemplo, colunas);
  - Uma série representando as **receitas** por mês (por exemplo, linha vermelha), permitindo visualizar o **equilíbrio (ou desequilíbrio) entre receitas e despesas** no período;
- Deve destacar, de alguma forma:
  - Os **maiores gastos por categoria**;
  - Os **maiores gastos por estabelecimento**;
  - Os **principais indicadores do trimestre** (resumo numérico).

Você tem liberdade para organizar o layout da aba do dashboard, cores, legendas e destaques da forma mais intuitiva e profissional possível.

> Pense no dashboard como a "tela inicial" de um produto de análise financeira pessoal.

---

## 8. Apresentação do dashboard

Após a conclusão do desafio, você deverá:

- **Selecionar um horário** para apresentar o dashboard;
- Realizar uma **apresentação de até 30 minutos** via **Google Meet**;
- Focar a apresentação em:
  - Explicar os **gráficos escolhidos** e por que os escolheu;
  - Destacar os **principais insights** obtidos;
  - Comentar decisões de **tratamento de dados e modelagem** (como categorização, filtros, métricas usadas);
  - Pontuar possíveis **melhorias futuras** no processo de análise e no seu próprio comportamento financeiro.

> Trate essa apresentação como se estivesse explicando um case de dados em um contexto profissional.

---

## 9. Prazo de entrega 📅

[![Prazo - 18/01/2026](https://img.shields.io/badge/Prazo-18%2F01%2F2026-critical)](#9-prazo-de-entrega)

- **Data limite para conclusão do desafio:** **18/01/2026**  
- Até esta data, você deve:
  - Finalizar o Google Sheets com dados tratados, tabelas dinâmicas e dashboard;
  - Enviar o link da planilha (com as permissões adequadas);
  - Combinar e confirmar o **horário da apresentação** no Google Meet.

> Sugestão: defina marcos intermediários (coleta, tratamento, análises, dashboard) para não deixar tudo para a última hora.

---

## 10. Entregáveis finais

1. **Google Sheets** contendo:
   - Abas com dados brutos/importados;
   - Abas com dados tratados, se forem separadas;
   - Abas com tabelas dinâmicas;
   - Aba do **dashboard final**.
2. **Apresentação de 30 minutos no Google Meet**, focada:
   - No **dashboard**;
   - Nos **insights financeiros**;
   - Nas **decisões de modelagem e visualização de dados**.

---

## Roteiro sugerido de execução

1. Enviar o **termo de aceite**.
2. Coletar e organizar os **extratos dos 3 meses**.
3. Montar a **base tratada** no Google Sheets.
4. Criar as **tabelas dinâmicas** e indicadores mínimos.
5. Transformar tudo em um **dashboard visual**.
6. Preparar a **apresentação de 30 minutos**, com foco em história e insights.

---

Use este desafio como uma oportunidade para se enxergar como um(a) verdadeiro(a) **analista de dados**, aplicando técnicas que você usaria em qualquer empresa, mas agora com algo que impacta diretamente a sua vida: **seu próprio dinheiro**.
