<!-- ELUCENIA technical documentation · gravidade-da-anafilaxia · en · no clinical/professional/rights approval -->

# Anaphylaxis severity (Brown)

[conditions, sources and permissions](https://elucenia.org/en/tools/gravidade-da-anafilaxia)

## How to use

Use the tool in the portal or open index.html through a local HTTP server. Select the language, complete the fields and calculate.

## Inputs and units

### Skin and subcutaneous tissue: generalized erythema, urticaria, periorbital edema or angioedema

`pele`

### Respiratory: dyspnea, stridor, wheezing, chest or throat tightness

`resp`

### Gastrointestinal: nausea, vomiting, abdominal pain

`gi`

### Presyncope (dizziness) or sweating

`cardio`

### Hypoxemia (SpO₂ ≤ 92%) or cyanosis

`hipoxia`

### Hypotension (systolic blood pressure \< 90 mmHg in adults)

`hipotensao`

### Neurological impairment: confusion, collapse, loss of consciousness or incontinence

`neuro`

## Method edition

Brown 2004: 3 grades, most severe finding; SpO₂≤92/SBP\<90/neurological

## Documented formula

Grade is defined by the most severe finding:

Grade 1 (mild): skin and subcutaneous tissue only.

Grade 2 (moderate): respiratory, cardiovascular or gastrointestinal involvement.

Grade 3 (severe): hypoxemia (SpO₂ ≤ 92% or cyanosis), hypotension (SBP \< 90 mmHg) or neurological impairment.

## Limits and population

The Brown classification was studied retrospectively in systemic hypersensitivity reactions in emergency care. Severity is not a complete diagnostic definition or a standalone treatment rule. Numerical thresholds and definitions for the version must be checked in the full method; signs and application conditions cannot be replaced by the total alone.

## References

- [Brown SGA. Clinical features and severity grading of anaphylaxis. J Allergy Clin Immunol, 2004.](https://doi.org/10.1016/j.jaci.2004.04.029)

- [Cardona V et al. World Allergy Organization Anaphylaxis Guidance 2020. World Allergy Organ J, 2020.](https://doi.org/10.1016/j.waojou.2020.100472)

## Reproduce the technical tests

Run node test.cjs in the root directory of this repository to repeat the recorded synthetic cases. Original inputs, expectations and tolerances are preserved. Technical tests do not constitute clinical validation.

```sh
node test.cjs
```

tool.json contains sources, edition and review scope. examples.json retains synthetic inputs and expectations; results.json records the obtained results.

[Record and references](../tool.json) · [JavaScript code](../calculator.js) · [Reference cases](../examples.json) · [results.json](../results.json)

## Review and conditions of use

Independent clinical review has not been performed.

This interface is an authorial translation, not an official or certified edition. Independent clinical review, professional language review and instrument rights clearance have not been performed.

Formula or classification result. Interpretation, care and applicability depend on professional assessment and the selected source.

## License and attribution

Apache-2.0 applies only to ELUCENIA code. Rights to instruments, publications, translations and data remain with their respective holders. Preserve LICENSE and NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
