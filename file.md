# TracerCam

Aplicacion web progresiva (PWA) para calcar imagenes usando la camara del celular.

## Funciones

- Activa la camara trasera o frontal del celular
- Carga cualquier imagen desde la galeria o archivos
- Ajusta la opacidad de la imagen superpuesta (0-100%)
- Ajusta la escala de la imagen (20-300%)
- Arrastra la imagen con el dedo para posicionarla
- Pellizca con dos dedos para hacer zoom
- Doble toque para reiniciar posicion
- Instalable como PWA (funciona sin internet)

## Uso

1. Abre la app en el navegador del celular
2. Presiona **CAMARA** para activar la camara
3. Presiona **CARGAR IMAGEN** para seleccionar un boceto
4. Ajusta la opacidad con el slider
5. Arrastra y escala la imagen sobre lo que quieres calcar
6. Coloca tu papel sobre la pantalla y calca

## Publicar en GitHub Pages

1. Crea un repositorio en GitHub
2. Sube todos los archivos
3. Ve a Settings > Pages > Source: main branch / root
4. Accede a: `https://TU_USUARIO.github.io/NOMBRE_REPO/`

## Tecnologias

- HTML5 / CSS3 / JavaScript vanilla
- getUserMedia API (camara)
- Service Worker (PWA / offline)
- Web App Manifest

## Notas

- Requiere HTTPS para funcionar (GitHub Pages lo provee automaticamente)
- Probado en Chrome y Safari movil
- Los iconos icon-192.png e icon-512.png son opcionales para PWA
