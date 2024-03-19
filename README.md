# NLP-Classique 
### NAVIGATE IN THIS REPOSITORY


| Numero TP |  Titre  | Voir |
|:-----|:--------:|------:|
| TP1   | NLP Preprocessing | link1 |
| TP2   | NULL | NULL |
| TP3   | NULL | NULL |



## TP2 Statement:
```
Essayez d'entraîner le modèle sur ce texte afin de :

1- Extraire la représentation vectorielle d'un mot 
2- Calculer la similarité entre deux mots 
3- Extraire les mots contextuels (les plus similaires) pour un mot central donné

```
The text to use : 

```
**Morocco and Marrakech: A Tapestry of Tradition and Modernity** Morocco, located at the crossroads of Europe and Africa, is a country drenched in history, mystery, and cultural richness. A testament to the ancient civilizations that once flourished here, this North African kingdom boasts a unique blend of Arab, Berber, and European influences. At the heart of Morocco's rich tapestry lies Marrakech, one of its four imperial cities and a vibrant epicenter of tradition and modernity. **Geographical Significance** Morocco is bordered by the Atlantic Ocean to the west, the Mediterranean Sea to the north, Algeria to the east and southeast, and the vast Sahara desert to the south. Its strategic location has historically made it a sought-after territory and a melting pot of cultures, religions, and trade routes. **Marrakech: The Red City** Marrakech, often referred to as "The Red City" due to its distinctive red-hued buildings, stands against the backdrop of the snow-capped Atlas Mountains. Established in the 11th century, it has remained a crucial political, economic, and cultural center of Morocco. **Journey through the Medina** Marrakech's old town, the Medina, is a UNESCO World Heritage site and a labyrinthine maze of narrow alleys, bustling souks, and historical landmarks. The Djemaa el-Fna Square lies at the heart of the Medina and comes alive every evening with storytellers, musicians, snake charmers, and food stalls offering tantalizing Moroccan delicacies. **Palaces and Gardens** The city is also home to grand palaces like the Bahia Palace, showcasing intricate Islamic architecture, and the Saadian Tombs, remnants of the Saadian dynasty. The Majorelle Garden, restored by the fashion designer Yves Saint Laurent, is a tranquil oasis of cacti, palm trees, and cobalt blue accents. **Modern Marrakech** While tradition and history permeate Marrakech, the city is not averse to the modern world. Gueliz, the new town, is brimming with contemporary art galleries, stylish cafes, and chic boutiques, offering a stark contrast to the ancient Medina. **Moroccan Cuisine** No journey through Morocco and Marrakech would be complete without indulging in the local cuisine. Tagines, couscous, and pastilla are just a few of the many dishes that combine a plethora of flavors and spices like saffron, cumin, and mint. Paired with Moroccan mint tea, the culinary experience is truly unparalleled. **In Conclusion** Morocco, with Marrakech at its heart, offers travelers an unparalleled journey through time. The convergence of history, culture, architecture, and gastronomy makes it an enthralling destination for those seeking both adventure and reflection. As the Moroccan proverb goes, "He who does not travel does not know the value of men." In the case of Morocco and Marrakech, it's not just the value of men, but also the value of time, tradition, and tales that have spanned centuries.

```


## TP3 Statement:

```
Dataset : https://www.kaggle.com/datasets/nltkdata/movie-review

Columns pour la classification : Text (features) et Tag (label)
Pre-processing des données textuelles :
Vous devez d&#39;abord effectuer le pre-processing des données textuelles en supprimant les stop words,
en convertissant tout le texte en minuscules, et en supprimant la ponctuation. Vous pouvez utiliser
des outils tels que NLTK ou spaCy pour cela.

Entraînement du modèle Word2Vec :
Une fois les données prétraitées, vous pouvez entraîner un modèle Word2Vec en utilisant Gensim. Le
modèle détermine comment représenter les mots sous forme de vecteurs en fonction de leur
utilisation dans le dataset.

Vectorisation des reviews de movies :
Après avoir entraîné le modèle Word2Vec, vous pouvez représenter chaque review d’un film sous
forme de vecteur en prenant la moyenne de Word2Vec embeddings des mots. Cela crée une
représentation vectorielle de chaque review qui montre comment les mots s&#39;articulent et ce qu&#39;ils
signifient.

Division des données :
Divisez le dataset en ensembles d&#39;entraînement (training sets) et de test (testing sets).

Construction d&#39;un classificateur :
Entraînez un modèle de machine learning tel que la logistic regression, les random forests, ou les
support vector machines en utilisant les représentations vectorielles des reviews comme input
features et les étiquettes de sentiment comme variable cible (label).

Évaluation du modèle :
Une fois le modèle entraîné, utilisez des métriques comme accuracy, precision, recall, et F1-score
pour évaluer ses performances sur l&#39;ensemble de test.

```


### NLP PROJECTS : 

Sentimatica: Emotion Extraction Master
Le projet a pour objectif de créer une solution capable de déterminer les émotions exprimées dans les données textuelles, avec des applications potentielles telles que l'analyse de la satisfaction client, la détection de sentiments sur les réseaux sociaux, etc.

Outils : Traitement du langage naturel (NLP), Python, bibliothèques NLP telles que NLTK et spaCy.
