# iTop-translation-guidelines
Simple repository related to translation guidelines for the Dutch version of iTop.
This is an unofficial document, but it contains some pointers on how to translate some strings in a consistent way. 
It contains discussions about tone (formal vs. informal), literal or natural translations, ...

It's written in Dutch because it focuses on specific things as well, sometimes including a bit of motivation.

---


# Doel van deze richtlijnen
De iTop-vertalingen bleken niet consequent in het gebruik van hoofdletters of bepaalde termen. Dit document kan een aanzet zijn voor Nederlandstalige vertalers om iTop (of extensies) ook in de toekomst op een gelijkaardige manier te vertalen als wat al beschikbaar is.

De vertaling van de iTop Community-versie 2.6 en 2.7 werd gebaseerd op onderstaande richtlijnen.

# Werkwijze
Aan de hand van enkele voorbeelden heb ik (Jeffrey Bostoen / @jbostoen) een poging gedaan om in overleg met de andere actieve Nederlandstalige vertaler @Hipska tot richtlijnen te komen zodat we op eenzelfde manier kunnen vertalen.

---


# Discussiepunten


## Culturele verschillen (BE <-> NL)
Er lijkt geen reden om onderscheid te maken tussen een vertaling voor Nederland en voor Vlaanderen. De verschillen zijn miniem.

* **contactpersoon - identificatienummer**: voorheen uitsluitend vertaald als 'burgerservicenummer', nu uitgebreid met suggesties als 'rijksregisternummer' en ook algemenere vertalingen in het infolabel. Het hoofdlabel kreeg een generieke term.


## Formeel of informeel
De oorspronkelijke vertaling gebruikte ook voornamelijk de je-vorm, we blijven hier op verder gaan. Er wordt geen formele vorm (u-vorm) gebruikt.


## Spelling
Tenzij het om specifieke termen gaat die momenteel onvertaald blijven (bijvoorbeeld 'Change Management'), wordt spelling gerespecteerd en worden woorden aan elkaar geschreven waar nodig (bijvoorbeeld 'Auditcategorie'). Omwille van leesbaarheid of herkenbaarheid werd soms geopteerd voor een koppelteken ('Configuratie-item' -> 'CI').
 


## Vertalen van termen

Veldlabels worden kort vertaald: 'Naam enclosure' (ipv 'Naam van de enclosure'). Bij de uitgebreide (+) beschrijving kan dit uiteraard wel volledig geschreven worden.


Een alfabetische lijst van enkele Engelse termen. Bevat ook principes.

* **Attachments**: Bijlagen ("bijlages" is geen correcte meervoudsvorm)

* **Email**: E-mailadres, e-mail (bericht)

* **Modify**: aanpassen

* **Notification**: Melding

* **Parent / Child**: hoofd / sub . Vroeger was er 'moederorganisatie' of de suggestie van 'deelverzoek', maar dit valt soms moeilijk door te trekken over verschillende klasses heen.

* **Reconciliation**: voorlopig niet vertaald. Voorstel is 'matchen', maar hier is geen consensus over.

* **Related**: 'gerelateerd'. Andere opties waren 'gelinkt' of 'verwant', maar we willen proberen om één term door te trekken in diverse vertalingen.

* **Resolution date**: 'Opgelost sinds'. Dit is gebruiksvriendelijker dan de vroegere term 'resolutiedatum' (of 'datum resolutie').

* **Services**: bewust niet meer vertaald als 'diensten', om verwarring te vermijden met 'een dienst' ('departement') en omdat 'service' ('dienstverlening') ook wel ingeburgerd is.

* **State**: Mogelijkheden waren 'toestand', 'staat', 'fase'. Wordt gebruikt in een levenscyclus, waardoor geopteerd wordt voor 'fase' en om het verschil te maken met 'status' van een object.

* **Status**: 'obsolete' wordt 'Buiten gebruik'. (voordien: 'overbodig' en in dezelfde vertaling ook 'verouderd')

* **Update**: aanpassen

* **Template**: sjabloon



## Consequent vertalen

* **Acties in linkermenu**: 
* Het infolabel (+) is iets uitgebreider.
* 'New' is enkelvoud
* 'Search' is meervoud

```
'Menu:NewContact' => 'Nieuw contact',
'Menu:NewContact+' => 'Maak een nieuw contact aan',
'Menu:SearchContacts' => 'Zoek naar contacten',
'Menu:SearchContacts+' => 'Zoek naar contacten',
```

## Afkortingen
* 'Referentie' wordt in combinatie met andere woorden afgekort tot 'Ref.'
* 'Bijvoorbeeld' zal afgekort worden tot 'bv.'

## Overgang van fases (states in een lifecycle), actie-knoppen
* Bevelvorm. Bijvoorbeeld: 'Pas toe', 'Markeer als opgelost', ...

## Hoofdlettergebruik

* **Klassenamen**: 
  * Blijven met een hoofdletter geschreven worden (bv. Persoon). 
  * Soms vervalt de spatie, omdat een klassenaam aan elkaar geschreven wordt achterliggend in de code. (voorbeeld?)

* **Labels voor keuzelijstjes**: Start met hoofdletter.

## Volgorde van termen (bv. naam model <-> modelnaam)
* **Change Manager Email**: E-mailadres Change Manager. 
  * De vuistregel is om er '<eigenschap> (van) <persoon of item>' van te maken. Deze vertalingen voelen natuurlijker aan voor eindgebruikers. 
  * Om daarbij ook consequent te blijven, kiezen we ook voor 'Naam merk', 'Naam model', ... in plaats van gekende samenstellingen als 'Merknaam', 'Modelnaam', ... . 
  
# id, name, friendlyname
  * Velden eindigend op 'id' worden vertaald als '<Klasse>'. Voorbeeld: osversion_id -> 'Soort besturingssysteem'.
  * Velden eindigend op 'name' worden vertaald als 'Naam <klasse in kleine letters'. Voorbeeld: osversion_name -> 'Naam soort besturingssysteem'.
  

# Gelijkaardige modules
  * In het verleden werden sommige keuzes niet consequent vertaald tussen bijvoorbeeld **request-mgmt** en **request-mgmt-itil** . 
  * Het gevolg is dat er inhoudelijke verschillen optraden: bijvoorbeeld de waardering door de gebruikers (tevredenheidsscore): waar in de ene versie de klant nog 'matig' tevreden was, bleek dit bij de andere al 'eerder ontevreden'. 
  * Het is daarom aangeraden dat dezelfde vertaler beide versies bijwerkt.


# Consultaties:
* https://www.taaladvies.net
* https://www.linguee.nl/nederlands-engels/search?source=auto&query=x


