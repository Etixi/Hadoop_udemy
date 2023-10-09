## **Programmes**
<hr>

### **Section 1 : Bienvenue à la formation Hadoop**
### **Section 2 : Les Principes du Big Data**
### **Section 3 : Presentation Generale**
### **Section 4 : Hadoop: Presentation Generale**
### **Section 5 : Le coeur d'Hadoop: HDFS, MapReduce et YARN**
### **Section 6 : Les Bases de Données Relationnelles et NoSQL avec Hadoop**
### **Section 7 : Programmation avec : Spark et Pig**
### **Section 8 : Traitement des données en temps réel**
### **Section 9 : Hadoop dans le cloud**


## **Installation**
  1) [Hadoop dans Windows](https://medium.com/analytics-vidhya/hadoop-how-to-install-in-5-steps-in-windows-10-61b0e67342f8)
  2) [Soit par le biais d'un VM Virtualbox](https://www.udemy.com/course/hadoop-maitriser-le-big-data/learn/lecture/21831890#overview)


## **L'écosystème d'Hadoop : un foisonnement de logiciels**
+ L'écosystème des solutions du Big Data est important et continue à se developper inlassablement:
  + 2012 : Ensemble des techonologies visibles sur un slide.
  + 2019: Complexification de l'éventail des solutions.

### **Categories de composants Hadoop**

#### **Coeur D'Hadoop**

| Composants                                | Fonctionnalités                                                                                                                                           |
|-------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------|
| HDFS (`Hadoop Distributed File System`)   | Constitue le socle de stockage de fichiers. Il utilise deux systèmes : `le Namenode et le Datanode` pour pouvoir gérer les quantités immenses de données. |
| MapReduce                                 | parallélise le traitement des données                                                                                                                     |
| Yarn (`Yet Another Ressource Negociator`) | modèle de traitement pour HDFS                                                                                                                            |

#### **Base De Données**

| Composants | Fonctionnalités                                            |
|------------|------------------------------------------------------------|
| Hive       | Base de données de type DataWarehouse(entrepôt de données) |
| HBase      | Base de données NoSQL avec stockage en colonnes            |
| Sqoop      | Logiciel d'import/export de données relationnelles         |
| MySQL      | Base de données relationnelles indépendant d'Hadoop        |
| Cassandra  | Base de données NoSQL                                      |
| MongoDB    | base de données avec stockage en documents                 |

#### **Programmation**

| Composants | Fonctionnalités                                                                       |
|------------|---------------------------------------------------------------------------------------|
| Pig        | Langage de programmation (Pig Latin) de haut niveau masquant la complexité MapReduce. |
| Spark      | plate-forme proposant des APIs de manipulation de données d'un cluster HDFS.          |


#### **Traitement de données en temps réel**

| Composants     | Fonctionnalités                                        |
|----------------|--------------------------------------------------------|
| Kafka          | récupérer les données provenant d'objets connectés     |
| Flume          | récuprérer des données de fichier log                  |
| Flink          | Traiter des flux de données                            |
| Storm          | moteur de déploiement de calcul sur un flux de données |
| SparkStreaming | gestion de flux de données en temps réel               |


#### **Management**

| Composants | Fonctionnalités                                                                             |
|------------|---------------------------------------------------------------------------------------------|
| Tez        | permet une récupération graphique des tâches(DAG)                                           |
| Zeppelin   | Offre une mise en forme visuelle de données traités par Spark                               |
| Zookeeper  | propose un service de configuration et de coordination des traitements disribués sur Hadoop |
| Oozie      | sert à ordonnancer les traitements Hadoop                                                   |
| Mesos      | Optimise l'utilisation des ressources Hadoop                                                |