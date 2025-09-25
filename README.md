# Basic Chat Emilio Pavel

Aplicación de chat desarrollada en **Flutter** con integración de **Firebase**.

---

## 🚀 Requisitos previos

Antes de empezar, asegúrate de tener instalado:

- [Flutter SDK](https://docs.flutter.dev/get-started/install) (versión estable más reciente)  
- [Dart SDK](https://dart.dev/get-dart) (incluido en Flutter)  
- [Firebase CLI](https://firebase.google.com/docs/cli)  
- Android Studio o Visual Studio Code con los plugins de Flutter y Dart  
- Un emulador Android o un dispositivo físico conectado  

---

## 📦 Instalación

1. **Clonar el repositorio**

  ``` git clone https://github.com/Emiliox1526/basic_chat_emilio_pavel.git```
  ``` cd basic_chat_emilio_pavel```
Instalar dependencias


```flutter pub get```
Configurar Firebase

Descarga el archivo google-services.json desde la consola de Firebase

Colócalo en:

android/app/google-services.json
⚠️ Este archivo no está incluido en el repositorio por seguridad.

Generar configuraciones de Firebase con FlutterFire

```flutterfire configure```
Esto genera el archivo lib/firebase_options.dart.

▶️ Ejecución
Asegúrate de que un emulador esté corriendo o conecta tu dispositivo.

Lanza la app en modo debug:

```flutter run```
