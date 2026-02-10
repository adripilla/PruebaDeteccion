# Object Detection (Webcam) con TensorFlow.js + COCO-SSD

Demo en **HTML + JavaScript** que realiza **detección de objetos en tiempo real** usando la **cámara web** del navegador.  
Utiliza **TensorFlow.js** y el modelo preentrenado **COCO-SSD** para detectar objetos (person, bottle, phone, etc.) y dibuja los resultados en un **canvas** sobre el video.

---

## ✨ Características

- Accede a la **webcam** con `getUserMedia()`
- Carga el modelo **COCO-SSD** desde CDN
- Detecta objetos en el video y muestra:
  - Caja delimitadora (bounding box)
  - Etiqueta/clase detectada
- Renderiza detecciones en un `<canvas>` superpuesto al `<video>`
- Intervalo de detección configurable (actualmente cada 1 segundo)

---

## 🧠 Tecnologías

- HTML5 / CSS3 / JavaScript
- [TensorFlow.js](https://www.tensorflow.org/js)
- [COCO-SSD](https://github.com/tensorflow/tfjs-models/tree/master/coco-ssd)

---

## ✅ Requisitos

- Navegador moderno (Chrome / Edge / Firefox)
- Permiso para usar la **cámara**
- Recomendado ejecutar en `localhost` o HTTPS (algunos navegadores restringen la cámara en `file://`)

---

## 🚀 Cómo ejecutarlo

### Opción A: Abrir con servidor local (recomendado)

1. Guarda el archivo como `index.html`
2. Levanta un servidor local en la carpeta:

**Con Node.js:**
```bash
npx serve .
