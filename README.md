# projetoFinalSinaisESistemas

Desenvolva um Sistema de reconhecimento de face, que consiga reconhecer diversas pessoas diferentes em um grupo de pessoas. Utilize o banco de dados The ORL Database of Faces (ORL - https://www.dropbox.com/s/mnhfhb1i51loknk/orl_faces.zip). Esse banco de dados possui 40 pessoas e cada pessoa tem 10 amostras de face. As imagens possuem 92x112 pixels.

Converta cada imagem para o domínio da frequência (transformada de Fourier Bidimensional). Organize o banco de dados em amostras de treino e classificação utilizando a técnica de validação cruzada. Isto é, para cada pessoa, selecione 9 imagens para treinamento e 1 para classificação, a seleção dessas amostras deve ser aleatória. 

Para classificação utilize o algoritmo dos K-Vizinhos mais Próximos (KNN, k-nearest neighbors), com k=1. Utilize como métrica de distância o Erro Médio Quadrático, ou Distância Euclidiana, sobre uma sub-região retangular de menor frequência da transformada de Fourier bidimensional das imagens.

