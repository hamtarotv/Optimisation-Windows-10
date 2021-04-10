Clé USB Bootable Windows 10
• Tout d’abord je tiens à préciser que réinstaller Windows est primordial
pour faire des optimisations Windows ou juste pour avoir un PC sain !
Une clé USB de 8Go minimum est requise.
Si tu en as pas en voilà des pas cher :
• EMTEC 8Go USB 2.0 - 5.50€ : Ce lien
• Kingston Data Travel 32Go USB 2.0 - 6€ : Ce lien
• SanDisk 16Go USB 2.0 - 7€ : Ce lien
• Pack de 3X 32Go USB 3.0 - 16€ : Ce lien
Il y a 2 façons pour faire une clé bootable (que je connais tout du moins).
• Rufus : Il permet de faire correctement une clé USB Bootable 99,99% de
réussite.
Les ISO sont disponibles juste ici !
• L'outil de création du support Microsoft : Il permet de faire correctement
une clé USB Bootable 1/15 très souvent mais 99,99% de réussite chez
certains.
Comment faire ensuite “RUFUS” ?
Pour Rufus c’est simple.
Il te suffit juste de l’installer via ce lien (lien direct).
• Il risque de te demander de vérifier les mises à jour, alors met oui ;)
• Après ça tu ouvres Rufus.
Présentation :
• Dans le périphérique tu dois avoir ta clé USB que tu as branché à ton PC.
• Type de démarrage tu laisses par défaut. (Image disque ou ISO etc).
• Tu cliques sur “sélection” afin de sélectionner l’ISO que tu as téléchargé juste
avant.
• Schéma de partition tu laisses MBR s'il est en GPT ce n’est pas grave met l'en
MBR.
• Tout le reste tu le laisses comme c’est.
Comment faire ensuite “L'outil de création de support” ?
Pour L'outil de création du support c’est simple.
Il te suffit juste de l’installer via ce lien (lien direct).
• Tu n'as qu'à suivre ce que Microsoft te demande ;).
Après tout ça tu as fini ta clé USB Bootable ;)
Félicitations !!!
Appris via la vidéo de AngA_TV sur sa vidéo de la création Clé USB Bootable !
Pour plus d’info merci d’aller voir le le discord !
Installation / Réinstallation Windows 10
Le lien du premier doc : ce lien
• Tout d’abord je tiens à préciser que réinstaller Windows est primordial
pour faire des optimisations Windows ou juste pour avoir un PC sain !
ATTENTION :
• Avant de commencer, je vous conseille fortement de sauvegarder vos
données importantes sur un disque dur externe. Si vous suivez toutes
les indications correctement, tout devrait bien se passer.
• Si une manipulation vous fait peur et que vous pensez faire n’importe
quoi, ne la faites tout simplement pas.
• Je vous invite également à regarder la vidéo plusieurs fois avant afin de
comprendre comment ça fonctionne et éviter les bêtises.
Ce GDOC est là pour ceux qui ne veulent pas regarder la vidéo mais la suivre
juste en lisant.
Merci de descendre afin de voir pour les BIOS en question
!!! JUSTE AVANT DE COMMENCER :
Débrancher le câble “RJ45” “Ethernet” afin de faire en sorte qu’il ne fasse pas
toutes les mises à jour car nous allons le faire nous-même et proprement. !!!
Pour MSI :
Il faut commencer par démarrer / redémarrer votre ordinateur.
Cette façon est aussi bonne pour l’utilitaire de Microsoft !
• Vous allez appuyer sur le bouton “Suppr / Delete” afin de rentrer dans le
BIOS.
• Une fois arrivé sur le BIOS vous allez donc appuyer sur
- “F7” pour rentrer dans le mode avancé.
- Vous faites “entrer” sur Settings.
- Puis vous descendez sur “Boot”.
- “Entrer” sur “Boot”.
Pour ceux qui sont en MBR vérifier que le “Boot Mode Select” soit bien sur [LEGACY
+ UEFI] et pour ceux qui sont en GPT sélectionner [LEGACY] !
Ensuite vous allez descendre sur :
• “Boot Option #1”
• “Entrer” sur “Boot Option #1”
• Sélectionner UEFI KEY:UEFI nom de votre clé USB, Partition 1
• “Entrer”
Puis pour les autres “Boot Option # ”
• “Boot Option #2”
• “Entrer” sur “Boot Option #2”
• Sélectionner “Désactivé”
• “Entrer”
Répéter cette action autant de fois que vous avez de “Boot Option”
Une fois que vous avez fini alors faite
• “F10”
• “Oui”
Le PC redémarre !!! Ne retirez pas la clé USB !!!
Cette manipulation consiste à réduire le temps de démarrage. Windows va voir tous les “Boot Options”
et va vouloir tous les préparer. Alors qu’il n'y en a qu’un seul !
Attention : Si vous faites un CMOS “Clear CMOS” (réinitialisation de la carte-mère alors tout ce que
vous avez fait aura tout simplement été retiré et il faudra tout refaire).
La suite juste en dessous !
Une fois que le PC à redémarrer
• Il va vous afficher une fenêtre avec marquer “Installer Maintenant”.
• Cliquer dessus.
• Il va vous afficher de nouveau une fenêtre avec marquer “activer Windows”.
Pour ceux qui n'ont pas de clé Windows voici un lien pour en acheter des officiels à
usage unique. Ce lien
Rentrer la clé qui vous a été envoyée.
Pour ceux qui en ont ou juste avec un compte Microsoft alors faite :
• “Je n’ai pas de clé de produit
• Cliquer sur “Suivant”
• Descendez et sélectionnez Windows 10 Professionnel
• “Suivant”
• Sélectionner “Personnalisé”
A ce moment la vous verrez votre SSD / HDD et toutes les partitions !
Attention : Veillez à bien sauvegarder vos documents / fichiers sur un disque dur
Externe, cette manipulation supprime tout de votre disque dur / SSD à vie et sera
donc impossible de les récupérer !
Ensuite :
• Cliquer sur l’une des partitions et faite “Supprimer”
Refaite le sur toutes les partitions afin qu’il reste seulement Lecteur 0 et 1 ou
uniquement 0 si vous n'avez qu’un SSD / HDD.
*Il se peut que votre SSD soit en “lecteur 1” et que votre HHD en “Lecteur 0”
sélectionner bien votre SSD dans ce cas-là.
• Sélectionnez votre SSD ou votre HDD
• Faite “nouveau”
• Attendez le temps que tout soit “re-sélectionnable"
• Cliquez sur “Suivant”
Vous avez une nouvelle fenêtre qui s’ouvre avec les statuts qu’il va faire.
Attendez bien que tout soit bien terminé.
La suite juste en dessous !
Le PC va donc redémarrer et refaite “Suppr / Delete” afin de rentrer dans le
BIOS.
Une fois arrivé sur le BIOS vous allez donc appuyer sur :
• “F7” pour rentrer dans le mode avancé.
• Vous faites “entrer” sur Settings.
• Puis vous descendez sur “Boot”.
• “Entrer” sur “Boot”.
• “Boot Option #1”
• “Entrer” sur “Boot Option #1”
• Sélectionner UEFI Hard Disk:Windows Boot Manager (Votre SSD ou HDD).
• “Entrer”
• “F10”
• “Oui”
Le PC redémarre, vous pouvez retirer votre clé USB.
Félicitations tu viens d’installer Windows 10 !!!
Le PC va donc redémarrer un message “Préparation” s’affiche, alors attendez.
Configuration Windows 10 :
• Sélectionner “Français” pour la langue courante du PC,
• “Oui”
• Sélectionner “Français” pour la langue du clavier,
• “Oui”
• “Configurer pour une utilisation personnelle”
• “Compte Hors Connexion” nous choisissons cette solution pour avoir le moins
de services Windows qui sont chiant à désactiver, avoir le PC le plus sain et
pour avoir le plus de vie privé
• “Expérience Limitée” nous choisissons cette solution pour avoir le moins de
services Windows qui sont chiant à désactiver, avoir le PC le plus sain et pour
avoir le plus de vie privé
• Mettez votre “pseudo” ou votre “prénom”
• Mettez ou non un mot de passe
• Sélectionner “Ne pas utiliser la reconnaissance vocale en ligne” puis
“accepter”
• Sélectionner “Non” puis “accepter”
• Sélectionner “Non” puis “accepter”
• Sélectionner “Non” puis “accepter”
• Sélectionner “Basique” puis “accepter”
• Sélectionner “Non” puis “accepter”
• Sélectionner “Non” puis “accepter”
• Sélectionner “Non” puis “accepter”
• “Non”
• “Pas maintenant”
Attendez le PC termine sa configuration !
Une fois arrivé sur le bureau, rentre la ligne de commande suivante qui permet de
faire en sorte de ne pas faire de mise à jour automatiquement et qui va tout merder
souvent !
• Cette commande vient de Piwi_
REG ADD
"HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Driver
Searching" /v SearchOrderConfig /t REG_DWORD /d 00000000 /f
Redémarrer votre PC et brancher votre câble Ethernet / RJ45.
• Ses autres commandes viennent de Piwi_ !
Désactiver Cortana pour garder une vie privée et des performances !
REG ADD
"HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\Windows
Search" /v AllowCortana /t REG_DWORD /d 00000000 /f
Désactive la veille (en gros il ne s'éteint pas réellement quand on fait “arrêter)
REG ADD "HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Session
Manager\Power" /v HiberbootEnabled /t REG_DWORD /d 00000000 /f
Désactiver les raccourcis Alt + Maj ou Windows + Maj (ce qui nous fait rager
souvent par une fausse manip)
REG ADD "HKCU\Keyboard Layout\toggle" /v "Language Hotkey" /t REG_SZ
/d 3 /f
Désactiver l’abaissement des fenêtres (Quand on prend une page et que l’on la
déplace / secoue, toutes les autres s'abaissent).
REG ADD
"HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explore
r\Advanced" /v DisallowShaking /t REG_DWORD /d 00000001 /f
Désactiver aussi comme la 3ème commande mais supprime le fichier (et
économise quelques Gigas !
powercfg -h off
Active / s’assure que le stockage soit sur tout le SSD et non sur 1 seule partie
du ssd (Augmente la durée de vie du SSD) !
fsutil behavior set DisableDeleteNotify 0
S’assure d’avoir une réserve sur le processeur !
REG ADD "HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows
NT\CurrentVersion\Multimedia\SystemProfile" /v SystemResponsiveness
/t REG_DWORD /d 00000010 /f
Bravo vous avez fini d’installer Windows maintenant commençons
l’optimisation et les mises à jour ! Mais ça c’est dans le prochain doc / vidéo !
Pour plus d’info merci d’allez voir le Git Hub de Piwi_ ou de venir sur
le discord !
Appris via la vidéo de AngA_TV sur sa vidéo de la création Clé USB Bootable !
Appris via la vidéo et GitHub de Piwi_ son Git Hub !
Pour les carte graphique :
Nvidia :
Tout d’abord commencer par aller sur Microsoft edge.
Et mettez Drivers GTX ou RTX si vous avez une carte graphique GTX / RTX.
Sinon allez directement ce lien (lien officiel Nvidia).
• Pour carte graphique NVidia :
Pour ceux qui voudront installer uniquement le driver (à mettre à jour toutes
les 2-4 semaines manuellement sans installer GeForce experience) :
• Type de produit mettez : GeForce
• Série de produits sélectionnés : GeForce GTX ou RTX suivant votre carte (et
notebooks si c'est un portable).
• Gamme de produits sélectionnés : votre carte graphique (1650-1660-1070 ti3070 etc)
• Système d'exploitation Windows 10
• Type de téléchargement : Pilote GRD
• Langue Français
Une fois que c’est installé :
• Lancer le driver
• Sélectionné “personnalisé”
• “Continuer” / “Suivant”
• Continuer l’installation en faisant ce qu’ils disent et une fois le driver installé ça
sera bon.
• Pour avoir directement Nvidia qui vous informe d'un nouveau pilote (pour les
têtes en l'air) :
https://fr.download.nvidia.com/GFE/GFEClient/3.21.0.36/GeForce_Experience
_v3.21.0.36.exe
• Faite comme en haut mais n’oubliez pas d'installer GeForce Experience ;)
• Connectez-vous avec un compte google.
• Vérifiez les mises à jour via GeForce Experience
• Lancer l’installation et faire comme ce qui est écrit plus haut.
• Pour les cartes graphique AMD :
Pour ceux qui voudront installer uniquement le driver (à mettre à jour toutes
les 2-4 semaines manuellement sans installer le AMD Radeon Software de mise
à jour automatique) :
• Graphics : AMD Radeon xxxx https://www.amd.com/fr/support
• Pour avoir directement AMD qui vous informe d'un nouveau pilote (pour les
têtes en l'air) : https://drivers.amd.com/drivers/installer/20.50/beta/radeonsoftware-adrenalin-2020-21.3.2-minimalsetup-210329_web.exe
Pour plus d’info merci d’allez voir le le discord !
Appris via la vidéo de AngA_TV sur sa vidéo de la configuration du panneau
NVIDIA !
Encore plus en dessous !
Mise à jour de Windows 10
Optimisation Windows 0.1
!!! Avant toutes manipulations merci de faire ces quelques
manipulations afin de “prévenir” !!!
1) Créer un point de restauration système :
Cliquez sur le menu démarrer et écrivez « créer un point de restauration »
(copier/coller le texte).
2) Appuyez sur Enter ou cliquez sur le résultat.
Sélectionnez le disque où il est écrit système, ensuite cliquez sur « créer ».
3) Nommez votre sauvegarde avec une date afin de vous y retrouver si vous possédez
plusieurs sauvegardes et cliquez sur « Créer ».
4) La sauvegarde est terminée, vous pouvez cliquer sur « fermer » et fermer toutes les
fenêtres.
Continuité : juste en dessous
Mettre à jour votre PC / Carte mère :
Selon votre marque de carte-mère allez sur Microsoft edge.
• Marquez le nom de votre carte-mère suivi de drivers
Exemple : MSI MPG Z390 Gaming Plus drivers
Sélectionner le site constructeur comme sur cette image :
Vous devriez arriver sur une page dans ce style :
La suite en dessous ;)
Sélectionner “Pilotes”
Sélectionner “Win 10 64Bits”
Puis parcourez tous les menus / toutes les sélections et téléchargez les derniers en
date.
• Téléchargez-les, un par un.
• Il se peut que certains vous demandent de redémarrer votre PC, d'autres
vous diront que certains logiciels sont déjà lancés et que pour pouvoir en
relancer il faut redémarrer votre PC.
• Continuer jusqu' à avoir des drivers à installer.
Installez ensuite les logiciels / drivers de vos périphériques.
• Exemple :
J’ai une SteelSeries Rival 300, il faut que j’installe SteelSeries Engine 3.
J’ai une Logitech G502, il faut que j’installe GHub.
Pour les carte graphique :
Nvidia :
Tout d’abord commencer par aller sur Microsoft edge.
Et mettez Drivers GTX ou RTX si vous avez une carte graphique GTX / RTX.
Sinon allez directement ce lien (lien officiel Nvidia).
• Pour carte graphique NVidia :
Pour ceux qui voudront installer uniquement le driver (à mettre à jour toutes
les 2-4 semaines manuellement sans installer GeForce experience) :
• Type de produit mettez : GeForce
• Série de produits sélectionnés : GeForce GTX ou RTX suivant votre carte (et
notebooks si c'est un portable).
• Gamme de produits sélectionnés : votre carte graphique (1650-1660-1070 ti3070 etc)
• Système d'exploitation Windows 10
• Type de téléchargement : Pilote GRD
• Langue Français
Une fois que c’est installé :
• Lancer le driver
• Sélectionné “personnalisé”
• “Continuer” / “Suivant”
• Continuer l’installation en faisant ce qu’ils disent et une fois le driver installé ça
sera bon.
• Pour avoir directement Nvidia qui vous informe d'un nouveau pilote (pour les
têtes en l'air) :
https://fr.download.nvidia.com/GFE/GFEClient/3.21.0.36/GeForce_Experience
_v3.21.0.36.exe
• Faite comme en haut mais n’oubliez pas d'installer GeForce Experience ;)
• Connectez-vous avec un compte google.
• Vérifiez les mises à jour via GeForce Experience
• Lancer l’installation et faire comme ce qui est écrit plus haut.
• Pour les cartes graphique AMD :
Pour ceux qui voudront installer uniquement le driver (à mettre à jour toutes
les 2-4 semaines manuellement sans installer le AMD Radeon Software de mise
à jour automatique) :
• Graphics : AMD Radeon xxxx https://www.amd.com/fr/support
• Pour avoir directement AMD qui vous informe d'un nouveau pilote (pour les
têtes en l'air) : https://drivers.amd.com/drivers/installer/20.50/beta/radeonsoftware-adrenalin-2020-21.3.2-minimalsetup-210329_web.exe
Pour plus d’info merci d’allez voir le le discord !
Appris via la vidéo et GitHub de Piwi_ son Git Hub !
Continuité : juste en dessous
Optimisation Windows 10 :
LA RAM #1/..
!!! Avant toutes manipulations merci de faire ces quelques
manipulations afin de “prévenir” !!!
1) Créer un point de restauration système :
Cliquez sur le menu démarrer et écrivez « créer un point de restauration »
(copier/coller le texte).
2) Appuyez sur Enter ou cliquez sur le résultat.
Sélectionnez le disque où il est écrit système, ensuite cliquez sur « créer ».
3) Nommez votre sauvegarde avec une date afin de vous y retrouver si vous possédez
plusieurs sauvegardes et cliquez sur « Créer ».
4) La sauvegarde est terminée, vous pouvez cliquer sur « fermer » et fermer toutes les
fenêtres.
Continuité : juste en dessous
ISLC
Intellingent Stanbly List Cleaner
ISLC sert à vider votre ram quand elle est remplie d'informations et qui peuvent ralentir / faire
freeze votre pc en jeux !
Pour l’installer vas sur (lien direct) : ce lien
Une fois que tu l’a télécharger,
• Ouvre-le
• Une page s’ouvre de ce type
• Extrait le dans un endroit où tu n’es sûr de jamais y aller et où surtout tu n’es pas
susceptible de le supprimer.
Exemple :
• Une fois que c’est extrait il te reste plus qu’à aller à l’emplacement du logiciel.
• Ouvre-le puis coche :
Start ISLC minimized and auto-start monitoring (le démarre dans la barre de tâches)
Launch ISLC on user logon (TaskScheduler).
Configuration :
Alors maintenant on va commencer à le configurer.
• Nous allons commencer par mettre 500mb pour “The list size is at least”
Ça veut dire que ça va vider la ram quand elle atteindra 500mb de consommation /
de données stockées.
• Nous allons allouer 5000 mb de ram pour “Free memory is lower than :”
Ça veut dire que ça ne va pas dépasser 5Go de ram restante, en gros s’il reste 5Go
sur 16Go alors il va tout vider.
• Pour ISLC polling rate (ms) : 1000
Ça veut dire que toutes les xxxx ms il va vérifier la RAM et il va décider de la vider.
• Pour « Wanted time resolution » nous mettons “0.50”
Ça veut dire que ça se met à jour toutes les 0.50ms
• Cochez la case “Enable custom timer resolution”
• Cliquez sur “Start”
• Cliquez sur Purge Standby list
Et enfin cliquez sur le petit trait qui sert à abaisser le logiciel;
Il va se mettre en bas dans la barre de tâches, et fera tout automatiquement.
Et voilà tu as optimisé ta ram ;)
Appris via la vidéo et GitHub de Piwi_ son Git Hub !
Pour plus d’info merci d’allez voir le le discord !
Optimisation Windows 10 :
L'alimentation #2/..
!!! Avant toutes manipulations merci de faire ces quelques
manipulations afin de “prévenir” !!!
1) Créer un point de restauration système :
Cliquez sur le menu démarrer et écrivez « créer un point de restauration »
(copier/coller le texte).
2) Appuyez sur Enter ou cliquez sur le résultat.
Sélectionnez le disque où il est écrit système, ensuite cliquez sur « créer ».
3) Nommez votre sauvegarde avec une date afin de vous y retrouver si vous possédez
plusieurs sauvegardes et cliquez sur « Créer ».
4) La sauvegarde est terminée, vous pouvez cliquer sur « fermer » et fermer toutes les
fenêtres.
• Aucun danger, la seule chose est que ça peut faire légèrement augmenter ta
consommation mais de très peu de -1% !
• On fait ça de façon à faire en sorte que ton proco soit au max des performances
quand on en a besoin. et au minimum quand t’es sur le bureau afin de profiter au
max de ton pc !
Continuité : juste en dessous
Optimisation de l’alimentation :
Nous commençons par aller sur le logo Windows
• Mettez “Panneau de configuration”
• Ouvrez le
• Allez sur matériel et audio
• Puis sur Options d’alimentation
• Déroulez les modes supplémentaires
Cochez “Performance élevées” (dans mon cas je l’ai déjà fait donc il est
en haut).
• Cliquez sur “Modifier les paramètres du mode”
• Sur “Éteindre l’écran” sélectionnez “JAMAIS”
• Sur “Mettre l’ordinateur en veille” sélectionnez “JAMAIS”
Descendez ;)
• Cliquez sur “Modifiez les paramètres d’alimentation avancés”
Une fenêtre s’ouvre et est mis par défaut Disque Dur
• Configuration :
“Disque Dur - Arrêter le disque dur après : “0 mins” qui signifie “jamais”.
“Paramètres d’arrière plan du bureau - Diaporama : “Suspendu”
“Paramètres des cartes sans fil - Mode économies d’énergies :
“Performances maximales”
“Veille - Veille après : “0 mins” qui signifie “jamais”,
Autoriser les minuteurs de sortie de veille “désactivé”
“Paramètre USB - Paramètre de la suspension sélective USB “Désactivée”
“PCI Express - Gestion de l’alimentation de l’état de la liaison “Désactivé”
Gestion de l’alimentation du processeur - État min du processeur “5%”
 État max du processeur “100%”
“Affichage - Éteindre l’affichage après “Jamais”
Parfait tu viens d’optimiser l’alimentation de ton PC ;)
Pour plus d’info merci d’allez voir le le discord !
Appris via la vidéo de AngA_TV sur sa chaîne !
Optimisation Windows 10 :
L'affichage #3/..
!!! Avant toutes manipulations merci de faire ces quelques
manipulations afin de “prévenir” !!!
1) Créer un point de restauration système :
Cliquez sur le menu démarrer et écrivez « créer un point de restauration »
(copier/coller le texte).
2) Appuyez sur Enter ou cliquez sur le résultat.
Sélectionnez le disque où il est écrit système, ensuite cliquez sur « créer ».
3) Nommez votre sauvegarde avec une date afin de vous y retrouver si vous possédez
plusieurs sauvegardes et cliquez sur « Créer ».
4) La sauvegarde est terminée, vous pouvez cliquer sur « fermer » et fermer toutes les
fenêtres.
Continuité : juste en dessous
Optimisation de l’affichage :
Nous commençons par aller sur le logo Windows
• Mettez “Panneau de configuration”
• Ouvrez-le !
• Allez sur “Système et sécurité”
• Puis sur “Système” (pour ceux qui sont avec une version de W10 avant 2004)
Sinon mettez cette ligne de commande :
“Panneau de configuration\Système et sécurité\Système”
• Cliquez sur “Paramètres système avancés”
• Puis cliquez sur “Paramètres …” dans “performances”
• Cochez “Paramètres personnalisés”.
• Décochez tout sauf
“Afficher des miniatures au lieu d’icônes”
“Lisser les polices écran
• Cliquez sur "Appliquer".
• Puis sur “OK”.
Parfait tu viens d’optimiser l’affichage “windows” de ton PC ;)
Appris via Théo TV
Pour plus d’info merci d’allez voir le le discord !
Optimisation Windows 10 :
NVIDIA #4/..
!!! Avant toutes manipulations merci de faire ces quelques
manipulations afin de “prévenir” !!!
1) Créer un point de restauration système :
Cliquez sur le menu démarrer et écrivez « créer un point de restauration »
(copier/coller le texte).
2) Appuyez sur Enter ou cliquez sur le résultat.
Sélectionnez le disque où il est écrit système, ensuite cliquez sur « créer ».
3) Nommez votre sauvegarde avec une date afin de vous y retrouver si vous possédez
plusieurs sauvegardes et cliquez sur « Créer ».
4) La sauvegarde est terminée, vous pouvez cliquer sur « fermer » et fermer toutes les
fenêtres.
Cette manipulation sera à refaire à chaque fois que l’on mettra à
jour notre driver / réinstallation du driver.
Continuité : juste en dessous
Vérifiez bien que vous ayez votre driver à jour !
Optimisation du Pannel NVIDIA !
Tout d’abord, commencez par aller sur votre bureau.
Faites un clique droit “Panneau de configuration”.
• Allez dans la catégorie “Affichage” et allez sur “Changer la résolution”.
Vérifiez bien que vous êtes sur la fréquence de rafraîchissement au max et en
résolution PC !
• Dans “Régler les paramètres des couleurs du bureau”
Mettez “L’éclat numérique” à 55-60%” c’est pour rendre les couleurs vives.
Mettez “Teinte” à 360°
Cliquez sur Appliquer en bas à droite du panneau de configuration NVIDIA
• Dans “Régler la taille et la position du bureau”
• Cocher dans l’onglet “Mise à l’échelle” :
Pas de mise à l’échelle.
• Dans “Effectuez la mise à l’échelle sur :”
Processeur graphique
Cliquez sur Appliquer en bas à droite du panneau de configuration NVIDIA
• Allez dans la catégorie “Paramètre 3D” et allez sur “Régler les paramètres
d’image avec aperçu".
• Cocher “Utiliser mes préférences pour améliorer :”
• Mettez le curseur à fond, c'est-à-dire “tout à droite”.
Cliquez sur Appliquer en bas à droite du panneau de configuration NVIDIA
Continuité : juste en dessous
• Allez sur “Gérer les paramètres 3D".
• Lissage d’images : “Désactiver”
• Mode de faible latence (plus bas) : “Désactiver”
Il n’y a pas de différence donc à tester pour vous !
• Filtrage de texture - qualité : “Désactiver”
• Mode de faible latence (plus bas) : “Désactiver”
• Mode de gestion de l’alimentation : “Privilégier les performances
maximales”.
• La synchronisation verticale : “Désactiver”
Cliquez sur Appliquer en bas à droite du panneau de configuration NVIDIA
Parfait tu viens d’optimiser ton panneau de configuration NVIDIA ;)
Pour plus d’info merci d’allez voir le le discord !
Appris via la vidéo de AngA_TV sur sa vidéo de la configuration du panneau
NVIDIA !
Optimisation Windows 10 :
Gestion des périphériques #5/..
!!! Avant toutes manipulations merci de faire ces quelques
manipulations afin de “prévenir” !!!
1) Créer un point de restauration système :
Cliquez sur le menu démarrer et écrivez « créer un point de restauration »
(copier/coller le texte).
2) Appuyez sur Enter ou cliquez sur le résultat.
Sélectionnez le disque où il est écrit système, ensuite cliquez sur « créer ».
3) Nommez votre sauvegarde avec une date afin de vous y retrouver si vous possédez
plusieurs sauvegardes et cliquez sur « Créer ».
4) La sauvegarde est terminée, vous pouvez cliquer sur « fermer » et fermer toutes les
fenêtres.
Cette manipulation sera à refaire à chaque fois que l’on mettra à
jour notre driver / réinstallation du driver.
Continuité : juste en dessous
Optimisation des périphériques:
Nous commençons par aller sur le logo Windows
• Faites un clique droit
• Allez sur “gestionnaire de périphérique”
• Et allez dans chaque catégorie.
Et sur chaque périphérique !
• Faites “Entrer”, puis allez dans “Gestion de l’alimentation” si possible.
• En général cette option est dans :
- “Clavier”
- “Contrôleur audio, vidéo et jeu”
- “Contrôleurs de bus USB”
- “Entrées et sorties audio”
- “Périphériques d’interface utilisateur”
- “Souris et autres périphériques de pointage”.
Pour plus d’info merci d’allez voir le le discord !
Parfait tu viens d’optimiser l’alimentation de tes périphériques pour PC ;)
Optimisation Windows 10 :
L’explorateur de fichier #6/..
!!! Avant toutes manipulations merci de faire ces quelques
manipulations afin de “prévenir” !!!
1) Créer un point de restauration système :
Cliquez sur le menu démarrer et écrivez « créer un point de restauration »
(copier/coller le texte).
2) Appuyez sur Enter ou cliquez sur le résultat.
Sélectionnez le disque où il est écrit système, ensuite cliquez sur « créer ».
3) Nommez votre sauvegarde avec une date afin de vous y retrouver si vous possédez
plusieurs sauvegardes et cliquez sur « Créer ».
4) La sauvegarde est terminée, vous pouvez cliquer sur « fermer » et fermer toutes les
fenêtres.
Continuité : juste en dessous
Ce n’est pas réellement une optimisation mais plutôt une aide / de la confortabilité.
Allez dans votre explorateur de fichier.
• Sur “Fichier” en haut à gauche.
• Allez dans “Modifier les options des dossiers et des recherches”.
• Dans “Ouvrir l’explorateur de fichier dans :” “Ce PC”
• Ouvrir “les éléments par un double - clic (sélection par simple clic)”
• Faite “Appliquer” puis “Ok”
Parfait tu viens “d'optimiser” l'explorateur de fichier de ton PC ;)
Appris via la vidéo de AngA_TV !
Pour plus d’info merci d’allez voir le le discord !
Optimisation Latence Windows 10 :
BIOS #7/..
!!! Avant toutes manipulations merci de faire ces quelques
manipulations afin de “prévenir” !!!
Merci de regarder la vidéo plusieurs fois même si ce que l’on va faire à aucun
risque sur la carte-mère ! Juste on désactive quelques démarrages !
Cette manipulation sera à refaire à chaque fois que l’on mettra à
jour notre driver / réinstallation du driver.
Continuité : juste en dessous
“Optimisation” de la latence du BIOS !
• Commencez par redémarrer votre PC !
• Ensuite appuyez sur votre touche “Suppr” / “Delete” / “F10” / “F1” ou autre
afin de rentrer dans le bios.
• Pour ceux qui ont une carte-mère “Custom” style “MSI / Asus / ASROCK /
Gigabyte / AORUS”, merci d’appuyer sur “F7” pour rentrer dans le mode
“avancé”.
• Faites entrer "settings" pour “MSI” puis “boot”, et désactiver tous les
“boots option”. Pour le premier “boots option” mettez “UEFI Hard
Drive:Windows Boot Manager(P1 : ........)”
• Faites “F10” puis “Entrer” sur “Oui”.
Nous faisons ça afin que Windows démarre plus rapidement, si nous laissions
les autres “boot options” il va donc les charger, et ça mettra plus de temps !
Bravo, tu as fait en sorte que ton PC démarre plus rapidement (même si c’est
minim) !
Pour plus d’info merci d’allez voir le le discord !
Appris via la vidéo de AngA_TV sur sa vidéo de formatage !
