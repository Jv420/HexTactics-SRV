# HexTactics SRV installeren

## Via txAdmin

1. Open txAdmin en kies **Recipe Deployer**.
2. Gebruik de raw URL van `recipe.yaml` uit deze repository.
3. Vul tijdens de installatie de databasegegevens in.
4. Pas na installatie in `server.cfg` de Cfx.re license key aan.
5. Start de server volledig opnieuw.

## Handmatig

1. Download `HexTactics_v2_COMPLEET_MET_CITYCENTRAL.zip` uit de nieuwste GitHub Release.
2. Pak de map `HexTactics` uit naar `resources/[hextactics]`.
3. Importeer de SQL-bestanden van RDW, APK en billing.
4. Neem de startvolgorde uit `recipe.yaml` over in `server.cfg`.
5. Start `CityCentral` en laat `esx_joblisting` uitgeschakeld om dubbele jobcenters te voorkomen.

## Belangrijk

CityCentral gebruikt Cfx.re Asset Escrow. De server moet de juiste aangekochte asset-entitlement hebben op dezelfde Cfx.re-account als de gebruikte server-key.

Interne ESX-identifiers, events en societynamen zijn waar mogelijk ongewijzigd gehouden om compatibiliteit met bestaande resources te behouden.
