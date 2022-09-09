MOREL Loïc

#<p style="text-align: center;"> TP1 - Linux Ubuntu</p>
Installation d’Ubuntu Server et prise en main du shell - CPE Lyon - 4ETI, 3IRC & 3ICS - Année 2022/2023 Administration Système

##Exercice 2
###Manuel

![](./image/Aspose.Words.e3d5cc18-ac28-4f0b-b9c8-be250add7ed4.001.png)

1) La commande which permet de localiser le binaire d'une commande
1) Il faut écrire « /paterne » pour chercher un text
1) Il faut écrire « q » pour quitter
1) La première page de la section 6 concerne les jeux, économiseurs d’écran, gadgets...

![](./image/Aspose.Words.e3d5cc18-ac28-4f0b-b9c8-be250add7ed4.002.png)

###Navigation








![](./image/Aspose.Words.e3d5cc18-ac28-4f0b-b9c8-be250add7ed4.003.png)

1) ![](./image/Aspose.Words.e3d5cc18-ac28-4f0b-b9c8-be250add7ed4.004.png)
1) ![](./image/Aspose.Words.e3d5cc18-ac28-4f0b-b9c8-be250add7ed4.005.png)
1) ![](./image/Aspose.Words.e3d5cc18-ac28-4f0b-b9c8-be250add7ed4.006.png)
1) ![](./image/Aspose.Words.e3d5cc18-ac28-4f0b-b9c8-be250add7ed4.007.png)
1) Je n’ai pas la permission d’accéder au dossier

![](./image/Aspose.Words.e3d5cc18-ac28-4f0b-b9c8-be250add7ed4.008.png)

1) Ça permet d’accédé au dossier en effet sudo permet de lancer la commande avec de privilège plus élever

![](./image/Aspose.Words.e3d5cc18-ac28-4f0b-b9c8-be250add7ed4.009.png)

8) On ne peut pas supprimer le dossier 

![](./image/Aspose.Words.e3d5cc18-ac28-4f0b-b9c8-be250add7ed4.010.png)


9) On utilise la command rm –d pour supprimer un dossier

![](./image/Aspose.Words.e3d5cc18-ac28-4f0b-b9c8-be250add7ed4.011.png)

10) On peut pas supprimer le dossier car il n’est pas vide![](./image/Aspose.Words.e3d5cc18-ac28-4f0b-b9c8-be250add7ed4.012.png)
11) Il faut utiliser la command rm -r

![](./image/Aspose.Words.e3d5cc18-ac28-4f0b-b9c8-be250add7ed4.013.png)

###Commandes importantes

![](./image/Aspose.Words.e3d5cc18-ac28-4f0b-b9c8-be250add7ed4.014.png)

1) La commande pour lire l’heure est date

![](./image/Aspose.Words.e3d5cc18-ac28-4f0b-b9c8-be250add7ed4.015.png)

La commande time permet de savoir en combien de temps la commande c’est exécuter

2) Le fichier qui commence par un « . » sont des fichier cachée

![](./image/Aspose.Words.e3d5cc18-ac28-4f0b-b9c8-be250add7ed4.016.png)

3) La commande « ls » ce situe dans /usr/bin/ls

![](./image/Aspose.Words.e3d5cc18-ac28-4f0b-b9c8-be250add7ed4.017.png)







4) Cette commande n’est pas dans le man car c’est un alias, Ajoute la possibilité de voir les permissions

![](./image/Aspose.Words.e3d5cc18-ac28-4f0b-b9c8-be250add7ed4.018.png)

5) La commande « ls /bin » permet d’afficher le contenue de « /bin »
6) La commande « ls .. » permet d’afficher le contenue du répertoire précèdent
7) La commande « pwd » donne le chemin complet du dossier courant

![](./image/Aspose.Words.e3d5cc18-ac28-4f0b-b9c8-be250add7ed4.019.png)

8) La commande « > » écrit ‘bip’ dans le fichier plop en écrasants le précèdent

![](./image/Aspose.Words.e3d5cc18-ac28-4f0b-b9c8-be250add7ed4.020.png)

9) La command « >> » ecrit ‘bip’ en fin du fichier

![](./image/Aspose.Words.e3d5cc18-ac28-4f0b-b9c8-be250add7ed4.021.png)

10) Le programme attend 10 seconde avant d’afficher ‘toto’

![](./image/Aspose.Words.e3d5cc18-ac28-4f0b-b9c8-be250add7ed4.022.png)

11) Le permet de savoir si c’est un fichier ou un dossier

![](./image/Aspose.Words.e3d5cc18-ac28-4f0b-b9c8-be250add7ed4.023.png)

12) On observe que le fichier lien\_phy est liée au fichier original

Si on supprime le ficher original cela n’a pas d’importance pour le fichier lien\_phy

![](./image/Aspose.Words.e3d5cc18-ac28-4f0b-b9c8-be250add7ed4.024.png)









13) Le deux fichier sont synchroniser si on modifier un des deux fichiers l’autre est aussi modifier, si on supprime le fichier le lien symbolique ne fonctionne plus

![](./image/Aspose.Words.e3d5cc18-ac28-4f0b-b9c8-be250add7ed4.025.png)

14) La commande est « tail –F /var/log/syslog », pour arrêter « ctl+s » pour reprendre « ctl+q »

Il faut utiliser la commande « head –Nx /var/log/syslog » permet d’afficher x première ligne du fichier

![](./image/Aspose.Words.e3d5cc18-ac28-4f0b-b9c8-be250add7ed4.026.png)

![](./image/Aspose.Words.e3d5cc18-ac28-4f0b-b9c8-be250add7ed4.027.png)

Il faut utiliser la commande « tail –Nx /var/log/syslog » permet d’afficher x dernière ligne du fichier
15) 
![](./image/Aspose.Words.e3d5cc18-ac28-4f0b-b9c8-be250add7ed4.028.png)

16) La commande « dmesg | less » permet d’afficher page par page













17) Le dossier « /etc/passwd » permet de voir les utilisateurs, leur id et leur id group et où se situe son répertoire personnel et le chemin absolu du shell

![](./image/Aspose.Words.e3d5cc18-ac28-4f0b-b9c8-be250add7ed4.029.png)





















18) On utilise la command « awk –F ‘ :’ ‘{print $1}’ /etc/passwd | sort –r » 

![](./image/Aspose.Words.e3d5cc18-ac28-4f0b-b9c8-be250add7ed4.030.png)

19) La commande « wc » permet de savoir le nombre de ligne dans un fichier![](./image/Aspose.Words.e3d5cc18-ac28-4f0b-b9c8-be250add7ed4.031.png)
20) 
![](./image/Aspose.Words.e3d5cc18-ac28-4f0b-b9c8-be250add7ed4.032.png)













21) La commande qui permet de trouvée tous les fichiers se nommant passwd présents sur la machine est « find / -name « passwd »

![](./image/Aspose.Words.e3d5cc18-ac28-4f0b-b9c8-be250add7ed4.033.png)

![](./image/Aspose.Words.e3d5cc18-ac28-4f0b-b9c8-be250add7ed4.050.png)

22) A
23) La commande locate ne returne rien

![](./image/Aspose.Words.e3d5cc18-ac28-4f0b-b9c8-be250add7ed4.034.png)A

24) Le fichier n’apparait pas

![](./image/Aspose.Words.e3d5cc18-ac28-4f0b-b9c8-be250add7ed4.035.png)

