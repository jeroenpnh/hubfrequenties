# Hubfrequenties
### Aanpak om lijnfrequenties te berekenen van alle OV hubs van Noord-Holland

Het belangrijkste bestand is 'notebook editor for compute_OV_data.ipynb' waarin de dataverwerking daadwerkelijk plaatsvindt. Dit bestand is gemaakt op het platform 'Dataiku', en zal daarom niet 1,2,3 werken op een locale computer. Daarvoor moet het inladen van data even worden veranderd. Het notebook heeft als belangrijkste input de GTFS-feed.  

De feed is geen onderdeel van deze repo en moet worden gedownload van 'https://transitfeeds.com/p/ov/814', met een datum naar keuze. Let wel op dat in de eerste regel van het notebook BESTANDSNAAM moet matchen met de naam van het feed-bestand. Alle andere bestanden in deze repo zijn ook inputbestanden die gebruikt woorden om hubs, hubnamen, en bustypen te mappen op de feed. 

De output is een csv-bestand met lijnfrequenties. Ook kunnen er controle bestanden worden gegenereerd om te checken of er lijnen ontbreken of juist onbekend blijken te zijn. 

Voor meer informatie bekijk het powerpoint bestand.
