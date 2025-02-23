# Flowers Recognition - Visão Computacional com CNN

Este repositório contém códigos e experimentos desenvolvidos para a exploração do dataset [Flowers Recognition](https://www.kaggle.com/datasets/alxmamaev/flowers-recognition). O objetivo é aplicar técnicas de Visão Computacional com redes neurais convolucionais (CNNs) para a identificação de diferentes tipos de flores.

## 📌 Conteúdo do Repositório

Aqui você encontrará:
- Scripts para pré-processamento e organização do dataset.
- Implementação de redes neurais convolucionais para classificação das imagens.
- Análises de métricas como precisão, recall, F1-score e matriz de confusão.
- Estratégias para otimização do treinamento, como regularizações L1/L2, Dropout e Early Stopping.

## 📺 Playlist Completa no YouTube

Para acompanhar o desenvolvimento passo a passo, assista à playlist completa disponível no YouTube: [Flowers Recognition - Visão Computacional](https://youtube.com/playlist?list=PLEQcn1oRilpMKY1amZFRHsAle5f1DFs3G&si=oxB_8PYDJyEYjyfU)

A playlist inclui os seguintes vídeos:

1. **Download do Dataset e Configuração do Projeto**
2. **Instalação de Dependências:** TensorFlow, Matplotlib, NumPy, Scipy
3. **Configuração do Jupyter Notebook e Instalação de Bibliotecas Adicionais:** Seaborn, Scikit-learn
4. **Importação de Bibliotecas e Acesso às Imagens**
5. **Divisão do Dataset:** Training, Validation e Test Sets
6. **Exploração do Hiperparâmetro `BATCH SIZE`**
7. **Carregamento de Imagens no TensorFlow com `flow_from_directory`**
8. **Definição de Hiperparâmetros na CNN - Parte 1:** Kernel, Input Shape, Pooling, Função de Ativação
9. **Uso de Dropout para Prevenção de Overfitting**
10. **Cálculo da Função de Perda (`Categorical Crossentropy`)**
11. **Ajuste do Hiperparâmetro Learning Rate**
12. **Interpretação dos Outputs Durante o Treinamento**
13. **Análise da Acurácia e da Loss Function ao Longo das Épocas - Overfitting**
14. **Interpretação da Matriz de Confusão**
15. **Cálculo do Precision**
16. **Cálculo do Recall**
17. **Cálculo do F1-Score**
18. **Construção da Curva ROC - Passo a Passo**
19. **Discussão sobre Curva ROC, AUC e Ponto de Youden**
20. **Impacto das Regularizações L1 (Lasso) e L2 (Ridge)**
21. **Implementação e Comparação das Regularizações L1 e L2**
22. **Aplicação de Callbacks para Early Stopping**
23. **Combinação de Regularização, Dropout e Early Stopping para Reduzir Overfitting**
24. **Impacto do Número de Camadas e Parâmetros na Acurácia**

## 🚀 Como Executar os Scripts

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   cd seu-repositorio
   ```
2. Instale as dependências necessárias:
   ```bash
   pip install -r requirements.txt
   ```
3. Execute os notebooks no Jupyter Notebook ou Google Colab.

## 📌 Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

---

🔗 **Siga-me no YouTube para mais conteúdos sobre Machine Learning e Visão Computacional:** [Canal no YouTube](https://youtube.com/playlist?list=PLEQcn1oRilpMKY1amZFRHsAle5f1DFs3G&si=oxB_8PYDJyEYjyfU)
