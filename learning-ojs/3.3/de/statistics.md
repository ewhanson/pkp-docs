---
book: learning-ojs
version: 3.3
showPageTOC: true
title: Open Journal Systems 3.3 lernen - Statistiken
---

# Statistiken

Mit den Statistikfunktionen von OJS können Sie verschiedene Zahlen zur Aktivität, zum Zugriff und zum Herunterladen von verschiedenen Aspekten Ihrer Website anzeigen, einschließlich der Aufrufe von Artikeln und Zusammenfassungen, der Abonnementaktivität, der redaktionellen und der Begutachtungsaktivität sowie der nach Rollen getrennten Nutzer/innenzahlen. Es gibt auch einen Berichtsgenerator, mit dem Sie aus einigen der verfügbaren Daten verschiedene Berichte erstellen können.

In diesem Abschnitt werden die in OJS verfügbaren Statistikberichte/Visualisierungswerkzeuge und ihre Verwendung beschrieben. Wenn Sie sich für die Verwaltung von Statistiken als Systemadministrator/in interessieren, einschließlich der Konfiguration des Statistik-Frameworks, der Verwaltung von früheren Statistiken und Statistiken in OJS 2 sowie der Fehlerbehebung bei Statistiken, lesen Sie bitte die [Dokumentation zu Statistiken im PKP Administrator's Guide](https://docs.pkp.sfu.ca/admin-guide/en/statistics) (in englischer Sprache).

Für ein Erklärungsvideo zu den Statistiken in OJS siehe [Zeitschrift in OJS 3.3 einrichten. Modul 13: Statistik](https://www.youtube.com/watch?v=fU1orCK7GSM&list=PLg358gdRUrDVTXpuGXiMgETgnIouWoWaY) Video (englischsprachig) unten.

[![Einrichten einer Zeitschrift in OJS 3.3. Modul 13: Statistik](https://img.youtube.com/vi/fU1orCK7GSM/0.jpg)](https://www.youtube.com/watch?v=fU1orCK7GSM\&list=PLg358gdRUrDVTXpuGXiMgETgnIouWoWaY)

## Definitionen {#definitions}

Die folgenden Definitionen können Ihnen helfen, die von OJS erfassten Statistiken zu verstehen.

- **Abstract-Seite**: Die Landing-Page für einen Artikel, die den Titel, die Autor/inneninformationen, die Artikelzusammenfassungen, den DOI und Links zu den Volltextfahnen der Artikel enthält.  Wird auch als „Artikelseite“ oder „Landing Page“ bezeichnet. Diese Seite wird in der Regel als Referenzseite des Artikels für DOIs oder andere Hyperlinks verwendet: Die DOIs von Crossref werden zu den Seiten mit den Artikelzusammenfassungen aufgelöst, im Gegensatz zum Beispiel zu den Druckfahnen, wie es die meisten anderen Indexierungsdienste tun.
- **Artikelansicht**: Im Rahmen der Statistik bedeutet jede Bezugnahme auf eine „Artikelansicht“ eine einzelne Ansicht der Artikelzusammenfassung durch eine/n Besucher/in. Dabei handelt es sich nicht um eine Gesamtzählung aller Artikel- und Druckfahnenaufrufe, sondern nur um die Aufrufe der Artikelzusammenfassungen.
- **Druckfahnenansicht**: Im Rahmen der Statistik bedeutet jeder Verweis auf eine „Druckfahnenansicht“ eine einzelne Ansicht oder einen einzelnen Download einer bestimmten Druckfahnendatei durch eine/n Besucher/in. Dies wird auch als „Download“ bezeichnet. Dabei handelt es sich nicht um eine Gesamtzahl aller Druckfahnenaufrufe - wenn es mehrere Dateien für einen Artikel gibt (z. B. eine HTML-Datei, eine PDF-Datei usw.), wird für jede einzelne Druckfahne eine eigene Zählung vorgenommen. OJS unterscheidet in der Metrik-Tabelle nicht zwischen Downloads und Ansichten; Downloads werden als Ansichten gezählt.
- **Mehrfachklicks**: der \(versehentliche oder böswillige\) Versuch, die Nutzungszahlen zu erhöhen, indem eine abstrakte Seite oder eine Druckfahnendatei mehrere Male in kurzer Folge angeklickt wird. OJS identifiziert und entfernt diese Versuche aus den Nutzungsstatistiken gemäß dem COUNTER Code of Practice.
- **COUNTER Code of Practice**: eine Reihe von Praktiken, die von COUNTER entwickelt wurden, um eine Möglichkeit zu schaffen, über Nutzungsstatistiken für elektronische Ressourcen auf einheitliche Weise zu berichten. Der Code enthält Regeln dafür, was als Ansicht gezählt werden sollte, einschließlich spezifischer Regeln für die automatische Durchsuchung der Website und den Missbrauch durch Mehrfachklicks. OJS filtert die Statistiken anhand dieser Regeln. Ferner ist anzumerken, dass PKP Teil der COUNTER-Arbeitsgruppe Bots und Crawler ist.
- **Robots, Crawler, Bots**: nicht-menschliche Website-Besucher, die dennoch Artikeldaten ansehen und herunterladen können. Sie werden in der Regel vom Server als solche erkannt. OJS zählt sie gemäß dem COUNTER Code of Practice nicht in den Nutzungsstatistiken.

## Artikel {#articles}

OJS bietet Redakteur/innen und Zeitschriftenverwalter/innen die Möglichkeit, grafische und tabellarische Darstellungen der Artikelnutzung anzuzeigen, einschließlich Artikelzusammenfassungen und Volltext-Downloads.

Die visuellen Statistiken finden Sie unter „Statistiken“ auf der linken Menüleiste, indem Sie auf „Artikel“ klicken.

![OJS Menü mit der Option „Artikel“, die im linken Menü unter „Statistik“ hervorgehoben ist.](./assets/ojs-statsmenu.png)

Die Artikelstatistiken zeigen die Aufrufe der Artikel sowohl in grafischer als auch in tabellarischer Form. Die visuelle Grafik kann auf Monats- oder Tagesansicht umgestellt werden. Im Tabellenformat können Sie die Gesamtzahl in aufsteigender oder absteigender Reihenfolge filtern.

![Beispiel eines Diagramms für die Aufrufe von Zusammenfassungen, das mit dem Statistik-Tool für Artikel erstellt wurde](./assets/abstract-views.png)

![Beispiel für eine Artikel-Detailtabelle, die durch das Statistikwerkzeug für Artikel erstellt wurde.](./assets/article-details.png)

Über das Kalendersymbol in der rechten oberen Ecke Ihres Dashboards können Sie die Ansicht der Artikel auf die letzten 30 Tage, die letzten 90 Tage, die letzten 12 Monate, alle Daten oder einen benutzer/innendefinierten Datumsbereich ändern.

![Der Kalender, der für die Auswahl des Datumsbereichs verwendet wird.](./assets/calendar-range-articles.png)

Über das Filtersymbol in der rechten oberen Ecke Ihres Dashboards haben Sie die Möglichkeit, die Artikel nach den Rubriken der Zeitschrift zu filtern.

![Filtermöglichkeit, die Artikel nach Rubriken auszuwählen.](./assets/article-filters.png)

Sie haben auch die Möglichkeit, die Statistiken eines bestimmten Artikels nach Titel, Autor/in oder ID zu durchsuchen, indem Sie die Suchfunktion unter Artikeldetails verwenden.

![Die Suchleiste um bestimmte Artikelstatistiken zu finden.](./assets/article-details-search.png)

## Redaktionelle Aktivität {#editorial-activity}

Dieser Abschnitt enthält Statistiken über den redaktionellen Arbeitsablauf, wie z. B. die Anzahl der eingegangenen Beiträge, die Tage bis zur ersten redaktionellen Entscheidung sowie die Annahme- und Ablehnungsraten. Sie können diese Statistiken mit Hilfe eines benutzer/innendefinierten Datumsbereichs filtern, um z. B. die Anzahl der angenommenen Artikel in einem 12-Monats-Zeitraum zu ermitteln.

![Beispiel für redaktionelle Statistiken.](./assets/editorial-activity.png)

Bei der Betrachtung der Daten in diesen Berichten gibt es einige wichtige Dinge zu beachten:

- Veröffentlichte Einreichungen innerhalb eines Datumsbereichs zählen nur das Datum der Erstveröffentlichung und nicht spätere Versionen.
- Bei den Tagen bis zur Entscheidung wird ein Schwellenwert von 80 % verwendet, d. h. die aufgeführten Daten bedeuten, dass 80 % der Einreichungen eine Entscheidung innerhalb von X Tagen erhalten haben.
- Bei den Annahme- und Ablehnungsquoten werden nur Beiträge gezählt, die eine Annahme-/Ablehnungsentscheidung erhalten haben, d. h. sie schließen Beiträge aus, die sich noch in der Warteschlange befinden.
- Wird ein Datumsbereich angegeben, werden nur Beiträge gezählt, die innerhalb dieses Datumsbereichs eingereicht UND angenommen/abgelehnt wurden. So wird z. B. ein Beitrag, der vor dem Datumsbereich eingereicht wurde, aber innerhalb des Datumsbereichs eine Annahme-/Ablehnungsentscheidung erhalten hat, nicht gezählt. Aus diesem Grund ist es am besten, lange Datumsbereiche und ältere Datumsbereiche zu verwenden, um genaue Annahme-/Ablehnungsraten zu erhalten.

Ein redaktioneller Tätigkeitsbericht wird monatlich erstellt und kann per E-Mail an Redakteur/innen und Rubrikredakteur/innen gesendet werden. In den Standardeinstellungen erhalten alle Verwalter/innen und Rubrikredakteur/innen keine monatlichen Berichte; Sie können sich jedoch dafür entscheiden, indem Sie zu Benutzer/innenprofil > Benachrichtigungen gehen und das Kontrollkästchen deaktivieren, das die automatische E-Mail abstellt.

## Benutzer/innen {#users}

Dieser Abschnitt enthält Informationen über neue Benutzer/innen- und Rollenregistrierungen innerhalb eines bestimmten Zeitraums. Die Spalte „Gesamt“ gibt nicht die Gesamtzahl der erstellten Konten an, sondern zeigt an, wie viele Benutzer/innen diese Rolle derzeit im System haben. Wenn ein/ bestehende/r Benutzer/in eine neue Rolle erhält, wie z. B. ein/e registrierte/r Autor/in, der/die zum/zur Gutachter/in wird, spiegelt sich diese Erweiterung der Gesamtzahl der Gutachter/innen im System in den Daten durch eine Erhöhung der Anzahl der Gutachter/innen, aber keine Änderung der Gesamtzahl der Benutzer/innen wider.

![Beispielstatistik für Benutzer/innen.](./assets/users.png)

## Berichtserstellung {#report-generator}

Die Seite Berichtserstellung ermöglicht den Zugriff auf eine Vielzahl von Berichten aus Ihrer Zeitschrift.

![Die Liste der Berichte auf der Berichtserstellungsseite in OJS, weiter unten detailliert.](./assets/report-generator.png)

Das System generiert Berichte, die Details zur Nutzung der Website und zu Beiträgen über einen bestimmten Zeitraum hinweg aufzeichnen. Diese Berichte lassen sich grob in Nutzungsberichte, die Nutzungskennzahlen zur Leser/innenschaft enthalten, und Inhaltsberichte, die Daten zum jeweiligen Artikel (z. B. Informationen zu Begutachtungen) liefern, unterteilen. Die Berichte werden im CSV-Format erstellt, das eine externe Software zur Ansicht erfordert.

- Nutzungsstatistik-Bericht: Zeigt detaillierte tägliche Nutzungsmetriken für alle Artikel, Artikeldateien, Ausgaben und Websiteaufrufe/Downloads. Enthält auch Daten zum Land des/der Besuchers/Besucherin, sofern diese protokolliert werden. Weitere Informationen und Beispiele finden Sie im Abschnitt "Nutzungsstatistik-Bericht" weiter unten. (Nutzung)
- Abonnement-Bericht: Bietet Informationen über alle individuellen und institutionellen Abonnements. Diese Berichtsoption ist nur verfügbar, wenn Abonnements für die Zeitschrift aktiviert sind. (Inhalt)
- Artikel-Bericht: Liefert eine Tabelle mit allen veröffentlichten Artikeln. (Inhalt)
- COUNTER-Berichte: Bietet COUNTER-Berichte für alle Zeitschriften in der OJS-Instanz. Bietet monatliche und jährliche Gesamtzahlen für Zusammenfassungen und Druckfahnenansichten. (Nutzung)
- Bericht über Begutachtungen: Bietet Informationen zu allen Artikeln im System, einschließlich der Namen der Begutachter/innen, Begutachtungen und Empfehlungen. (Inhalt)
- Lese-Bericht: Liefert einen Bericht über die Ansicht von Druckfahnen und Artikelzusammenfassungen durch Leser/innen (d. h. wie oft ein PDF für einen Artikel angesehen wurde). (Nutzung)
- Benutzerdefinierten Bericht erzeugen: Anpassbare Version des Berichts zur Nutzungsstatistik, bei der verschiedene Facetten ausgewählt und bestimmte Zeiträume festgelegt werden können. Weitere Informationen und Beispiele finden Sie unter "Benutzer/innendefinierte Berichte erstellen". (Nutzung)

### Nutzungsstatistik-Bericht

Dieser Bericht enthält detaillierte Daten zu den monatlichen Aufrufen der Zeitschriften-Website, der Inhaltsverzeichnisse, der Artikelzusammenfassungen/Landing Pages und der Dateiaufrufe in einem CSV-Format. Er enthält Länderinformationen (falls konfiguriert). Jede Zeile enthält die Gesamtzahl der monatlichen Aufrufe für ein bestimmtes Objekt (Zeitschriften-Webseite, Artikelseite, Druckfahnen oder Inhaltsverzeichnis). Er ist außerdem nach Ländern aufgeschlüsselt, wenn die Länderunterstützung aktiviert und richtig konfiguriert wurde.

**Verwendung für**: Generierung eines vielschichtigen Überblicks über die Nutzung von Inhalten von Monat zu Monat. Er listet die monatlichen Zugriffszahlen für alle Artikel, die Downloads von Artikeldateien, die Aufrufe des Inhaltsverzeichnisses einer Ausgabe und die Aufrufe der Zeitschriften-Website für den angegebenen Zeitraum auf. Der resultierende Bericht muss zusätzlich manuell bearbeitet werden, um aggregierte Ergebnisse zu erhalten.

**Nicht verwenden für**: den Versuch, einen schnellen Nutzungsüberblick zu erhalten, ältere Nutzungsdaten oder Zeitschriften, die über einen sehr großen Datensatz verfügen (aufgrund einer langen Historie, einer hohen Leser/innenschaft oder einer hohen Granularität der Statistiken). Erzeugen Sie stattdessen einen benutzerdefinierten Bericht.

**Besondere Hinweise:**

- Dieser Bericht versucht, den gesamten Nutzungsverlauf zu erfassen für: die Zeitschriften-Website, alle Artikelzusammenfassungen, alle Druckfahnen und alle Inhaltsverzeichnisse der Ausgaben.
- **OJS Version 3.1.1 oder ältere Installationen**: Um die Gefahr einer Überschreitung der Zeitlimits für Downloads zu verringern, enthält dieser Bericht nur 5.000 Datensätze. Wenn Sie viele berichtspflichtige Daten haben, wird dieser Bericht höchstwahrscheinlich nicht alle Daten erfassen. In diesem Fall erzeugen Sie stattdessen einen benutzerdefinierten Bericht über das Plugin und wählen dabei kleinere Datumsbereiche aus. (Diese Einschränkung wurde in OJS 3.1.2. aufgehoben)

**Beispieldaten (der Klarheit halber leicht bearbeitet\):**

\| **ID** | **Type** | **Title** | **Issue** | **Journal** | **Country** | **Month** | **Count** |
\| --- | --- | --- | --- |
\| 1 | Journal | Canadian Journal of Communication | CJC | CA | 201502 | 1678 |  |
\| 112 | Article | Toronto Star Fires Reporter Claire Hoy, Sues Him and TV Stations on Libel Charge | Vol 1, No 3 \(1974\) | CJC | CA | 201502 | 3 |
\| 112 | Article | Toronto Star Fires Reporter Claire Hoy, Sues Him and TV Stations on Libel Charge | Vol 1, No 3 \(1974\) | CJC | US | 201502 | 1 |

Aus dem obigen Beispiel geht hervor, dass im Februar 2015 die Hauptseite der Zeitschrift CJC 1.678 Mal aufgerufen wurde und dass der Artikel „Toronto Star Fires Reporter …“ dreimal aus Kanada und einmal aus den Vereinigten Staaten aufgerufen wurde.

### Lese-Bericht

Dieser Bericht enthält die Aufrufe von Artikelzusammenfassungen und Druckfahnenansichten/Downloads pro Artikel. Diese Nutzungsstatistiken sind nicht nach Mehrfachklicks oder Bot-/Crawler-Aktivitäten gefiltert und können daher im Vergleich zu neueren Statistiken überhöht erscheinen.

Beispieldaten (der Klarheit halber leicht bearbeitet):

In dem Beispiel unten sehen wir, dass Artikel 95, „The Making of the Canadian Media“, 443 Artikelseitenaufrufe und insgesamt 1476 Aufrufe der Druckfahnen hatte. Die PDF-Aufrufe und die Gesamtzahl der Druckfahnenaufrufe sind gleich, da es keine HTML-Aufrufe gab. Bei Artikel 1125, „Digital Networks“, wurde die Zusammenfassung 1821 Mal aufgerufen und die Gesamtzahl der Druckfahnenaufrufe beträgt 8478, was der Summe der HTML- und PDF-Aufrufe entspricht.

****

\| **ID** | **Article Title** | **Issue** | **Date Published** | **Abstract** | **Total Galleys** | **HTML** | **PDF** |
\| --- | --- | --- |
\| 95 | The Making of the Canadian Media | Vol 6, No 1 \(1979\) | 1979-01-03 | 443 | 1476 |   | 1476 |
\| 1125 | Digital Networks | Vol 24, No 4 \(1999\) | 1999-04-01 | 1821 | 8478 | 2093 | 6385 |

### Benutzerdefinierten Bericht erzeugen

Mit dieser Funktion können Sie Ihre eigenen Berichte erstellen. Diese Berichte enthalten detaillierte Daten zu den täglichen Ansichten der Zeitschrift unter Verwendung des vollständigen Datensatzes. Sie können die Ergebnisse nach folgenden Kriterien zusammenfassen:

- Land
- Region
- Stadt
- Monat
- Tag

Statistiken werden für bestimmte Artikeltypen (auch als „Objekte“ bezeichnet) erhoben:

- Downloads von Artikeldateien
- Aufrufe der Abstractseiten von Artikeln
- Aufrufe des Inhaltsverzeichnis der Ausgabe
- Startseiten-Aufrufe

![Das Menü für benutzerdefinierte Berichterstellungen in OJS.](./assets/custom-report-generator1.png)

Sie können die Ergebnisse auch auf bestimmte Zeiträume beschränken.

Dies ist die flexibelste Berichtsoption, die in OJS verfügbar ist, und kann eine sehr detaillierte Datenmenge liefern. Nachfolgend finden Sie einige Beispiele für statistische Fragen, die für Zeitschriften nützlich sein könnten, sowie eine Anleitung, wie Sie einen Bericht zur Beantwortung dieser Fragen mit dieser Funktion erstellen können.

Besondere Hinweise zur benutzerdefinierten Berichtserstellung:

- Je nach der Datenmenge in Ihrem System, den abzurufenden Facetten und der gewählten Zeitspanne kann es vorkommen, dass es dem System nicht gelingt, einen vollständigen Bericht ohne Zeitüberschreitung zu erstellen. Versuchen Sie in diesem Fall, die angeforderte Zeitspanne zu verringern.
- Wenn Sie einen benutzer/innendefinierten Bericht erstellen, erhalten Sie in dem Bericht auch eine Berichts-URL, die Sie speichern können, um den gleichen Berichtsprozess zu wiederholen. Achten Sie darauf, die URL zu kopieren und irgendwo zu speichern, damit Sie Ihre Suche später erneut durchführen können (sie verschwindet, sobald die Seite neu geladen wird).
- Wenn Sie einen Bericht erstellen, der sich auf „gestern“ oder „den aktuellen Monat“ bezieht, verwendet die daraus resultierende Berichts-URL immer ‚gestern‘ oder den „aktuellen Monat“, bezogen auf den Tag, an dem Sie den Bericht ausführen. Wenn Sie also ursprünglich einen Bericht für „gestern“ vor einem Jahr erstellt haben und ihn dann heute ausführen, würde der Bericht für gestern erstellt werden. Wenn Sie jedoch einen bestimmten Datumsbereich angeben, z. B. 1. April - 15. April 2018, wird die resultierende Berichts-URL immer Metriken für diesen spezifischen Bereich ausgeben.
- Beachten Sie, dass die Daten des aktuellen Tages erst am nächsten Tag verfügbar sein werden.
- Der Generator funktioniert wie ein Trichter für Daten. Der Trick besteht darin, die größeren Elemente einzugrenzen (z. B. den Zeitraum), von dort aus auszuwählen, was Sie interessiert (Ausgaben, Artikel usw.), und dann die Daten am Ende zu optimieren (z. B. nach Anzahl der Downloads zu sortieren).
- Der Berichtsgenerator ist am nützlichsten, wenn Sie die erweiterten Einstellungen verwenden. In allen folgenden Beispielen werden die erweiterten Einstellungen verwendet.

#### Beispielbericht: Wie gut hat sich eine bestimmte (d. h. die jüngste) Ausgabe in den letzten Monaten entwickelt?

Mit dieser Abfrage erhalten Sie eine monatliche Zählung, wie viele Druckfahnen von einer bestimmten Ausgabe heruntergeladen worden sind. Sie erhalten eine Spalte für den Monat und die Gesamtzahl für den Monat sowie eine separate Zeile für jeden Monat.

- Wählen Sie unter „Standard-Berichtsvorlagen“ die Option „Downloads von Artikeldateien“ aus der Dropdown-Liste.
- Deaktivieren Sie alle Kontrollkästchen unter „Erzeuge Statistiken nach“.
- Klicken Sie auf die Auswahlmöglichkeit „Monat“ und geben Sie einen Datumsbereich unter „Oder wähle Zeitraum nach“ ein.

![Die benutzerdefinierte Berichtserstellung mit den oben beschriebenen Einstellungen in OJS.](./assets/custom-report-generator10.png)

- Öffnen Sie „Erweiterte Einstellungen“ und wählen Sie unter ‚Spalten‘ nur „Monat“

!["Monat" ausgewählt unter den erweiterten Optionen bei der benutzerdefinierten Berichtserstellung.](./assets/custom-report-generator3.png)

- Es braucht nur eine sehr leichte Filterung der Daten. Wählen Sie die eingereichten Dateien und dann die Druckfahnenformate aus, die Sie in Ihren Bericht aufnehmen möchten. In diesem Beispiel wird nur PDF ausgewählt, aber Sie können auch PDF und HTML auswählen, wenn Ihre Zeitschrift auch Volltext-HTML-Artikel zum Download anbietet. Verwenden Sie Strg+Klick oder cmd+Klick, um mehrere Typen auszuwählen. Geben Sie unter Objekt-ID die Objekt-ID der gewünschten Ausgabe ein, die in der URL der Ausgabe enthalten ist. Eine Ausgabe mit der URL publicknowledgeproject.org/journal/index.php/journal/issue/view/**24** hat zum Beispiel die Objekt-ID 24.

![Eine Muster-Ausgaben-ID wurde in der benutzerdefinierten Berichterstellung eingegeben.](./assets/custom-report-generator4.png)

- Ignorieren Sie die Optionen „Nach geografischem Standort“ und „Sortieren nach“ und klicken Sie auf „Benutzer/innendefinierten Bericht erstellen“.
- Sie erhalten einen sehr einfachen monatlichen Bericht über die Druckfahnen-Downloads für die eine Ausgabe, die für Ihre Zeitschrift von Interesse ist.

![Ergebnisse im .csv-Format, die aus dem oben genannten benutzerdefinierten Bericht zurückgegeben wurden.](./assets/custom-report-generator5.png)

- Speichern Sie die URL unten auf der Seite für Ihre Unterlagen!

#### Beispielbericht: Welches sind die am häufigsten heruntergeladenen Artikel der letzten 5 Jahre?

Dieser Bericht enthält eine Liste der Artikeltitel (und der Ausgaben, aus denen sie stammen), geordnet nach absteigender Anzahl der Downloads.

- Wählen Sie „Downloads von Artikeldateien“ aus dem Dropdown-Menü.
- Deaktivieren Sie alle Kontrollkästchen unter „Erzeuge Statistiken nach:“.
- Wählen Sie die Auswahloption „Monat“ und geben Sie einen Zeitraum ein.

![Die benutzerdefinierte Berichtserstellung mit den oben beschriebenen Einstellungen in OJS.](./assets/custom-report-generator10.png)

- Wählen Sie unter „Spalten“ nur „Artikel“ und „Ausgabe“ aus. Der Typ wird zu einem späteren Zeitpunkt in der Abfrage eingegrenzt.

!["Artikel" und "Ausgabe" ausgewählt in den erweiterten Optionen der benutzerdefinierten Berichtserstellung.](./assets/custom-report-generator6.png)

- Wählen Sie unter Objekttyp „Beitragsdateien“ und wählen Sie alle Druckfahnen-Typen aus, die Sie in die Download-Zählung einbeziehen möchten.

![Die oben beschriebenen Einstellungen in OJS eingetragen](./assets/custom-report-generator7.png)

- Ignorieren Sie die Option „Nach geografischem Standort“ (hier nicht angezeigt).
- „Sortieren nach“ ordnet Ihre Artikel in absteigender Reihenfolge nach der Anzahl der Downloads. Wählen Sie dazu im ersten Dropdown-Feld „Anzahl“ und dann „Absteigend“.

![Pfeile zeigen auf die ersten beiden „Sortieren nach“ - Dropdown-Listen, wobei „Anzahl“ und „Absteigend“ ausgewählt sind](./assets/custom-report-generator8.png)

- Der resultierende Bericht sieht wie folgt aus (gekürzt):

![Ergebnisse im .csv-Format, die aus dem oben genannten benutzerdefinierten Bericht zurückgegeben wurden.](./assets/custom-report-generator9.png)

- Speichern Sie die URL unten auf der Seite für Ihre Unterlagen!

#### Beispiel: Was ist unsere beliebteste Ausgabe?

Diese Abfrage zeigt die Anzahl der Volltext-Downloads für jede Zeitschriftenausgabe an und ordnet die Ergebnisse vom höchsten zum niedrigsten Wert.

- Wählen Sie „Downloads von Artikeldateien“ aus dem Dropdown-Menü.
- Deaktivieren Sie alle Kontrollkästchen unter „Erzeuge Statistiken nach:“.
- Wählen Sie die Auswahloption „Monat“ und geben Sie einen Zeitraum ein.

![Die benutzerdefinierte Berichtserstellung mit den oben beschriebenen Einstellungen in OJS.](./assets/custom-report-generator10.png)

- Klicken Sie unter „Spalten“ auf „Ausgabe“.

!„Ausgabe“ ausgewählt unter den erweiterten Optionen bei der benutzerdefinierten Berichtserstellung.](./assets/custom-report-generator11.png)

- Wählen Sie bei den Filtern unter Objekttyp die Option „Beitragsdateien“ und wählen Sie den/die von Ihrer Zeitschrift verwendeten Typ(en) von Druckfahnendateien aus (verwenden Sie Strg+Klick oder cmd+Klick, um mehrere Typen auszuwählen).

![Die oben beschriebenen Einstellungen in OJS eingetragen](./assets/custom-report-generator7.png)

- Ignorieren Sie die Option „Nach geografischem Standort“ (hier nicht angezeigt).
- „Sortieren nach“ ordnet Ihre Artikel in absteigender Reihenfolge nach der Anzahl der Downloads. Wählen Sie dazu im ersten Dropdown-Feld „Anzahl“ und dann „Absteigend“.

![Pfeile zeigen auf die ersten beiden „Sortieren nach“ - Dropdown-Listen, wobei „Anzahl“ und „Absteigend“ ausgewählt sind](./assets/custom-report-generator8.png)

- Führen Sie Ihren Bericht aus. Sie erhalten folgendes Ergebnis:

![Ergebnisse im .csv-Format, die aus dem oben genannten benutzerdefinierten Bericht zurückgegeben wurden.](./assets/custom-report-generator12.png)

- Vergessen Sie nicht, Ihre URL zu speichern, um sie zu einem späteren Zeitpunkt erneut auszuführen.

#### Beispiel: Aus welchen Ländern werden unsere Artikel heruntergeladen (für einen bestimmten Zeitraum)?

Diese Abfrage zeigt die Gesamtzahlen der Volltext-Downloads nach Land in absteigender Reihenfolge an. Beachten Sie, dass Sie einen bestimmten Zeitraum angeben müssen.

- Wählen Sie „Downloads von Artikeldateien“ aus dem Dropdown-Menü.
- Deaktivieren Sie alle Kontrollkästchen unter „Erzeuge Statistiken nach:“.
- Wählen Sie die Auswahloption „Monat“ und geben Sie einen Zeitraum ein.

![Die benutzerdefinierte Berichterstellung mit den oben beschriebenen Einstellungen in OJS.](./assets/custom-report-generator10.png)

- Wählen Sie unter „Spalten“ nur „Zeitschrift“ und „Land“ aus. Sie können Strg+Klick oder cmd+Klick verwenden, um mehrere Elemente auszuwählen. Der Typ wird zu einem späteren Zeitpunkt in der Abfrage eingegrenzt.

!["Zeitschrift" und "Land" ausgewählt in den erweiterten Optionen der benutzerdefinierten Berichterstellung.](./assets/custom-report-generator13.png)

- Wählen Sie bei den Filtern unter Objekttyp die Option „Beitragsdateien“ und wählen Sie den/die von Ihrer Zeitschrift verwendeten Typ(en) von Druckfahnendateien aus (verwenden Sie Strg+Klick oder cmd+Klick, um mehrere Typen auszuwählen).

![Die oben beschriebenen Einstellungen in OJS eingetragen](./assets/custom-report-generator7.png)

- „Sortieren nach“ ordnet Ihre Artikel in absteigender Reihenfolge nach der Anzahl der Downloads. Wählen Sie dazu im ersten Dropdown-Feld „Anzahl“ und dann „Absteigend“.

![Pfeile zeigen auf die ersten beiden „Sortieren nach“ - Dropdown-Listen, wobei „Anzahl“ und „Absteigend“ ausgewählt sind](./assets/custom-report-generator8.png)

- Führen Sie den Bericht aus.
- Vergessen Sie nicht, Ihre URL zu speichern, um sie zu einem späteren Zeitpunkt erneut auszuführen.

![Ergebnisse im .csv-Format, die aus dem oben genannten benutzerdefinierten Bericht zurückgegeben wurden.](./assets/custom-report-generator14.png)

### Nutzungsstatistiken für Leser/innen anzeigen

In OJS 3 können Sie die Nutzungsstatistiken eines Artikels für das laufende Jahr als Diagramm auf der Artikelseite anzeigen, indem Sie das Nutzungsstatistik-Plugin verwenden, wie in diesem Bild zu sehen.

![Ein Beispielartikel mit einem Diagramm der monatlichen Downloads, das unter der Zusammenfassung angezeigt wird.](./assets/reader-statistics.png)

So aktivieren Sie das Nutzungsstatistik-Plugin:

1. Gehen Sie zu Einstellungen &gt; Website &gt; Plugins.
2. Suchen Sie unter Allgemeine Plugins das **Nutzungsstatistik-Plugin**.
3. Aktivieren Sie das Kästchen rechts neben der Plugin-Beschreibung.

So konfigurieren Sie das Nutzungsstatistik-Plugin:

1. Gehen Sie zu Einstellungen &gt; Website &gt; Plugins.
2. Suchen Sie unter Allgemeine Plugins das **Nutzungsstatistik-Plugin**.
3. Klicken Sie auf den blauen Pfeil links neben dem Plugin-Namen, damit Links unter dem Plugin erscheinen.
4. Klicken Sie auf **Einstellungen**.
5. Scrollen Sie in dem sich öffnenden Popup-Fenster bis zum unteren Rand zum Abschnitt **Statistikanzeigeoptionen**.
6. Aktivieren Sie das Kontrollkästchen neben **Einreichungsstatistikdiagramm für Leser/innen anzeigen**.
7. Darunter können Sie auswählen, ob Sie die Statistiken als Balken- oder Liniendiagramm anzeigen möchten, und die maximale Anzahl der Monate angeben, für die die Nutzung angezeigt werden soll.
8. Klicken Sie **Speichern**.

![Die optionalen Statistik-Kontrollkästchen, mit denen die Nutzer/innen die Erfassung von Stadt- oder Regionaldaten aktivieren/deaktivieren und die Statistiken für die Leser/innen sichtbar machen können](./assets/usage-stats-plugin-configuration-basic.png)

Bitte beachten Sie folgendes:

- Nutzungsstatistiken können nur für das laufende Jahr angezeigt werden. Das Plugin wird zu Beginn eines jeden Jahres zurückgesetzt.
- Die angezeigte Statistik gibt an, wie oft ein Artikel heruntergeladen wurde.
