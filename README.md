# Previsão de Preços de Imóveis com Regressão Linear

> ℹ️ **NOTE:** Projeto desenvolvido como parte do meu aprendizado em Ciência de Dados, para a formação de Data Science do programa [ONE - Oracle Next Educacion](https://www.oracle.com/br/education/oracle-next-education/) realizada na plataforma [Alura](https://www.alura.com.br/), com foco em modelagem preditiva e análise exploratória de dados.

Este projeto tem como objetivo aplicar técnicas de Regressão Linear para estimar os preços de imóveis no município do Rio de Janeiro com base em variáveis como área do imóvel, distância até a praia e distância até a farmácia.

## 🏘️ Sobre o dataset
- **Tamanho**: 5.000 imóveis
- **Variáveis**:
  - `Valor`: Preço de oferta do imóvel (R$)
  - `Area`: Área útil do imóvel (m²)
  - `Dist_Praia`: Distância até a praia (km)
  - `Dist_Farmacia`: Distância até a farmácia mais próxima (km)

## 🧪 Etapas do projeto
1. Análise exploratória dos dados
2. Transformação logarítmica das variáveis para adequação à regressão linear
3. Treinamento de modelos com `statsmodels` e `scikit-learn`
4. Avaliação de performance via R² e análise dos resíduos
5. Interpretação dos coeficientes (elasticidade dos preços)

## 📊 Principais insights
- A área do imóvel tem impacto **positivo** e significativo no preço.
- A distância até a praia tem impacto **negativo**, confirmando a valorização da proximidade do litoral.
- A variável "distância até farmácia" foi descartada por não apresentar significância estatística.

## 🔧 Tecnologias utilizadas
- Python
- Pandas
- Seaborn & Matplotlib
- NumPy
- Scikit-learn
- Statsmodels

## 📈 Resultado
- **R² (treino):** 0.805
- **R² (teste):** 0.79

## 🚀 Simulador
O projeto também inclui um simulador simples onde é possível prever o preço estimado de um imóvel com base na área e distância da praia.

---


<p align="center">
<img 
    src="src/projetos_banner.gif"
    >
