Système de Gestion des Cours et des Salles de Classe

Description: Ce projet est une application web développée en Java avec le framework Spring Boot. Elle permet à une institution éducative de gérer les cours et les salles de classe. L'application offre des fonctionnalités de gestion des cours, des salles, des assignations de cours, ainsi que des options de recherche et de pagination pour faciliter la navigation dans les données.

Fonctionnalités: Gestion des Cours : Ajouter un nouveau cours avec son nom, sa description et sa durée. Consulter la liste des cours disponibles avec leurs descriptions. Rechercher des cours par nom ou description. Pagination des résultats pour une navigation aisée. Visualiser les détails d'un cours. Modifier les informations d'un cours. Supprimer un cours. Gestion des Salles de Classe : Ajouter une nouvelle salle avec son nom, sa capacité et ses équipements. Consulter la liste des salles de classe disponibles. Rechercher des salles par nom ou capacité. Pagination des résultats pour faciliter la visualisation. Visualiser les détails d'une salle, y compris les cours assignés. Modifier les informations d'une salle. Supprimer une salle.

Structure du Projet: Packages controller : Contient les contrôleurs de l'application qui gèrent les requêtes HTTP. CoursController : Contrôleur pour gérer les opérations CRUD des cours. SalleController : Contrôleur pour gérer les opérations CRUD des salles. entities : Contient les entités qui représentent les objets de données.

Cours : Représente un cours avec les attributs nom, description et durée. Salle : Représente une salle de classe avec les attributs nom, capacité et équipements. repositories : Contient les interfaces de dépôt pour interagir avec la base de données.

CoursRepository : Interface de gestion des cours, étendant CrudRepository. SalleRepository : Interface de gestion des salles, étendant CrudRepository. resources/templates : Contient les templates Thymeleaf pour l'interface utilisateur.

listCours.html : Page pour afficher la liste des cours avec pagination et recherche. detailsSalle.html : Page pour afficher les détails d'une salle de classe, y compris les cours assignés. et add cours et salles et update salles et cours

Fichier de configuration application.properties : Contient la configuration de l'application, y compris la connexion à la base de données.

Prérequis: Java 11+ : Assurez-vous d'avoir Java 11 ou une version ultérieure installée. Maven : Pour gérer les dépendances et construire le projet. Base de données : Configurez une base de données compatible avec Spring Data JPA (par exemple, MySQL ou H2) et assurez-vous de mettre à jour les informations de connexion dans application.properties

Védio démo : https://github.com/user-attachments/assets/04f2b8a9-38a7-4bb8-82d4-3e2d934eee05
