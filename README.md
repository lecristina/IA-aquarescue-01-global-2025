# ✨ Título do Projeto
**AquaRescue – Previsão de Seca para Comunidades Vulneráveis com Machine Learning**
---
## Vídeo
* https://youtu.be/XeC0OsIRnw4

---
## Pitch geral
* https://youtu.be/72TR3quH2Dg

---
## 👥 Desenvolvedores

- Leticia Cristina Dos Santos Passos RM: 555241
- André Rogério Vieira Pavanela Altobelli Antunes RM: 554764
- Enrico Figueiredo Del Guerra RM: 558604

## 📆 Descrição do Problema
A escassez de água é um problema recorrente em regiões afastadas ou negligenciadas por sistemas de monitoramento. 
Esse projeto propõe uma solução preditiva para identificar, com antecedência, quais comunidades estão em risco de seca, permitindo a atuação de ONGs ou órgãos públicos para evitar crises.

## 📊 Metodologia

### Exploração de Dados
- Geramos uma base simulada de 60 dias para três comunidades.
- As variáveis incluem temperatura, umidade, chuva, vento, radiação e dados populacionais.
- Analisamos correlações e distribuições para entender padrões relacionados à seca.

### Levantamento de Hipótese
- Hipótese principal: valores baixos de umidade (<30%) e chuva (<0.5 mm) por vários dias são bons indicadores de risco de seca.

### Treinamento do Modelo
- Modelo escolhido: **Random Forest Classifier**.
- Justificativa: alta robustez, manuseio de variáveis mistas e boa performance sem necessidade de normalização.
- Dividimos os dados em 70% para treino e 30% para teste.

### Validação
- Avaliação com matriz de confusão e relatório de classificação.
- Métricas: acurácia, precision, recall e F1-score.

### Resultados
- O modelo previu corretamente a maioria dos dias de seca com boa precisão.
- Gráficos por comunidade mostram períodos com alta probabilidade de seca.

## 🧰 Conclusão
O AquaRescue se mostrou uma solução eficaz e replicável para previsão de secas.
Pode ser utilizado como ferramenta de apoio a decisão em contextos sociais e ambientais. Seu modelo é leve e facilmente integrável com sistemas meteorológicos.

## 💻 Execução
- Todo o código está no arquivo `aquarescue_seca_ML.ipynb`
- Pode ser executado diretamente no Google Colab.

## 📑 Tecnologias Utilizadas
- Python
- Pandas, NumPy, Matplotlib
- Scikit-learn
