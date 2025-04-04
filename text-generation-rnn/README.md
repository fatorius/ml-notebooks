# 📝 Geração de Texto com RNN - Machado de Assis  

Este notebook apresenta um experimento de **geração de texto** utilizando **Redes Neurais Recorrentes (RNNs)** com camadas **LSTM**. O objetivo é replicar o estudo de **Andrej Karpathy** no artigo *[The Unreasonable Effectiveness of RNNs](https://karpathy.github.io/2015/05/21/rnn-effectiveness/)*, treinando um modelo de linguagem baseado nas obras de **Machado de Assis**.  

O dataset utilizado contém textos completos do autor e passou por pré-processamento para tokenização e normalização. A rede neural foi treinada para prever o próximo caractere em uma sequência, aprendendo padrões estilísticos e estruturais da escrita de Machado.  

A arquitetura do modelo inclui camadas **LSTM empilhadas**, regularização com **Dropout**, e um mecanismo de amostragem para geração de texto. Após o treinamento, a rede neural conseguiu produzir trechos com estilo semelhante ao do autor, ainda que com algumas limitações na coerência textual.  