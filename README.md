# Projeto - 1 Unidade

## 📋 Descrição do Projeto
[cite_start]Este projeto foi desenvolvido para a disciplina **Sistemas Inteligentes (PAM0466)**.

[cite_start]O objetivo é construir um modelo matemático de **Regressão Linear Múltipla** para prever a produção líquida horária de energia elétrica ($PE$) com base em sensores ambientais[cite: 11, 19]. 

## 🛠️ Contexto Técnico
[cite_start]Uma usina de ciclo combinado utiliza simultaneamente turbinas a gás e a vapor (ciclos Brayton e Rankine) para aumentar o rendimento energético, podendo chegar a 60% de eficiência[cite: 6, 7, 8]. [cite_start]O desafio do modelo é integrar variáveis de dois ciclos termodinâmicos distintos para prever a saída de potência[cite: 9].

### Variáveis do Sistema:
* [cite_start]**AT (Ambient Temperature):** Temperatura em °C[cite: 15].
* [cite_start]**V (Exhaust Vacuum):** Vácuo de escape em cm Hg[cite: 16].
* [cite_start]**AP (Ambient Pressure):** Pressão atmosférica em mbar[cite: 17].
* [cite_start]**RH (Relative Humidity):** Umidade relativa em percentagem[cite: 18].
* [cite_start]**PE (Net Hourly Electrical Energy Output):** Variável alvo em MW[cite: 19].

## 📊 Conjunto de Dados
[cite_start]O treinamento utiliza o dataset **UCI CCPP**, que contém **9.568 amostras** coletadas ao longo de 6 anos[cite: 13, 14].

## 🚀 Atividades Realizadas
O projeto seguiu o roteiro acadêmico proposto:
1. [cite_start]**Análise de Correlação:** Cálculo da relação entre variáveis independentes e a variável alvo ($PE$)[cite: 22].
2. [cite_start]**Estudo de Multicolinearidade:** Análise da correlação entre as variáveis independentes para identificar relações fortes entre elas[cite: 24, 25].
3. [cite_start]**Desenvolvimento do Modelo:** Construção da Regressão Linear Múltipla com divisão de dados em **80% para treino** e **20% para teste**[cite: 26, 27].
4. [cite_start]**Avaliação:** Uso das métricas $R^{2}$, RMSE e MAE para validar a adequação do modelo[cite: 28].

## 📂 Estrutura do Repositório
* `/codigos`: Contém o notebooks utilizados na análise.
* `/relatorio`: Documentação com as interpretações dos resultados e conclusões.

## 👥 Discentes
* **Maria Alice Ferreira Teixeira**
* **Thiago Luan Moreira Sousa**
