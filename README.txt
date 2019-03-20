# car-ontology
This is an ontology for cars. It describes a car with it's brand, model, type, seating, etc.

## Classes
There are total 23 classes including 3 classes and other subclasses.


Class "Car" is manufactured by class "brand" and
The class "Car" is equipped by class "parts".
Therefore isManufacturedBy and isEquipedBy are object properties.


"Car" has the following sub classes: (has a VIN literal)
* bodyType
	having further subclasses
* classType
	having further subclasses
* model (has cost, name as literals)


"Parts" has following sub classes:
* numberOfSeats
	having further subclasses based on seat count
* engine (has a engine number literal)
	having further sublcasses for engine types


"brand" (has a companyName literal)
