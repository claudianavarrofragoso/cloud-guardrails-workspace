# GC Cloud Guardrails for Google Workspace
Recommended configuration guidance for Google Workspace / Conseils de configuration recommandés pour Google Workspace

(Note: Google Workspace has only been approved for Unclassified Data)

([Français](#mesures-de-sécurité-dinformatique-en-nuage-du-gc-pour-google-workspace))

This repository details the guardrails required for Google Workspace to be deployed within the Government of Canada. The target audience of this documentation is GC employees looking to deploy Google Workspace as a productivity and collaboration solution.

## Purpose

The purpose of these guardrails is to ensure that departments and agencies are implementing a baseline set of controls for their Google Workspace environment.

**Note: these guidelines are meant to be for unclassified data within the Government of Canada.**

## Initial Guardrails

A summary of the cloud guardrails to be implemented in the initial phase are provided in the table below.

| ID. | Guardrail |
| --- | --- |
| 01 | [Manage identity and access](EN/01_Manage-Identity-Access.md) |
| 02 | [Use 2-Step Verification](EN/02_Use_2Step_Verification.md) |
| 03 | [Apply context-aware access policies](EN/03_Implement_Context_Aware_Access.md) |
| 04 | [Enable logging and monitoring](EN/04_Enable-Logging-and-Monitoring.md) |
| 05 | [Implement data protection](EN/05_Implement_Data_Protection.md) |
| 06 | [Perform service hardening](EN/06_Perform_Service_Hardening.md) |
| 07 | [Perform device hardening](EN/07_Perform_Device_Hardening.md) |
| 08 | [Validate settings](EN/08_Validate_Settings.md) |

**The detailed implementation guidance on how to deploy the guardrails is available [here](https://github.com/claudianavarrofragoso/cloud-guardrails-google-workspace-cis/blob/main/Google%20Workspace%20Guardrails%20-%20CIS%20Benchmarks.xlsx). This checklist is aligned with the CIS Benchmarks. Please note that this is a living document and subject to change as new services and features are made available.**

Google Workspace provides GC departments with actionable insights and alerts, as well as security recommendations to triage and act against threats through the [Security Center](https://workspace.google.com/products/admin/security-center/) and [Alert Center](https://workspace.google.com/products/admin/alert-center/). These tools also provide a single and comprehensive way to view your security effectiveness and security alerts.

### Considerations

Departments are expected to continue implementing the security requirements as outlined in:

* [Direction on the Secure Use of Commercial Cloud Services: Security Implementation Notice (SPIN)](https://www.canada.ca/en/government/system/digital-government/modern-emerging-technologies/direction-secure-use-commercial-cloud-services-spin.html)
* [Government of Canada Security Control Profile for Cloud-Based GC Services](https://www.canada.ca/en/government/system/digital-government/modern-emerging-technologies/cloud-services/government-canada-security-control-profile-cloud-based-it-services.html)

Departments should engage with their IT Security Risk Management teams to obtain advice and guidance on integrating security assessment and authorization activities as part of the implementation of the GC cloud environment. The [Government of Canada Cloud Security Risk Management Approach and Procedures](https://www.canada.ca/en/government/system/digital-government/modern-emerging-technologies/cloud-services/cloud-security-risk-management-approach-procedures.html) outlines activities for Departments to consider as part of the departmental risk management activities.

### How to Contribute

See [How to Contribute](Contributing.md)

### License

Unless otherwise noted, the source code of this project is covered under Crown Copyright, Government of Canada, and is distributed under the [MIT License](LICENSE).

The Canada wordmark and related graphics associated with this distribution are protected under trademark law and copyright law. No permission is granted to use them outside the parameters of the Government of Canada's corporate identity program. For more information, see [Federal identity requirements](https://www.canada.ca/en/treasury-board-secretariat/topics/government-communications/federal-identity-requirements.html).

______________________
# Mesures de sécurité d’informatique en nuage du GC pour Google Workspace

([English](#gc-cloud-guardrails-for-google-workspace))

Ce projet détaille les mesures de sécurité requises pour que Google Workspace soit déployé au sein du gouvernement du Canada. Les utilisateurs de cette documentation seront les employés du GC qui cherchent à déployer Google Workspace en tant que solution de productivité et de collaboration.

## Objectif

L'objectif de ces mesures de sécurité est de garantir que les services et les agences mettent en œuvre un ensemble de contrôles de base pour leur environnement Google Workspace.

**Remarque : ces mesures de sécurité sont destinées aux données non classifiées au sein du gouvernement du Canada.**

## Mesures de sécurité initiales

Un résumé des mesures de sécurité d’informatique en nuage à mettre en œuvre dans la phase initiale est fourni dans le tableau ci-dessous.

| ID. | Mesure de sécurité |
| --- | --- |
| 01 | [Gérer l’identité et l’accès](FR/01_Gérer-l’identité-et-l’accès.md) |
| 02 | [Utiliser l’authentification à deux facteurs ](FR/02_Utiliser-2SV.md) |
| 03 | [Appliquer des politiques d'accès contextuelles](FR/03_Appliquer-des-politiques-d’accès-contextuelles.md) |
| 04 | [Activer la journalisation et la surveillance](FR/04_Activer-la-journalisation-et-la-surveillance.md) |
| 05 | [Mettre en œuvre la protection des données](FR/05_Mettre-en-œuvre-la-protection-des-données.md) |
| 06 | [Exécuter le renforcement des services](FR/06_Exécuter-le-renforcement-des-services.md) |
| 07 | [Exécuter le renforcement des appareils](FR/07_Exécuter-le-renforcement-des-appareils.md) |
| 08 | [Valider les paramètres](FR/08_Valider-les-paramètres.md) |

**Les conseils de mise en œuvre détaillés sur la façon de déployer les mesures de sécurité sont disponibles [ici](https://github.com/claudianavarrofragoso/cloud-guardrails-google-workspace-cis/blob/main/Google%20Workspace%20Guardrails%20-%20CIS%20Benchmarks.xlsx). Cette liste de contrôle est alignée sur les Benchmarks CIS. Veuillez noter qu'il s'agit d'un document évolutif et susceptible d'être modifié à mesure que de nouveaux services et fonctionnalités sont mis à disposition.**

Google Workspace fournit aux départements du GC des informations et des alertes exploitables, ainsi que des recommandations de sécurité pour trier et agir contre les menaces via le [Centre de Sécurité](https://workspace.google.com/products/admin/security-center/) et le [Centre d'alerte](https://workspace.google.com/products/admin/alert-center/). Ces outils offrent également un moyen unique et complet d'afficher l'efficacité de votre sécurité et les alertes de sécurité.

### Considérations

Les ministères devraient continuer à mettre en œuvre les exigences de sécurité énoncées dans les documents suivants:

* [Orientation sur l’utilisation sécurisée des services commerciaux d’informatique en nuage : Avis de mise en œuvre de la Politique sur la sécurité (AMOPS)](https://www.canada.ca/fr/gouvernement/systeme/gouvernement-numerique/innovations-gouvernementales-numeriques/services-informatique-nuage/orientation-utilisation-securisee-services-commerciaux-informatique-nuage-amops.html)
* [Profil des mesures de sécurité pour les services du GC fondés sur l’informatique en nuage](https://www.canada.ca/fr/gouvernement/systeme/gouvernement-numerique/innovations-gouvernementales-numeriques/services-informatique-nuage/profil-controle-securite-services-ti-fondes-information-nuage.html)

Les ministères devraient collaborer avec leurs équipes de gestion des risques liés à la sécurité des TI pour obtenir des conseils et des orientations sur l'intégration des activités d'évaluation et d'autorisation de la sécurité dans le cadre de la mise en œuvre de l'environnement infonuagique du GC. L'[ approche et les procédures de gestion des risques liés à la sécurité de l'infonuagique du gouvernement du Canada](https://www.canada.ca/fr/gouvernement/systeme/gouvernement-numerique/technologiques-modernes-nouveaux/services-informatique-nuage/approche-procedures-gestion-risques-securite-informatique-nuage.html) décrivent les activités que les ministères doivent envisager dans le cadre des activités ministérielles de gestion des risques.

### Comment contribuer

Voir [Comme contribuer](Contributing.md)

### Licence

Sauf indication contraire, le code source de ce projet est protégé par le droit d’auteur de la Couronne du gouvernement du Canada et distribué sous la [licence MIT](LICENSE).

Le mot-symbole « Canada » et les éléments graphiques connexes liés à cette distribution sont protégés en vertu des lois portant sur les marques de commerce et le droit d’auteur. Aucune autorisation n’est accordée pour leur utilisation à l’extérieur des paramètres du programme de coordination de l’image de marque du gouvernement du Canada. Pour obtenir de plus amples renseignements à ce sujet, veuillez consulter les [Exigences pour l’image du Canada](https://www.canada.ca/fr/secretariat-conseil-tresor/sujets/communications-gouvernementales/exigences-image-marque.html).
