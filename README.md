Detector de Objetos em Tempo Real com ResNet50 e YOLO

Este é um projeto de detector de objetos em tempo real usando uma câmera de vídeo e o modelo pré-treinado ResNet50. Utiliza também um arquivo de rótulos baseado no conjunto COCO para identificação das classes de objetos detectados.

Funcionalidades Principais:

Detecção de Objetos: Utiliza um modelo ResNet50 treinado para classificar objetos em tempo real a partir de uma câmera de vídeo.

Tradução de Classes: Traduz automaticamente os nomes das classes de objetos para o português.
Visualização Gráfica: Gera gráficos para visualizar a distribuição das classes de objetos detectados.

Requisitos:

Python 3.x

Bibliotecas: OpenCV, NumPy, Pandas, Matplotlib, Torch, torchvision

Como Usar:

Configuração do Ambiente:

Certifique-se de ter Python instalado junto com as bibliotecas listadas acima.
Instale o PyTorch e torchvision conforme necessário.
Execução:

Execute o script object_detection.py.
Certifique-se de que a câmera está corretamente configurada e acessível.
Interatividade:

Pressione 'q' para sair do programa.
A detecção e classificação dos objetos serão exibidas em tempo real na janela de vídeo.
Estrutura do Projeto:
object_detection.py: Script principal que configura a captura de vídeo, processa os frames e realiza a detecção de objetos.
coco.names: Arquivo contendo os nomes das classes utilizadas para treinamento do modelo.
README.md: Este arquivo, explicando o projeto e como utilizá-lo.
Exemplo de Resultado:
Um DataFrame é exibido com dados de detecção, incluindo classe, confiança e timestamp.
Um gráfico de barras é gerado para visualizar a distribuição das classes detectadas.
Observações:
Este projeto demonstra uma aplicação simples de detecção de objetos usando visão computacional e aprendizado profundo.
Pode ser estendido para suportar diferentes modelos de detecção ou para integrar com outras fontes de vídeo além da câmera.
