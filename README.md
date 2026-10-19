TP 5 : Intégration de Spring et Hibernate dans une Architecture Microservices

## Description du Projet:
Ce projet implémente la couche d'accès aux données d'un microservice de gestion de catalogue (`product-service`). Il illustre l'intégration entre le framework **Spring** (inversion de contrôle, injection de dépendances) et l'ORM **Hibernate** (JPA) à travers la mise en œuvre d'un pattern DAO générique réutilisable.

---

## Objectifs Pédagogiques:
- Configurer un projet Java d'entreprise avec **Maven**.
- Mettre en place la persistance des données via **Spring ORM** et **Hibernate**.
- Implémenter le mapping Objet-Relationnel (ORM) avec les annotations JPA (`@Entity`, `@Table`, `@Id`).
- Concevoir un **DAO générique** (`IDao<T>`) pour factoriser les opérations CRUD de base.
- Configurer la source de données (`DataSource`) et la fabrique de sessions (`SessionFactory`) via Spring `@Configuration`.

## Structure du Projet

```text
product-service/
├── pom.xml
└── src/
    └── main/
        ├── java/
        │   └── com/
        │       └── microservice/
        │           └── product/
        │               ├── config/
        │               │   └── HibernateConfig.java
        │               ├── dao/
        │               │   ├── IDao.java
        │               │   └── ProductDaoImpl.java
        │               └── entity/
        │                   └── Product.java
        └── resources/
```


<img width="1517" height="307" alt="image" src="https://github.com/user-attachments/assets/24570dbc-10d7-4843-974d-1a8f651fb407" />
<img width="1331" height="570" alt="image" src="https://github.com/user-attachments/assets/44cc8840-4116-4c5d-82f0-5bc90cd85acb" />
<img width="1251" height="218" alt="image" src="https://github.com/user-attachments/assets/891fb0e4-9e5a-46ba-af29-531d620519f6" />



