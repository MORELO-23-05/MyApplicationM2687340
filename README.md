# MyApplication2687340M en Compose tutorial de andriod
Este repositorio contiene una aplicación de mensajería simple construida con  una imagen y diferentes caracteristicas como temas y arreglos en la imagen con Jetpack Compose, una moderna herramienta de interfaz de usuario para crear interfaces nativas en Android. La aplicación muestra una lista de mensajes en un formato de conversación, permitiendo a los usuarios expandir y contraer mensajes individuales para una mejor legibilidad.

# Características
Mostrar mensajes en un formato de conversación.
Cada mensaje se puede expandir para mostrar el cuerpo completo del mensaje o contraerse para mostrar solo la primera línea.
Previsualizaciones de modo oscuro y modo claro están disponibles.
Capturas de Pantalla
Vista Previa Modo Claro
Vista Previa Modo Oscuro

# Componentes
MainActivity: El punto de entrada de la aplicación. Configura el tema, ademas de tener y renderizar una imagen y muestra el componible Conversation.

MessageCard: Un componible que representa un mensaje individual. Incluye el nombre del autor, una imagen de perfil circular y el cuerpo del mensaje. Los usuarios pueden hacer clic en un mensaje para expandir/contraer su contenido.

Conversation: Un componible que recibe una lista de objetos Message y los muestra utilizando un LazyColumn. Utiliza el componible MessageCard para renderizar cada mensaje.

# Modelo de Datos
Message: Una clase de datos que representa un mensaje en la conversación, la imagen y su modificacion. Contiene el nombre del autor y el cuerpo del mensaje.

# Previsualizaciones
PreviewMessageCard: Proporciona una vista previa del componible MessageCard en los modos claro y oscuro.

PreviewConversation: Proporciona una vista previa del componible Conversation utilizando datos de muestra.

# Uso
Para ejecutar la aplicación, sigue estos pasos:

Clona este repositorio.
Abre el proyecto en Android Studio.
Compila y ejecuta la aplicación en un emulador o dispositivo físico.

# Requisitos
Android Studio 
Android SDK 
Kotlin 
Jetpack Compose 

# Reconocimientos
Esta aplicación fue creada como una demostración de cómo construir una interfaz de usuario de mensajería simple utilizando Jetpack Compose. Utiliza componentes de Material Design y muestra la flexibilidad y facilidad de desarrollo que ofrece Jetpack Compose.

## Pantallazos 
![Captura![Captura de pantalla 2023-08-10 153430](https://github.com/MORELO-23-05/MyApplicationM2687340/assets/127150027/4d2843e7-f015-4fa3-afd5-e7f60b8dc61f)
 de pantalla 2023-08-10 153157](https://github.com/MORELO-23-05/MyApplicationM2687340/assets/127150027/84603f96-8e78-44bd-b1ba-c9a9dfb17574)
![Captura de pantalla 2023-08-10 153730](https://github.com/MORELO-23-05/MyApplicationM2687340/assets/127150027/5e65d3e2-a759-4646-bfeb-94333a6b7535)
![Captura de pantalla 2023-08-10 154118](https://github.com/MORELO-23-05/MyApplicationM2687340/assets/127150027/fcb0fd51-e7a9-45b2-a7b3-14a14ef2f294)
![Captura de pantalla 2023-08-10 154207](https://github.com/MORELO-23-05/MyApplicationM2687340/assets/127150027/52cafa8c-9810-4083-81f9-a6aa34f1646b)
![Captura de pantalla 2023-08-10 154657](https://github.com/MORELO-23-05/MyApplicationM2687340/assets/127150027/f0f97d28-b97b-42db-9f6b-a7643e340e0c)
![Captura de pantalla 2023-08-10 154941](https://github.com/MORELO-23-05/MyApplicationM2687340/assets/127150027/bab38f19-48ff-4751-b0b1-f2b95f47dd59)
![Captura de pantalla 2023-08-10 155507](https://github.com/MORELO-23-05/MyApplicationM2687340/assets/127150027/809e37a1-fb9c-4294-935d-6ca025a77e3b)
![Captura de pantalla 2023-08-10 160031](https://github.com/MORELO-23-05/MyApplicationM2687340/assets/127150027/16d40c01-e9b2-4448-80d7-315520fe91ab)
![Captura de pantalla 2023-08-10 160445](https://github.com/MORELO-23-05/MyApplicationM2687340/assets/127150027/a11d32a3-cb4a-4a12-b6fc-9d63e0401072)
![Captura de pantalla 2023-08-10 160754](https://github.com/MORELO-23-05/MyApplicationM2687340/assets/127150027/bc2ad1d1-078a-4e72-aec1-08a899f75f90)
![Captura de pantalla 2023-08-10 171527](https://github.com/MORELO-23-05/MyApplicationM2687340/assets/127150027/08483d88-4911-4b5f-af3a-a06ef7a31413)
![Captura de pantalla 2023-08-10 171825](https://github.com/MORELO-23-05/MyApplicationM2687340/assets/127150027/c54b461a-e1dd-4119-9a10-e306358d4dbd)
![Captura de pantalla 2023-08-14 132404](https://github.com/MORELO-23-05/MyApplicationM2687340/assets/127150027/1826e963-086a-40ad-a03a-3ea3cf1acd1b)

