# remote
# Explication de la commande Remote 

la commande git remote permet a l'utilisateur  de creer , voir ou effacer des connexions a un depot distant.
Sans arguments la commande permet de voir la liste des connexions. <br>
    Exemple : git remote <br>
            >>>origin <br>

Toujours sans arguments mais avec l'option -v , la commande git remote permet de voir 
la liste des connexions aux depots ainsi que leur URL.<br>
    Exemple : git remote -v <br>
            >>>origin  https://github.com/FifthYonko/remote.git (push)<br>

Cette commande possede plusieurs arguments de commande comme par exemple : add, rename, remove.
La commande git remote add + nom + URL permet de  creer une nouvelle connexion a depot distant. Apres la creation de la nouvelle connexion, le nom sera le raccourci de l'URL.<br>
    Exemple :   git remote add origin https://github.com/akin-ay/remote.git<br>
            >>> Pas de reponse si tout se passe bien
             

