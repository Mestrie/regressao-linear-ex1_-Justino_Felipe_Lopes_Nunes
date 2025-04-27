# README

**Título:** Implementação de Regressão Linear com Visualização

**Descrição:**

Este Jupyter Notebook (`regressao_linear_ex1__Justino_Felipe_Lopes_Nunes_.ipynb`) implementa um modelo de regressão linear simples para prever o lucro de uma cidade com base em sua população. O script executa as seguintes etapas principais:

1.  **Exercícios de Aquecimento:** Implementa funções básicas do NumPy para familiarização com operações matriciais.
2.  **Carregamento e Plotagem de Dados:** Carrega e visualiza os dados de treinamento.
3.  **Função de Custo:** Implementa a função de custo do Erro Quadrático Médio (MSE) para avaliar o desempenho do modelo.
4.  **Descida do Gradiente:** Implementa o algoritmo da descida do gradiente para otimizar os parâmetros do modelo (theta).
5.  **Visualização dos Resultados:** Plota a linha de regressão ajustada, a convergência da função de custo e a superfície da função de custo para análise.

**Arquivos:**

* `regressao_linear_ex1__Justino_Felipe_Lopes_Nunes_.ipynb`: O Jupyter Notebook principal com a implementação da regressão linear.
* `ex1data1.txt`: Arquivo de dados contendo a população da cidade (em 10.000s) e o lucro (em 10.000 dólares).
* `Functions/`: Diretório contendo arquivos de função auxiliar:
    * `compute_cost.py`: Função para calcular o custo.
    * `gradient_descent.py`: Função para executar a descida do gradiente.
    * `plot_data.py`: Função para plotar os dados.
    * `warm_up_exercise.py`: Funções para os exercícios de aquecimento.
* `Figures/`: Diretório onde as figuras geradas pelo script são salvas.

**Requisitos:**

* Python 3.x
* Bibliotecas Python:
    * NumPy
    * Matplotlib

**Como Executar:**

1.  Certifique-se de que todos os arquivos (incluindo `ex1data1.txt`) estão no mesmo diretório ou nos diretórios especificados.
2.  Abra o notebook `regressao_linear_ex1__Justino_Felipe_Lopes_Nunes_.ipynb` usando o Jupyter Notebook ou JupyterLab.
3.  Execute todas as células do notebook sequencialmente. Os resultados, incluindo gráficos e valores de custo, serão exibidos no notebook.

**Estrutura do Código:**

O notebook está organizado da seguinte forma:

* **Células de Markdown:** Contêm texto explicativo, títulos e seções.
* **Células de Código:** Contêm código Python para:
    * Definir funções.
    * Carregar e processar dados.
    * Implementar o algoritmo de regressão linear.
    * Gerar gráficos.

**Explicação dos Gráficos Gerados:**

1.  **Convergência da Descida do Gradiente:** Mostra como a função de custo diminui ao longo das iterações da descida do gradiente.
2.  **Ajuste da Regressão Linear:** Plota os dados de treinamento e a linha de regressão linear ajustada.
3.  **Superfície da Função de Custo:** Visualização 3D da função de custo em relação aos parâmetros θ₀ e θ₁.
4.  **Contorno da Função de Custo:** Visualização 2D (contorno) da função de custo.
5.  **Contorno da Função de Custo com Trajetória do Gradiente:** Mostra a trajetória da descida do gradiente sobre o gráfico de contorno.
6.  **Superfície da Função de Custo com Trajetória 3D:** Visualização 3D da trajetória da descida do gradiente na superfície da função de custo.

**Observações:**

* O código segue as convenções PEP8 e utiliza docstrings no formato Doxygen.
* Os gráficos são salvos no diretório `Figures/`.
* A taxa de aprendizado (`alpha`) e o número de iterações são parâmetros que podem ser ajustados para observar diferentes comportamentos do algoritmo.
