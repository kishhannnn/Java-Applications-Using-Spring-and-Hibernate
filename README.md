## 📌 Overview

This project contains three Java applications demonstrating **Spring** and **Hibernate** concepts:

1. **Part A:** Spring Dependency Injection
2. **Part B:** Hibernate CRUD with MySQL
3. **Part C:** Spring + Hibernate Transaction Management

---

## ✅ Prerequisites

* Java 17+
* MySQL (database: `nimbusdb`)
* Spring, Hibernate, MySQL JDBC JARs
* Maven (optional)

---

## 🟦 Part A: Spring Dependency Injection

Shows DI using annotations and Java-based config.

### Run:

```bash
javac -cp "path_to_spring_jars/*" ...
java -cp ".:path_to_spring_jars/*" com.example.di.MainApp
```

**Output:**

```
Student Name: John Doe
Enrolled in course: Artificial Intelligence
```

---

## 🟩 Part B: Hibernate CRUD

Performs Create, Read, Update, Delete operations on Student entity.

### Run:

```bash
javac -cp "path_to_hibernate_jars/*:path_to_mysql_connector/*" ...
java -cp ".:path_to_hibernate_jars/*:path_to_mysql_connector/*" com.example.hibernatecrud.MainApp
```

---

## 🟨 Part C: Transaction Management

Banking system with Spring’s `@Transactional` for safe money transfer.

### Run:

```bash
javac -cp "path_to_spring_jars/*:path_to_hibernate_jars/*:path_to_mysql_connector/*" ...
java -cp ".:path_to_spring_jars/*:path_to_hibernate_jars/*:path_to_mysql_connector/*" com.example.banking.MainApp
```

---

## 📝 Notes

* Spring uses **Java-based config** only.
* MySQL credentials must be updated in `hibernate.cfg.xml`.
* All parts require correct classpath setup for dependencies.