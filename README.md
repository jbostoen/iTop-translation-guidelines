# iTop-translation-guidelines
Simple repository related to translation guidelines for Dutch version.
This is an unofficial document, but it contains some pointers on how to translate some strings. 
It contains discussions about tone (formal vs. informal), literal or natural translations, ...

It's written in Dutch because it focuses on specific things as well, sometimes including a bit of motivation.

---


# Doel van deze richtlijnen
De iTop-vertalingen bleken niet consequent in het gebruik van hoofdletters of bepaalde termen. Dit document kan een aanzet zijn voor Nederlandstalige vertalers om iTop (of extensies) ook in de toekomst op een gelijkaardige manier te vertalen als wat al beschikbaar is.

De vertaling van de Community-versie 2.6 werd gebaseerd op onderstaande richtlijnen.

# Werkwijze
Aan de hand van enkele voorbeelden heb ik een poging gedaan om in overleg met de andere actieve Nederlandstalige vertaler @Hipska tot richtlijnen te komen zodat we eenduidig kunnen vertalen.

---


# Discussiepunten


## Culturele verschillen (BE <-> NL)
Er lijkt geen reden om onderscheid te maken tussen een vertaling voor Nederland en voor Vlaanderen. De verschillen zijn miniem.

* **contactpersoon - identificatienummer**: voorheen uitsluitend vertaald als 'burgerservicenummer', nu uitgebreid met suggesties als 'rijksregisternummer' en ook algemenere vertalingen in het infolabel. Het hoofdlabel kreeg een generieke term.


## Formeel of informeel
De oorspronkelijke vertaling gebruikte ook voornamelijk de je-vorm, we blijven hier op verder gaan. Er wordt geen formele vorm (u-vorm) gebruikt.


## Spelling
Tenzij het om specifieke termen gaat die momenteel onvertaald blijven ('Change Management'), wordt spelling gerespecteerd en woorden aan elkaar geschreven waar nodig. 'Auditcategorie' wordt bv. als één woord geschreven, zonder spatie tussen.

## Vertalen van termen

* **Change Manager Email**: E-mailadres Change Manager. 
De vuistregel is eigenlijk om er '<eigenschap> (van) <persoon of item>' van te maken. Deze vertalingen voelen natuurlijker aan voor eindgebruikers. Om daarbij ook consequent te blijven, kiezen we ook voor 'Naam merk', 'Naam model', ... in plaats van gekende samenstellingen als 'Merknaam', 'Modelnaam', ... . Een uitzondering hierop is VLAN-tag, wat beschouwd wordt als één term (vandaar ook het koppelteken).

* **Email**: E-mailadres, e-mail (bericht)

* **Notification**: Notificatie (nog geen discussie gevoerd om dit door 'melding' te vervangen)

* **Parent / Child**: hoofd / sub . Vroeger was er 'moederorganisatie' of de suggestie van 'deelverzoek', maar dit valt soms moeilijk door te trekken over verschillende klasses heen.

* **Reconciliation**: voorlopig niet vertaald. Voorstel is 'matchen', maar hier is geen consensus over.

Veldlabels worden kort vertaald: 'Naam enclosure' (ipv 'Naam van de enclosure'). Bij de uitgebreide (+) beschrijving kan dit uiteraard wel volledig geschreven worden.

* **Related**: 'gerelateerd'. Andere opties waren 'gelinkt' of 'verwant', maar we willen één term doortrekken.

* **Resolution date**: 'Opgelost sinds'. Dit is gebruiksvriendelijker dan 'resolutiedatum'.

* **Services**: bewust niet meer vertaald als 'diensten', om verwarring te vermijden met 'een dienst' ('departement') en omdat 'service' ('dienstverlening') ook wel ingeburgerd is.

* **Status**: 'obsolete' wordt 'Buiten gebruik'. (voordien: 'overbodig' en in dezelfde vertaling ook 'verouderd')


## Consequent vertalen

* **Acties in linkermenu**: 
'new', 'search': het infolabel is iets uitgebreider.
'Menu:NewContact' => 'Nieuw contact',
'Menu:NewContact+' => 'Maak een nieuw contact aan',
'Menu:SearchContacts' => 'Zoek naar contacten',
'Menu:SearchContacts+' => 'Zoek naar contacten',

## Afkortingen
* 'Referentie' wordt in combinatie met andere woorden afgekort tot 'Ref.'
* 'Bijvoorbeeld' zal afgekort worden tot 'bv.'

## Overgang van fases (states in een lifecycle)
* Bevelvorm. 'Pas toe', 'Markeer als opgelost', ...

## Hoofdlettergebruik

* **Klassenamen**: blijven met een hoofdletter geschreven worden. Soms vervalt de spatie, omdat een klassenaam aan elkaar gescherven wordt achterliggend.

* **Labels voor keuzelijstjes**: Start met hoofdletter.

# Gelijkaardige modules
In het verleden werden sommige keuzes niet consequent vertaald tussen bijvoorbeeld request-mgmt en request-mgmt-itil . Daardoor leek ook de waardering van gebruikers (tevredenheidsscore) enigzins anders: waar in de ene versie de klant nog 'matig' tevreden was, bleek dit bij de andere al 'eerder ontevreden'. Het is daarom aangeraden dat dezelfde vertaler beide versies bijwerkt.


Consultaties:
* https://www.taaladvies.net
* https://www.linguee.nl/nederlands-engels/search?source=auto&query=x


