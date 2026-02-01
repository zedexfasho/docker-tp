# Docker TP – JPetStore

## 📌 Contexte du projet
Ce dépôt a été réalisé dans le cadre d’un **TP Docker et DevOps**.  
L’objectif est de découvrir :
- Git et le travail collaboratif
- Docker et la conteneurisation
- L’intégration continue avec GitHub Actions

Le projet utilisé comme support est **MyBatis JPetStore**.

---

## 🎯 Objectifs du TP
- Cloner et gérer un projet avec Git
- Travailler en branches et via des Pull Requests
- Protéger la branche `main`
- Mettre en place une intégration continue (CI)
- Conteneuriser l’application avec Docker

---

## 🛠️ Technologies utilisées
- Git / GitHub
- GitHub Actions (CI)
- Docker / Docker Compose
- Java / Maven
- MyBatis, Spring, Stripes

---

## 📦 Projet d’origine : MyBatis JPetStore

MyBatis JPetStore est une application web Java complète basée sur :
- MyBatis 3
- Spring 5
- Stripes

![mybatis-jpetstore](https://mybatis.org/images/mybatis-logo.png)

### Documentation officielle
- https://www.mybatis.org/jpetstore-6

---

## ▶️ Lancer l’application avec Docker

### Construction de l’image
```bash
docker build -t jpetstore .

