Lista de exercícios 1 - Visão Computacional

1. Considere uma imagem de 1 canal possuindo valores do tipo inteiro sem sinal (unsigned integer) de 8 bits (uint8). Um pixel dessa imagem pode possuir quantos valores? Se a imagem possuir 3 canais (RGB), quantos valores distintos um pixel pode ter?
R: Se a imagem possui um único canal, então cada pixel dentre os 256x256 pixels tem 2^8 = 256 valores distintos, variando de 0 a 255. No caso de 3 canais, cada pixel tem 2^8 x 2^8 x 2^8 = 256x256x256 = 16777216 valores distintos

2. Um conjunto de dados possui os seguintes valores para as variáveis 𝑥 e 𝑦:
𝑥 = [1, 2, 3, 4]
𝑦 = [2, 7, 6, 12]
O modelo 𝑓(𝑥) = 2𝑥 + 1 foi criado para representar esses dados. Calcule o erro quadrático médio
do modelo
R: Predições: 3, 5, 7, 9
mse = 1/4 [1^2 + 2^2 + 1^2 + 3^2] = 15/4