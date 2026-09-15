---
book: learning-ojs
version: 3.3
title: Learning Open Journal Systems 3.3 - Tools
showPageTOC: true
description: Eine Anleitung zur Verwendung des Werkzeuge-Menüs in OJS, inklusive Import/Export-Funktionen und Schnelleinreichungs-Plugin.
---

# Werkzeuge

Auf den Bereich Werkzeuge kann man über das Menü links an der Seite zugreifen.

![Seitenmenü-Optionen der Werkzeuge](./assets/learning-ojs3.2-jm-users-tools.png)

Der Bereich Werkzeuge besteht aus einem Reiter Import/Export und einem Reiter Berichtserstellung (Statistik in OJS 3.1.1 und früher) und einem Reiter Rechte.

{% include video.html id="v3zjjVFYAyc" provider="youtube" title="Video of setting up a journal in OJS 3.3. Module 14: Tools"%}

Dieses englischsprachige Video der PKP School erklärt, wie Sie auf die Import/Export Werkzeuge zugreifen und diese verwenden. Weitere Videos dieser Reihe finden Sie auf dem [YouTube-Kanal von PKP](https://www.youtube.com/playlist?list=PLg358gdRUrDVTXpuGXiMgETgnIouWoWaY).

## Import/Export {#importexport}

Import/Export ermöglicht es Ihnen, einfach Daten Ihrer OJS-Zeitschrift zu im- und exportieren.

![Liste von verfügbaren Import/Export-Plugins.](./assets/learning-ojs3.2-jm-users-tools-import.png)

Einige der Werkzeuge erlauben Ihnen den Export zu Drittanbietersystemen wie PubMed oder DOAJ. Andere ermöglichen den Import oder Export von Artikeldaten.

Wenn Sie Benutzer/innendaten exportieren möchten, finden Sie hier die Möglichkeit, sie als XML-Datei zu exportieren. Wenn Sie Ihre Benutzer/innendaten als Tabelle bevorzugen, können Sie unter **Statistiken > Benutzer/innen** eine CSV-Datei herunterladen.

Detaillierte Hinweise zum Importieren und Exportieren finden Sie in [Administrator's Guide](https://docs.pkp.sfu.ca/admin-guide/en/data-import-and-export) (englischsprachig).

Weitere Informationen zum Crossref-Export/Registrierungs-Plugin finden Sie im [PKP Crossref Guide](https://docs.pkp.sfu.ca/crossref-ojs-manual/en/) (englischsprachig).

### Schnelleinreichungs-Plugin

{% include video.html id="_nm1dGIZS8Y" provider="youtube" title="Video of setting up a journal in OJS 3.3. Module 18: Plugins- QuickSubmit"%}

Dieses englischsprachige PKP School Video erklärt, wie man das Schnelleinreichungs-Plugin verwendet, um komplette Einreichungen zu einer Ausgabe hinzuzufügen. Weitere Videos dieser Reihe finden Sie auf dem [PKP YouTube-Kanal](https://www.youtube.com/playlist?list=PLg358gdRUrDVTXpuGXiMgETgnIouWoWaY).

Mit dem Schnelleinreichungs-Plugin können Sie schnell komplette Einreichungen zu einer Ausgabe hinzufügen. Es erlaubt somit einen einstufigen Einreichungsprozess für Redakteur/innen, die den traditionellen Einreichungs-, Überprüfungs- und Bearbeitungsprozess umgehen müssen.

Das Schnelleinreichungs-Plugin kann in den folgenden Fällen verwendet werden:

- Zeitschriften, die OJS verwenden, um ihre Inhalte anzuzeigen und zu veröffentlichen, ohne den redaktionellen Workflow zu benutzen.
- Zeitschriften, die ursprünglich mit einer anderen Plattform veröffentlicht wurden und zu OJS migrieren, wenn es kein Konvertierungstool für diese Plattform gibt.
- Zeitschriften, die ursprünglich gedruckt erschienen sind und seitdem digitalisiert wurden.

Um dieses Plugin zu nutzen, benötigen Sie Folgendes:

- Sie müssen als Redakteur/in oder Zeitschriftenverwalter/in eingetragen sein.
- Eine Reihe von publikationsfertigen Dateien (z.B. PDFs).
- Alle Metadaten für die Dateien (z.B. Autor/innennamen, Titel, Abstracts usw.).

Stellen Sie zunächst sicher, dass das Schnelleinreichungs-Plugin für Ihre Zeitschrift installiert und aktiviert wurde.  Sie benötigen die Rolle des/der Zeitschriftenverwalter/in, um das Plugin zu aktivieren. Um das Plugin zu installieren, wird die Administrator/innen-Rolle benötigt.

![Die Einstellungen der Seitenmenüoptionen mit der Option für Webseite ausgewählt.](./assets/find-plugins.png)

1. Gehen Sie zu Einstellungen > Website > Plugins
2. Suchen Sie unter den installierten Plugins nach dem Schnelleinreichungs-Plugin.  Wenn es dort gelistet ist, springen Sie zu Schritt 8.
3. Wenn Sie das Schnelleinreichungs-Plugin nicht unter den installierten Plugins sehen, gehen Sie auf den Reiter Plugin-Galerie.
4. Klicken Sie auf das Schnelleinreichungs-Plugin. Ein Pop-up-Fenster öffnet sich.
5. Klicken Sie auf "Installieren".  Wenn Sie den Button "Installieren" nicht sehen, müssen Sie eine Person mit der Rolle Administrator/in bitten, das Plugin für Sie zu installieren.
6. Ein Pop-up-Fenster öffnet sich und Sie werden gefragt, ob Sie sich sicher sind, dass Sie das Plugin installieren möchten.  Klicken Sie auf OK und warten Sie bis die Installation abgeschlossen ist.
7. Nachdem das Plugin installiert ist, gehen Sie zurück in den Reiter "Installierte Plugins" und suchen Sie das Schnelleinreichungs-Plugin.
8. Wählen Sie das Kästchen rechts neben dem Plugin-Namen und der Beschreibung aus, um das Plugin zu aktivieren.

![Liste der Import/Export Plugins aus der Registerkarte Installierte Plugins in den Website-Einstellungen.](./assets/enabled-import-plugins.png)

Als Nächstes müssen Sie die Ausgaben erstellen, die die neuen Artikel enthalten sollen, die Sie importieren.

1. Gehen Sie zu Ausgaben > Zukünftige Ausgaben und wählen Sie Ausgabe anlegen aus.
2. Geben Sie die Metadaten für die Ausgabe ein.
3. Wenn die Ausgabe bereits veröffentlicht ist, entfernen Sie das Häkchen bei „Veröffentlicht“.
4. Klicken Sie auf Speichern.
5. Tun Sie dies für alle Ausgaben, für die Sie Artikel hochladen.

![Band 1, Nummer 1, 2017 Ausgabe mit dem Titel "From below" produziert unter zukünftige Ausgaben](./assets/create-issue.png)

Als nächstes können Sie jeden Artikel mit dem Schnelleinreichungs-Plugin importieren.

![Seitenmenü Optionen der Werkzeuge mit Import/Export ausgewählt.](./assets/import-plugins.png)

1. Gehen Sie zu Werkzeuge > Import/Export und wählen Sie Schnelleinreichungs-Plugin.
2. Laden Sie ein Titelbild hoch, wenn Sie eines haben.  Dieses Feld ist optional und kann ignoriert werden.
3. Wählen Sie die Rubrik der Zeitschrift, in der der Artikel erscheinen soll, aus der Dropdown-Liste im Feld Rubrik aus.
4. Geben Sie die Metadaten für den Artikel in die anderen Felder ein. Wenn Sie nicht alle gewünschten Metadatenfelder sehen, gehen Sie zu Workflow-Einstellungen > Einreichung > Metadaten um zu konfigurieren, welche Felder in den Einreichungen enthalten sein sollen.
5. Unter Liste der Beiträger/innen klicken Sie auf Beiträger/in hinzufügen, um die Namen der Autor/innen und anderer Beitragender des Artikels einzutragen.
6. Klicken Sie unter Fahnen auf Fahne hinzufügen, um eine PDF-Datei des Artikels hochzuladen.  Es öffnet sich ein Pop-up-Fenster, in dem Sie die Fahnenbezeichnung und die Sprache der Fahne eingeben können.  Sobald Sie auf Speichern klicken, öffnet sich ein weiteres Fenster, in dem Sie Artikel-Bestandteil auswählen und die Datei hochladen können.
7. Am Ende des Schnelleinreichnungs-Plugin-Formulars können Sie auswählen, ob Sie den Artikel, den Sie hinzufügen, sofort publizieren oder unveröffentlicht lassen möchten, falls Sie ihn später veröffentlichen möchten. Wenn Sie **Veröffentlicht** wählen, müssen Sie die Ausgabe auswählen, in der Sie veröffentlichen möchten und das **Veröffentlichungsdatum** eingeben. Sie können optional auch Seitenzahlen und Rechte eingeben.
8. Wenn Sie alle Daten für den Artikel eingegeben haben, klicken Sie auf Speichern.

![Einreichungsformular bei QuickSubmit.](./assets/quick-submit-plugin-2.png)

DOIs werden mit dem Schnelleinreichungs-Plugin nicht hinzugefügt. Stattdessen müssen Sie diese separat hinzufügen.

Um bereits zugewiesene DOIs zu Artikeln hinzuzufügen:

1. Aktivieren und konfigurieren Sie das DOI-Plugin, so dass Sie einen individuellen DOI-Suffix für jedes publizierte Element eingeben müssen.
2. Nachdem Sie den Artikel mit dem Schnelleinreichungs-Plugin hochgeladen haben, klicken Sie auf „Zur Einreichung gehen“, um zum Einreichungsdatensatz zu gelangen. Oder gehen Sie zum Einreichungsdatensatz des Artikels über das Einreichungs-Dashboard.
3. Öffnen Sie Metadaten oben rechts und gehen Sie zum Reiter Identifier.
4. Geben Sie das DOI-Suffix für den Artikel ein.
5. Klicken Sie auf Speichern und dann erneut speichern, um die DOI zuzuweisen.
6. Wenn Sie DOIs normalerweise nach einem Standardmuster zuweisen, konfigurieren Sie das DOI-Plugin entsprechend, nachdem Sie DOIs zu Artikeln hinzugefügt haben, die Sie mit dem Schnelleinreichungs-Plugin hochgeladen haben.

Artikeln neue DOIs zuweisen:

1. Stellen Sie sicher, dass das DOI-Plugin aktiviert und konfiguriert ist.
2. Nachdem Sie den Artikel mit dem Schnelleinreichungs-Plugin hochgeladen haben, klicken Sie auf „Zur Einreichung gehen“, um zum Einreichungsdatensatz zu gelangen. Oder gehen Sie zum Einreichungsdatensatz des Artikels über das Einreichungs-Dashboard.
3. Öffnen Sie Metadaten oben rechts und gehen Sie zum Reiter Identifier. Sie sollten eine Vorschau der DOI sehen, die zugewiesen wird, und ein markiertes Kästchen neben „DOI diesem Artikel zuweisen“.
4. Klicken Sie auf "Speichern" und die DOI wird zugewiesen.

## Rechte {#permissions}

Mit dem Werkzeug "Artikelrechte zurücksetzen" können Sie die Urheberrechtserklärung und die Lizenzinformationen aller veröffentlichten Artikel zurücksetzen und sie wird auf die aktuellen Standardeinstellungen Ihrer Zeitschrift zurückgesetzt. Seien Sie aufmerksam, wenn Sie dieses Werkzeug verwenden und suchen Sie sich juristischen Rat, wenn Sie nicht sicher sind, welche Rechte Sie an den in Ihrer Zeitschrift veröffentlichten Artikeln haben.

![Option zum Zurücksetzen der Artikelrechte in der Registerkarte Werkzeuge.](./assets/learning-ojs3.2-jm-users-tools-permissions.png)
