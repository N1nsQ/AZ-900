# Core Architectural Components of Azure | Azure arkkirehtuurien ydin 

## Azuren fyysinen infrastruktuuri

### Regions | Alueet

- Maantieteellinen alue, jossa sijaitsee yksi tai useampi datakeskus.
- Resursseja jaetaan datakeskuksien välillä niin että kuorma on tasapainossa

### Availability Zone

- Availability Zore on Regionin sisällä oleva yksikkö, joka toimii itsenäisesti
- Muodostuu yhdestä tai useammasta datakeskuksesta, joilla on oma virrantulo, jäähdytys ja verkkoyhteys
- Erillään toisistaan: Jos yksi kaatuu, toinen jatkaa toimintaansa
- Availability Zonet ovat yhteydessä toisiinsa **High-speed private fiber-optic network**in avulla
- Sietokyvyn takaamiseksi jokaisella Availibility Zoneja tukevalla regionilla on vähintään 3 erillistä Availability Zonea. (Huom. kaikki Regionit eivät tue Availability Zone ominaisuutta)

## Azuren hallinta infrastruktuuri 

### Resource
- **the basic building block of Azure**
- Anything you create, provision, or deploy is a resource.
- VMs, virtual networks, databases, and Azure AI services are all examples of resources.

### Resource Groups
- groupings of resources
- **Every resource must belong to exactly one resource group**
- Each resource belongs to exactly one resource group
- Resources can be moved between groups
- can't be nested
- can't be renamed after creation
- Deleting resource group deletes everything inside it
- Actions you apply to a resource group affect all resources inside it.


Describe Azure regions, region pairs, and sovereign regions.
Describe Availability Zones.
Describe Azure datacenters.
Describe Azure resources and Resource Groups.
Describe subscriptions.
Describe management groups.
Describe the hierarchy of resource groups, subscriptions, and management groups.
