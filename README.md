# Inteligência Artificial

Roteiros, exercícios e trabalhos da disciplina de Inteligência Artificial (Engenharia de Computação, UFMT, 2025.1), em Python: busca, agentes lógicos, regressão, redes neurais, SVM e CNN.

## Estrutura
- `roteiros/`: notebooks dos roteiros, numerados na ordem da disciplina (`roteiro-00-python` até `roteiro-12-cnn`).
- `exercicios/`: implementações próprias de agentes lógicos, regressão polinomial e regressão logística.
- `redes-neurais/`: rede neural para o MNIST (`rede_neural_1.py` com pesos prontos, `rede_neural_2.py` com treinamento), os dados `mnistdata.mat` e `pesos.mat`, e `controle_braco_serial.py` (interface Tkinter que envia ângulos de servo pela serial).
- `trabalhos/`:
  - `tp1-busca-a-estrela-8-puzzle.ipynb` e `tp1-scripts/` (busca exaustiva e árvore de Monte Carlo para o 8-puzzle);
  - `tp2-classificacao-vagas-cnrpark.ipynb`: classificação de vagas de estacionamento (CNRPark);
  - `disturbios-qualidade-de-energia.ipynb`: classificação de distúrbios de qualidade de energia.

## Como executar
- Notebooks: `jupyter lab` e abrir os `.ipynb` (Python 3 com `numpy`, `matplotlib` e `scikit-learn`; cada notebook importa o que usa no início).
- Scripts das redes neurais: rodar de dentro de `redes-neurais/`, porque leem os `.mat` pelo caminho relativo (`cd redes-neurais && python rede_neural_1.py`).

Os roteiros partem de enunciados do professor; as soluções são minhas.
