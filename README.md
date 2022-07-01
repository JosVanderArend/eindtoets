# Defs bij afsprakenset "Logistiek proces Eindtoets po"
De OAS3-definities (Defs) in YAML-bestand "eindtoetsketen-openapi.yaml" zijn bedoeld voor de REST API t.b.v. Logisieke proces rondom de Eindtoets PO voor schooljaar 2022-2023. In deze versie voor schooljaar dit zijn de volgende wijzigingen conform het specificatie-document aangebracht t.o.v. de versie voor voorgaande schooljaar:
* De eigenschap version heeft waarde "20220701"
* De 3 endpoint-paden zijn allemaal ingekort tot identificerend /registreren, /leerlingresultaat respectievelijk /leerlingrapport/{rapportid}
* Binnen gegevensblok Deelnemerslijst zijn de gegevens aanbieder en locatie vervangen door het nieuwe gegevensblok Deelnemersgroep.
* De waarde van eigenschap versie in Deelnemerslijst en Leerlingresultaat gewijzigd in "Eindtoetsketen_v3" (versievolgnummer zonder schooljaar).
* De eigenschappen achternaam, voorvoegsel en roepnaam binnen Leerling hebben een maximum lengte gekregen.
* De eigenschappen id en omschrijving binnen Groep hebben een maximum lengte gekregen.
* Bij eigenschappen is de beschrijving uit het specificatie document bijgevoegd (in description).

Iedere publicatie van dit YAML-bestand voor de eindtoetsketen is een getagde versie en is beschikbaar onder releases: https://github.com/JosVanderArend/eindtoets/releases. Daar zijn tevens hulpmiddelen beschikbaar om getagde versies te vergelijken. 
Er kan maximaal worden teruggekeken naar en vergeleken met de definitieve versie van het schooljaar 2020-2021 (hoewel deze versie door een aangepaste inrichting enigszins beperkt is).

Indien er problemen of verbetersuggesties zijn specifiek over de YAML dan graag indienen onder issues: https://github.com/JosVanderArend/eindtoets/issues.


De actuele versie van deze OAS3-definities kan met de Swagger Editor worden ingezien via deze link: https://editor.swagger.io/?url=https://raw.githubusercontent.com/JosVanderArend/eindtoets/main/eindtoetsketen-openapi.yaml. 
 

