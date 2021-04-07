# Optimisation-Windows-10
Ce doc vous permettra de faire un pc le plus sain possible et optimisé !
Clé USB Bootable Windows 10

•	Tout d’abord je tiens à préciser que réinstaller Windows est primordial pour faire des optimisations Windows ou juste pour avoir un PC sain !

Une clé USB de 8Go minimum est requise.

Si tu en as pas en voilà des pas cher :
•	EMTEC 8Go USB 2.0 - 5.50€ : Ce lien
•	Kingston Data Travel 32Go USB 2.0 - 6€ : Ce lien
•	SanDisk 16Go USB 2.0 - 7€ : Ce lien
•	Pack de 3X 32Go USB 3.0 - 16€ : Ce lien

Il y a 2 façons pour faire une clé bootable (que je connais tout du moins).

•	Rufus : Il permet de faire correctement une clé USB Bootable 99,99% de réussite.
•	L'outil de création du support Microsoft : Il permet de faire correctement une clé USB Bootable 1/15 très souvent mais 99,99% de réussite chez certains.

Comment faire ensuite “RUFUS” ?
Pour Rufus c’est simple.
Il te suffit juste de l’installer via ce lien (lien direct).

•	Il risque de te demander de vérifier les mises à jour, alors met oui ;)
•	Après ça tu ouvres Rufus. 

Présentation :
•	Dans le périphérique tu dois avoir ta clé USB que tu as branché à ton PC.
•	Type de démarrage tu laisses par défaut. (Image disque ou ISO etc).
•	Tu cliques sur “sélection” afin de sélectionner l’ISO que tu as téléchargé juste avant.
•	Schéma de partition tu laisses MBR s'il est en GPT ce n’est pas grave met l'en MBR.
•	Tout le reste tu le laisses comme c’est.

Comment faire ensuite “L'outil de création de support” ?
Pour L'outil de création du support c’est simple.
Il te suffit juste de l’installer via ce lien (lien direct).


•	Tu n'as qu'à suivre ce que Microsoft te demande ;).

Après tout ça tu as fini ta clé USB Bootable ;)
Félicitations !!!
Installation / Réinstallation Windows 10

Le lien du premier doc : ce lien


•	Tout d’abord je tiens à préciser que réinstaller Windows est primordial pour faire des optimisations Windows ou juste pour avoir un PC sain !

ATTENTION :
•	Avant de commencer, je vous conseille fortement de sauvegarder vos données importantes sur un disque dur externe. Si vous suivez toutes les indications correctement, tout devrait bien se passer.


•	Si une manipulation vous fait peur et que vous pensez faire n’importe quoi, ne la faites tout simplement pas.


•	Je vous invite également à regarder la vidéo plusieurs fois avant afin de comprendre comment ça fonctionne et éviter les bêtises.

Ce GDOC est là pour ceux qui ne veulent pas regarder la vidéo mais la suivre juste en lisant.

Merci de descendre afin de voir pour les BIOS en question


!!! JUSTE AVANT DE COMMENCER :

Débrancher le câble “RJ45” “Ethernet” afin de faire en sorte qu’il ne fasse pas toutes les mises à jour car nous allons le faire nous-même et proprement. !!!

Pour MSI :

Il faut commencer par démarrer / redémarrer votre ordinateur.
Cette façon est aussi bonne pour l’utilitaire de Microsoft !


•	Vous allez appuyer sur le bouton “Suppr / Delete” afin de rentrer dans le BIOS.
•	Une fois arrivé sur le BIOS vous allez donc appuyer sur 

- “F7” pour rentrer dans le mode avancé.
- Vous faites “entrer” sur Settings.
- Puis vous descendez sur “Boot”.
- “Entrer” sur “Boot”.

Pour ceux qui sont en MBR vérifier que le “Boot Mode Select” soit bien sur [LEGACY + UEFI] et pour ceux qui sont en GPT sélectionner [LEGACY] !

Ensuite vous allez descendre sur :
•	“Boot Option #1” 
•	“Entrer” sur “Boot Option #1”
•	Sélectionner UEFI KEY:UEFI nom de votre clé USB, Partition 1
•	“Entrer”
Puis pour les autres “Boot Option # ”
•	“Boot Option #2”
•	“Entrer” sur “Boot Option #2”
•	Sélectionner “Désactivé”
•	“Entrer”
Répéter cette action autant de fois que vous avez de “Boot Option”

Une fois que vous avez fini alors faite 
•	“F10”
•	“Oui”
Le PC redémarre !!! Ne retirez pas la clé USB !!!

Cette manipulation consiste à réduire le temps de démarrage. Windows va voir tous les “Boot Options” et va vouloir tous les préparer. Alors qu’il n'y en a qu’un seul !
Attention : Si vous faites un CMOS “Clear CMOS” (réinitialisation de la carte-mère alors tout ce que vous avez fait aura tout simplement été retiré et il faudra tout refaire).


La suite juste en dessous ! 
Une fois que le PC à redémarrer
•	Il va vous afficher une fenêtre avec marquer “Installer Maintenant”.
•	Cliquer dessus.
•	Il va vous afficher de nouveau une fenêtre avec marquer “activer Windows”.

Pour ceux qui n'ont pas de clé Windows voici un lien pour en acheter des officiels à usage unique. Ce lien
Rentrer la clé qui vous a été envoyée.
Pour ceux qui en ont ou juste avec un compte Microsoft alors faite :


•	“Je n’ai pas de clé de produit
•	Cliquer sur “Suivant”
•	Descendez et sélectionnez Windows 10 Professionnel
•	“Suivant”
•	Sélectionner “Personnalisé”

A ce moment la vous verrez votre SSD / HDD et toutes les partitions !

Attention : Veillez à bien sauvegarder vos documents / fichiers sur un disque dur Externe, cette manipulation supprime tout de votre disque dur / SSD à vie et sera donc impossible de les récupérer !

Ensuite : 
•	Cliquer sur l’une des partitions et faite “Supprimer”

Refaite le sur toutes les partitions afin qu’il reste seulement Lecteur 0 et 1 ou uniquement 0 si vous n'avez qu’un SSD / HDD.

*Il se peut que votre SSD soit en “lecteur 1” et que votre HHD en “Lecteur 0” sélectionner bien votre SSD dans ce cas-là.


•	Sélectionnez votre SSD ou votre HDD
•	Faite “nouveau”
•	Attendez le temps que tout soit “re-sélectionnable"
•	Cliquez sur “Suivant”

Vous avez une nouvelle fenêtre qui s’ouvre avec les statuts qu’il va faire.
Attendez bien que tout soit bien terminé.




La suite juste en dessous !
Le PC va donc redémarrer et refaite “Suppr / Delete” afin de rentrer dans le BIOS.

Une fois arrivé sur le BIOS vous allez donc appuyer sur :
•	“F7” pour rentrer dans le mode avancé.
•	Vous faites “entrer” sur Settings.
•	Puis vous descendez sur “Boot”.
•	“Entrer” sur “Boot”.
•	“Boot Option #1” 
•	“Entrer” sur “Boot Option #1”
•	Sélectionner UEFI Hard Disk:Windows Boot Manager (Votre SSD ou HDD).
•	“Entrer”
•	“F10”
•	“Oui”
Le PC redémarre, vous pouvez retirer votre clé USB.


Félicitations tu viens d’installer Windows 10 !!!

Le PC va donc redémarrer un message “Préparation” s’affiche, alors attendez.

Configuration Windows 10 :


•	Sélectionner “Français” pour la langue courante du PC, 
•	“Oui”
•	Sélectionner “Français” pour la langue du clavier,
•	“Oui”
•	“Configurer pour une utilisation personnelle”
•	“Compte Hors Connexion” nous choisissons cette solution pour avoir le moins de services Windows qui sont chiant à désactiver, avoir le PC le plus sain et pour avoir le plus de vie privé
•	“Expérience Limitée” nous choisissons cette solution pour avoir le moins de services Windows qui sont chiant à désactiver, avoir le PC le plus sain et pour avoir le plus de vie privé
•	Mettez votre “pseudo” ou votre “prénom”
•	Mettez ou non un mot de passe
•	Sélectionner “Ne pas utiliser la reconnaissance vocale en ligne” puis “accepter”
•	Sélectionner “Non” puis “accepter”
•	Sélectionner “Non” puis “accepter”
•	Sélectionner “Non” puis “accepter”
•	Sélectionner “Basique” puis “accepter”
•	Sélectionner “Non” puis “accepter”
•	Sélectionner “Non” puis “accepter”
•	Sélectionner “Non” puis “accepter”
•	“Non”
•	“Pas maintenant”

Attendez le PC termine sa configuration !

Une fois arrivé sur le bureau, rentre la ligne de commande suivante qui permet de faire en sorte de ne pas faire de mise à jour automatiquement et qui va tout merder souvent !

•	Cette commande vient de Piwi_

REG ADD "HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\DriverSearching" /v SearchOrderConfig /t REG_DWORD /d 00000000 /f

Redémarrer votre PC et brancher votre câble Ethernet / RJ45.

Bravo vous avez fini d’installer Windows maintenant commençons l’optimisation et les mises à jour ! Mais ça c’est dans le prochain doc / vidéo !


Mise à jour de Windows 10

!!! Avant toutes manipulations merci de faire ces quelques manipulations afin de “prévenir” !!!

1) Créer un point de restauration système :
Cliquez sur le menu démarrer et écrivez « créer un point de restauration » (copier/coller le texte).
 

2) Appuyez sur Enter ou cliquez sur le résultat.
Sélectionnez le disque où il est écrit système, ensuite cliquez sur « créer ».
 

3) Nommez votre sauvegarde avec une date afin de vous y retrouver si vous possédez plusieurs sauvegardes et cliquez sur « Créer ».
 
4) La sauvegarde est terminée, vous pouvez cliquer sur « fermer » et fermer toutes les fenêtres.

Continuité : juste en dessous

Mettre à jour votre PC / Carte mère :

Selon votre marque de carte-mère allez sur Microsoft edge.
•	Marquez le nom de votre carte-mère suivi de drivers 
Exemple : MSI MPG Z390 Gaming Plus drivers
Sélectionner le site constructeur comme sur cette image :
 

Vous devriez arriver sur une page dans ce style :
 

La suite en dessous ;)
Sélectionner “Pilotes”
 

Sélectionner “Win 10 64Bits”
 

Puis parcourez tous les menus / toutes les sélections et téléchargez les derniers en date.
 


•	Téléchargez-les, un par un.
•	Il se peut que certains vous demandent de redémarrer votre PC,  d'autres vous diront que certains logiciels sont déjà lancés et que pour pouvoir en relancer il faut redémarrer votre PC.
•	Continuer jusqu' à avoir des drivers à installer.

Installez ensuite les logiciels / drivers de vos périphériques.
•	Exemple :
J’ai une SteelSeries Rival 300, il faut que j’installe SteelSeries Engine 3.
J’ai une Logitech G502, il faut que j’installe GHub.
Pour les carte graphique : 

Nvidia : 
Tout d’abord commencer par aller sur Microsoft edge.

Et mettez Drivers GTX ou RTX si vous avez une carte graphique GTX / RTX.

Sinon allez directement ce lien (lien officiel Nvidia).


•	Pour carte graphique NVidia :

Pour ceux qui voudront installer uniquement le driver (à mettre à jour toutes les 2-4 semaines manuellement sans installer GeForce experience) :


•	Type de produit mettez : GeForce
•	Série de produits sélectionnés : GeForce GTX ou RTX suivant votre carte (et notebooks si c'est un portable).
•	Gamme de produits sélectionnés : votre carte graphique (1650-1660-1070 ti-3070 etc)
•	Système d'exploitation Windows 10
•	Type de téléchargement : Pilote GRD
•	Langue Français 

Une fois que c’est installé :
•	Lancer le driver
•	Sélectionné “personnalisé”
•	“Continuer” / “Suivant”
•	Continuer l’installation en faisant ce qu’ils disent et une fois le driver installé ça sera bon.
•	Pour avoir directement Nvidia qui vous informe d'un nouveau pilote (pour les têtes en l'air) : https://fr.download.nvidia.com/GFE/GFEClient/3.21.0.36/GeForce_Experience_v3.21.0.36.exe
•	Faite comme en haut mais n’oubliez pas d'installer GeForce Experience ;)
•	Connectez-vous avec un compte google.
•	Vérifiez les mises à jour via GeForce Experience
•	Lancer l’installation et faire comme ce qui est écrit plus haut.

•	Pour les cartes graphique AMD :

Pour ceux qui voudront installer uniquement le driver (à mettre à jour toutes les 2-4 semaines manuellement sans installer le AMD Radeon Software de mise à jour automatique) :

•	Graphics : AMD Radeon xxxx https://www.amd.com/fr/support
•	Pour avoir directement AMD qui vous informe d'un nouveau pilote (pour les têtes en l'air) : https://drivers.amd.com/drivers/installer/20.50/beta/radeon-software-adrenalin-2020-21.3.2-minimalsetup-210329_web.exe


Pour les carte graphique :

Nvidia : 
Tout d’abord commencer par aller sur Microsoft edge.

Et mettez Drivers GTX ou RTX si vous avez une carte graphique GTX / RTX.

Sinon allez directement ce lien (lien officiel Nvidia).


•	Pour carte graphique NVidia :

Pour ceux qui voudront installer uniquement le driver (à mettre à jour toutes les 2-4 semaines manuellement sans installer GeForce experience) :

•	Type de produit mettez : GeForce
•	Série de produits sélectionnés : GeForce GTX ou RTX suivant votre carte (et notebooks si c'est un portable).
•	Gamme de produits sélectionnés : votre carte graphique (1650-1660-1070 ti-3070 etc)
•	Système d'exploitation Windows 10
•	Type de téléchargement : Pilote GRD
•	Langue Français 

Une fois que c’est installé :
•	Lancer le driver
•	Sélectionné “personnalisé”
•	“Continuer” / “Suivant”
•	Continuer l’installation en faisant ce qu’ils disent et une fois le driver installé ça sera bon.

Pour avoir directement Nvidia qui vous informe d'un nouveau pilote (pour les têtes en l'air) : https://fr.download.nvidia.com/GFE/GFEClient/3.21.0.36/GeForce_Experience_v3.21.0.36.exe

•	Faite comme en haut mais n’oubliez pas d'installer GeForce Experience ;)
•	Connectez-vous avec un compte google.
•	Vérifiez les mises à jour via GeForce Experience
•	Lancer l’installation et faire comme ce qui est écrit plus haut.


•	Pour les cartes graphique AMD :

Pour ceux qui voudront installer uniquement le driver (à mettre à jour toutes les 2-4 semaines manuellement sans installer le AMD Radeon Software de mise à jour automatique) :


•	Graphics : AMD Radeon xxxx https://www.amd.com/fr/support
•	Pour avoir directement AMD qui vous informe d'un nouveau pilote (pour les têtes en l'air) : https://drivers.amd.com/drivers/installer/20.50/beta/radeon-software-adrenalin-2020-21.3.2-minimalsetup-210329_web.exe


Optimisation Windows 10 : 
LA RAM #1/..
!!! Avant toutes manipulations merci de faire ces quelques manipulations afin de “prévenir” !!!

1) Créer un point de restauration système :
Cliquez sur le menu démarrer et écrivez « créer un point de restauration » (copier/coller le texte).

2) Appuyez sur Enter ou cliquez sur le résultat.
Sélectionnez le disque où il est écrit système, ensuite cliquez sur « créer ».

3) Nommez votre sauvegarde avec une date afin de vous y retrouver si vous possédez plusieurs sauvegardes et cliquez sur « Créer ».

4) La sauvegarde est terminée, vous pouvez cliquer sur « fermer » et fermer toutes les fenêtres.

Continuité : juste en dessous


ISLC
Intellingent Stanbly List Cleaner

ISLC sert à vider votre ram quand elle est remplie d'informations et qui peuvent ralentir / faire freeze votre pc en jeux !

Pour l’installer vas sur (lien direct) : ce lien

Une fois que tu l’a télécharger,
•	Ouvre-le
•	Une page s’ouvre de ce type
 
•	Extrait le dans un endroit où tu n’es sûr de jamais y aller et où surtout tu n’es pas susceptible de le supprimer.
Exemple :  


•	Une fois que c’est extrait il te reste plus qu’à aller à l’emplacement du logiciel.
•	Ouvre-le puis coche :
Start ISLC minimized and auto-start monitoring (le démarre dans la barre de tâches)
 
Launch ISLC on user logon (TaskScheduler).
 

Configuration :
Alors maintenant on va commencer à le configurer.
•	Nous allons commencer par mettre 500mb pour “The list size is at least”
Ça veut dire que ça va vider la ram quand elle atteindra 500mb de consommation / de données stockées.
 
•	Nous allons allouer 5000 mb de ram pour “Free memory is lower than :”
Ça veut dire que ça ne va pas dépasser 5Go de ram restante, en gros s’il reste 5Go sur 16Go alors il va tout vider.
 

•	Pour ISLC polling rate (ms) : 1000
Ça veut dire que toutes les xxxx ms il va vérifier la RAM et il va décider de la vider.
 
•	Pour Wanted time resolution nous mettons “0.50”
Ça veut dire que ça se met à jour toutes les 0.50ms
 
•	Cochez la case “Enable custom timer resolution”
 


•	Cliquez sur “Start”
 
•	Cliquez sur Purge Standby list
 
Et enfin cliquez sur le petit trait qui sert à abaisser le logiciel;
Il va se mettre en bas dans la barre de tâches, et fera tout automatiquement.
 
 
Et voilà tu as optimisé ta ram ;)



Optimisation Windows 10 :
L'alimentation #2/..

!!! Avant toutes manipulations merci de faire ces quelques manipulations afin de “prévenir” !!!

1) Créer un point de restauration système :
Cliquez sur le menu démarrer et écrivez « créer un point de restauration » (copier/coller le texte).

2) Appuyez sur Enter ou cliquez sur le résultat.
Sélectionnez le disque où il est écrit système, ensuite cliquez sur « créer ».

3) Nommez votre sauvegarde avec une date afin de vous y retrouver si vous possédez plusieurs sauvegardes et cliquez sur « Créer ».

4) La sauvegarde est terminée, vous pouvez cliquer sur « fermer » et fermer toutes les fenêtres.



•	Aucun danger, la seule chose est que ça peut faire légèrement augmenter ta consommation mais de très peu de -1% !
•	On fait ça de façon à faire en sorte que ton proco soit au max des performances quand on en a besoin. et au minimum quand t’es sur le bureau afin de profiter au max de ton pc !


Continuité : juste en dessous


Optimisation de l’alimentation :

Nous commençons par aller sur le logo Windows  
•	Mettez “Panneau de configuration”
•	Ouvrez le
•	Allez sur matériel et audio
•	Puis sur Options d’alimentation
•	Déroulez les modes supplémentaires
Cochez “Performance élevées” (dans mon cas je l’ai déjà fait donc il est en haut).
 
•	Cliquez sur “Modifier les paramètres du mode”
 
•	Sur “Éteindre l’écran” sélectionnez “JAMAIS”
•	Sur “Mettre l’ordinateur en veille” sélectionnez “JAMAIS”



Descendez ;) 
•	Cliquez sur “Modifiez les paramètres d’alimentation avancés”
		Une fenêtre s’ouvre et est mis par défaut Disque Dur


•	Configuration : 
“Disque Dur - Arrêter le disque dur après : “0 mins” qui signifie “jamais”.
“Paramètres d’arrière plan du bureau - Diaporama : “Suspendu”
“Paramètres des cartes sans fil - Mode économies d’énergies : “Performances maximales”
“Veille - Veille après : “0 mins” qui signifie “jamais”,
Autoriser les minuteurs de sortie de veille “désactivé”
“Paramètre USB - Paramètre de la suspension sélective USB “Désactivée”
“PCI Express - Gestion de l’alimentation de l’état de la liaison “Désactivé”
Gestion de l’alimentation du processeur - État min du processeur “5%”
  État max du processeur “100%”

	“Affichage - Éteindre l’affichage après “Jamais”


Parfait tu viens d’optimiser l’alimentation de ton PC ;) 
