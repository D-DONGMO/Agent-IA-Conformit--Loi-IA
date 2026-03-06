# Agent IA : Monitoring de Conformite (Loi Europeenne sur l'IA)

## Presentation
Ce projet automatise l'identification des entreprises dont les activites presentent un profil de risque eleve au regard de la reglementation europeenne sur l'IA. Il assure une veille proactive via une chaine d'automatisation orchestree par n8n.

## Architecture du Workflow
![Architecture](architecture.png)

## Fonctionnalites
- Orchestration : Automatisation via n8n.
- Analyse : Utilisation de modeles de langage (LLM) pour l'evaluation des risques.
- Conformite : Alignement sur les exigences de la Loi europeenne sur l'IA.

## Etat du Projet
- Version actuelle : Proof of Concept (PoC) pour l'analyse d'une cible unique.
- Roadmap : En phase d'integration du traitement de masse (Batch Processing) pour scanner plusieurs centaines d'entreprises simultanement.

## Installation
1. Telechargez le fichier workflow_conformite_ia.json.
2. Importez-le dans votre instance n8n.
