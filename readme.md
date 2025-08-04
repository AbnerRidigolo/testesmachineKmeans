# Análise de Indicadores por País (1997–2011) + Cálculo de Derivadas

Este projeto foi desenvolvido como parte de um exercício prático utilizando o Google Colab para análise exploratória de dados e cálculo de derivadas.

## 📁 Arquivos

- `dados_1997_2011_paises_csv.csv`: base de dados com indicadores de países entre 1997 e 2011.
- `Testemachine.ipynb`: notebook com carregamento dos dados, análise estatística e resolução de derivadas.

## 🚀 Etapas do Projeto

1. **Carregamento dos dados**  
   Utilização do `pandas` para importar e visualizar os dados de países com codificação `latin1`.

2. **Análise Estatística do Brasil**  
   Foram calculadas as seguintes medidas para as colunas `idh` e `competitividade_indice`:  
   - Média  
   - Mediana  
   - Mínimo  
   - Máximo  

3. **Análise Estatística da Alemanha**  
   As mesmas medidas foram aplicadas ao país Alemanha, permitindo uma comparação direta com o Brasil.

4. **Discussão das Diferenças**  
   Análise qualitativa sobre as principais discrepâncias entre os indicadores dos dois países.

5. **Cálculo de Derivadas**  
   Derivadas de duas funções foram resolvidas simbolicamente:
   - A) \( f(x) = 2x^2 + 5x + 3 \)
   - B) \( f(x) = (5x + 3) \cdot (3x - 2) \)

## 🧮 Tecnologias e Bibliotecas

- Python 3
- Pandas
- Google Colab
- SymPy (para cálculo simbólico)

## 📝 Resultados

- O Brasil apresentou valores menores de IDH e competitividade em comparação à Alemanha na média do período.
- As derivadas foram calculadas corretamente utilizando regras básicas do cálculo diferencial.

## 📌 Como executar

1. Faça o upload do notebook no [Google Colab](https://colab.research.google.com/)
2. Envie também o arquivo CSV no mesmo diretório.
3. Execute as células na ordem.

Desenvolvido como parte de um exercício acadêmico na disciplina de Ciência de Dados.

