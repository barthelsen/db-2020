## 3.1 Query 01

**Beschrijving**

Het resultaat van deze functie is een Pandas dataframe met: de teamnaam, het jaar, en het aantal homeruns per team, en dit voor alle teams.

Sorteer aflopend op het aantal homeruns.

## 3.2 Query 02

**Beschrijving**

Het resultaat van deze functie is een Pandas dataframe met: de voornaam, achternaam, geboortejaar, geboortemaand, geboortedag van spelers die hun eerste major league appearance maakten na een gegeven *`datum_x`*. 

Sorteer alfabetisch oplopend op achternaam.

## 3.3 Query 03

**Beschrijving**

Het resultaat van deze functie is een Pandas dataframe dat, per club: de clubnaam en de voor- en achternaam van alle managers weergeeft, die ooit voor de club gewerkt hebben als playermanager. Per club mag een welbepaalde manager slechts 1 keer in het resultaat voorkomen. 

Sorteer alfabetisch oplopend op clubnaam.


## 3.4 Query 04

**Beschrijving**

Het resultaat van deze functie is een Pandas dataframe dat: de teams waarvan, gedurende een bepaald jaar, geen enkele speler meer verdiende dan `salaris`.

Een speler speelt voor een team in een bepaald jaar wanneer deze speler datzelfde jaar betaald wordt door dat team. 

Het resultaat bestaat uit teamID, naam, jaar, wins en losses in dat jaar en tenslotte het maximum salaris in dat team.

Sorteer oplopend op teamID en dan oplopend op yearID.


## 3.5 Query 05

**Beschrijving**

Het resultaat van deze functie is een Pandas dataframe dat: alle teams bevat waar een (i.e., minstens 1) speler voor speelde die tussen `jaar_x` en `jaar_y` werd opgenomen in de Hall of Fame.

Een speler speelt voor een team in een bepaald jaar wanneer deze speler datzelfde jaar betaald wordt door dat team. 

Het resultaat bestaat uit teamID, naam, jaar en de rang.

Sorteer aflopend op jaar en een team slechts eenmaal voorkomt per jaar.


## 3.6 Query 06

**Beschrijving**

Het resultaat van deze functie is een Pandas dataframe dat alle unieke personen bevat die als manager meer dan `n_awards` hebben gewonnnen.

Van deze personen willen we de playerID, voornaam en achternaam.

Sorteer aflopend op achternaam.


## 3.7 Query 07

**Beschrijving**

Het resultaat van deze functie is een Pandas dataframe dat: alle personen bevat die voor een team speelden dat tussen `jaar_x` en `jaar_y` meer dan `n_wins` heeft behaald. Let op, we bedoelen hier het *totaal* aantal wins van een team in dat bepaalde interval tussen `jaar_x` en `jaar_y`, over de jaren heen dus.

Een speler speelt voor een team in een bepaald jaar wanneer deze speler datzelfde jaar betaald wordt door dat team. 

Van deze personen willen we de playerID, voornaam en achternaam en teamID.

Sorteer oplopend op playerID.


## 3.8 Query 08

**Beschrijving**

Het resultaat van deze functie is een Pandas dataframe dat voor alle teams: hun team ID, naam, *beste jaar* en het aantal homeruns en wins van dat jaar bevat.

Het *"beste jaar"* voor een team wordt hier gedefinieerd als het jaar met het hoogste aantal homeruns van dat team. In het geval van jaren met hetzelfde aantal homeruns is het meest recente jaar het beste jaar. 

Sorteer aflopend op aantal homeruns en dan aflopend op teamID.


## 3.9 Query 09

**Beschrijving**

Het resultaat van deze functie is een Pandas dataframe dat voor een `jaar_x` alle teams bevat die voor dat jaar een bovengemiddeld aantal homeruns hadden.

Van deze teams willen we de teamID, naam, jaar, rang en natuurlijk het aantal homeruns.

Sorteer aflopend op aantal homeruns en dan aflopend op rang.


## 3.10 Query 10

**Beschrijving**


Het resultaat van deze functie is een Pandas dataframe dat: de teamnaam bevat van het team (of de teams, indien meerdere) dat het meeste aantal spelers heeft die zijn opgenomen in de Hall of Fame.

Van dit team willen we de teamID, naam en het aantal spelers opgenomen in de Hall of Fame.