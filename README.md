<h1> Echantillonnage d'itemsets à forte utilité moyenne sous contraintes de taille </h1>


<b>Résumé.</b> Les algorithmes d’extraction d'High-Utility Itemset (HUI) sont des méthodes permettant de découvrir des connaissances dans une base de données où les items sont pondérés. Leur importance a été largement démontrée dans de nombreuses applications réelles. Les algorithmes traditionnels renvoient l’ensemble de tous les motifs ayant une utilité supérieure à un seuil d’utilité minimale qui est très difficile à fixer, tandis que les algorithmes dits top-k ont tendance à manquer de diversité sur les motifs produits. Dans cet article, nous proposons un algorithme nommé \uisampling pour échantillonner des itemsets ou chaque itemset est tiré avec une probabilité proportionnelle à son utilité dans la base de données et sous contraintes de taille pour éviter le problème de la longue traîne (itemset rare, très long avec des items ayant des poids très faibles). L'originalité de notre méthode découle du fait qu'elle combine des contraintes de taille avec des utilités qualitatives et quantitatives. Les expérimentations montrent que \uisampling tire en quelques secondes des milliers de motifs à forte utilité moyenne sur différents jeux de données.
	



<b>Abstract.</b> High-Utility Itemset mining algorithms are methods for discovering knowledge in a database where items are weighted. Their usefulness has been widely demonstrated in many real world applications. The traditional algorithms return the set of all the patterns having utility above a minimum utility threshold which is very difficult to fix, while the top-k algorithms tend to lack of diversity in the produced patterns. We propose an algorithm to sample itemsets where each itemset is drawn with a probability proportional to its average utility in the database and under length constraints to avoid the long tail problem (rare itemset, very long with items having very low weights). The originality of our method stems from the fact that it combines length constraints with qualitative and quantitative utilities. 



<!--
### 
**HISampler/hisampler** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
