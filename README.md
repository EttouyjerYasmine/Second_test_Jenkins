# jenkins testing webhooks 2

# Second_test_Jenkins

Ce projet illustre un pipeline CI/CD avec Jenkins pour un ensemble de micro‑services Java/Spring Boot, intégrés avec SonarQube pour l’analyse de la qualité du code et Docker pour la conteneurisation.

---

## Architecture

- **Services :**
  - `car` : micro‑service de gestion des voitures
  - `client` : micro‑service de gestion des clients
  - `gateway` : API Gateway Spring Cloud
  - `server_eureka` : serveur Eureka pour la découverte des services
- **Dossier `deploy/`** : contient la configuration Docker Compose pour lancer l’ensemble des services.
- **SonarQube** : utilisé pour l’analyse statique et le suivi de la qualité du code.

---

##  Prérequis

- **Java 17+**
- **Maven 3.8+**
- **Docker & Docker Compose**
- **Jenkins** (avec plugins nécessaires : Git, Pipeline, SonarQube Scanner)
- **SonarQube** (local ou distant, ex. `http://localhost:9000`)

---

##  Installation & Build

1. **Cloner le dépôt :**
   ```bash
   git clone https://github.com/EttouyjerYasmine/Second_test_Jenkins.git
   cd Second_test_Jenkins

##  Execution de travail pratique 

<img width="1916" height="938" alt="tp31" src="https://github.com/user-attachments/assets/f4abe089-08fa-4e5b-828a-fb2f71459f56" />


<img width="1907" height="901" alt="TP31-2" src="https://github.com/user-attachments/assets/edab2aa0-5b01-4d1e-ab19-b0ed8c55a9a3" />


   
