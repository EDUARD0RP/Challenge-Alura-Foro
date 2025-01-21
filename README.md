# ForoHub - API REST 

CONSTRUYENDO UNA API REST

## 🚀 Descripción
Esta aplicación ofrece las siguientes funcionalidades:
ForoHub es una API basada en el modelo REST, creada con Spring Boot, 
que facilita la administración de temas de discusión. Ofrece funcionalidad completa para crear, consultar, 
modificar y eliminar tópicos, además de incluir mecanismos de autenticación y autorización utilizando tokens JWT.

## 🛠️ Tecnologías Utilizadas
Java 17
Spring Framework
Spring Security
Spring Boot 3.4.1

Base de datos:
MySQL
Flyway para migraciones

Herramientas y utilidades:
Swagger para la documentación interactiva
Maven como gestor de dependencias
IntelliJ IDEA como entorno de desarrollo
Insomnia para automatización de pruebas y tests

## 💻 Instalación 
1.- Clona el repositorio:
Clona el repositorio ejecutando el siguiente comando:

```bash
git clone https://github.com/yourusername/Challenge-Alura-Foro.git
```
2.- Configura la conexión a la base de datos y las variables de entorno en el archivo src/main/resources/application.properties:
```bash
 spring.datasource.url=yourDatabaseUrl
 spring.datasource.username=yourUsername
 spring.datasource.password=yourPassword
 jwt.secret=yourSecretKey
```
3.- Ejecuta el codigo y verifica lo obtenido, en la base de datos. En esste caso el ejemplo quedaria algo asi:

![image](https://github.com/user-attachments/assets/1f6b5c46-44f5-42f6-a52d-01f81d1496db)

Consejo: Por seguridad es importante encriptar la contraseña que ingrese el Usuario, ya que en caso de tener
plageo o algun tipo de Ataque Cibernetico, dificultara la obtencion de datos y por ello, en este Challenge se 
hizo uso de:
```bash
https://www.browserling.com/tools/bcrypt
```
Y en este caso la contraseña encriptada, se ve de la siguiente manera:

![image](https://github.com/user-attachments/assets/424c0a2e-295d-4da5-8196-bb2e98a2accd)

## 🙏 Agradecimientos
Este proyecto fue desarrollado como una iniciativa para mejorar las habilidades en desarrollo de software y la integración de JSON.
Y para poner en práctica lo aprendido a lo largo de estos meses en el curso de Alura LATAM

## 👤 Autor
Este proyecto fue creado por [Rodriguez Perez Eduardo].
