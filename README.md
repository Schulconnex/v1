# SchulConneX  

Dieses Werk ist lizenziert unter Creative Commons Namensnennung-Keine Bearbeitung 2.0 Deutschland [(CC BY-ND 2.0 DE)](https://creativecommons.org/licenses/by-nd/2.0/de/legalcode). 

## Beschreibung der Schnittstellen von SchulConneX für Dienste und Quellsysteme 

Das Dokument spezifiziert den Schnittstellenstandard SchulConneX. SchulConneX dient dem Austausch und der Synchronisation von Identitäten und Kontextdaten zwischen schulischen Identitätsmanagementsystemen einerseits und Anwendungen andererseits. 

Die Definition und Bereitstellung dieser Schnittstellen (APIs) wird als Teil der im Rahmen der Kultusministerkonferenz „Bildung in der digitalen Welt“ im Jahre 2016 erstellten Strategie zur Einrichtung landesweiter ID-Management-Systeme im schulischen Bereich verstanden. Ziel ist ein standardisiertes Anmeldesverfahren für den Zugang zu digitalen Bildungsplattformen und -medien zu schaffen.

Dabei ist herauszuheben, dass hiermit weder eine Vereinheitlichung der bei den Schulverwaltungen eingesetzten Systeme noch eine zentrale Datenhaltung beabsichtigt ist.

Prinzipiell unterstützt die API zwei grundlegend unterschiedliche Anwendungsfälle: Zum einen die Bereitstellung von Nutzer- und Kontextdaten im Zusammenhang mit einem Single Sign-on für Anwendungen (Dienste), zum anderen die Synchronisation von Nutzer- und Kontextdaten zwischen Schulverwaltungssystemen (Quellsystemen). 
Ein SchulConneX Service ist ein Dienst, der den Vorgaben der SchulConneX Spezifikation folgt. Der Zugriff auf alle Endpunkte der REST-APIs eines SchulConneX Services werden durch einen zentralen Authentifizierungs- und Autorisierungsserver gesichert. Ein Zugriff auf die Endpunkte darf nur mit einem gültigen, von diesem Server ausgestellten Access-Token möglich sein. Um Access-Token für die API-Nutzung zu erhalten, müssen Quellsysteme und Dienste als Clients mit einer Client-ID registriert sein. 

 ### Ansprechpartner
    
    Aufgabensteller:
      Landesinitiative n-21: Schulen in Niedersachsen online e. V.
      Dr. Boris Heithecker (Ansprechpartner)
      Schiffgraben 27
      30159 Hannover
     	 
    Fachliche Ausarbeitung der Schnittstellenspezifikation: 
      Fraunhofer-Institut für Offene Kommunikationssysteme FOKUS
      Dr. Christopher Krauß (Ansprechpartner)
      Kaiserin-Augusta-Allee 31
      10589 Berlin


 

