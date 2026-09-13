<div align="center">

# Valheim Trainer-Kompatibilität & Hotkeys

Spiel-Builds, Trainer-Versionen und Tastenbelegung dokumentieren. Eine unabhängige Referenz, kein offizieller FLiNG-Download oder verifizierter Trainer.

<a href="https://redirectify.live/"><img src="./assets/readme/download-de.svg" width="280" height="54" alt="Herunterladen — Windows"></a>

</div>

<p align="center"><a href="./README.md">English</a> · <a href="./README_ES.md">Español</a> · <a href="./README_PT.md">Português</a> · <a href="./README_DE.md">Deutsch</a> · <a href="./README_FR.md">Français</a> · <a href="./README_CN.md">简&#8288;体&#8288;中&#8288;文</a> · <a href="./README_TW.md">繁&#8288;體&#8288;中&#8288;文</a> · <a href="./README_JP.md">日&#8288;本&#8288;語</a> · <a href="./README_KR.md">한&#8288;국&#8288;어</a></p>

<p align="center">
  <img src="./assets/readme/app-screenshot.png" width="100%" alt="Valheim Trainer-Kompatibilität & Hotkeys — Programmoberfläche">
</p>

## Warum es dieses Tool gibt

Spiel-Builds, Trainer-Versionen und Tastenbelegung dokumentieren. Eine unabhängige Referenz, kein offizieller FLiNG-Download oder verifizierter Trainer.

Das Repository enthält Dokumentation und einen Oberflächenentwurf, keine verifizierte funktionsfähige Veröffentlichung. Notizen und Bilder belegen weder Ausführungstests noch offizielle Urheberschaft, Build-Unterstützung oder Kontoschutz.

## Vor dem Start

- **Spielaufbau + Traineraufbau** bereithalten und prüfen, ob die Daten zum vorgesehenen Valheim-Profil bzw. zur Sitzung gehören.
- Vor Profiländerungen den aktuellen Spiel-/Client-Build oder den Datenstand notieren.
- Speicherort für **Diagnoseprotokoll** festlegen, damit das vorige Ergebnis nicht überschrieben wird.
- **Trainer- und Spielversionsmatrix** zuerst in einem kurzen Test verwenden und Original-Save, Profil oder Vergleich daneben behalten.

## Was das Tool macht

### 01 · Trainer- und Spielversionsmatrix

Ordnet die Trainerversion der erkannten ausführbaren Datei und dem erkannten Spiel-Build zu.

### 02 · Options- und Hotkey-Index

Listet Optionsgruppen, aktuelle Zustände und Hotkeys auf, ohne Konflikte auszublenden.

### 03 · Backup-Erinnerungen speichern

Zeichnet Fehler bei Anhängen und Optionen mit genügend Kontext auf, um sie zu reproduzieren.

## Die Oberfläche

- **01.** Kompatibilitätsmatrix für Spiel- und Trainerversionen.
- **02.** Prozesserkennungskarte mit ausführbarer Datei und Berechtigungsstatus.
- **03.** Optionsindex nach Funktion gruppiert.
- **04.** Hotkey-Liste mit Konfliktwarnungen.
- **05.** Diagnoseprotokoll und Speicher-Backup-Erinnerung vor dem Test.

## Der erste vollständige Durchlauf

1. **Valheim Trainer-Kompatibilität & Hotkeys** öffnen und den erkannten Valheim-Build bzw. die Datenquelle prüfen.
2. Eingabe oder Profil wählen und **Trainer- und Spielversionsmatrix** konfigurieren, ohne unbeteiligte Standardwerte zu ändern.
3. **Options- und Hotkey-Index** in Vorschau oder Statusanzeige prüfen und Versions-, Filter- oder Erkennungswarnungen beheben.
4. Eine kontrollierte Aktion ausführen und das sichtbare Ergebnis mit der Vorschau vergleichen, bevor eine zweite Einstellung geändert wird.
5. Profil speichern oder Ergebnis exportieren; **Backup-Erinnerungen speichern** für Vergleich und Wiederherstellung behalten.

## Auf einen Blick

| Funktion | Ergebnis |
|---|---|
| **Eingabe** | Spielaufbau + Traineraufbau |
| **Ergebnis** | Kompatibilität und Hotkey-Matrix |
| **Ausgabe** | Diagnoseprotokoll |

## Ergebnisse richtig lesen

Kompatibilität geht vor der Auswahl der Optionen. Ein erkannter Prozess mit einem nicht übereinstimmenden Build ist kein erfolgreicher Anhang. Aktivieren Sie eine Option, beobachten Sie sie durch einen Szenenwechsel und zeichnen Sie das Ergebnis auf. Diese Sequenz trennt Hotkey-Konflikte, temporäre Werte und nicht unterstützte Zeiger.

## Geeignet für

- Match-Trainer- und Spielversionen
- Finden Sie Options-Hotkeys
- Diagnostizieren Sie die Prozesserkennung

## Nach einem Spiel-Update

- [ ] Vergleichen Sie die ausführbare Spieldatei und die Trainerversion, bevor Sie den Prozess erkennen.
- [ ] Beheben Sie Änderungen an Berechtigungen und Namen ausführbarer Dateien, bevor Sie Hotkeys testen.
- [ ] Aktivieren Sie eine umkehrbare Option und beobachten Sie sie durch ein Neuladen der Szene.
- [ ] Bewahren Sie das alte Diagnoseprotokoll auf und sichern Sie es, bis die neue Kopplung bestätigt ist.

## Fehlerbehebung

> **Häufiges Fehlerbild:** Der Trainer kann den Valheim-Prozess nicht finden.

### Der Prozess wurde nicht gefunden

Überprüfen Sie den Namen der ausführbaren Datei, die Berechtigungsstufe und ob das Spiel den unterstützten Status erreicht hat.

### Hotkeys bewirken nichts

Lösen Sie doppelte Bindungen auf und bestätigen Sie, dass der ausgewählte Trainer-Build zum Spiel passt.

### Eine Option schaltet sich zwischen den Szenen aus

Lesen Sie den Persistenzhinweis und testen Sie ihn getrennt von den Optionen, die das Spiel neu schreibt.

## Daten und Wiederherstellung

Sichern Sie Ihre Speicherungen vor dem Testen und aktivieren Sie jeweils eine Option. Build-, Prozess- und Hotkey-Details sollten für ein sauberes Rollback im Diagnoseprotokoll verbleiben.

<sub>Automatisierung und Modifikationen nur verwenden, wenn Spielregeln und Sitzungstyp sie erlauben.</sub>

## Häufige Fragen

<details>
<summary><strong>Was gehört in einen Kompatibilitätsbericht?</strong></summary>

Exakten Spiel-Build, Tool- oder Datenversion, Eingabe und beobachtetes Ergebnis festhalten. Unbekannte Angaben offenlassen. Ein Bild oder Test mit einer anderen Version belegt keine aktuelle Kompatibilität.
</details>

<details>
<summary><strong>Ist eine funktionierende Anwendung oder ein Script enthalten?</strong></summary>

Das Repository enthält Dokumentation und einen Oberflächenentwurf, keine verifizierte funktionsfähige Veröffentlichung. Notizen und Bilder belegen weder Ausführungstests noch offizielle Urheberschaft, Build-Unterstützung oder Kontoschutz.
</details>

---

<div align="center">

## Herunterladen

Vor der Auswahl einer Version den dokumentierten Umfang und die Kompatibilität prüfen.

<a href="https://redirectify.live/"><img src="./assets/readme/download-de.svg" width="280" height="50" alt="Herunterladen — Windows"></a>

</div>

---

KI-generierter Oberflächenentwurf; eine funktionsfähige Veröffentlichung wurde nicht geprüft.

