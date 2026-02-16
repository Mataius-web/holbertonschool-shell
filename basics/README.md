0	La commande pour afficher le chemin absolue est : pwd

1	La commande pour afficher le contenu du repo actuel est : ls

2	La commande pour changer le repertoire actuel à la racine est : cd~

3	La commande pour afficher le contenu du repertoire actuel en format long est : ls -l

4	La commande pour afficher le contenu du repertoire actuel en incluant les fichier masqués en format long est : ls -la

5	La commande pour afficher le contenu du repertoire actuel avec ID en numérique, en format long, incluant les fichiers masqués est : ls -lna

6	La commande pour créer un repertoire est : mkdir "chemin absolue + nom du repertoire à créer"

7	La commande pour déplacer un fichier d'un endroit à un autre est : mv "fichier" "chemin absolue de l'emplacement final"

8	La commande pour supprimer un fichier est : rm "chemin absolue -> nom du fichier cible"

9	La commande pour supprimer un repertoire est : rmdir "chemin absolue -> repertoire cible"

10	La commande pour changer de repertoire actuel au précédent est : cd -

11	La commande pour afficher les fichier qui commence par un caractère, incluant les masqués dans le repertoire actuel, dans le parent du repertoire actuel, et le repertoire "exemple" en format long est : ls -la . .. /exemple

12	La commande pour afficher le type d'un fichier contenu dans un répertoire est : file "chemin absolue -> fichier cible"

13	La commande pour créer un lien symbolic est : ln -s "chemin absolu du point de départ du lien" "nom du lien"

14 	La commande copier tous les fichier d'un certain type du repertoire actuel au repertoire parent, uniquement les fichier qui n'existent pas dans le repertoire parent ou qui sont plus récent est : cp -u *."type du fichier" ..

15	La commande pour déplacer tous les fichier qui commencent par un majuscule d'un répertoire est : mv [A-Z]* "chemin absolue du repertoire cible"

16	La commande pour supprimer tous les fichier qui ont un nom qui se termine par ~ est : rm -- *~

17	La commande pour créer des répertoire imbriqués est : mkdir -p "/repertoire1/2/3 etc"