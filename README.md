
![Alt text](lafleche_logo_small-1.png)


# ANALYSER LES INDICATEURS DE L'EGALITE FEMMES-HOMMES AVEC KNIME

Projet realisé en août 2023 dans le cadre de ma formation Data Analyst avec OpenClassrooms.

## Objectif du projet
Chaque année avant le 1er mars, les entreprises d’au moins 50 salariés doivent calculer et publier sur leur site internet leur index de l’égalité femmes-hommes. Laflèche & Associés est un cabinet de consultants spécialisé dans la transformation digitale des entreprises. Le cabinet compte déjà plus de 150 salariés et est en plein développement. Dans ce contexte économique, le recrutement de consultants expérimentés est un véritable enjeu stratégique et le cabinet se doit d'afficher une politique volontariste pour développer l’égalité femmes-hommes, améliorer sa marque employeur et attirer plus facilement des talents.

L'objectif du projet est double:
- automatiser la création d’un rapport diagnostic sur l’égalité professionnelle femmes-hommes à partir des données brutes produites par les RH et en utilisant l'outil no-code KNIME Analytics Platform ; et
- produire un fichier de données anonymisé au format .csv en conformité avec le RGPD, en vue d'analyses ultérieures, sur un outil de dashboarding par exemple.

Outre les données RH, différentes sources d'information ont été utilisées pour ce projet:
- Le site du Ministère du Travail: https://travail-emploi.gouv.fr/IMG/pdf/guide_egalite_tpe_pme_2021.pdf
- L'outil de diagnostic égalité: https://s3-eu-west-1.amazonaws.com/static.oc-static.com/prod/courses/files/parcours-data-analyst/Pre%CC%81sentation+outil+Diagnostic+E%CC%81galite%CC%81.pdf
- Le MOOC de la CNIL sur le RGPD: https://cnil.fr/fr/comprendre-le-rgpd/le-mooc-de-la-cnil-est-de-retour-dans-une-nouvelle-version-enrichie
 

## Liste des dossiers & fichiers

* **dossiers :**
    - **donnees-brutes :** données RH (format .xlsx)

* **fichiers :**
	- **knime_workflow.knwf :** workflow produit avec la platforme KNIME Analytics (indicateurs statistiques et graphiques)
  - **clean_data.csv :** fichier de données anonymisées produit selon les préconisations du RGPD
  - **knime_workflow.png:** vue d'ensemble du workflow
  - **metanode_traitement_donnees.png:** vue éclatée du métanode dans le workflow
  - **presentation.pdf:** diapositives de présentation du projet
  - **presentation_notes.pdf:** commentaires & analyses accompagnant les diapositives de presentation du projet


## Compétences développées
- Collecter des données en respectant le RGPD
- Préparer des données pour l'analyse en respectant les normes internes à l’entreprise
- Transférer des données .csv vers une zone de préparation



## Langages & software

* KNIME Analytics Platform
* Excel / PowerQuery








