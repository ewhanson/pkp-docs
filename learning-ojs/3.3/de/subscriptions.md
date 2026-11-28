---
book: learning-ojs
version: 3.3
showPageTOC: true
title: Open Journal System 3.3 lernen - Abonnements
---

# Abonnements

OJS erlaubt es Ihnen einige oder alle Ihre Inhalte auf Abonnent/innen zu beschränken. Um Abonnements zu aktivieren, gehen Sie zuerst auf [Einstellungen > Vertrieb > Zugriff](./settings-distribution.md).

## Abonnementrichtlinien {#subscription-polices}

Geben Sie auf dieser Seite Einzelheiten zu Ihren Abonnement-Richtlinien an.

![Die Registerkarte für individuelle Abonnements im Abonnement-Menü.](./assets/learning-ojs3.3-jm-subscriptions-policies.png)

- **Abonnementverwalter/in**: Fügen Sie persönliche Daten für die verantwortliche Person hinzu.
- **Abonnementinformationen**: Fügen Sie Informationen zu Ihrem Abonnementmodell hinzu, die auf der Webseite der Zeitschrift angezeigt werden sollen.
- **Auslaufen des Abonnements**: Legen Sie fest, ob ehemalige Abonnent/innen weiterhin Zugriff auf ältere Inhalte haben sollen.
- **Erinnerung an Auslaufen des Abonnements**: Konfigurieren Sie automatische Verlängerungserinnerungen.
- **Online-Zahlungsbenachrichtigungen**: Informieren Sie den/die Abonnementverwalter/in über Zahlungsaktivitäten.
- **Open-Access-Option für Abonnementzeitschriften**: Wählen Sie ggf. die Anzahl der Monate für die Zugriffsbeschränkung. Ältere Inhalte werden automatisch zugänglich gemacht.

## Abonnement-Arten {#subscription-types}

Der nächste Schritt bei der Einrichtung der Abonnementverwaltung besteht darin, die Typen von Abonnements festzulegen, die die Zeitschrift anbietet.

![Die Registerkarte Abonnementstypen im Abonnementmenü](./assets/learning-ojs3.3-jm-subscriptions-types.png)

Zeitschriften bieten in der Regel individuelle Abonnements und institutionelle Abonnements an. Einige Zeitschriften haben spezielle Angebote für Mitglieder einer Organisation oder für Studierende. OJS unterstützt die Verwaltung von Print- und/oder Online-Abonnements. Es können mehrere Abonnementtypen erstellt werden, um längere Zeiträume abzudecken (12 Monate, 36 Monate).

Wählen Sie **Einen neuen Abonnementtyp erstellen**, um ein neues Abonnement hinzuzufügen.

![Einen neuen Abonnementtyp erstellen-Fenster.](./assets/learning-ojs3.3-jm-subscriptions-types-create.png)

- **Name des Abonnementtyps**: Geben Sie diesem neuen Abonnementtyp einen eindeutigen Namen (z. B. Student).
- **Beschreibung**: Geben Sie eine kurze Beschreibung an, die auf der Webseite erscheinen wird.
- **Kosten**: Wählen Sie die Währungsart und den Betrag.
- **Format**: Wählen Sie das zutreffende Format (z. B. online).
- **Dauer**: Geben Sie die Anzahl der Monate an, die dieser Abonnementtyp abdeckt (z. B. 12).
- **Abonnements**: Geben Sie an, ob dieser Typ Einzelpersonen oder Institutionen umfasst.
- **Optionen**: Wählen Sie die passenden Optionen (falls vorhanden).

## Zahlweisen {#payment-types}

{% include video.html id="9r0mRqtNVuU" provider="youtube" title="Module 11: Distribution. Unit 3: Payments"%}

Dieses englischsprachige Video der PKP-School erklärt, wie Sie verschiedene Zahlungsarten in Ihrer Zeitschrift einrichten. Weitere Videos dieser Reihe finden Sie auf dem [PKP-YouTube-Kanal](https://www.youtube.com/playlist?list=PLg358gdRUrDVTXpuGXiMgETgnIouWoWaY).

Wenn Sie dies noch nicht getan haben, gehen Sie zu [Einstellungen > Vertrieb > Zahlungen](./settings-distribution.md) und stellen Sie die entsprechende Währung und Zahlungsweisen (z. B. PayPal) ein.

Auf dieser Seite können Sie die Beträge für die verschiedenen Arten von Gebühren festlegen.

![Die Registerkarte Zahlweisen im Abonnement-Menü.](./assets/learning-ojs3.3-jm-subscriptions-paytypes.png)

### Autor/innengebühren

Wenn Sie den Autor/innen eine Bearbeitungsgebühr für Artikel in Rechnung stellen möchten, geben Sie den Betrag hier ein. Mit der Option Autor/innengebühren aktivieren können Sie nach Abschluss des Begutachtungsprozesses eine Bearbeitungsgebühr für den Artikel anfordern. Wenn der Artikel nach der Begutachtung der/des Redakteur/in angenommen wird, besteht die Möglichkeit, eine Zahlung zu verlangen. Daraufhin erhält der/die Autor/in eine Benachrichtigung in OJS und eine E-Mail, die ihn/sie durch den Zahlungsvorgang leitet.

Beachten Sie, dass die Option, Autor/innen über die Autor/innengebühr zu benachrichtigen, nur erscheint, wenn die Zahlungsdetails (PayPal-Kontodaten oder manuelle PayPal-Anweisungen) in [Einstellungen > Vertrieb > Zahlungen](./settings-distribution#payments) ausgefüllt wurden.

![Eine Beispielbenachrichtigung an den Autor mit der Option "Veröffentlichungsgebühr anfordern" aktiviert.](./assets/learning-ojs3.3-jm-subscriptions-authorfees.png)

Autor/innen müssen sich bei der Zeitschrift anmelden, bevor sie zur Zahlungsabwicklung an PayPal weitergeleitet werden.

### Lesegebühren

Wenn Sie für den Zugriff auf einzelne Artikel und Ausgaben Gebühren erheben möchten, können Sie hier die Preise für Artikel und Ausgaben eingeben.

Sie können die Gebühren nur auf PDF-Dateien anwenden, indem Sie die Option „Eingeschränkter Zugriff nur auf PDF-Versionen von Artikeln“ aktivieren.

Beachten Sie, dass Sie eine Fahne hochladen müssen, um Zugriff zu einer Ausgabe zu verkaufen.

### Allgemeine Gebühren

Nutzen Sie dies, um andere Gebühren, z. B. für Mitgliedschaften, zu erheben.

## Zahlungen {#payments}

Wenn verschiedene Zahlungen eingehen, werden sie in diesem Reiter aufgeführt.

Nur Zahlungen, die über PayPal erfolgen, werden hier erfasst.

Seit Version 3.3 gibt es auf dem Manuskript-Dashboard einen Reiter „Zahlung“, auf der die Redakteur/innen den Zahlungsstatus der Autorengebühren erfassen können. Manuskripte können erst dann für eine Ausgabe geplant werden, wenn die Autorengebühr als bezahlt oder erlassen markiert wurde.

![Registerkarte für die Zahlung der Autor/innengebühren.](./assets/learning-ojs3.3-jm-subscription-authorpublicationfee.png)

## Individuelle Abonnements {#individual-subscriptions}

Alle Typen von individuellen Abonnements werden hier angezeigt.

![Die Registerkarte für individuelle Abonnements im Abonnement-Menü.](./assets/learning-ojs3.3-jm-subscriptions-indiv.png)

Sie können ein neues individuelles Abonnement erstellen, indem Sie den Link **Neues Abonnement** anklicken. Zunächst müssen Sie jedoch unter Benutzer/innen & Rollen ein neues Konto für diese Person erstellen (siehe Kapitel [Benutzerkonten](./user-accounts)). Sobald dies geschehen ist, können Sie hier nach dem Konto suchen und die verschiedenen Konfigurationen anwenden.

![Neues Abonnement-Fenster.](./assets/learning-ojs3.3-jm-subscriptions-indiv-create.png)

**Abonnementtyp**: Wählen Sie den entsprechenden Typ für diese/n neue/n Abonnent/in (z. B. Student) und dessen Status (z. B. Aktiv).

> Die Abonnementtypen wurden weiter oben in diesem Kapitel konfiguriert.

**Datum**: Legen Sie das Start- und Enddatum für dieses Abonnement fest.

**Mitgliedschaft**: Wenn Abonnent/innen mit irgendwelchen relevanten Mitgliedschaften verbunden sind, fügen Sie diese Informationen hier hinzu (optional).

**Referenznummer**: Wenn das Abonnement mit einer relevanten Referenznummer verbunden ist (z. B. einer Rechnungsnummer für die Zahlung), fügen Sie diese Information hier ein (optional).

**Anmerkungen**: Wenn Sie wichtige Anmerkungen hinzufügen möchten, können Sie diese hier eintragen (optional).

## Institutionelle Abonnements {#institutional-subscriptions}

Alle Arten von institutionellen Abonnements werden hier angezeigt.

![Die Registerkarte Institutionelle Abonnements im Abonnement-Menü.](./assets/learning-ojs3.3-jm-subscriptions-instit.png)

Institutionelle Abonnements werden ähnlich verwaltet wie individuelle Abonnements, werden aber für Bibliotheken, Forschungsinstitute und andere Organisationen verwendet, die Ihre Zeitschrift abonnieren.

Sie können ein neues institutionelles Abonnement erstellen, indem Sie den Link "Ein neues Abonnement erstellen" verwenden. Zunächst müssen Sie jedoch unter Benutzer/innen & Rollen ein neues Konto für die Kontaktperson der Einrichtung anlegen (siehe [Kapitel Benutzerkonten](./user-accounts)). Sobald dies geschehen ist, können Sie hier nach dem Konto suchen und die verschiedenen Konfigurationen anwenden.

![Neues Abonnement-Fenster.](./assets/learning-ojs3.3-jm-subscriptions-instit-create.png)

- **Abonnementtyp**: Wählen Sie den entsprechenden Typ für diese neuen Abonnent/innen (z. B. Bibliothek) und dessen Status (z. B. Aktiv). (Abonnementtypen wurden weiter oben in diesem Kapitel konfiguriert).
- **Datum**: Legen Sie das Anfangs- und Enddatum für dieses Abonnement fest.
- **Name der Einrichtung**: Fügen Sie den Namen der Institution für dieses Abonnement hinzu (z. B. Simon Fraser University Library).
- **Adresse**: Fügen Sie die Adresse der Einrichtung hinzu.
- **Domain**: Leser/innen, die von einem Computer mit dieser Domain kommen, erhalten automatisch Zugriff (z. B. sfu.ca). Dies gilt für Benutzer/innen auf dem Campus.
- **IP-Bereiche**: Die Institution kann Ihnen IP-Bereiche zur Verfügung stellen. Leser/innen, die einen Computer in diesem IP-Bereich verwenden, erhalten automatisch Zugriff. Jeder IP-Bereich sollte in einer neuen Zeile eingegeben werden.

![Das IP-Bereichsfeld, in dem IP-Bereiche eingegeben werden.](./assets/learning-ojs3.3-jm-subscriptions-instit-IP.png)

- **Anmerkungen**: Wenn Sie wichtige Anmerkungen hinzufügen möchten, können Sie diese hier eintragen (optional).

## Zahlungsbenachrichtigungen {#payment-notifications}

### Manuelle Zahlungsbenachrichtigungen

Bei einer manuellen Zahlungsbenachrichtigung wird der/die Abonnementverwalter/in nach dem Ausfüllen dieser Informationen per E-Mail benachrichtigt, dass eine manuelle Zahlung erfolgt ist. Da die Sandbox nicht in der Lage ist, E-Mails zu versenden, würden alle Tests, die Sie durchführen würden, keine E-Mails versenden, wie es normalerweise der Fall ist.

Diese manuellen Abonnements werden auch im Reiter Zahlung > Individuell oder Institutionell erfasst. Das Beispiel unten zeigt ein Testabonnement.

Von hier aus kann der/die Abonnementverwalter/in den Status je nach Bedarf auf der Grundlage ihres Arbeitsablaufs aktualisieren.

![Ein Beispiel für ein individuelles Abonnement mit dem Status "Manuelle Zahlung abwarten".](./assets/learning-ojs3.3-subs-manual-notification.png)

### PayPal-Zahlungsbenachrichtigungen

Wenn eine Zahlung über PayPal abgewickelt wurde, erhält der/die Kontoverwalter/in Ihres PayPal-Kontos eine Zahlungsbestätigung. Die Zahlung wird auch im Reiter Zahlung unter Zahlungen > Zahlung erfasst.

## Abonnement-Block {##subscription-block}

Wenn ein/e Benutzer/in über ein Abonnement Zugang zu einer Webseite oder deren Inhalt erhält, können die Informationen der Abonnent/innen, die den Zugriff gewährt, in der Seitenleiste angezeigt werden. Die Funktion Abonnement-Block muss für die Anzeige in Website-Einstellungen > Aussehen > Einrichtung > Seitenleiste ausgewählt werden.

## Artikel als Open Access festlegen {#setting-articles-as-open-access}

Wenn Sie bestimmte Artikel als Open-Access einstellen möchten, können Sie dies unter **Ausgaben** im linken Menü tun. Wenn Sie dies vor der Veröffentlichung der Ausgabe festlegen möchten, klicken Sie auf den Reiter "Zukünftige Ausgaben" und dann auf den blauen Pfeil neben der Ausgabe.

Markieren Sie unter Inhaltsverzeichnis die Artikel, die als Open-Access eingestellt werden sollen.

![Das Kästchen "Open Access" neben einem Artikel im Inhaltsverzeichnis.](./assets/learning-ojs3.3-jm-subscriptions-single-article.png)
