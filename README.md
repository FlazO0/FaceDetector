
# Detector de Rosto

### Visão Geral do Projeto

Este projeto é um detector de rosto simples que utiliza a biblioteca OpenCV e um modelo de cascata Haar para detectar rostos em tempo real usando a câmera do seu computador. O programa exibe um retângulo ao redor dos rostos detectados na janela de vídeo.

### Funcionalidades

- Detecção de rostos em tempo real usando a câmera do computador.
- Exibição de retângulos ao redor dos rostos detectados.

### Tecnologias Utilizadas

- **Python:** Linguagem de programação principal do projeto.
- **OpenCV:** Biblioteca para processamento de imagens e vídeo.
- **Modelo de Cascata Haar:** Utilizado para a detecção de rostos.

### Configuração e Instalação

#### Requisitos

- Python 3.7 ou superior
- OpenCV

#### Clone o Repositório

```bash
git clone https://github.com/FlazO0/FaceDetector.git
cd FaceDetector
```

#### Instale as Dependências

Certifique-se de ter o Python instalado. Em seguida, instale os pacotes necessários:

```bash
pip install opencv-python
```

### Uso

1. Certifique-se de que a câmera do seu computador está funcionando.
2. Baixe o arquivo `haarcascade_frontalface_default.xml` do repositório oficial do OpenCV e coloque-o no diretório do projeto.
3. Execute o script Python:

    ```bash
    python app.py
    ```

4. A aplicação abrirá uma janela mostrando o vídeo da sua câmera com retângulos ao redor dos rostos detectados.
5. Pressione `q` para sair da aplicação.

