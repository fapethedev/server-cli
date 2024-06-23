# SpringBoot OAuth2 Server Client

## Description
Spring Boot OAuth2 Server and Client application.

## Prérequis

- Java 21.0.1 ou supérieur
- Maven 3.9.0 ou supérieur
- Docker ou Docker Desktop

## Installation

1. Clonez le dépôt :

   ```sh
   git clone https://github.com/fapethedev/server-cli.git
   cd server-cli
   ```

2. Compilez et installez les dépendances :

   ```sh
   mvn clean install
   ```

## Utilisation

1. Configurer l'environnement
    
    ```dotenv
    POSTGRES_DB
    POSTGRES_PASSWORD
    POSTGRES_USER
    ```

2. Pour lancer l'application, utilisez la commande Maven suivante :

   ```sh
   mvn spring-boot:run
   ```

3. L'application sera accessible à l'adresse suivante :

   ```
   http://localhost:8285
   ```

## Contributeurs

- **Nom du Contributeur** - [Fapethedev](https://github.com/fapethedev)

## Licence

Ce projet est sous licence MIT. Voir le fichier [LICENSE](LICENSE) pour plus de détails.
