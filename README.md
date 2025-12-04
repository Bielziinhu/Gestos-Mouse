# 🖱️ Projeto IHC Mouse Virtual

Este projeto permite controlar o cursor do mouse do computador usando apenas uma webcam e gestos manuais. Desenvolvido em **Python**, utiliza a biblioteca **MediaPipe** para rastreamento de mãos e **PyAutoGUI** para interação com o sistema operacional.

## ✨ Funcionalidades

* **Controle de Cursor:** Mova o mouse apontando com o dedo indicador.
* **Clique Esquerdo & Arrastar:** Pinça com Indicador + Polegar (suporta Drag & Drop).
* **Clique Direito:** Pinça com Dedo Médio + Polegar.
* **Ajuste de Sensibilidade:** Controle em tempo real via teclado.
* **Estabilidade:** Algoritmo de suavização para evitar tremores no cursor.

## 🛠️ Pré-requisitos

Certifique-se de ter o **Python 3.10.0** instalado em sua máquina.

### Instalação das Dependências

Abra seu terminal ou prompt de comando na pasta do projeto e execute:

```bash
pip install opencv-python mediapipe pyautogui numpy
