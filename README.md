# Detector de Motocicletas

Este projeto utiliza YOLOv5 para detectar motocicletas em imagens e mostrar suas posições na tela.

## Requisitos

- Python 3.7 ou superior
- PyTorch
- OpenCV (cv2)
- NumPy

## Instalação

1. Clone este repositório ou baixe os arquivos

2. Instale as dependências necessárias:
```bash
pip install torch torchvision
pip install opencv-python
pip install numpy
```

## Como Executar

1. Certifique-se de que você tem uma imagem para testar (por padrão, o código procura por 'motos2.jpg' no mesmo diretório)

2. Execute o script principal:
```bash
python challenge.py
```

## Funcionalidades

- Detecta motocicletas em imagens
- Desenha retângulos verdes ao redor das motocicletas detectadas
- Marca o centro de cada motocicleta com um círculo vermelho
- Mostra as coordenadas (x,y) de cada motocicleta detectada
- Exibe a imagem com as detecções em uma janela
- Imprime as posições das motocicletas no console

## Observações

- O modelo YOLOv5 será baixado automaticamente na primeira execução
- Para fechar a janela de visualização, pressione qualquer tecla
- Para usar uma imagem diferente, modifique o caminho da imagem no código (`image_path`) 