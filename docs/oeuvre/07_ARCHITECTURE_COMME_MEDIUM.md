# 07 — L’infrastructure comme médium artistique

> **Position dans *Profondeur* :** l’architecture est un matériau et une manifestation opératoire de la signature « Mécanismes Abstraits — par Gustave ». Elle n’est ni le titre, ni le centre unique, ni une machine globale possédant un nom distinct. Voir [18 — La signature comme œuvre](18_LA_SIGNATURE_COMME_OEUVRE_ET_EFFACEMENT.md).

*Document de la série **Profondeur**, une création de Réjean McCormick. L’œuvre réunit une création d’identité d’auteur et des réalisations techniques, sans constituer une machine unique.*

## Ce que l’on regarde lorsqu’on explore *Profondeur*

Dans une œuvre informatique, la forme ne s’arrête pas à l’écran. Elle réside aussi dans la façon dont les composants communiquent, dans les contrats qui les séparent, dans le traitement des absences et dans les parcours qu’une personne peut suivre entre une question et une réponse.

L’architecture devient un **médium** : les données, le code, les standards, les relations et les validations sont à la fois matériau et forme. L’objectif n’est pas de remplacer le regard artistique par un schéma d’ingénierie, mais de rendre la structure elle-même lisible comme choix de composition.

## La chaîne conceptuelle

La chaîne ci-dessous décrit une **intention d'ensemble** et des responsabilités complémentaires. Ce n’est **pas** une affirmation qu'une chaîne de production complète reliant tous les dépôts fonctionne déjà de bout en bout.

```text
Sources ouvertes et répertoires de concepts
   ├── Thésaurus de l'UNESCO : domaines, concepts et relations
   └── Wikidata : identifiants, déclarations et lexèmes
                      ↓
       Alignement documenté et provenance
                      ↓
  Kristal : représentation et états de connaissance
                      ↓
      Ressources linguistiques GF / RGL
                      ↓
  Méthodes de validation, de revue et de version
                      ↓
      Consultation et articulation multilingues
                      ↓
              Rencontre entre personnes
```

### Le Thésaurus de l’UNESCO

Le [Thésaurus de l’UNESCO](https://vocabularies.unesco.org/) constitue un référentiel documentaire de sujets. Au 4 novembre 2026, le portail officiel annonce environ **4 500 concepts, cinq langues, sept domaines et 88 microthésaurus** ; il fournit notamment une représentation en SKOS. Ces chiffres décrivent le **référentiel UNESCO**, pas une couverture linguistique déjà réalisée par Profondeur.

L’UNESCO n’est pas présentée comme une partenaire ni comme une institution qui aurait validé Profondeur. L’usage et la redistribution de données sous **CC BY-SA 3.0 IGO** exigent le respect des conditions de licence et une identification claire des adaptations éventuelles.

### Wikidata

[Wikidata](https://www.wikidata.org/) apporte des identifiants et des données structurées pouvant être utilisés pour lier des concepts à d’autres connaissances. Ses données structurées sont en [CC0](https://www.wikidata.org/wiki/Wikidata:Licensing). Une correspondance entre deux référentiels n’est pas correcte du seul fait qu’elle est suggérée automatiquement : la qualité de l’alignement, la provenance et la validation restent des tâches distinctes.

### Kristal Framework

[Kristal Framework](https://github.com/Rejean-McCormick/Kristal-Framework) travaille sur la représentation déterministe d’états de connaissance, la provenance, les identités sémantiques, les dictionnaires et la séparation entre concepts et formulations lexicales. Le profil compagnon [UNESCO](https://github.com/Rejean-McCormick/Kristal-Framework/tree/main/profiles/unesco) décrit une classification de sujets. La version 11 y est présentée comme **brouillon**, non comme un réseau mondial certifié.

Les relations de collaboration conceptuelle avec Profondeur peuvent être documentées sans attribuer indistinctement à chaque dépôt l’autorité technique ou la maturité des autres.

### Grammatical Framework (GF), RGL et les outils Profondeur

Les grammaires permettent de respecter des réalités plus profondes que la simple substitution de mots : accord, ordre, morphologie, syntaxe et variations selon la langue.

- [GF Wordbench](https://github.com/MA-Gustave/GF_Wordbench) : outil mis en œuvre pour la sélection de sources, les contrôles, la compilation GF, les scénarios, les diagnostics et la conservation de preuves. Il ne remplace pas le compilateur GF ni la revue linguistique humaine.
- [GF RGL AI Compendium](https://github.com/MA-Gustave/GF_RGL_AI_Compendium) : corpus de contrats, de modèles et de méthodes d’ingénierie linguistique. C’est un référentiel, non un générateur autonome.
- [GF Observatory](https://github.com/MA-Gustave/GF_Observatory) : outils partiels d’inventaire et de visualisation des preuves ; les fonctionnalités opérationnelles doivent être distinguées de l’architecture plus ambitieuse documentée.
- [Ars Magna Defluens](https://github.com/MA-Gustave/Ars-Magna-Defluens) : projet d’orchestration multilingue, dont le dépôt indique explicitement que l'orchestrateur intégral n’est pas encore opérationnel.

### EncyKlopedia

[EncyKlopedia](https://github.com/Rejean-McCormick/EncyKlopedia) décrit une application de lecture et de découverte de connaissance multilingue. Son README consulté indique une **alpha 0.1.0 démontrable localement sur des données synthétiques**, sans publication publique du corpus réel ni qualification d’une centaine de langues. Sa trajectoire fait écho à l’ambition de Profondeur, mais son état ne doit pas être amalgamé à une mise en production confirmée.

## L'esthétique de l'absence explicite

Une opération qui refuse de fabriquer une traduction non vérifiée montre un trait de l’œuvre : **ne pas déguiser l’absence de connaissance en fluidité verbale**. Une donnée manquante, une variante non attestée ou une grammaire non qualifiée peuvent devenir visibles comme des états du système.

L’artiste fait ici un choix de forme et de confiance : la vérité d’une lacune peut être plus belle, et plus utile, qu’une fausse élégance.

## Comment explorer sans « démonter »

L’œuvre peut être explorée à plusieurs échelles : interface, définition d’un concept, liens vers les sources, états de validation, contrats, code et méthode de fabrication. L’exploration n’exige pas de briser l’objet ; la nature numérique permet à chacun de changer de profondeur selon son intérêt, dans les limites de l’accès et des droits réellement ouverts.

**La documentation fait partie de cette possibilité d’exploration.**
