0	La commande pour switch en superuser "betty" est : su "utilisateur"

1 La commande pour afficher le nom de l'utilisateur actuel est : whoami

2 La commande pour afficher le groupe auquel appartient l'utilisateur actuel est : groups

3 La commande pour changer le propriétaire d'un fichier est : chown "nom du nouveau propriétaire" "nom du fichier"

4 La commande pour créer un fichier vide est : touch "nom du fichier"

5 La commande pour donner le droit d'execution d'un fichier au propriétaire est : chmod u+x "nom du fichier"

6 La commande pour donner le droit d'execution au propriétaire et au groupe propriétaire ainsi que le droit de lecture aux autres utilisateurs du fichier est : chmod ug+x,o+r "nom du fichier"

7 La commande pour donner le droit d'execution au propriétaire, au groupe propriétaire et aux autres utilisateurs du fichier est : chmod a+x "nom du fichier"

8 La commande pour donner les droits aux groupes tel que owner = no permission at all, group= no permission at all, other user= all the permissions est : chmod 007 "nom du fichier"

9 La commande pour donner les droits de l'exemple "-rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello" est : chmod 753 "nom du fichier"

10 La commande pour assigner les même droits qu'un autre fichier est : chmod --reference "nom du fichier référence" " nom du fichier"

11 La commande donner les mêmes droits aux sous répertoires du répertoire actuel est : chmod a+x */

12 La commande pour créer un répertoire avec par exemple les droits 751 est : mkdir -m 751 "nom du répertoire"

13 La commande pour changer le group propriétaire d'un fichier est : chgrp "nom du groupe" "nom du fichier"

14 La commande pour changer le proriétaire ainsi que le groupe propriétaire des tous les fichiers du répertoire actuel est : chown "nom du propriétaire":"nom du groupe" ./*

15 La commande pour changer le propriétaire et le groupe propriétaire d'un lien symbolique est : chown -h "nom du propriétaire":"nom du groupe" _"nom du lien"

16 La commande pour changer le propriétaire à condition qu'il appartient à un utilisateur précis est : chown --from="nom de l'utilisateur précis" "nom du propriétaire" "nom du fichier"
