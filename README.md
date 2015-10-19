# Covoiturage
Covoiturage PromÃ©o

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




Déclaration du conducteur (seulement pour les offrants)
Moi ____________________________ reconnaît être en possession d’un permis de conduire
(Inscrire votre nom en lettre moulée)
valide au Québec non expiré et non suspendu et que mon (ou mes véhicules) est immatriculé et
fait l’objet d’une police d’assurance, telle qu’il est requis par la loi, et que je suis assuré en vertu
de ladite police.
En remplissant le présent formulaire, je consens à ce que les renseignements personnels que je
fournis soient transmis à un tiers afin de permettre la mise en œuvre du programme de
covoiturage et la réalisation des jumelages. Transport Autonomie Beauce-Etchemins se
dégage de toute responsabilité pour toute perte ou tout vol et dommage matériel et physique
résultant du covoiturage. 

Transport Autonomie Beauce-Et chemins se décharge de toutes responsabilités
et agit seulement en tant qu'intermédiaire. 

Vérifier que la personne soit de proméo
Page portail
récupération photo 