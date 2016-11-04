# Informationen zum Bachelor Projekt 5. Semester AI 
Allgemeine Informationen zur Veranstaltung

# Anforderungen eAkte Anwendung

- Ein Benutzer sieht alle Organisationeinheiten auf die er Zugriff hat.
- Ein Benutzer kann eine Organisationseinheit auswählen.
- Ein Benutzer bekommt alle Akten zu einer ausgewählten Organisationseinheit angezeigt. 
- Ein Benutzer kann eine Akte auswählen und bekommt dadurch die Liste aller Dokumenten und Vorgänge der Akte angezeigt.
- Ein Benutzer kann einen Vorgang auswählen und bekommt alle Dokumente des Vorgangs angezeigt.
- Alle Listendarstellungen von Containern und Dokumenten sind filter und sortierbar.
- Alle Container und Dokumente verfügen über eine View/Edit Maske für Metadaten.
- Ein Mitartbeiter kann Akten und Vorgänge erstellen, bearbeiten, löschen und umregistrieren(verscchieben).
- Beim Erstellen einer Akte muss der Mitarbeiter ein Aktenplanzeichen aus dem Aktenplan auswählen.
- Ein Mitarbeiter kann Dokumente in eine Akte / einen Vorgang registrieren(hinzufügen), deren Metadaten bearbeiten, 
die Datei herunterladen, die Datei in einer neuen Version hochladen, das Dokument löschen.
- Der Benutzer kann Container und Dokumente zu seinen lokalen Favoriten hinzufügen.
- Der Benutzer hat eine Liste mit seinen Favoriten.
- Die letzten x verwendeten Dokumente und Container werden dem Benutzer in einer Liste angezeigt.
- Der Benutzer kann Dateien herunterladen und bekommt diese in der zugehörigen Applikation auf dem Client angezeigt.
- Bekannte Dateitypen sollen mit ihrem Icon in der Anwendung angezeigt werden. (docx, pdf, etc.)
- Gelöschte Elemente liegen im Papierkorb der eAkte-Anwendung, dieser muss angezeigt werden und ein Wiederherstellen soll möglich sein.
- Einige Metadatenfelder werden über vordefinierte Einträge befüllt, Lookupwerte, diese Werte müssen beim Erstellen / Bearbeiten von der Schnittstelle bezogen werden. 

## Nicht zu Implementieren
- Die Anwendung soll keine eigene Datenhaltung implementieren. Ein Caching von abgerufenen Informationen ist zulässig.
- Momentan funktioniert die Schnittstelle Synacta noch nicht mit tatsächlichen Benutzern, daher muss die Anwendung keine Benutzerinformationen bearbeiten.  


## Begriffsdefinition
- Akte, Vorgang sind Containertypen, die zur organisation von Dokumenten in einer hierarischen Form, vergleichbar mit dem Dateisystem, dienen. 
- Dokumente bestehen aus einer Datei (Bytestream) und einem Container, der Metainformationen zur Datei bereitstellt.
- Aktenplan ist eine parallele hierarischen Organisationsstruktur für Akten, Vorgange und Dokumente. Der Aktenplan bestimmt die thematische 
Klassifizierung eines Containers unabhängig von der Zugehörigen Organisation. Der Aktenplan ist in der Regel stabil über meherere Behörden einer 
Verwaltung. Zum Beispiel verfügt ein Bundesland über einen abgestimmten Aktenplan, der von allen Ministerien angewandt wird.
- Organisationen stellen die tatasächliche Struktur einer Behörde dar. 

# Synacta Informationen
- Allgemeine Beschreibung [Synacta](http://www.synacta.de)
- Demoschnittstelle für das Projekt https://synacta.agile-is.de
- Swagger Dokumentation [Synacta swagger](https://synacta.agile-is.de/_api/)
- Beispiel Clients für Synacta [JavaScript](https://github.com/AgileIS/synacta-js-client)  [.net](https://github.com/AgileIS/synacta-csharp-client) 
- Authentifizierung für das Projekt mit "Authorization: Token FHProjekt2016" im Request-Header jeder Anfrage
- Die Entwicklung zu Synacta ist aktuell noch nicht abgeschlossen, bitte Fehler und Fragen an info@agile-is.de 

# Vorgeschlagene Technologien
Die Wahl des Technologiestacks ist dem jeweiligen Team überlassen. Die folgende Liste ist als Empfehlung zu Werten:
- [Cordova](https://cordova.apache.org/) 
  - cross plattform mobile apps 
  - Sprachen: JavaScript, HTML, CSS
  - IDE bsp. Visual Studio
- [Electron](http://electron.atom.io/) 
  - cross platform desktop apps
  - Sprachen: JavaScript, HTML, CSS
  - IDE bsp. Visual Studio, VS Code, etc.
- [Windows Universal Apps](https://developer.microsoft.com/de-de/windows/getstarted)
  - Windows 10
  - Sprache: C#, XAML
  - IDE: Visual Studion
- [Xamarin](https://www.xamarin.com/)
  - cross plattform mobile apps 
  - Sprache: C#, XAML
  - IDE: Visual Studion
- ??? Was immer man sich noch vorstellen kann ???

