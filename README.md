# Projeto - 1 Unidade

## 📋 Descrição do Projeto
Este projeto foi desenvolvido para a disciplina **Sistemas Inteligentes (PAM0466)**.

O objetivo é construir um modelo matemático de **Regressão Linear Múltipla** para prever a produção líquida horária de energia elétrica ($PE$) com base em sensores ambientais. 

## 🛠️ Contexto Técnico
Uma usina de ciclo combinado utiliza simultaneamente turbinas a gás e a vapor (ciclos Brayton e Rankine) para aumentar o rendimento energético, podendo chegar a 60% de eficiência. O desafio do modelo é integrar variáveis de dois ciclos termodinâmicos distintos para prever a saída de potência.

### Variáveis do Sistema:
* **AT (Ambient Temperature):** Temperatura em °C.
* **V (Exhaust Vacuum):** Vácuo de escape em cm Hg.
* **AP (Ambient Pressure):** Pressão atmosférica em mbar.
* **RH (Relative Humidity):** Umidade relativa em percentagem.
* **PE (Net Hourly Electrical Energy Output):** Variável alvo em MW.

## 📊 Conjunto de Dados
O treinamento utiliza o dataset **UCI CCPP**, que contém **9.568 amostras** coletadas ao longo de 6 anos.

## 🚀 Atividades Realizadas
O projeto seguiu o roteiro acadêmico proposto:
1. **Análise de Correlação:** Cálculo da relação entre variáveis independentes e a variável alvo ($PE$).
2. **Estudo de Multicolinearidade:** Análise da correlação entre as variáveis independentes para identificar relações fortes entre elas.
3. **Desenvolvimento do Modelo:** Construção da Regressão Linear Múltipla com divisão de dados em **80% para treino** e **20% para teste**.
4. **Avaliação:** Uso das métricas $R^{2}$, RMSE e MAE para validar a adequação do modelo.

## 📂 Estrutura do Repositório
* `/codigos`: Contém o notebooks utilizados na análise.
* `/relatorio`: Documentação com as interpretações dos resultados e conclusões.

## 👥 Discentes
* **Maria Alice Ferreira Teixeira**
* **Thiago Luan Moreira Sousa**
