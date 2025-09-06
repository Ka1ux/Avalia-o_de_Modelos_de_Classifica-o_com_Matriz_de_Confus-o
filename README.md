# Avaliação de Modelos de Classificação com Matriz de Confusão

## Descrição do Projeto
Este projeto demonstra como calcular e visualizar métricas de avaliação de modelos de classificação binária usando Python:

- Acurácia
- Precisão (Precision)
- Revocação (Recall)
- F1-Score

Além disso, o projeto mostra como criar e visualizar a **matriz de confusão**, essencial para entender os erros do modelo.

## Tecnologias Utilizadas
- Python 3
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Como Executar
1. Clone o repositório:

```bash
git clone https://github.com/seu-usuario/avaliacao_modelos.git
cd avaliacao_modelos
```

2. Instale as dependências:

```bash
pip install -r requirements.txt
```

3. Execute o script Python:

```bash
python matriz_confusao.py
```

## Explicação do Código
O script realiza os seguintes passos:

1. **Importação das bibliotecas**  
2. **Criação dos dados de exemplo** (`y_true` e `y_pred`)  
3. **Cálculo e visualização da matriz de confusão normalizada**  
4. **Cálculo das métricas de avaliação** (Acurácia, Precisão, Recall, F1-Score)  
5. **Exibição das métricas e heatmap da matriz de confusão**

## Saída Esperada
- **Matriz de Confusão Normalizada**  
- **Métricas de Avaliação** como:

```
Acurácia: 0.80
Precisão: 0.86
Revocação (Recall): 0.75
F1-Score: 0.80
```

## Conclusão
A matriz de confusão e as métricas fornecem uma visão clara sobre o desempenho do modelo e ajudam a identificar áreas de melhoria.
