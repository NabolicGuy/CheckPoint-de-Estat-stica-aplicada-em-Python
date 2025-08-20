# 📈 Estatística & Modelagem — Checkpoint (2º semestre)

Notebook com três estudos aplicados que combinam **modelagem matemática**, **integração** e **análise estatística/descritiva**, usando Python (NumPy, SciPy e Matplotlib). O objetivo é transformar problemas reais em **métricas interpretáveis** e **visualizações** que apoiam decisão.

## 🔬 Escopo do que foi feito

1) **Fluxo financeiro (Resistência)**
   - Modelagem de **faturamento F(t)** e **despesas D(t)** com polinômios.
   - Lucro pontual: **L(t) = F(t) − D(t)**.
   - **Lucro acumulado** no período via **integração definida**: ∫ L(t) dt.
   - Gráfico do lucro e interpretação do sinal/área (lucro vs. prejuízo).

2) **Operação de coleta (orgânico vs. reciclável)**
   - Duas funções O(t) e R(t) para volumes coletados.
   - **Diferença acumulada** entre séries pela **área entre curvas**: ∫ |O(t) − R(t)| dt.
   - Visualização comparativa e leitura de dominância ao longo do tempo.

3) **Desigualdade de renda (Lothal)**
   - Curva de **Lorenz** modelada por um polinômio g(x) e **normalizada** em [0,1].
   - **Índice de Gini** por integração numérica: **G = 1 − 2·Área(Lorenz)**.
   - Comparação com a distribuição **ideal** (linha de 45°) e discussão dos desvios.

## 🧠 Conceitos demonstrados
- Modelagem por **funções polinomiais** e leitura de parâmetros.
- **Integração definida** para transformar taxas/valores pontuais em **acumulados**.
- **Área sob a curva** e **área entre curvas** como métricas de impacto/erro.
- **Curva de Lorenz** e **Índice de Gini** como medidas de **desigualdade**.
- **Integração numérica** (SciPy `quad`, NumPy `trapz`) e **visualização** (Matplotlib).

## 🛠️ Stack
- **Python**: NumPy, SciPy, Matplotlib

> Resultado: um passo a passo que conecta **fórmulas → integrais → métricas → gráficos**, evidenciando domínio prático em **estatística descritiva**, **cálculo de integrais** e **interpretação de indicadores**.
