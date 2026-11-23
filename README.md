# 724-Events – Campagne de tests fonctionnels

Projet réalisé dans le cadre de la formation **Testeur logiciel** d'OpenClassrooms.

## Contexte

724-Events est le site vitrine d'une agence événementielle, développé en React. Avant sa mise en production, j'ai mené une campagne de tests fonctionnels pour vérifier qu'il respectait le cahier des charges.

**Période des tests :** du 18 octobre au 14 novembre 2025

## Objectifs

- Vérifier que les fonctionnalités sont conformes aux exigences
- Identifier, documenter et prioriser les anomalies
- Optimiser la couverture de test en regroupant les exigences liées
- Décider si le site peut partir en production (GO / NO GO)

## Livrables

| Fichier | Contenu |
|---|---|
| `Chung_Cédric_1_cahier_de_recette_102025.pdf` | Cahier de recette : cas de test, résultats attendus et obtenus |
| `Chung_cédric_2_export_jira_102025.csv` | Export Jira des 16 anomalies remontées |
| `Chung_Cédric_3_biland_de_campagne_de_tests_102025.pdf` | Bilan de campagne : résultats par fonctionnalité et décision finale |

## Résultats

- **16 anomalies** remontées dans Jira, dont 4 de priorité maximale : formulaire d'inscription en erreur, cartes Google Maps ne correspondant pas aux adresses, absence de message de succès sur le formulaire de contact, envoi du formulaire « World Eco Forum » non fonctionnel.
- **Décision : NO GO.** Une seule fonctionnalité respectait les critères du cahier de recette, et plusieurs bugs critiques bloquaient les parcours principaux (inscription, contact, navigation).

## Compétences mises en œuvre

- Rédaction et exécution d'un cahier de recette
- Rédaction de rapports d'anomalies reproductibles et priorisation
- Suivi des anomalies dans Jira
- Rédaction d'un bilan de campagne et recommandation GO / NO GO
