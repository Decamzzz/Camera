# Captura y recorte de imágenes en Flutter

Ejemplo educativo de captura, selección y recorte de imágenes utilizando
Flutter, image_picker e image_cropper.

## Tecnologías

- Flutter
- Dart
- image_picker 1.2.3
- image_cropper 12.2.1

## Funcionalidad

La aplicación permite:

1. Seleccionar una imagen desde la galería.
2. Abrir el editor de recorte.
3. Modificar el encuadre.
4. Confirmar el recorte.
5. Mostrar la imagen resultante.

## Instalación

Clonar el repositorio:

git clone https://github.com/Decamzzz/Camera.git

Entrar al proyecto:

cd camera

Instalar dependencias:

flutter pub get

Ejecutar:

flutter run

## Android

Agregar UCropActivity en:

android/app/src/main/AndroidManifest.xml

## Flujo

image_picker
    ↓
Imagen seleccionada
    ↓
image_cropper
    ↓
CroppedFile
    ↓
Image.file

© Deiby Camilo Botina - Jaider Orlando España 2026
