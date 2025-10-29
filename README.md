# 🧠 Trabajo Práctico — JPQL, Persistencia y JPA con Hibernate

Proyecto desarrollado para la cátedra **Desarrollo de Software**, con el objetivo de aplicar los conceptos de **persistencia de datos en Java** mediante **JPA**, **JPQL**, y el uso del patrón **ORM (Object-Relational Mapping)** con **Hibernate**.

---

## 🚀 Objetivos del trabajo

- Implementar un **modelo de dominio completo** con relaciones entre entidades (Cliente, Factura, Artículo, Imagen, Categoría, Unidad de Medida, etc.).
- Utilizar **JPA + Hibernate** para mapear las clases Java hacia una base de datos relacional (H2).
- Desarrollar y ejecutar **consultas JPQL** para resolver requerimientos típicos de negocio.
- Aplicar el uso de **Lombok** para simplificar la escritura del modelo y constructores.
- Implementar una **carga inicial de datos (`DataLoader`)** a partir de un script SQL.
- Diseñar una clase de servicios (`JPQLService`) con consultas complejas:
  - Listar artículos, insumos, manufacturados.
  - Calcular totales facturados, promedios, y conteos.
  - Actualizar precios y eliminar registros con JPQL.
- Organizar un `MainApp` prolijo y explicativo, con salida formateada para consola.

---

## 🧰 Tecnologías utilizadas

| Herramienta | Uso |
|--------------|-----|
| **Java 21** | Lenguaje base del proyecto |
| **Gradle 9.1** | Sistema de construcción |
| **Hibernate ORM 6.3.1.Final** | Motor JPA |
| **H2 Database** | Base de datos embebida (persistencia local) |
| **Jakarta Persistence (JPA 3.1)** | API estándar de persistencia |
| **Lombok** | Simplificación de entidades |
| **JUnit 5 (opcional)** | Pruebas automáticas |
| **IntelliJ IDEA** | Entorno de desarrollo |

---

## 🧩 Estructura del proyecto

src/
└── main/java/org/example/
├── modelo/
│ ├── entidades (@Entity)
│ ├── DataLoader.java
│ ├── JPQLService.java
│ ├── JPAUtil.java
└── MainApp.java


👨‍🏫 Créditos

Trabajo desarrollado por Matías Fernández, Luisina Battella Alma Ponce Maria Jose Villarreal Aracelly Caballero M. Candela Gonzalez
con enfoque académico y pedagógico en el uso de JPA, JPQL y Hibernate.
Guía paso a paso y explicaciones acompañadas por IA docente.
