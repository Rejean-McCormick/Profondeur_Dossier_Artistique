# 08 — Manifestations publiques, preuves et limites

## Comment lire ce chapitre

*Profondeur* est une œuvre autour d'une signature, et non l'annonce d'une application unique déjà intégralement déployée. Ses manifestations techniques possèdent chacune **une responsabilité, un dépôt et un niveau de maturité distincts**.

La matrice ci-dessous décrit les éléments **documentés dans les dépôts publics consultés début novembre 2026**. Les fonctionnalités imminentes, les versions locales non publiées et les perspectives de déploiement ne sont pas assimilées à une certification publique.

| Élément | État documenté et portée |
| --- | --- |
| [Site Mécanismes Abstraits](https://ma-gustave.github.io/MA-Gustave/fr/) | Présence éditoriale et visuelle publique de la signature « par Gustave » |
| [Prépublication *Beyond Writing Code*](https://doi.org/10.5281/zenodo.23503438) | Article déposé le 20 octobre 2026 ; **prépublication non évaluée par les pairs** ; son texte GitHub vivant n'est pas nécessairement identique au PDF déposé |
| [GF Wordbench](https://github.com/MA-Gustave/GF_Wordbench) | Atelier implémenté de diagnostics, tests, compilations ciblées et conservation de preuves selon les profils ; un résultat candidat n'est pas une qualification linguistique complète |
| [GF Observatory](https://github.com/MA-Gustave/GF_Observatory) | Fonctions locales de consultation de preuves, d'inventaire et de diagnostic ; ne prétend pas être une plateforme de publication intégrale |
| [GF RGL AI Compendium](https://github.com/MA-Gustave/GF_RGL_AI_Compendium) | Référentiel d'ingénierie linguistique, explicitement **provisoire et non certifié** par compilation et revue humaine complète |
| [Ars Magna Defluens](https://github.com/MA-Gustave/Ars-Magna-Defluens) | Architecture et contrats d'un orchestrateur multilingue ; **le dépôt ne prouve pas un orchestrateur complet en exploitation** |
| [Kristal Framework](https://github.com/Rejean-McCormick/Kristal-Framework) | Standard et outils de connaissance versionnés ; ses spécifications v11 et la couverture multilingue visée comportent des limites et étapes futures |
| [EncyKlopedia](https://github.com/Rejean-McCormick/EncyKlopedia) | La version publique documentée est une **démonstration alpha locale avec contenu synthétique**, pas un service public multilingue certifié |
| [VectorPath-RVV — Test 106](https://github.com/MA-Gustave/VectorPath-RVV/blob/main/docs/release/TEST106_PUBLICATION_REPORT_EN.md) | Étude de performance sur 18 fichiers JSON publics et deux machines natives ; résultat spécialisé ne certifiant pas tout l'écosystème |

## Résultat mesuré : exemple de la méthode

Le rapport **Test 106** de VectorPath-RVV rapporte des débits DOM de **1,6007×** sur Cloud-V et de **1,8946×** sur EPCC par rapport au backend **fallback officiel de simdjson 5.0.4**, sur un corpus de **18 documents publics fixés**. Il documente également des régressions sur des fichiers très petits et des limites de validation. Ce résultat n'est ni une preuve de supériorité universelle ni une preuve générale que l'IA accélère tous les projets.

Le rôle de cet exemple dans *Profondeur* est méthodologique : il illustre des travaux techniques concrets et vérifiables produits dans la démarche. Il ne remplace pas l'argument artistique.

## Données externes

Le [Thésaurus de l'UNESCO](https://vocabularies.unesco.org/) sert de référence de classification dans certains travaux liés à Kristal. Les identifiants et relations du thésaurus restent sous autorité documentaire de l'UNESCO ; cette référence ne crée **ni approbation ni partenariat**. Wikidata fournit des informations structurées externes, avec ses propres mécanismes et limites.

## Règle de mise à jour

Pour chaque nouveau déploiement revendiqué, ajouter : **URL publique exacte, version, date, corpus, langues réellement couvertes, statut de validation, limites connues, droits et licence applicable**. Ne pas annoncer comme accomplie une certification dont les preuves ne sont pas disponibles.

[← Index](README.md) · [IA et provenance →](09_IA_PROVENANCE_ET_CREDIT.md)
