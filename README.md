# Entrenamiento de modelo - Detector de Frutas

Este proyecto utiliza TensorFlow.js para entrenar un modelo de clasificación de frutas. Se le dara los pasos de jeecucion desde 0 para que entrene y utilice el modelo.

## Requisitos
- Instalar icrawler
  
## Como clonar este repositorio
1. Clonar el repositorio
```bash
git https://github.com/Fleitaselene-dev/mod_detector_frutas.git
cd  tp-tensorflow-detector-frutas.git
```
### ¿Cómo entrenar el modelo?

1. Accede a la carpeta `programaEntrenar` desde la terminar:
```bash
cd ./programaEntrenar
```
2. Ejecutar en la terminal para crear las carpetas con las imágenes de frutas.
```bash
python traer.frutas.py
```
3. Ejecuta el `index.html` con el comando o podes abrir manualmente en tu navegador
```bash
start index.html
```
4. Subí la carpeta de imágenes desde el boton `Choose Files`.

5. Por siguiente una vez cargada las imagenes, preciona el boton `Entrenar`

#### Nota: 
El código está configurado para que sean 5 imagenes por cada fruta. Podés cambiarlo en el archivo `traer-fruta.py` en la última función donde dice `max_num=(cantidad)`

6. Una vez finalizado, el modelo se guardará automáticamente como archivos descargables:
   - `modelo-frutas.json`
   - `modelo-frutas.weights.bin`

7. Copiá esos archivos a la carpeta `utilizarModelo`.

8. Colocarse en la carpeta `utilicarModelo`
```bash
cd ..

cd ./utilizarModelo
```

7. Ejecutar atravez del servidor local de Python o con LiveServer:
```
python -m http.server

```
8. Abrí desde tu navegador:
`http://localhost:8000`

9. Subí una imágen y observa cuánto el modelo se acerca.
