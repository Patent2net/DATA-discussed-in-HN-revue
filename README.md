# Données sources discutées (en partie) dans article de revue [https://journals.openedition.org/revuehn/](Humanités Numériques) vol 5. 
 Données sources pour les traitements par les logiciels IRAMuTeQ, Gephi, Freeplane et Carrot2 produites par le logiciel [https://github.com/Patent2net/P2N-Docker](Patent2Net (P2N)) à partir de la base mondiale de données brevets de l'office européen des brevets via l'API [https://worldwide.espacenet.com/](espacenet). Les données ont été capturées en décembre 2021. 
 
 La correspondance est la suivante :
 - EN_Abstract_HN2.txt : [http://iramuteq.org/](fichier IRAMuTeQ)
 - EN_Abstract_HN2.xml : [https://search.carrot2.org/#/workbench](fichier Carrot2)
 - HN2FP.mm : [https://www.freeplane.org/wiki/index.php/Home](fichier Freeplane)
 - HN2*.gexf : [https://gephi.org/users/download/](fichiers Gephi)

Pour ces derniers la convention de nommage est que le caractère générique détermine le type de noeud(s) pour les relations identifiées dans le corpus de brevets. Ainsi *HN2_Citations.gexf* désigne le graphe des citations. *HN2_Inventors.gexf* le graphe des collaborations entre inventeurs, etc.
