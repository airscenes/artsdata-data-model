---
class_name: Person
layout: class-doc
shex: person
---

## Adding people

To add a performing arts person please create the person in Wikidata and fill in the following required fields. Please add as much data as possible to help cases that require disambiguation.  We recommend linking social media profiles, and external global IDs like ISNI, but these are not mandatory. 

* Given name
* Family name
* Occupation
  * actor
  * stage director
  * musician
* Instance of human
* Gender
  * male
  * female
  * intersex
  * transgender female
  * transgender male
  * non-binary
* Date of birth


Artsdata uses [ShEx](https://shex.io) to validate data for import. If the data passes the ShEx validation, the person will automatically be added to Artsdata.ca in a couple of days.

###  ShEx Validator 

Test using this [Online Validator](https://shex-simple.toolforge.org/wikidata/packages/shex-webapp/doc/shex-simple.html?data=Endpoint:%20https://query.wikidata.org/sparql&hideData&manifest=[]&textMapIsSparqlQuery&schemaURL=https://raw.githubusercontent.com/culturecreates/artsdata-data-model/master/shex/wikidata_person.shex)


