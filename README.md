[10:34, 30/05/2025] Laura Eletrocardio: Narrativa com Dados: Como o Nível de Escolaridade Impacta a Renda no Brasil?


---

1) Base de Dados Utilizada

Utilizaremos a Pesquisa Nacional por Amostra de Domicílios Contínua (PNAD Contínua) do IBGE, acessível publicamente no site do IBGE ou via o pacote sidra/pandas com dados extraídos da plataforma SIDRA.

Para simplificação neste exercício, usaremos uma versão resumida da base PNAD 2022 disponibilizada em plataformas como Kaggle (com colunas como renda, escolaridade, idade, UF, gênero).


---

2) Pergunta Orientadora

Existe relação entre o nível de escolaridade e a renda no Brasil?

Essa pergunta visa entender se indivíduos com maior escolaridade ganham salários significativamente maiores, e como isso varia por gênero ou região.


---

3) Análise e Visualizações com Python

Abaixo, o código Python que realiza a análise com visualizações (pandas + seaborn/matplotlib):
[10:45, 30/05/2025] Laura Eletrocardio: # 📊 Projeto de Análise e Visualização do Conhecimento

*Componente Curricular:* Projeto e Análise de Visualização do Conhecimento  
*Professora:* Carolina Toledo Ferraz  
*Curso:* Tecnologia em Ciência de Dados  
*Aula 4 – Narrativa com Dados*

---

## 🎯 Pergunta Orientadora

*Existe uma relação significativa entre escolaridade e renda no Brasil?*

Este projeto busca responder essa pergunta por meio de análise exploratória e visualização de dados utilizando uma base derivada da PNAD (Pesquisa Nacional por Amostra de Domicílios – IBGE).

---

## 🗂️ Dataset

A base de dados simula informações da PNAD, contendo variáveis como:
- Anos de estudo
- Nível educacional
- Renda mensal

📁 *Fonte:* [PNAD - Dados simulados (GitHub)](https://github.com/rafaelnduarte/datasets)

---

## 📌 Objetivo

Explorar a hipótese de que a escolaridade impacta positivamente a renda das pessoas no Brasil, utilizando técnicas de data storytelling com visualizações e estrutura narrativa.

---

## 📊 Visualizações Criadas

1. *Gráfico de Dispersão:* Relação entre anos de estudo e renda
2. *Boxplot:* Distribuição da renda por nível educacional
3. *Gráfico de Barras:* Média de renda por nível educacional

---

## ✍️ Estrutura Narrativa

O notebook contém uma narrativa em Markdown baseada nos seguintes elementos:

| Elemento | Conteúdo |
|---------|----------|
| *Personagem* | Cidadãos brasileiros economicamente ativos |
| *Cenário* | Desigualdade de renda no Brasil e busca por ascensão via educação |
| *Enredo* | Como a escolaridade se conecta com a renda? |
| *Conflito* | Escolaridade explica toda a variação de renda? |
| *Desenvolvimento* | Visualizações e análise estatística |
| *Clímax* | A escolaridade influencia, mas não é o único fator |
| *Desfecho* | A educação importa, mas políticas públicas são necessárias para equidade |

---

## 🧰 Ferramentas Utilizadas

- Python 3
- pandas
- seaborn
- matplotlib
- Jupyter Notebook

