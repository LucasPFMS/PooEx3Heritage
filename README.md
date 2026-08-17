Exercice 3 : Projet « PooEx3Heritage »
•
Exercice 3.1 : Commencer cette fois ci par créer un package "fr.fms.entities" puis dans celui-ci une classe Capitale qui hérite de la classe Ville avec comme particularité d'avoir un monument.
En effet, Paris est une Ville avec un monument la tour Eiffel ! (N’oublier pas d'ajouter la classe Ville dans votre package) puis ajouter une classe de Test avec un main dans votre package afin d'instancier plusieurs capitale, les modifier via les accesseurs et les afficher in fine via la méthode toString().
Nous devrions obtenir ceci :
<img width="1113" height="610" alt="image" src="https://github.com/user-attachments/assets/a9013caa-e39a-4ad8-88e3-9835ef7091cd" />


Exercice 3.2 : Dans le même package, ajouter la classe Employé qui hérite de Personne tel qu'un Employé est une Personne avec comme particularité d'être dans une entreprise avec un salaire. Puis créer une classe Test dans votre main pour instancier des Employés, afficher les en ajoutant une méthode toString() ! Faites en sorte qu’il y ai des employés ayant pour ville de naissance de type Capital ou City. Nous devrions avoir ce résultat sur la console :
Gate , Bill , 65ans , habitant aux USA , Ville de naissance : Washington , USA , 7600000 d'habitants monument : W-M , Entreprise : Fondation B&M , salaire : 100000.0
Musk , Elon , 49ans , habitant à palo alto , Ville de naissance : Pretoria , Afrique du Sud , 800000 d'habitants , Entreprise : Tesla , salaire : 150000.0
•
Exercice 3.3 : Ajouter une classe Commerciale qui est une personne qui travaille pour une entreprise avec une rémunération sur la base d’un pourcentage du chiffre d’affaires par mois puis vous connaissez dorénavant le mode opératoire : tester là !
Dupont , robert , 50ans , habitant rue des rosiers à Toulouse , Ville de naissance : Limoges , France , 133000 habitants Entreprise : brico , % CA : 5.0

•
Exercice 3.4 : Veiller à empêcher l’utilisateur de faire des mauvaises saisies (salaire ou remise négative par ex), dans ce cas, mettez des valeurs minimums par défaut que l’on pourra aisément modifier par la suite, tester pour vérifier si ça répond aux besoins.
% du chiffre d'affaire inférieur à 0 impossible
Dupont , robert , 50ans , habitant rue des rosiers à Toulouse , Ville de naissance : Limoges , France , 133000 habitants Entreprise : brico , % CA : 3.5
•
Exercice 3.5 : Faites en sorte que la population d’une ville n’apparaisse plus dorénavant
Gate , Bill , 65ans , habitant aux USA , Ville de naissance : Washington , USA monument : W-M , Entreprise : Fondation B&M , salaire : 100000.0
•
Exercice 3.6 : Dans une classe de Test « TestEntities » par ex, 
Utiliser un tableau avec plusieurs instances d’Employee et Commercial à parcourir pour afficher les informations de chaque objet la aussi à l'aide de la méthode toString().
Reproduisez le même test avec une liste d’objets pouvant contenir des employés ou des commerciaux.

<img width="1095" height="144" alt="image" src="https://github.com/user-attachments/assets/bdb12754-026b-4bd9-b0b9-4f9eb4bfb370" />

Exercice 3.7 : Ajouter la méthode rémunération d’un côté pour empêcher des instanciations de Person et de l’autre pour permettre aux classes filles de calculer respectivement la rémunération d’un employé (salaire - charges) ou d’un commercial (% du ca). Utiliser des données fictives et(ou) moyennes pour les charges (20%) et chiffre d’affaire (moyen : 50000) . Parcourez à nouveau le tableau de Person et appelez cette nouvelle méthode avec
un affichage réduit
:

<img width="563" height="147" alt="image" src="https://github.com/user-attachments/assets/dc18e76c-37c2-4eb3-aa91-ab23509b98b6" />
