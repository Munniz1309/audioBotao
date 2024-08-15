# Análise de Sinais de Áudio
Este projeto realiza uma análise detalhada do sinal de áudio contido no arquivo botao.wav, utilizando bibliotecas como librosa, matplotlib, numpy, e scipy.stats. O objetivo é explorar o comportamento do sinal de áudio através de visualizações gráficas, análise estatística e autocorrelação, entre outras abordagens.

# Funcionalidades
O código realiza as seguintes tarefas:

- Carregar e Plotar o Áudio:

Utiliza librosa para carregar o arquivo de áudio botao.wav e gerar o gráfico do sinal de áudio utilizando matplotlib.

- Histograma do Sinal de Áudio:

Gera um histograma do sinal de áudio com 50 barras para visualizar a distribuição dos valores do sinal.

- Cálculo de Assimetria e Curtose:

Utiliza funções da biblioteca scipy.stats para calcular a assimetria (skewness) e curtose (kurtosis) do sinal de áudio.

- Divisão do Sinal em Partes e Cálculo da Média Temporal:

O sinal é dividido em 10 partes de aproximadamente 6.000 amostras cada.
<br> A média temporal de cada uma das partes é calculada e o comportamento dessas médias é analisado para verificar se há variação ao longo do tempo.

- Função de Autocorrelação:

Calcula a autocorrelação para cada uma das 10 partes do sinal, utilizando 20 valores de atraso.
<br> Os resultados da autocorrelação são comparados entre as partes e analisados no código.

- Análise de Estacionariedade:

Com base nas questões anteriores, o código investiga se o sinal é estacionário no sentido amplo, discutindo os resultados através de comentários.

# Pré-requisitos
Antes de executar o código, certifique-se de ter as seguintes bibliotecas instaladas:

- librosa
- matplotlib
- numpy
- scipy
