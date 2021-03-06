[Retour à l'accueil](README.md)

# M2203 | TD3 (+TP3) | Analyse DUTAF et Mise en place de la Bd


#### Objectif :
Mettre en œuvre une Solution PHP/MySQL pour répondre à un problème de gestion de base de données.

#### Exposé du sujet :
• La société Dutaf, qui vend des articles en tout genre, vous demande de créer son site Internet sur lequel ses
clients pourront consulter le catalogue complet. Cette société appartient à M. Pastot. Son catalogue est
composé de plus de 500 articles.

• II désire pouvoir faire la mise à jour de ses produits lui-même (changer un prix, ajouter un article, effacer un
article) sans avoir à faire appel à vos services. Pour cela, il vous demande de développer le site de telle manière
qu’il y ait une section qui lui sera réservée et dans laquelle il pourra, via Internet et des pages web, venir faire
ses modifications.

• Un article est identifié par un numéro dans le catalogue, une désignation, un descriptif, un prix de vente, une
quantité disponible, un numéro de fournisseur, un nom de fournisseur, un téléphone de fournisseur, une ville
de localisation du fournisseur. Remarque : un artcle du catalogue ne peut provenir que d'un seul fournisseur.

• II existe une cinquantaine de fournisseurs. Sur le même principe que les articles, M. Pastot désire pouvoir
faire ses propres changements dans la liste des fournisseurs.

• M. Pastot se sert déjà un peu d’internet mais il ne connaît aucun logiciel de mise en page web et ne compte
pas s'investir dans la création de page web. II ne connaît d'ailleurs pas plus les notons de base de données.

• II désire aussi qu’un client puisse demander uniquement la liste des articles correspondant à son budget. Pour
cela, il devra y avoir une section dans laquelle le client pourra entrer un prix maximum et par la suite consulter
uniquement les articles correspondants à sa requête.

#### Premier exercice : analyse SGBDR
1. Après avoir répertorié les données du problème, proposez le dictionnaire des données.
2. Après avoir fait l'analyse des dépendances fonctionnelles, construisez le MCD.
3. Ecrire le MLD.

#### Deuxième exercice : mise en œuvre de la base de données sous mySQL
1. En vous basant sur l'analyse, créez les tables dans PhpMyAdmin.
2. Récupérez le fichier [dutaf.xls](dutaf.xls) contenant les données nécessaires au TD pour les importer dans les
tables. (attention, n'utilisez pas l'importation automatique ! Passez par des fichiers CSV)

#### complément:
Tester les requetes suivantes:
1. Afficher la liste des articles (description, prix de vente) par ordre décroissant du prix .
2. Afficher la liste des articles de moins de 50 Euros.
3. Afficher la liste complète des artcles avec à chaque fois la provenance (le fournisseur).
4. Supprimer l’article numéro 12.
5. Augmenter tous les prix de vente de 4%.
6. Retrouver les prix d’origine.
7. Afficher la description et le prix de l’article le moins cher.
8. Afficher la description et le prix de l'article le plus cher.
9. De la même façon, afficher le prix moyen des articles.
10. Afficher le prix moyen des articles pour chacun des fournisseurs.
11. Compter les articles pour chacun des fournisseurs.

#### Troisieme exercice : analyse fonctionnelle et mise en place du site 
Analysez le cahier des charges des fonctions demandées (visu catalogue, formulaire...) et retrouver ces
fonctionnalités dans l'arborescence proposée.
Développer l'ensemble des pages en mode statique (mettre quelques exemples sur la page catalogue) 
analyser l'ensemble des fonctionnalités nécessaires et leur structuration au sein du site.
![GitHub Logo](/plan.png)

#### pour chacune des pages, citer la requete SQL nécessaire à son fonctionnement:
catalogue.php :

budget_art.php :

gest_art.php :

form_new_art.php :

valide_new_art.php :

valide_sup_art.php :

form_modif_art.php :

valide_modif_art.php :

#### creation de l'infrastructure
développer l'ensemble des pages en mode statique (mettre quelques exemples sur la page catalogue)

#### (ancien document)
lien: http://195.83.128.55/~fmeuzeret/vrac/docs/m2203~tp1dutaf.pdf
