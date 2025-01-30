# 🧬 Annotation d’un Fragment Génomique  

📌 **Résumé du projet**  
Ce projet vise à annoter un fragment génomique bactérien (*Lactococcus lactis*) en utilisant divers outils bioinformatiques pour la prédiction de gènes et l'analyse des séquences régulatrices.

🔬 **Technologies et Outils Utilisés**  
- **Prédiction des gènes** : GeneMark, GeneMark.hmm  
- **Identification des motifs** : scan_for_matches  
- **Annotation fonctionnelle** : InterProScan, EMBOSS  
- **Programmation** : Python (développement de parsers), Shell/Linux  
- **Formatage des résultats** : Transformation des sorties en format GFF  

## 📊 **Méthodologie**

1️⃣ **Prédiction des gènes** avec **GeneMark** et **GeneMark.hmm**, en identifiant les cadres de lecture ouverts (ORFs).  

2️⃣ **Détection des motifs régulateurs** tels que RBS, promoteurs et terminateurs avec **scan_for_matches**.  

3️⃣ **Annotation fonctionnelle** des gènes prédits en identifiant leurs domaines et localisation cellulaire avec **InterProScan et EMBOSS**.  

4️⃣ **Transformation des données** : Développement de **parsers en Python** pour convertir les sorties des outils en **format GFF**, facilitant la visualisation et l'analyse.  

5️⃣ **Rédaction d'un rapport détaillé**, incluant la méthodologie, les résultats et une analyse critique des approches utilisées.  

## 📂 **Fichiers et ressources**
- 📜 [Script de parsing des annotations]
- 📊 [Exemple de sortie GFF]
- 📑 [Rapport détaillé du projet] 
- 🔗 [Lien vers le dépôt complet]

## 🎯 **Conclusion et Perspectives**
Ce projet a permis de mettre en place un pipeline complet d’annotation génomique et d’explorer différentes approches pour améliorer la qualité des annotations. Les méthodes développées pourraient être adaptées pour l’étude d’autres fragments génomiques ou intégrées dans des pipelines bioinformatiques plus complexes.
