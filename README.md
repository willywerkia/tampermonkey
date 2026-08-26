# Werkia Tampermonkey Toolboxes

Fertig gebaute Tampermonkey-Userscripts fuer KAM/CEM/OBC. Dieses Repo wird automatisch von der internen Werkia_OPS-CI gepflegt (`.github/workflows/mirror-toolboxes.yml`) - Aenderungen hier werden beim naechsten Sync ueberschrieben.

Installation: die gewuenschte `.user.js`-Datei unten anklicken - Tampermonkey erkennt sie automatisch und bietet die Installation an. Updates kommen danach automatisch ueber Tampermonkeys eigene Update-Pruefung (`@updateURL`), ohne dass hier nochmal etwas angeklickt werden muss.

## KAM Toolbox

[KAM-Toolbox.user.js](https://raw.githubusercontent.com/willywerkia/tampermonkey/main/KAM-Toolbox.user.js)

Enthaltene Funktionen:

- Setzt Wiedervorlagedatum und KAM-Status fuer mehrere Zeilen in der Matches-Liste gleichzeitig. Bei Out werden offene Terminvorschlaege abgelehnt.
- Zeigt bei jedem Arbeitgeber ein Badge zur Kontakthaeufigkeit (z. B. "Direkter Kontakt", "Kein Kontakt").
- Technische Hintergrundfunktion ohne eigene Anzeige - merkt sich Kandidat/Vakanz des offenen Fragebogens fuer andere Funktionen.
- Blendet neben dem OM-Fragebogen ein Panel mit den oeffentlichen Vakanzangaben ein ("Zustaendigkeiten", "Dein Profil").
- Vergleicht Fragebogen-Antworten mit den Vakanzanforderungen und zeigt eine farbige Ampel-Empfehlung plus Notizfeld.
- Berechnet und zeigt die Fahrstrecke/-zeit zwischen Kandidatenwohnort und Arbeitsort im Fragebogen.
- Oeffnet die Kandidatendatei per Klick direkt in einem Popup statt in einem neuen Tab.
- Zeigt eine Konfetti-/Feier-Animation, wenn ein Match auf "Senden" oder "Hired" gesetzt wird.
- Zeigt im Chat ein farbiges Banner mit dem aktuellen CEM/KAM-Status des zugehoerigen Matches.
- Korrigiert den Chat-Button in "Meine Matches", damit er direkt die richtige Unterhaltung oeffnet.
- Kopiert Terminvorschlaege (Ort, Hinweise, Datum/Uhrzeit) per Knopfdruck von einem Dialog in einen anderen.
- Zeigt unter jedem Termin VTA- und VTV-Buttons, die den passenden Slack-Text des Matches kopieren.
- Fuegt im Arbeitgeberprofil OM-Flag-Vorlagen direkt am Feld OM Notes ein.
- Markiert dringend zu besetzende Vakanzen bei potenziellen Kandidaten-Matches farblich in der Liste.

## CEM Toolbox

[CEM-Toolbox.user.js](https://raw.githubusercontent.com/willywerkia/tampermonkey/main/CEM-Toolbox.user.js)

Enthaltene Funktionen:

- Zeigt bei jedem Arbeitgeber ein Badge zur Rueckmeldegeschwindigkeit (z. B. "Schnelle Rueckmeldung", "Keine Rueckmeldung").
- Zeigt bei Reverse-Match-Vorschlaegen zusaetzlich den passenden KAM-Status als Tag an.
- Markiert Zeilen von Arbeitgebern mit besonderer Absprache (GA-TEC) farblich mit Hinweistext "[Absprache vor OFM]".
- Technische Hintergrundfunktion ohne eigene Anzeige - merkt sich den Kontext des offenen Fragebogens fuer andere Funktionen.
- Blendet neben dem Fragebogen ein Panel mit den oeffentlichen Vakanzangaben ein.
- Faerbt das Status-Auswahlfeld eines Matches passend zum gewaehlten Status ein (z. B. Hot Case orange, Hired gruen).
- Vergleicht Fragebogen-Antworten mit den Vakanzanforderungen und zeigt eine farbige Match-Empfehlung an.
- Berechnet und zeigt die Fahrstrecke/-zeit zwischen Kandidatenwohnort und Arbeitsort im Fragebogen.
- Ergaenzt die Kandidatenliste einer Vakanz um Zusatzinfos je Kandidat (Reisebereitschaft, Status, Registrierungsdatum, Telefonnummer) und eine Anruf-Empfehlung.
- Zeigt unter jedem Termin VTA- und VTV-Buttons, die den passenden Slack-Text des Matches kopieren.
- Markiert dringend zu besetzende Vakanzen bei potenziellen Kandidaten-Matches farblich in der Liste.

## OBC Toolbox

[OBC-Toolbox.user.js](https://raw.githubusercontent.com/willywerkia/tampermonkey/main/OBC-Toolbox.user.js)

Enthaltene Funktionen:

- Zeigt bei jedem Arbeitgeber ein Badge zur Antwortgeschwindigkeit (z. B. "Schnelle Rueckmeldung", "Keine Rueckmeldung").
- Markiert Zeilen von Arbeitgebern mit besonderer Absprache (GA-TEC) farblich mit Hinweistext "[Absprache vor OFM]".
- Zeigt bei Reverse-Match-Vorschlaegen zusaetzlich den zugehoerigen KAM-Status als Tag an.
- Technische Hintergrundfunktion ohne eigene Anzeige - merkt sich Kandidat/Vakanz des offenen Fragebogens.
- Blendet neben dem Fragebogen ein Panel mit den oeffentlichen Vakanzangaben ein.
- Vergleicht Fragebogen-Antworten mit den Vakanzanforderungen und zeigt eine farbige Match-Entscheidungs-Empfehlung.
- Zeigt eine hervorgehobene Box mit den OM-Notizen zum Fragebogen direkt im Dialog.
- Berechnet und zeigt die Fahrstrecke/-zeit zwischen Kandidatenwohnort und Arbeitsort im Fragebogen.
- Markiert dringend zu besetzende Vakanzen bei potenziellen Kandidaten-Matches farblich in der Liste.
