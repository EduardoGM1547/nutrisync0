📱 NutriSync
🎯 Objetivo
Desarrollar una aplicación móvil centrada en el bienestar personal, que permita a los usuarios: Registrar sus actividades de salud: ejercicios, comidas, sueño y peso Visualizar su progreso de forma clara y amigable Recibir seguimiento por parte de un coach Obtener recomendaciones inteligentes de una IA Mantener la motivación mediante frases

📌 Alcance
El proyecto NutriSync es una aplicación móvil desarrollada en Kotlin utilizando Jetpack Compose, orientada al seguimiento de hábitos saludables y el control de peso del usuario. Entre sus principales funcionalidades se incluyen:

Registro diario de actividades y hábitos (alimentación, ejercicio, sueño, etc.)
Seguimiento y visualización del peso a través de gráficas
Personalización de tema (claro/oscuro)
Persistencia local de datos sin necesidad de conexión a internet
Interfaz adaptable
🖥️ Requerimientos técnicos
Componente	Requisito
Sistema operativo	Android 8.0 (API 26) o superior
IDE	Android Studio Hedgehog o superior
Lenguaje	Kotlin
Arquitectura	Jetpack Compose + Room
Base de datos	SQLite (a través de Room)
Librerías	Material3, MPAndroidChart, DataStore
Emulador recomendado	Nexus S API 33 o superior
🗃️ Base de datos utilizada
La aplicación utiliza Room, un wrapper ORM de SQLite, para la persistencia de los datos de usuario. Las principales entidades del modelo son:

RegistroHabito: contiene los hábitos diarios del usuario.
PerfilUsuario: contiene información del perfil del usuario.
Room permite almacenar, consultar y actualizar datos localmente de manera eficiente, incluso sin conexión a internet.

La base de datos se construye con fallbackToDestructiveMigration() para permitir migraciones automáticas durante el desarrollo.

👨‍💻 Autor
Diego Eduardo Godínez Montes: diego.godinez.montes@gmail.com
Cindy Abad Giron: abad.cindy27@gmail.com
