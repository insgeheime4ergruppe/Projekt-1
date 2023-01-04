
<h2>Datenquellen:</h2>

    - Kundendaten
    - Grundriss (vom Kunden und/oder vom Techniker)
    - Netzwerkplan
    - Angebot

Kundendaten:

    - Bereitsteller: Kunde/Vertrieb
    - Datenformat: .pdf
    - Metainformation: Name, Anschrift, E-Mail-Adresse, Telefonnummer, 
      Alter, Geschlecht

Grundriss (vom Kunden):

    - Bereitsteller: Kunde
    - Datenformat: .jpg, .pdf, .skp, .3dm
    - Metainformation: Längen- und Breitenverhältnisse der Räume, 
    - Position von Hindernissen wie Fenstern, Säulen oder Möbel, 
    - Steckdosen, Datenkabel, Abstellräume für Server

Grundriss:

    - Bereitsteller: Techniker
    - Datenformat: .skp
    - Metainformationen: Längen- und Breitenverhältnisse der Räume; 
      Position von Hindernissen wie Fenstern; Säulen oder Möbel; 
      Steckdosen; Datenkabel; Abstellräume für Server

Netzwerkplan: 

    - Bereitsteller: Techniker
    - Datenformat: .pdf
    - Metainformationen: IP-Adressen der Geräte, Standortinformationen, 
      Überblick der IT-Infrastruktur, Usernamen und Passwörter der verwendeten Systeme  

<h2>Weiterverarbeitung:</h2>

    - Alle Daten (Kundendaten, Grundriss, Netzwerkplan) werden in einer Datenbank abgespeichert,
      falls diese nicht vorhanden sind


Kundendaten:

    - IT-Komponenten: Datenbank-Server (Interneterreichbarkeit), 
    - Konfiguration eines Intranets, Router


Grundriss:

    - Fall: Kunde schickt Grundriss
    -> Umwandlung des Datenformates, falls es keine skp-Datei ist
    -> Auswertung des Grundrisses – Überarbeitung bei Änderungsbedarf


Netzwerkplan:

    - benötigte Komponenten sind im Plan abgebildet und können im Angebot aufgenommen werden 

<h2>Angebot:</h2>

    - Datenformat: .pdf
    - Grund: Unabhängig vom benutzten Gerät oder Betriebssystem bleibt das originale Layout, 
      inklusive Schriftarten und Bildern. Damit ist garantiert,
      dass der Kunde das Angebot lesen kann.

Zugriffserlaubnis:

    - Der Techniker und der Vertrieb, sowie die späteren Entwickler 
      (falls das Angebot angenommen wurde), dürfen die Daten nutzen und weiterbearbeiten.


