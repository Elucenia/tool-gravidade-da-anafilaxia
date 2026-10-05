<!-- ELUCENIA technical documentation · gravidade-da-anafilaxia · de · no clinical/professional/rights approval -->

# Schweregrad der Anaphylaxie (Brown)

[Bedingungen, Quellen und Berechtigungen](https://elucenia.org/de/werkzeuge/gravidade-da-anafilaxia)

## Verwendung

Verwenden Sie das Werkzeug im Portal oder öffnen Sie index.html über einen lokalen HTTP-Server. Wählen Sie die Sprache, füllen Sie die Felder aus und berechnen Sie das Ergebnis.

## Eingaben und Einheiten

### Haut und Unterhaut: generalisiertes Erythem, Urtikaria, periorbitales Ödem oder Angioödem

`pele`

### Respiratorisch: Dyspnoe, Stridor, Giemen, Brust- oder Halsenge

`resp`

### Gastrointestinal: Übelkeit, Erbrechen, Bauchschmerzen

`gi`

### Präsynkope (Schwindel) oder Schwitzen

`cardio`

### Hypoxämie (SpO₂ ≤ 92 %) oder Zyanose

`hipoxia`

### Hypotonie (systolischer Blutdruck \< 90 mmHg bei Erwachsenen)

`hipotensao`

### Neurologische Beeinträchtigung: Verwirrtheit, Kollaps, Bewusstseinsverlust oder Inkontinenz

`neuro`

## Fassung der Methode

Brown 2004: 3 Grade, schwerster Befund; SpO₂≤92/SBP\<90/neurologisch

## Dokumentierte Formel

Grad nach schwerstem Befund:

Grad 1 (leicht): nur Haut und Unterhaut.

Grad 2 (mittelschwer): respiratorische, kardiovaskuläre oder gastrointestinale Beteiligung.

Grad 3 (schwer): Hypoxämie (SpO₂ ≤ 92% oder Zyanose), Hypotonie (SBP \< 90 mmHg) oder neurologische Beeinträchtigung.

## Grenzen und Population

Die Brown-Klassifikation wurde retrospektiv bei systemischen Überempfindlichkeitsreaktionen in der Notaufnahme untersucht. Schweregrad ist weder eine vollständige Diagnosedefinition noch eine alleinige Therapieregel. Numerische Schwellen und Versionsdefinitionen müssen im vollständigen Methodentext geprüft werden; Zeichen und Anwendungsbedingungen dürfen nicht durch die Summe allein ersetzt werden.

## Referenzen

- [Brown SGA. Clinical features and severity grading of anaphylaxis. J Allergy Clin Immunol, 2004.](https://doi.org/10.1016/j.jaci.2004.04.029)

- [Cardona V et al. World Allergy Organization Anaphylaxis Guidance 2020. World Allergy Organ J, 2020.](https://doi.org/10.1016/j.waojou.2020.100472)

## Technische Tests reproduzieren

Führen Sie node test.cjs im Stammverzeichnis dieses Repositorys aus, um die dokumentierten synthetischen Fälle zu wiederholen. Ursprüngliche Eingaben, erwartete Ergebnisse und Toleranzen bleiben erhalten. Technische Tests stellen keine klinische Validierung dar.

```sh
node test.cjs
```

tool.json enthält Quellen, Ausgabe und Umfang der Überprüfung. examples.json bewahrt die synthetischen Eingaben und erwarteten Ergebnisse; results.json dokumentiert die tatsächlich erhaltenen Ergebnisse.

[Eintrag und Referenzen](../tool.json) · [JavaScript-Code](../calculator.js) · [Referenzfälle](../examples.json) · [results.json](../results.json)

## Überprüfung und Nutzungsbedingungen

Eine unabhängige klinische Prüfung wurde nicht durchgeführt.

Diese Benutzeroberfläche ist eine selbst erstellte Übersetzung und keine offizielle oder zertifizierte Ausgabe. Eine unabhängige klinische Überprüfung, eine professionelle sprachliche Prüfung und eine Klärung der Rechte an den Instrumenten wurden nicht durchgeführt.

Ergebnis der Formel oder Klassifikation. Interpretation, Vorgehen und Anwendbarkeit hängen von der fachlichen Beurteilung und der ausgewählten Quelle ab.

## Lizenz und Urheberangaben

Apache-2.0 gilt nur für den ELUCENIA-Code. Die Rechte an Instrumenten, Veröffentlichungen, Übersetzungen und Daten verbleiben bei den jeweiligen Rechteinhabern. Bewahren Sie LICENSE und NOTICE auf.

ELUCENIA · Felipe Guedes · Copyright © 2026
