**24 octobre 2025**<br>
**JOU4500 - Journalisme numérique II**<br>
**Félix Pilon, Rose Grzela et Junior Cédric Assue**<br>
**Présenté à Jean-Sébastien Marier**<br>

# Analyse exploratoire de données (AED) et proposition

## 1. Introduction

Nous allons analyser des données sur le plus haut certificat, diplôme ou grade obtenu par la population âgée de 15 ans et plus dans les ménages privés d'Ottawa. Ces données proviennent d'un jeu de données de la Ville d'Ottawa mis à jour pour la dernière fois le 14 août 2024. Il se base sur le questionnaire recensement canadien détaillé de 2021 réalisé par Statistique Canada. Celui-ci a été envoyé à 25 % des ménages du Canada. Ce qui sera intéressant avec ces données sera de constater quels quartiers ou communautés d'Ottawa contiennent les citoyens les plus ou moins éduqués.

Le jeu de données original de la Ville d'Ottawa peut être retrouvé sur [ce lien](https://ouverte.ottawa.ca/datasets/ottawa::questionnaire-d%C3%A9taill%C3%A9-du-recensement-de-2021-donn%C3%A9es-par-quartier/about).

La version en CSV, prête à petre importée dans Google Feuilles de calcul, se trouve [ici](https://raw.githubusercontent.com/jsmarier/files-for-course-assignments/refs/heads/main/Questionnaire_d%C3%A9taill%C3%A9_du_recensement_de_2021_Donn%C3%A9es_par_quartier.csv).

Dans ce travail, nous allons d'abord faire des observations générales sur les données. Ensuite, nous allons aller plus loin en réalisant un analyse VIMA qui nous permettra d'évaluer la qualité, l’exactitude et la fiabilité. Nous allons par après les nettoyer pour garantir leur cohérence et aussi exécuter une analyse exploratoire des données (AED). Avant de conclure notre travail, nous allons proposer un récit potentiel en lien avec notre jeu de données. 

## 2. Obtenir les données

D'abord, nous avons importé les données dans l'outil Google Feuilles de calcul en téléchargeant le fichier en format CSV depuis Brightspace. Pour y arriver, il faut faire un clic droit dans la page web et cliquer sur *Enregistrer sous*. Ensuite, dans Google Feuilles de calcul, il faut aller dans le menu *Fichier* et cliquer sur *Importer*.

Voici ce que ça donne et le [lien](https://docs.google.com/spreadsheets/d/1n6u9YcId6_9M40IpYNTZEE7qXEqNcJYxlNoqJJsuAGE/edit?usp=sharing) pour consulter le jeu de données : 

![](jeu-donnees-initial.png)<br>


On constate qu'il y a beaucoup d'informations : 16 lignes et 26 colonnes contenant des données. Heureusement, elles semblent être assez propres. Il ne semble pas y avoir de fautes d'ortographe dans les colonnes, les chiffres sont bien placés dans les différentes cases et rien ne semble sortir du lot.

On voit toutefois que certaines variables dans les lignes (comme les lignes 7, 9 ou 14) sont placées en retrait. En fait, il ne s'agit pas d'une erreur. C'est parce que cette variable est une sous-catégorie plus précise de la variable qui se trouve juste au-dessus. Il n'y a donc rien à nettoyer à cet endroit.

Portons une attention particulière à certaines colonnes.

La colonne A appelée *Caractéristiques* contient tous les noms des plus hauts types de diplômes obtenus par les résidents des différents quartiers de la Ville d'Ottawa. Plus on descend dans la liste, plus le diplôme est important.

La colonne B appelée *Ville d'Ottawa* contient le nombre de résidents dans tout le territoire de la ville qui ont complété un diplôme. Donc, vis-à-vis la case B2, on connaît le nombre de citoyens d'Ottawa qui ont répondu au questionnaire qui n'ont aucun diplôme.

La colonne C appelée *Orléans Est-Cumberland - Quartier 1* part du même principe que la colonne B mais seulement pour les résidents du quartier 1. Les autres colonnes à sa droite contiennent des données spécifiques pour les différents quartier de la Ville d'Ottawa.

## 3. Comprendre les données

### 3.1. Analyse VIMA

Utilisez trois croisillons (`###`) pour créer un intertitre de niveau 3 comme celui-ci. Je vous prie de suivre ce modèle en ce qui a trait aux intertitres de niveaux 1 et 2. Toutefois, je vous laisse le loisir d'utiliser les intertitres de niveau 3 comme bon vous semble.

Insérez votre texte ici.

Appuyez vos affirmations en citant les sources appropriées. Veuillez suivre les [normes APA en matière d'attribution dans le corps du texte](https://apastyle.apa.org/style-grammar-guidelines/citations).

**Par exemple :**

Comme l'affirme Cairo (2016), une visualisation de données doit être véridique...

### 3.2. Nettoyage des données

Insérez votre texte ici.

### 3.3. Analyse exploratoire des données (AED)

Insérez votre texte ici.

**Cette section doit inclure une capture d'écran de votre tableau croisé dynamique, comme ceci :**

![](pivot-table-screen-capture.png)<br>
*Figure 2 : Ce tableau croisé dynamique montre...*

**Cette section doit aussi inclure une capture d'écran de votre graphique exploratoire, comme ceci :**

![](chart-screen-capture.png)<br>
*Figure 3 : Ce graphique exploratoire montre...*

## 4. Récit potentiel

Insérez votre texte ici.

## 5. Conclusion

Insérez votre texte ici.

## 6. Références

Veuillez inclure une liste de vos références ici. Assurez-vous de suivre les [normes APA pour les références](https://apastyle.apa.org/style-grammar-guidelines/references). Les retraits négatifs (*hanging paragraphs*) ne sont pas nécessaires. Le [guide sur l'adaptation APA](https://arts.uottawa.ca/lettres/sites/arts.uottawa.ca.lettres/files/cartu-outils-de-redaction-adaptation-apa.pdf) de l'Université d'Ottawa pourrait également vous être utile.

**Voici un exemple :**

Bounegru, L., & Gray, J. (Eds.). (2021). *The Data Journalism Handbook 2: Towards A Critical Data Practice*. Amsterdam University Press. [https://ocul-crl.primo.exlibrisgroup.com/permalink/01OCUL_CRL/hgdufh/alma991022890087305153](https://ocul-crl.primo.exlibrisgroup.com/permalink/01OCUL_CRL/hgdufh/alma991022890087305153)
