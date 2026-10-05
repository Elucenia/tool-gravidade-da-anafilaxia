<!-- ELUCENIA technical documentation · gravidade-da-anafilaxia · pt-BR · no clinical/professional/rights approval -->

# Gravidade da anafilaxia (Brown)

[condições, fontes e permissões](https://elucenia.org/pt-br/ferramentas/gravidade-da-anafilaxia)

## Como usar

Use a ferramenta no portal ou abra index.html em um servidor HTTP local. Selecione o idioma, preencha os campos e calcule.

## Entradas e unidades

### Pele e subcutâneo: eritema generalizado, urticária, edema periorbitário ou angioedema

`pele`

### Respiratório: dispneia, estridor, sibilância, aperto no peito ou na garganta

`resp`

### Gastrointestinal: náusea, vômitos, dor abdominal

`gi`

### Pré-síncope (tontura) ou sudorese

`cardio`

### Hipoxemia (SpO₂ ≤ 92%) ou cianose

`hipoxia`

### Hipotensão (PAS \< 90 mmHg no adulto)

`hipotensao`

### Comprometimento neurológico: confusão, colapso, perda de consciência ou incontinência

`neuro`

## Edição do método

Brown 2004:3 graus, achado maisgrave; Sp O 2≤92/PAS\<90/neurológico

## Fórmula documentada

O grau é definido pelo achado mais grave:

Grau 1 (leve): apenas pele e subcutâneo.

Grau 2 (moderado): sinais de envolvimento respiratório, cardiovascular ou gastrointestinal.

Grau 3 (grave): hipoxemia (SpO₂ ≤ 92% ou cianose), hipotensão (PAS \< 90 mmHg) ou comprometimento neurológico.

## Limites e população

A classificação Brown foi estudada retrospectivamente em reações de hipersensibilidade sistêmica na emergência. Gravidade não é uma definição completa de diagnóstico nem regra terapêutica isolada. Limiares numéricos e definições da versão devem ser conferidos no método integral; sinais e condições de aplicação não podem ser substituídos somente pelo total.

## Referências

- [Brown SGA. Clinical features and severity grading of anaphylaxis. J Allergy Clin Immunol, 2004.](https://doi.org/10.1016/j.jaci.2004.04.029)

- [Cardona V et al. World Allergy Organization Anaphylaxis Guidance 2020. World Allergy Organ J, 2020.](https://doi.org/10.1016/j.waojou.2020.100472)

## Reproduzir os testes técnicos

Execute node test.cjs na pasta raiz deste repositório para repetir os casos sintéticos registrados. As entradas, expectativas e tolerâncias originais são preservadas. Testes técnicos não constituem validação clínica.

```sh
node test.cjs
```

tool.json contém fontes, edição e escopo de revisão. examples.json conserva as entradas e expectativas sintéticas; results.json registra os resultados obtidos.

[Ficha e referências](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referência](../examples.json) · [results.json](../results.json)

## Revisão e condições de uso

Revisão clínica independente não realizada.

Esta interface é uma tradução autoral, não uma edição oficial ou certificada. Revisão clínica independente, revisão linguística profissional e autorização de direitos de instrumentos não foram realizadas.

Resultado da fórmula ou classificação. Interpretação, conduta e aplicabilidade dependem da avaliação profissional e da fonte selecionada.

## Licença e atribuição

Apache-2.0 aplica-se somente ao código da ELUCENIA. Os instrumentos, publicações, traduções e dados mantêm os direitos dos respectivos titulares. Preserve LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
