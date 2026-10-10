---
book: learning-ojs
version: 3.3
showPageTOC: true
title: Open Journal Systems 3.3 lernen - Administration der Website
---

# Administration der Website

Bei der Installation von OJS haben Sie ein Administrator/innenkonto für die Website erstellt. Wenn Sie sich mit diesem Konto bei OJS anmelden, haben Sie über das Dashboard Zugriff auf die Einstellungen des/der Administrators/Administratorin.

Sie können neue gehostete Zeitschrifteninstanzen erstellen, die Sprachunterstützung für Ihr System verwalten und andere administrative Funktionen ausführen.

Weitere technische Informationen zur Verwaltung einer OJS-Seite, einschließlich Upgrades, E-Mail, Statistiken, Import und Export, finden Sie im [Administrator/innenhandbuch](https://docs.pkp.sfu.ca/admin-guide/en/) (in englischer Sprache).

## Management der Website {#site-management}

Um zum Management der Website zu gelangen, melden Sie sich als Administrator/in an und wählen im linken Menü die Option Administration.

![OJS Administrator/innen Hauptmenü mit 2 Optionen: Management der Website und Administrationsaufgaben.](./assets/learning-ojs3.1-sa-site-admin.png)

### Zeitschriften auf dieser Website

Klicken Sie hier auf Zeitschriften auf dieser Website. Auf der folgenden Seite sehen Sie alle Zeitschriften in dieser OJS-Instanz. In dem Beispiel unten gibt es nur eine einzige.

![OJS gehostetes Zeitschriftenmenü mit einer existierenden Zeitschrift.](./assets/learning-ojs3.1-sa-hosted-journals.png)

Um die vorhandene Zeitschrift zu bearbeiten, klicken Sie auf den blauen Pfeil links neben dem Namen der Zeitschrift. Es werden Optionen zum Bearbeiten, Entfernen oder Aktualisieren der Einstellungen angezeigt.

![Bearbeitungsoptionen für vorhandene Zeitschriften: Bearbeiten, Entfernen, Einstellungsassistent, Benutzer/innen.](./assets/learning-ojs3.1-sa-hosted-journals-edit.png)

Mit **Bearbeiten** können Sie den Titel, die Beschreibung oder den Pfad ändern.

![Bearbeitungsbildschirm für vorhandene Zeitschriften mit den Feldern Titel, Beschreibung und Pfad.](./assets/learning-ojs-3-ch4-hosted-journals-edit-modal.png)

Mit **Entfernen** können Sie die Zeitschrift aus der Instanz löschen. Sie werden aufgefordert, zu bestätigen, dass Sie dies wirklich tun wollen, da es nicht rückgängig zu machen ist.

![Bestätigungsbildschirm zum Löschen einer Zeitschrift.](./assets/learning-ojs-3-ch4-hosted-journals-remove.png)

**Der Einstellungsassistent** führt Sie zu den verschiedenen Einstellungsoptionen für diese Zeitschrift.

Mit der Funktion „Massen-E-Mails einschränken“ kann der/die Zeitschriftenverwalter/in den Versand von Massen-E-Mails an bestimmte Rollen deaktivieren. Die Massen-E-Mail-Funktion kann unter [Einstellungen der Website > Massen-E-Mails aktiviert werden](#bulk-emails). Ein/e Administrator/in kann keine Massen-E-Mails an Rollen senden, die Sie unter der Einstellung „Rollen deaktivieren" auswählen. Verwenden Sie diese Einstellung, um den falschen Gebrauch der E-Mail-Benachrichtigungsfunktion einzuschränken. So kann es beispielsweise sicherer sein, Massen-E-Mails an Leser/innen, Autor/innen oder andere große Benutzer/innengruppen zu deaktivieren, die dem Erhalt solcher E-Mails nicht zugestimmt haben.

![Einstellungsassistent mit der Registerkarte "Massen-E-Mails einschränken" ausgewählt.](./assets/learning-ojs3.3-admin-restrict-bulk-emails.png)

Die übrigen Einstellungen werden in den jeweiligen Kapiteln im Detail erläutert.

![Einstellungsassistent mit der Registerkarte "Impressum" ausgewählt.](./assets/learning-ojs-3-ch4-hosted-journals-settings-wiz.png)

Unter **Benutzer/innen** können Sie die mit dieser Zeitschrift verbundenen Benutzer/innen hinzufügen und verwalten.

![Registerkarte "Benutzer/innen" mit einer Liste aktueller Benutzer.](./assets/learning-ojs3.1-sa-hosted-journals-users.png)

Wenn Sie sich wieder auf der Seite "Zeitschriften auf dieser Website" befinden, können Sie den Link "Eine Zeitschrift einrichten" verwenden, um eine neue Zeitschrift zu dieser OJS-Instanz hinzuzufügen. Füllen Sie im daraufhin angezeigten Formular die Felder mit den neuen Informationen aus.

![Bildschirm "Eine Zeitschrift einrichten" mit den Feldern Titel, Beschreibung und Pfad.](./assets/learning-ojs-3-ch4-hosted-journals-create.png)

> Hinweis: Wenn die neue Zeitschrift noch nicht sichtbar sein soll, deaktivieren Sie das Kontrollkästchen _Einstellen, dass diese Zeitschrift öffentlich auf der Website auftaucht._.

### Einstellungen der Website

Dieser Bereich wird angezeigt, wenn Sie zwei oder mehr Zeitschriften haben. In dem Bereich können Sie Informationen zu Ihrer gesamten OJS-Instanz hinzufügen, nicht zu einzelnen Zeitschriften.

#### Einrichtung der Website

Dies umfasst den Namen Ihrer Webseite, ein Logo, eine einleitende Erklärung zu Ihrer Webseite, eine Fußzeile, eine Weiterleitungsoption (wenn Sie nur eine Zeitschrift auf dieser Installation haben wollen), Kontaktinformationen, eine Mindestpasswortlänge für registrierte Benutzer/innen, Stylesheet- und Designoptionen sowie eine Seitenleistenverwaltung.

Zu einem späteren Zeitpunkt haben Sie die Möglichkeit, Einzelheiten zu den einzelnen Zeitschriften anzugeben.

![OJS Admin-Menü mit ausgewählter Registerkarte "Einrichtung der Website".](./assets/learning-ojs3.1-sa-site-settings.png)

#### Sprachen

OJS ist als mehrsprachiges System konzipiert, das es ermöglicht, Zeitschriften in einer Vielzahl von Sprachen auf einer einzigen Webseite zu hosten. Bei der Installation von OJS können Sie eine oder mehrere Sprachen für Ihre Seite auswählen.

Der Administrator/in kann die Standardsprache der Website festlegen und zusätzliche Regionaleinstellungen installieren, um andere Sprachen für die Nutzung durch Zeitschriften verfügbar zu machen. Zeitschriftenverwalter/innen können dann ihre eigenen Spracheinstellungen unter Website-Einstellungen > Einrichtung > Sprachen verwalten. Weitere Informationen finden Sie im Kapitel [Website-Einstellungen](./settings-website).

Unter Administration > Einstellungen der Website > Sprachen können Sie eine Liste der auf Ihrer Website installierten Sprachen einsehen, Sprachen aktivieren und eine beliebige Sprache als primäre Regionaleinstellung festlegen. Das ist die Sprache, die die Benutzer/innen beim ersten Besuch der Website zuerst sehen.

![OJS Admin-Menü mit ausgewählter Registerkarte "Sprachen".](./assets/learning-ojs3.1-sa-languages.png)

Um eine andere Sprache zu installieren:

1. Klicken Sie auf Regionaleinstellung installieren
2. Markieren Sie die Regionaleinstellung, die Sie installieren möchten
3. Klicken Sie auf Speichern

Nach der Installation der neuen Regionaleinstellung müssen Sie diese unter Einstellungen der Website > Einrichtung der Website > Sprachen aktivieren.  Die weitere Konfiguration der verfügbaren Sprachen auf der Webseite kann in den einzelnen Zeitschriften unter Einstellungen > Website > Einrichtung > Sprachen von einem/einer Zeitschriftenverwalter/in vorgenommen werden. Weitere Informationen finden Sie im Kapitel [Website-Einstellungen](./settings-website).

OJS 3 verfügt noch nicht über so viele Übersetzungen wie OJS 2, aber wir gehen davon aus, dass im Laufe der Zeit weitere Übersetzungen hinzukommen werden. Beiträge sind immer willkommen.

#### Plugins

Hier können Sie verschiedene Plugins aktivieren oder deaktivieren, sodass die Plugins für alle Zeitschriften auf dieser OJS-Instanz verfügbar sind (oder nicht).

![OJS Admin-Menü mit ausgewählter Registerkarte "Plugins".](./assets/learning-ojs3.1-sa-plugins.png)

#### Navigationsmenüs

In diesem Bereich können Sie die Menüs der übergeordneten Seite ändern. Mehr über die Konfiguration von Menüs erfahren Sie im Kapitel Website-Einstellungen.

![OJS Admin-Menü mit ausgewählter Registerkarte "Navigationsmenüs".](./assets/learning-ojs3.1-sa-menus.png)

#### Massen-E-Mails

OJS 3.3 bietet die Möglichkeit, Massen-E-Mails an mehrere Benutzer/innengruppen einer Zeitschrift auf einmal zu senden. Siehe [Benutzer/innen und Rollen > E-Mails an Benutzer/innen schreiben](./users-and-roles#email-users). Als Administrator/in können Sie in den Einstellungen der Website die gehosteten Zeitschriften auswählen, die Massen-E-Mails senden dürfen.

Beachten Sie, dass der Missbrauch dieser Funktion zum Versenden unerwünschter E-Mails in einigen Ländern gegen Anti-Spam-Gesetze verstößt und dazu führen kann, dass die E-Mails auf Ihrem Server als Spam blockiert werden. Holen Sie technischen Rat ein, bevor Sie diese Funktion aktivieren und ziehen Sie in Erwägung, sich mit anderen Zeitschriftenverwaltern/innen zu beraten, um sicherzustellen, dass die Funktion angemessen genutzt wird.

![OJS Admin-Einstellungen mit Registerkarte "Massen-E-Mails" ausgewählt.](./assets/learning-ojs3.3-site-settings-bulk-emails.png)

Es ist möglich, den Versand von Massen-E-Mails an bestimmte Rollen für einzelne Zeitschriften unter [Zeitschriften auf dieser Website] (#hosted-journals) > Einstellungsassistent zu deaktivieren.

### Nächste Schritte

Nachdem Sie eine Zeitschrift erstellt und die Einstellungen der Website konfiguriert haben, sollten Sie ein Benutzer/innenkonto für den/die Zeitschriftenverwalter/in oder den/die Redakteur/in einrichten - siehe Kapitel [Benutzer/innen und Rollen](./users-and-roles.md).

<hr />

## Administrationsaufgaben {#administrative-functions}

Dieser Abschnitt enthält detaillierte Informationen über den Server, auf dem Ihre OJS-Instanz läuft.

![OJS Aministrator/innen Hauptmenü mit 2 Optionen: Management der Webseite und Administrationsaufgaben.](./assets/learning-ojs3.1-sa-admin-functions.png)

### Systeminformationen

In diesem Abschnitt finden Sie detaillierte Informationen über den Server, auf dem Ihre Instanz läuft.

![Systeminformationsbildschirm mit aktueller Version, bisherigen Versionen und Serverinformationen.](./assets/learning-ojs3.1-sa-sysinfo.png)

Die OJS-Versionsinformationen zeigen an, welche Version derzeit installiert ist, sowie Ihre bisherigen Versionen einschließlich aller Upgrades. Sie können auf den Link "Nach Aktualisierungen suchen" klicken, um zu sehen, ob Sie die neueste Version von OJS verwenden.

Die Serverinformationen enthalten Details über die Serverumgebung, auf der Ihre OJS-Instanz läuft.

Der Abschnitt OJS-Konfiguration zeigt alle Konfigurationsoptionen und ihre Werte an, wie sie in _config.inc.php_ stehen.

Weitere Informationen über die Konfigurationsparameter von _config.inc.php_ finden Sie in der Datei selbst.

Der letzte Abschnitt auf dieser Seite zeigt zusätzliche Serverinformationen an: Ihr Betriebssystem, die PHP-Version, Server- und Datenbankinformationen. Sie können sich auch erweiterte PHP-Informationen anzeigen lassen, indem Sie auf den Link "Ausführliche Informationen zu PHP" klicken (hier wird die Ausgabe von `phpinfo()` angezeigt).

All diese Informationen können bei einer Fehlersuche nützlich sein.

### Benutzer/innensitzungen schließen

Wenn Sie auf _Benutzer/innensitzungen schließen_ klicken, werden alle aktiven Benutzer/innensitzungen im System sofort gelöscht, sodass sich jede/r Benutzer/in, der/die derzeit angemeldet ist, erneut am System anmelden muss. Dies kann vor einem Upgrade nützlich sein, um sicherzustellen, dass alle Benutzer/innen abgemeldet sind.

### Den Datenspeicher leeren

Wenn Sie auf _Den Datenspeicher leeren_ klicken, werden alle zwischengespeicherten Daten gelöscht, einschließlich Regionaleinstellungsinformationen, Hilfe-Cache und Such-Cache. Diese Funktion kann nützlich sein, um zu erzwingen, dass Daten neu geladen werden, nachdem Anpassungen vorgenommen wurden.

### Den Vorlagenspeicher leeren

Wenn Sie auf _Den Vorlagenspeicher leeren_ klicken, werden alle zwischengespeicherten Versionen von HTML-Vorlagen gelöscht. Diese Funktion kann nützlich sein, um das Neuladen von Vorlagen zu erzwingen, nachdem Anpassungen vorgenommen wurden.

### Logdateien zur Ausführung geplanter Aufgaben löschen

Wenn geplante Aufgaben für Ihre Zeitschrift aktiviert wurden, können Sie durch Klicken auf _Logdateien zur Ausführung geplanter Aufgaben löschen_ die Ausführungsprotokolldateien der Aufgaben von Ihrem Server löschen. Die Ausführungsprotokolldateien enthalten Datumsangaben, die sich auf bereits abgeschlossene geplante Aufgaben beziehen (z. B. das Versenden von automatischen E-Mails zur Erinnerung an die Begutachtung).
