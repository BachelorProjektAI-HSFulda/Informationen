# Informationen zum Bachelor Projekt 5. Semester WI

Allgemeine Informationen zur Veranstaltung

## Anforderungen des Kunden Anwendung

- Die App soll in der Lage sein, Photos von Visitenkarten zu erstellen.
- Die Daten einer Visitenkarte sollen ausgelesenen und den richtigen Attributen einer Person zugeordnet werden. (Name, Vorname, E-Mail, Telefon, Unternehmen, Position, etc)
- Die Daten einer Person sollen über soziale Netzwerke verifiziert und abgeglichen werden. (LinkedIn, Facebook, twitter, Xing, Github, etc. )
- Der Benutzer kann auswählen gegen welche sozialen Netzwerke geprüft werden soll
- Gefundene Profile der Person werden in den Kontaktdetails als Link hinterlegt.
- Das erfassen von neunen Kontakten erfolgt per Visitenkartenbild über die Kamara des aktuellen GErätes oder aus bereits gespeicherten Bildern.
- Kontakte werden im Rahmen von Kampanien erfasst werden. Beispielsweise Messen, Tagungen oder Konferenzen. Diese Kampanien müssenm in der App angeleget und verwaltet werden können. 
- Für kampanien kann bestimmt werden, wie Daten mit sozialen Netzwerken abgeglichen werden und wohin die Kontaktdaten gesendet werden. 
- Kontaktdaten können an unterschiedliche System gesendet werden. Beispielsweise Google-Kontakte, Exchange, Salesforce, etc.
- Für Kampanien können Kontakte mit Zusatzinformationen ( Gesprächsnotizen, usw.) an OneNote exportiert werden. Hierbei ist eine Kampanie ein Notizbuch und jeder Kontakt eine Seite.
- Zu Kontakten können Beschreibungen, Sprachnachrichten, Dateien und weitere Bilder hinzugefügt werden. Diese sollen in einem Verlauf dargestellt werden.
- Die App soll mit mehreren Endgeräten funktionieren, Benutzer melden sich mit einem vorhandenen Account an. (bsp.: Google, Github, Facebook, LinkedIn) 
- Die Daten werden zwischen den Geräten synchronisiert.    
- Ein Administrator kann weitere Personen zu einer Gruppe/Unternehmen hinzufügen. (Jede Person kann nur einer Gruppe / Unternehmen zugehörig sein)
- Die Eingabe von doppelten Kontakten muss von der App registriert und dem Benutzer angezeigt werden. 

### Nicht zu Implementieren
- Text und Spracherkennung -> hierfür sind exteren Dienste zu verwenden.
- Nutzeridentitäten werden von externen Identityprovidern bezogen, keine eigene Nutzerverwaltung nötig!

## Vorgeschlagene Technologien

Die Wahl des Technologiestacks ist dem jeweiligen Team überlassen. Die folgende Liste ist als Empfehlung zu Werten:

- [Cordova](https://cordova.apache.org/) 
  - cross plattform mobile apps 
  - Sprachen: JavaSCript, HTML, CSS
  - IDE bsp. Visual Studio, VS Code, etc
- [Electron](http://electron.atom.io/) 
  - cross platform desktop apps
  - Sprachen: JavaScript, HTML, CSS
  - IDE bsp. Visual Studio, VS Code, etc.
- [Xamarin](https://www.xamarin.com/)
  - cross plattform mobile apps 
  - Sprache: C#, XAML
  - IDE: Visual Studio
- [Unity](https://unity3d.com/)
  - cross plattform game engine
  - Sprachen: C#, JavaScript
  - IDE: Unity Editor, ? 
- ??? Was immer man sich noch vorstellen kann ???

## Services

- Gerne können hier die gefundenen Services mit den anderen Gruppen geteilt werden.
