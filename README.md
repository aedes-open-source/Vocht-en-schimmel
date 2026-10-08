# Vocht en Schimmel

Een open source project voor medewerkers van woningcorporaties om gezamenlijk te werken aan een voorspelmodel voor vocht- en schimmelproblemen in sociale huurwoningen.

**Dit project is een initiatief van [Aedes](https://aedes.nl)**

---

## Waarom dit project?

Steeds meer corporaties zijn bezig met een voorspelmodel voor vocht & schimmel. Uit onze eerste analyses blijkt dat daarbij niet alleen bouwkundige kenmerken relevant zijn, maar ook andere factoren een rol kunnen spelen. We willen voorkomen dat elke corporatie afzonderlijk hetzelfde onderzoekt, daarom is er een open-source GitHub project hiervoor opgezet. Hier kunnen corporatiemedewerkers in discussions hun bevindingen delen, elkaar helpen en gezamenlijk werken aan de ontwikkeling van een voorspelmodel.

## Doel

1. **Onderzoeken welke indicatoren significant zijn** voor het voorspellen van vocht- en schimmelproblemen
2. **Samen een voorspelmodel ontwikkelen** dat woningcorporaties kunnen inzetten

Het wordt geprefereerd als indicatoren **voor elke corporatie beschikbaar** zijn, zodat elke corporatie ze kan gebruiken. Je mag uiteraard eigen indicatoren onderzoeken, maar hou er rekening mee dat breed beschikbare indicatoren de voorkeur hebben.

## Achtergrond

Uit eerste analyses is gebleken dat het voorspellen van vocht- en schimmelproblemen vraagt om een bredere blik dan alleen bouwkundige kenmerken. We moedigen aan om ook te kijken in de richting van:

| Categorie | Voorbeelden |
|---|---|
| **Bouwkundig** | Bouwjaar, woningtype, energielabel, isolatiegraad, ventilatiesysteem |
| **Onderhoud** | Lekkages, eerdere schimmelmeldingen, onderhoudshistorie |
| **Omgeving** | Overstromingsrisico's, grondwaterstanden, ligging |
| **Bewonersgedrag** | Ventilatiegebruik, gebruik van gas/water/elektriciteit |
| **Sociaal-demografisch** | Huishoudgrootte, huishoudsamenstelling, inkomen |

Via [Discussions](../../discussions) kun je nieuwe indicatoren voorstellen en bespreken of ze significant zijn.

## Hoe meedoen?

Dit project is opgebouwd als een **kennisplatform**:

- **[Discussions](../../discussions)** — het forum waar je indicatoren bespreekt, resultaten deelt en databronnen uitwisselt
- **[Issues](../../issues)** — voor concrete verbeteringen aan de code of documentatie op deze repo
- **Pull Requests** — om code, analyses of notebooks bij te dragen

Lees de [CONTRIBUTING.md](CONTRIBUTING.md) voor hoe je kunt bijdragen.

## Belangrijk

> **Deel NOOIT ruwe data op deze repository of in Discussions.**
>
> Geen adressen, geen woningnummers, geen herleidbare gegevens. Deel alleen geaggregeerde resultaten, statistieken, coëfficiënten en methodebeschrijvingen.

Daarnaast kan dit model gebruikmaken van sociaal demografische kenmerken zoals huishoudsamenstelling, inkomen en energieverbruik. Het gebruik van dergelijke kenmerken kan privacy- en ethische vraagstukken met zich meebrengen, waaronder profilering. Houd hier rekening mee met het ontwikkelen van je model. 

## Discussion-categorieën

| Categorie | Waarvoor |
|---|---|
| **Indicatoren en analyses** | Bespreek of een indicator significant is, deel je analyse-resultaten |
| **Voorspelmodel** | Modelkeuze, feature engineering, validatie, ML-aanpak |
| **Hulp en vragen** | Technische hulp, vragen over scripts of methodes |

## Contactpersonen
Heb je vragen, suggesties of opmerkingen over dit project? Neem contact op met:

- **Bas van Nieuwenhuijsen** — [b.vannieuwenhuijsen@aedes.nl](mailto:b.vannieuwenhuijsen@aedes.nl)
- **Juliëtte van Alst** — [j.vanalst@aedes.nl](mailto:j.vanalst@aedes.nl)

## Licentie

Dit project valt onder de [MIT-licentie](LICENSE).

