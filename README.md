# HACS-Home-Assistant
Installation HACS Home Assistant

Comment installer HACS sur Home Assistant et étendre les possibilités de votre domotique

home-assistant-guide-installation-hacs
guide mis à jour le 2 février 2026

HACS pour Home Assistant Community Store, c’est tout simplement un indispensable pour la customisation de home assistant. Intégrations, composants du Frontend ou encore automatisations C’est dans ce market alternatif que la communauté des très nombreux utilisateurs de la solution domotique partagent leurs développements et intégrations custom.

Les prérequis à HACS
Avant de se lancer dans l’installation de HACS à proprement parlé, il faut déjà s’assurer de disposer de quelques prérequis. Rien de compliqué, mais il convient de préparer quelques éléments afin de pouvoir dérouler la procédure sans accros.

Le compte GitHub
Pour installer HACS et profiter de très nombreuses intégrations disponibles, il faut dans un premier temps créer un compte sur GitHub. Si vous en avez un, pas besoin de créer un nouveau. Un compte Gihub est gratuit, et va vous permettre de récupérer une clé api pour donner accès à HA sur les dépôts de HACS.

La création d’un compte sur Github est relativement très simple, je ne détaille pas cette partie. Ce compte sera nécessaire un peu plus loin dans cette procédure pour l’installation de HACS.

L’add-on Terminal et SSH:
Il faut également un autre prérequis pour effectuer cette installation. Il s’agit d’installer l’add-On officiel Terminal et SSH que vous trouverez dans Parametres/Modules complementaires/Boutique des modules complementaires.


1. Si vous ne trouvez pas le module, sous cet écran, il faut activer le mode avancé sous votre profil utilisateur.

2. Installez alors le module Addon et SSH puis demarrez-le.

3. Ouvrez le terminal avec l’option “Ouvrir l’interface utilisateur web” puis copier/coller la commande suivante pour lancer l’installation :

      wget -O - https://get.hacs.xyz | bash -

      *attention, parfois le copier coller peut casser la mise en forme ou oublier des caractères. Si vous recevez un messager d’erreur à l’execution de cette commande, procedez à un double check, puis       recommencez.

4. vous voyez alors l’installation defiler à l’écran.

5. terminer l’installation avec un redemarrage de Home Assistant


L’installation de HACS sur Home Assistant

  
1. Maintenant que nous avons chargé le depot de HACS sur le systeme domotique Home Assistant, passons à son activation. Rendez-vous dans Parametres / Appareils et services.


2. En bas à droite de la page, vous avez un bouton Ajouter l’intégration, cliquez dessus.


3. Recherchez HACS puis activez-le.


4. Pendant l’activation, il vous sera demandé de vous identifier sur GitHub pour lier votre accès API avec votre compte créé au tout début. Cliquez simplement sur le lien et copier le code d’activation


5. Enfin donnez l’autorisation à Home assistant à se lier à votre compte GitHub.


6. C’ est terminé pour la configuration


Il faut parfois attendre plusieurs minutes avant de voir le catalogue HACS complet. Si vous ne voyez toujours pas l’onglet HACS dans le menu Home Assistant, je vous conseille de vider le cache du navigateur, le fermer et le relancer. Après quelques minutes vous aurez enfin HACS dans le menu comme ci-dessous.


A présent, vous avez accès à une grande liste d’intégrations custom Home Assistant. Aussi bien des nouvelles cartes pour votre design que des thèmes d’affichage.

Il ne vous reste plus qu’a recherche l’extension que vous desirez installer via le moteur de recherche et proceder à son installation.

Sources: https://www.domo-blog.fr/comment-installer-hacs-home-assistant-store-integrations-custom-ha/

