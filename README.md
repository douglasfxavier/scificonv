# Scificonv Ontology v.1

Scificonv is an ontology created for describing data of a Science Fiction Convention. It contains the main concepts found in the most popular events from the same category.

## Taxonomy

* owl:Thing
	* Building
	* Floor
	* Room
		- Auditorium
		- Meeting Room
		- Seminar Room
	* Participant
		- Attendee
		- Guest of honour
		- Instructor
		- Moderator
		- Moderator and Panellist
		- Panellist
		- Speaker
	* Programme Item
		- Film Screening
			- MultiTrack Screening
		- Panel Session
			- Egalitarian Panel Session
		- Play
		- Reading
			- Guest Reading
		- Talk
		- Workshop
	* Programme Item by Duration
		- Long Duration Item
		- Short Duration Item
	* Track
	* Person
		- Female Person
		- Male Person
	* Gender

## Adding individuals

### Primitive classes
You should add new individuals on their respective primitive classes for **Building**, **Floor**, **Room**, **Participant**, and **Track**.

### Named subclasses
You should add new individuals on their specific subclasses for **Film Screening**, **Panel Session**, **Play**, **Reading**, **Talk**, and **Workshop**.
