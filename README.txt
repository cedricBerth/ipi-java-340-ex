Exercices de Java, module 350 pour l'IPI. Il est n�cessaire de forker ce repository pour pouvoir faire tout le TP !! Apr�s chaque question, pusher vos modifications sur votre repository.

Int�gration continue

Rajouter la configuration n�cessaire pour Travis dans le projet.
Vous connecter � Travis https://travis-ci.org avec votre compte Github.
Configurer le projet et v�rifier que le premier build se passe correctement. Apr�s chaque exercice, v�rifier que le build passe toujours...
Evaluation de la qualit�

Connectez-vous � SonarQube https://about.sonarcloud.io/ avec votre compte Github
Ajouter votre projet dans Sonar
Modifier votre configuration Travis pour lancer une analyse apr�s chaque build
V�rifier que tout est ok
Analyser le premier rapport de Sonar
Tests unitaires

Cr�er la classe CommercialTest dans le bon package pour tester quelques m�thodes de la classe Commercial.
Tester le plus compl�tement possible la m�thode permettant de r�cup�rer la prime annuelle
Cr�er la classe CommercialParameterizedTest dans le m�me package et tester compl�tement et de mani�re param�tr�e la m�thode equivalenceNote.
Ajouter le fichier application.properties de test pour utiliser une base de donn�es m�moire H2
Cr�er la classe EmployeRepositoryTest et tester la m�thode findByNomOrPrenomAllIgnoreCase le plus compl�tement possible.
Ajouter une m�thode before supprimant le contenu des tables manipul�es dans les tests.
Cr�er la classe EmployeServiceTest et tester la m�thode findByMatricule en mockant l'utilisation de la base de donn�es.
Cr�er la classe TechnicienServiceTest et tester la m�thode addManager en v�rifiant les param�tres pass�s aux m�thodes save des repository pour s'assurer que le manager a �t� ajout� au technicien et inversement.
Tests d'int�gration

Cr�er la classe ManagerServiceTest et tester de mani�re int�gr�e la m�thode addTechniciens
Tests d'acceptation


Probl�me sur la m�thode findEmployesPlusRichesHasSize() : la m�thode fonctionne mais la requ�te associ�e findEmployesPlusRiches() ne se fait de nouveau plus.