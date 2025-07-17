
# 🧠 OCR Prediction with YOLO Model

Este projeto utiliza um modelo treinado com YOLO (`best.pt`) para realizar detecção e reconhecimento de texto em imagens, vídeos ou webcam. O script principal (`predictWithOCR.py`) permite passar diferentes fontes de entrada via linha de comando.

---

## 🚀 Como Executar

Execute o script com a seguinte sintaxe:

```bash
python predictWithOCR.py model='best.pt' source='<input>'
```

### Exemplos de Uso

| Tipo de Entrada | Exemplo               | Descrição                    |
|-----------------|-----------------------|------------------------------|
| 🎥 Vídeo        | `source='demo.mp4'`   | Usa um arquivo de vídeo      |
| 🖼️ Imagem       | `source='image.jpg'`  | Usa uma única imagem         |
| 📷 Webcam       | `source=0`            | Usa a webcam do dispositivo  |

---

## 📁 Estrutura Esperada do Projeto

```
project/
├── predictWithOCR.py
├── best.pt
├── data/
│   └── images/
│       └── image.jpg
├── runs/
│   └── detect/
│       └── ... (resultados salvos)
```

---

## 📦 Requisitos

Crie um ambiente virtual e instale as dependências (exemplo com pip):

```bash
python -m venv venv
venv\Scripts\activate  # Windows
# ou
source venv/bin/activate  # Linux/Mac

pip install -r requirements.txt
```

---

## 📝 Notas

- O arquivo `best.pt` deve conter o modelo YOLO treinado para detecção OCR.
- Os resultados serão salvos automaticamente dentro da pasta `runs/detect/`.

---

## 👤 Autor

Desenvolvido por **Yago de Souza França**
