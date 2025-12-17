# Spring-Boot-Web  
Demo MVC – aprende Spring con un clic

## 🚀 ¿Qué hace?
- Sirve páginas web con plantillas **Thymeleaf**.  
- Recarga en caliente gracias a **Spring DevTools** (cambias → refrescas → ves).  
- Preparado para **Java 11** y **Spring Boot 2.1.3**.

## 📦 Stack tecnológico
| Capa | Tecnología |
|---|---|
| Web | Spring MVC + Thymeleaf |
| Build | Maven |
| Java | 11 |
| Recarga en caliente | Spring DevTools |
| Test | Spring Boot Test |

## ▶️ Ejecutar en 30 s
```bash
git clone https://github.com/AliciaJava/spring-boot-web.git
cd spring-boot-web
mvn spring-boot:run
```
Abre [http://localhost:8080](http://localhost:8080) – ¡empieza a codear!

## 📁 Estructura del proyecto
```
src
└── main
    ├── java/com.bolsadeideas.springboot.app
    │   └── SpringBootWebApplication.java   # clase boot
    └── resources
        ├── templates/     # HTML Thymeleaf
        ├── static/        # css, js, imágenes
        └── application.properties
```

## 🔧 Recarga en caliente
1. Arranca con `mvn spring-boot:run`.  
2. Edita cualquier archivo `.java` o `.html`.  
3. **Ctrl + F5** en el navegador – los cambios aparecen al instante (sin reiniciar).

## ✅ Test
```bash
mvn test
```

## 📚 Aprende más
- [Documentación Spring Boot](https://spring.io/projects/spring-boot)  
- [Tutorial Thymeleaf](https://www.thymeleaf.org/documentation.html)

**¡Happy coding!** – Dale una estrella al repo si te ha servido.
