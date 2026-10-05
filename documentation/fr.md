<!-- ELUCENIA technical documentation · gravidade-da-anafilaxia · fr · no clinical/professional/rights approval -->

# Sévérité de l’anaphylaxie (Brown)

[conditions, sources et autorisations](https://elucenia.org/fr/outils/gravidade-da-anafilaxia)

## Mode d’emploi

Utilisez l’outil sur le portail ou ouvrez index.html via un serveur HTTP local. Sélectionnez la langue, remplissez les champs et lancez le calcul.

## Données d’entrée et unités

### Peau et tissu sous-cutané : érythème généralisé, urticaire, œdème périorbitaire ou angio-œdème

`pele`

### Respiratoire : dyspnée, stridor, sifflements, oppression thoracique ou de la gorge

`resp`

### Gastro-intestinal : nausées, vomissements, douleur abdominale

`gi`

### Présyncope (étourdissement) ou sudation

`cardio`

### Hypoxémie (SpO₂ ≤ 92 %) ou cyanose

`hipoxia`

### Hypotension (pression artérielle systolique \< 90 mmHg chez l’adulte)

`hipotensao`

### Atteinte neurologique : confusion, collapsus, perte de conscience ou incontinence

`neuro`

## Édition de la méthode

Brown 2004 : 3 grades, signe le plus grave ; SpO₂≤92/PAS\<90/neurologique

## Formule documentée

Grade défini par le signe le plus grave :

Grade 1 (léger) : peau et sous-cutané seuls.

Grade 2 (modéré) : atteinte respiratoire, cardiovasculaire ou gastro-intestinale.

Grade 3 (sévère) : hypoxémie (SpO₂ ≤ 92% ou cyanose), hypotension (PAS \< 90 mmHg) ou atteinte neurologique.

## Limites et population

La classification Brown a été étudiée rétrospectivement dans des réactions d’hypersensibilité systémique aux urgences. La sévérité n’est ni une définition diagnostique complète ni une règle thérapeutique isolée. Les seuils numériques et définitions de la version doivent être vérifiés dans la méthode intégrale ; les signes et conditions d’application ne peuvent être remplacés par le seul total.

## Références

- [Brown SGA. Clinical features and severity grading of anaphylaxis. J Allergy Clin Immunol, 2004.](https://doi.org/10.1016/j.jaci.2004.04.029)

- [Cardona V et al. World Allergy Organization Anaphylaxis Guidance 2020. World Allergy Organ J, 2020.](https://doi.org/10.1016/j.waojou.2020.100472)

## Reproduire les tests techniques

Exécutez node test.cjs dans le répertoire racine de ce dépôt pour reproduire les cas synthétiques enregistrés. Les données d’entrée, les résultats attendus et les tolérances d’origine sont conservés. Les tests techniques ne constituent pas une validation clinique.

```sh
node test.cjs
```

tool.json contient les sources, l’édition et le périmètre de la revue. examples.json conserve les données d’entrée et les résultats attendus des cas synthétiques ; results.json consigne les résultats obtenus.

[Fiche et références](../tool.json) · [Code JavaScript](../calculator.js) · [Cas de référence](../examples.json) · [results.json](../results.json)

## Revue et conditions d’utilisation

Aucune révision clinique indépendante n’a été effectuée.

Cette interface est une traduction réalisée par nos soins, et non une édition officielle ou certifiée. La revue clinique indépendante, la révision linguistique professionnelle et l’autorisation des droits sur les instruments n’ont pas été réalisées.

Résultat de la formule ou de la classification. L’interprétation, la conduite et l’applicabilité dépendent de l’évaluation professionnelle et de la source sélectionnée.

## Licence et attribution

Apache-2.0 s’applique uniquement au code d’ELUCENIA. Les droits sur les instruments, publications, traductions et données restent ceux de leurs titulaires respectifs. Conservez LICENSE et NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
