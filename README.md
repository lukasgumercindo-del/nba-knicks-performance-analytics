# 🏀 New York Knicks & Jalen Brunson: Do Script em Python ao Dashboard Nível NBA Analytics

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![NBA Data](https://img.shields.io/badge/NBA_API-Stats-blue?style=for-the-badge)

---

## 📖 A História por Trás do Projeto

No Brasil, o futebol domina a paixão nacional. Mas para os entusiastas da **NBA (a liga profissional de basquete norte-americana)**, cada partida gera um volume massivo de dados estatísticos. O basquete é um dos esportes mais quantificáveis do mundo: cada passe, arremesso, vitória e derrota fica registrado em milissegundos.

### 🗽 O Contexto: O New York Knicks e o Fenômeno Jalen Brunson

O **New York Knicks** é uma das franquias mais tradicionais e valiosas da NBA, fundada na década de 1940 na cidade de Nova York. Apesar da sua relevância histórica, o time viveu décadas de altos e baixos na busca pelo título.

Nos últimos anos, a chegada do armador **Jalen Brunson** (camisa #11) mudou o patamar da equipe. Com performances memoráveis de pontuação e liderança em quadra, Brunson reacendeu a esperança da torcida nova-iorquina.

---

## 💡 O Desafio de Negócio / Dados

Como transformar décadas de registros históricos e métricas complexas da NBA em um **painel visual intuitivo, executivo e com estética de transmissão de TV**?

O objetivo deste projeto foi construir uma solução **End-to-End** (de ponta a ponta):
1. **Extrair** dados oficiais da API oficial da NBA (`nba_api`).
2. **Transformar e Modelar** o histórico da franquia e do atleta.
3. **Desenvolver** um dashboard interativo no Power BI com foco em **Storytelling de Dados** e altas práticas de **UI/UX**.

---

## 🛠️ O Pipeline de Dados (End-to-End)

```
[ NBA API (Python) ] ──> [ Tratamento de Dados (Power Query/DAX) ] ──> [ Dashboard Interativo (Power BI) ]
```

### 1️⃣ Extração de Dados (`nba_api` & Python)
* Conexão via scripts Python com a API oficial da NBA para raspagem e extração do histórico completo de jogos do New York Knicks desde a década de 1980, além da base detalhada de pontuação jogo a jogo de Jalen Brunson.

### 2️⃣ Tratamento e Modelagem de Dados
* **Limpeza e Padronização:** Tratamento de datas, remoção de duplicatas e criação de chaves primárias/estrangeiras.
* **Métricas em DAX (Data Analysis Expressions):** Criação de medidas para cálculo de taxa de vitória (*Win Rate %*), média de pontos por jogo (PTS) e assistências (AST).
* **Classificação por Local:** Segmentação dos jogos entre "Casa" (Madison Square Garden) e "Fora".

### 3️⃣ Design & UX/UI
* **Identidade Visual Temática:** Aplicação estrita da paleta oficial do Knicks — Azul Marinho Escuro (`#0A192F`), Laranja (`#F58426`), Azul Royal (`#006BB6`) e Branco.
* **Layout Escuro (Dark Mode):** Redução de fadiga visual e alto destaque para métricas em telas de apresentação.
* **Padrão Esportivo Profissional:** Integração de recortes em transparência (PNG) e organização modular em containers para leitura fluida.

---

## 📊 Estrutura e Funcionalidades do Dashboard

O relatório é composto por **2 Páginas Complementares**:

### 1️⃣ Página 1: Visão Geral da Franquia (Desempenho Histórico)
* 🎯 **Métricas Executivas (KPIs):** Total de jogos disputados, vitórias totais, derrotas e taxa geral de vitórias (*Win Rate*).
* 🏠 **Desempenho por Local (Casa vs. Fora):** Comparativo visual direto mostrando o impacto da torcida no Madison Square Garden frente aos jogos fora de casa.
* 📈 **Evolução Histórica por Temporada (1980 - Atual):** Gráfico de área temporal que evidencia as "Eras de Ouro" e os períodos de reconstrução do time ao longo dos anos.
* ⚔️ **Maiores Taxas de Vitória por Adversário (Top 10):** Análise dos confrontos em que o Knicks possui o maior domínio histórico na liga.

### 2️⃣ Página 2: Análise Individual — Jalen Brunson (#11)
* ⚡ **Métricas do Atleta:** Média de Pontos por Jogo (26.04 PTS), Média de Assistências (6.80 AST) e Recorde Pessoal de Pontuação (47 PTS).
* 📉 **Linha do Tempo de Pontuação:** Gráfico detalhado mostrando a consistência e os picos de pontuação jogo a jogo da estrela do time.

---

## 🔑 Termos Úteis para Não-Entusiastas do Basquete

| Termo em Inglês | O que significa? | Equivalente no Futebol |
| :--- | :--- | :--- |
| **Matchup** | Confronto contra um adversário específico | "Confronto Direto / Retrospecto" |
| **Win Rate (%)** | Percentual de vitórias em relação ao total de jogos | "Aproveitamento %" |
| **PTS (Points)** | Pontos marcados em uma partida | "Gols Marcados" |
| **AST (Assists)** | Passes que resultam em pontuação direta | "Assistências para Gol" |
| **Casa vs. Fora** | Jogar no próprio ginásio ou no ginásio do rival | "Mando de campo" |

---

## 💻 Como Reproduzir / Abrir o Projeto

1. Baixe o arquivo `.pbix` na pasta do repositório.
2. Abra no **Power BI Desktop** (versão mais recente recomendada).
3. Navegue entre as duas páginas utilizando os botões do relatório.

---

## 🧑‍💻 Autor

Desenvolvido por **Lucas Gumercindo**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lucas-gumercindo-9bbb791ab/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/lukasgumercindo-del)
