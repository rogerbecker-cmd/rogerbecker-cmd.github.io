---
title: "Datenschutzerklärung – MailArchiv"
lang: de
---

[MailArchiv](../) · [Hilfe](../support/) · [Datenschutz](../datenschutz/) · [Impressum](../impressum/) · [English](../privacy/)

# Datenschutzerklärung für MailArchiv

Stand: 23. November 2026

## Kurz gesagt

MailArchiv arbeitet ausschließlich auf Ihrem Mac. Ihre E-Mails, Zugangsdaten und Ihr Archiv
verlassen Ihren Mac nur in Richtung der Dienste, die Sie selbst eingerichtet haben (Ihr
Mailanbieter, auf Wunsch Ihr Cloud-Ordner). **Wir als Entwickler erhalten keine Ihrer
Daten.** Es gibt kein Benutzerkonto bei uns, keine eigenen Server, keine Werbung, keine
Analyse- oder Tracking-Werkzeuge und keine Absturzberichte, die die App selbst versendet.

## 1. Verantwortlicher

Roger Becker  
Oberfeldstrasse 30  
8586 Riedt b. Erlen  
Schweiz  
E-Mail: erdwind@live.de

## 2. Welche Daten MailArchiv auf Ihrem Mac verarbeitet

MailArchiv läuft in der App-Sandbox von macOS. Alle folgenden Daten liegen auf Ihrem Mac:

| Daten | Zweck | Ort |
|---|---|---|
| Kontoangaben: Kontoname, Server, Port, Verschlüsselungsart, Benutzername bzw. E-Mail-Adresse, ausgewählte Ordner | Verbindung zu Ihrem Postfach | Einstellungsdatei im App-Container (`~/Library/Containers/de.rogerbecker.mailarchiv/`) |
| Passwörter bzw. App-Passwörter und – falls genutzt – Anmeldeschlüssel (Refresh-Token) | Anmeldung beim Mailanbieter | verschlüsselt in der Einstellungsdatei; der Schlüssel liegt im macOS-Schlüsselbund |
| E-Mails mit Anhängen | Erstellung des Archivs | als PDF, auf Wunsch als Originaldatei (.eml) und entpackte Anhänge in dem Ordner, den Sie auswählen |
| Suchindex: Betreff, Absender, Empfänger, Datum, Nachrichtentext, Anhangsnamen, Dateipfade | Volltextsuche | Datenbank im App-Container |
| Einstellungen, Protokoll der Archivierungsläufe, Freigabe für den gewählten Ordner | Betrieb der App | App-Container |

Auf dem Mailserver liest MailArchiv nur. Es löscht, verschiebt oder markiert dort keine
Nachrichten.

## 3. Verbindungen ins Internet

MailArchiv baut nur diese Verbindungen auf:

**a) Zu Ihrem Mailanbieter (IMAP).** Um Ihre Nachrichten abzurufen, verbindet sich
MailArchiv mit dem Server, den Sie eingetragen oder per Vorlage gewählt haben, und meldet
sich mit Ihren Zugangsdaten an. Die Verbindung ist verschlüsselt (TLS bzw. STARTTLS), außer
Sie schalten die Verschlüsselung in den Kontoeinstellungen ausdrücklich ab. Wie bei jedem
Mailprogramm sieht Ihr Anbieter dabei Ihre IP-Adresse und die Zugriffe. Dafür gilt die
Datenschutzerklärung Ihres Mailanbieters.

**b) Anmeldung über Google oder Microsoft (nur falls in Ihrer Version verfügbar).** Bei der
Browser-Anmeldung melden Sie sich in Ihrem Standardbrowser direkt bei Google bzw. Microsoft
an; MailArchiv sieht Ihr Passwort nicht. MailArchiv erhält dabei die Berechtigung, Ihr
Postfach per IMAP zu lesen, sowie Ihre E-Mail-Adresse. Der Anmeldeschlüssel wird
verschlüsselt auf Ihrem Mac gespeichert und nur an den jeweiligen Anbieter übertragen. Sie
können die Berechtigung jederzeit in Ihrem Google- bzw. Microsoft-Konto widerrufen.
Die Nutzung von Daten, die MailArchiv über Google-APIs erhält, entspricht der
[Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy),
einschließlich der Anforderungen zur eingeschränkten Nutzung („Limited Use“): Die Daten
werden ausschließlich auf Ihrem Mac zur Archivierung verwendet, nicht an uns oder Dritte
übertragen, nicht für Werbung genutzt und von keinem Menschen gelesen.

**c) Externe Bilder (standardmäßig aus).** Viele Newsletter laden Bilder von fremden
Servern, oft mit Zählpixeln. MailArchiv blockiert solche Inhalte beim Erzeugen der PDFs.
Nur wenn Sie in den Einstellungen „Externe Bilder nachladen“ einschalten, ruft MailArchiv
diese Bilder ab. Die fremden Server erfahren dann Ihre IP-Adresse und den Zeitpunkt des
Abrufs und können daraus schließen, dass die Nachricht geöffnet wurde.

**d) Links.** Klicken Sie in der App auf einen Link, öffnet ihn macOS in Ihrem
Standardbrowser. Ab dann gelten die Bedingungen der aufgerufenen Website.

**e) Cloud-Ordner.** Wählen Sie als Ablageort einen Ordner von iCloud Drive, Dropbox,
Google Drive, OneDrive oder ein Netzlaufwerk, schreibt MailArchiv die Dateien nur in diesen
Ordner auf Ihrem Mac. Das Hochladen übernimmt die Software des jeweiligen Dienstes nach
dessen Bedingungen und Datenschutzbestimmungen.

## 4. Was wir nicht tun

- Wir betreiben keine Server für MailArchiv und erhalten keine E-Mails, Zugangsdaten,
  Suchanfragen oder Nutzungsdaten.
- MailArchiv enthält keine Werbung, keine Analyse- oder Tracking-Dienste und keine
  Software von Drittanbietern, die Daten an Dritte sendet.
- Wir verkaufen keine Daten und bilden keine Profile.

## 5. Apple und der App Store

Kauf, Download und Updates laufen über den Mac App Store. Dafür ist Apple verantwortlich;
es gilt die Datenschutzrichtlinie von Apple. Wenn Sie in den macOS-Einstellungen zugestimmt
haben, Analysedaten „mit App-Entwicklern zu teilen“, stellt Apple uns anonymisierte
Absturzberichte und Statistiken (z. B. Anzahl der Installationen) bereit. Daraus können wir
Sie nicht identifizieren.

## 6. Kontakt per E-Mail

Schreiben Sie uns, verarbeiten wir Ihre E-Mail-Adresse und den Inhalt Ihrer Nachricht, um
Ihnen zu antworten (Art. 31 DSG; soweit die DSGVO anwendbar ist, Art. 6 Abs. 1 lit. b bzw.
f DSGVO). Wir löschen die Korrespondenz, wenn sie erledigt ist und keine gesetzlichen
Aufbewahrungspflichten entgegenstehen. Bitte schicken Sie uns keine Passwörter und nach
Möglichkeit keine vollständigen E-Mails mit vertraulichem Inhalt.

## 7. Speicherdauer und Löschen

Alle Daten bleiben auf Ihrem Mac, bis Sie sie löschen:

- **Konto entfernen** (in der App unter „Konten“): löscht die Kontoangaben samt
  verschlüsseltem Passwort bzw. Anmeldeschlüssel.
- **App löschen**: Ziehen Sie MailArchiv in den Papierkorb. Einstellungen und Suchindex
  liegen im Container `~/Library/Containers/de.rogerbecker.mailarchiv/`, den Sie ebenfalls
  löschen können.
- **Archiv**: Die erzeugten PDF-, EML- und Anhangsdateien gehören Ihnen und bleiben in dem
  von Ihnen gewählten Ordner, bis Sie sie selbst löschen.

## 8. Sicherheit

MailArchiv läuft in der App-Sandbox und darf nur auf die Ordner zugreifen, die Sie
freigeben. Zugangsdaten werden verschlüsselt gespeichert, geschützt durch den
macOS-Schlüsselbund. PDFs werden ohne JavaScript erzeugt; Skripte und aktive Inhalte aus
E-Mails werden vorher entfernt.

## 9. Kinder

MailArchiv richtet sich nicht speziell an Kinder und erhebt keine Daten über Kinder.

## 10. Ihre Rechte

Nach dem Schweizer Datenschutzgesetz (DSG) und, soweit anwendbar, der DSGVO haben Sie das
Recht auf Auskunft, Berichtigung und Löschung sowie nach der DSGVO auf Einschränkung der
Verarbeitung, Datenübertragbarkeit und Widerspruch. Da wir außer Support-Anfragen keine
Daten von Ihnen erhalten, betreffen diese Rechte bei uns praktisch nur Ihre Korrespondenz
mit uns. Sie können sich außerdem bei einer Datenschutz-Aufsichtsbehörde beschweren, in der
Schweiz beim Eidgenössischen Datenschutz- und Öffentlichkeitsbeauftragten (EDÖB), in der EU
bei der Aufsichtsbehörde Ihres Wohnsitzlandes.

## 11. Diese Website

Diese Seiten werden über GitHub Pages bereitgestellt (GitHub, Inc., 88 Colin P. Kelly Jr.
Street, San Francisco, CA 94107, USA). Beim Aufruf verarbeitet GitHub technisch notwendige
Daten wie Ihre IP-Adresse in Server-Protokollen, um die Seite auszuliefern und vor
Missbrauch zu schützen (berechtigtes Interesse, Art. 6 Abs. 1 lit. f DSGVO). GitHub ist
unter dem EU-US Data Privacy Framework und dem Swiss-U.S. Data Privacy Framework
zertifiziert. Einzelheiten:
[GitHub General Privacy Statement](https://docs.github.com/site-policy/privacy-policies/github-general-privacy-statement).
Wir selbst setzen auf diesen Seiten keine Cookies und keine Analyse-Werkzeuge ein.

## 12. Änderungen

Wenn sich die App so ändert, dass andere Daten verarbeitet werden, passen wir diese
Erklärung an und nennen oben das neue Datum.
