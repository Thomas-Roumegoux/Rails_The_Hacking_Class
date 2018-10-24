THE HACKING CLASS

Requiert ruby 2.5.1
Requiert Rails 5.2.1
The_Hacking_Class est une application rails pour un site d'éducation en ligne.
Pour lancer l'application lancez "Bundle Install"
Ensuite faites un "rails db:seed"
A la suite de ça vous pourrez lancer "rails console" et parcourir les différentes tables créer
Elle contient une base de données qui fonctionne comme expliqué ci-dessous:

	Cour:
			- Nous avons une table cour qui contient le nom des cours,ainsi que leurs descriptions,ces cours contiennent plusieurs leçons et plusieurs élèves.
	Lecon:
			- Nous avons une table Lecon qui contient le titre des leçons,ainsi que leurs contenus,ces leçons sont dépendantes d'un cours.

	Eleve:
			- Nous avons une table Eleve qui contient le prénom et le nom des élèves,ils sont dépendant d'un cours.

Cette exercice a été réalisé avec l'aide de rado,mathieu et hannane