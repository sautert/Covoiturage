# Covoiturage
Covoiturage Proméo

CREATE TABLE IF NOT EXISTS user_info
(
	`id` SMALLINT UNSIGNED NOT NULL AUTO_INCREMENT PRIMARY KEY,
	`nom` VARCHAR(40) NOT NULL,
	`prenom` VARCHAR(40) NOT NULL,
	`email` VARCHAR(50) NOT NULL,
	`telephone` VARCHAR(20),
	`ville_depart` VARCHAR(30) NOT NULL,
	`point_de_rendez_vous` VARCHAR(30),
	`adresse_travail` VARCHAR(30),
	`site_promeo` SMALLINT NOT NULL,
	`conducteur` BOOLEAN,
	`photo` TEXT,
	`places` SMALLINT UNSIGNED
)ENGINE=INNODB;




D�claration du conducteur (seulement pour les offrants)
Moi ____________________________ reconna�t �tre en possession d�un permis de conduire
(Inscrire votre nom en lettre moul�e)
valide au Qu�bec non expir� et non suspendu et que mon (ou mes v�hicules) est immatricul� et
fait l�objet d�une police d�assurance, telle qu�il est requis par la loi, et que je suis assur� en vertu
de ladite police.
En remplissant le pr�sent formulaire, je consens � ce que les renseignements personnels que je
fournis soient transmis � un tiers afin de permettre la mise en �uvre du programme de
covoiturage et la r�alisation des jumelages. Transport Autonomie Beauce-Etchemins se
d�gage de toute responsabilit� pour toute perte ou tout vol et dommage mat�riel et physique
r�sultant du covoiturage. 

Transport Autonomie Beauce-Et chemins se d�charge de toutes responsabilit�s
et agit seulement en tant qu'interm�diaire. 

V�rifier que la personne soit de prom�o
Page portail
r�cup�ration photo 