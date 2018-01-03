
# Marking Guide   27 / 30


## Structural design 10/10
- add a key saying "UML" for future users.
- I would omit methods like "NUKE". Replace that with a test class. You really don't want a method that wipes your database anywhere near production. 
- Nice work incorporating the mechanics of using the    framework. If I had one critique it is that this is probably overkill for the size of app you have. There's a nice agile principle called "YAGNI", you aren't going to need it. Not everything has to be an interface.

## Runtime design 3/5
- it's a bit too sequential. This diagram doesn't describe process flow, but rather shows what components exist. So there's a UI, but you don't need to specify what UI here - save it for a sequence diagram.
- will you really have 3 databases?
- where is Spring in all this?


## Allocation views 5/5
- Delineates the mapping to requirements; each use case is captured by a design element.

## Rationale  9/10
- Good work here. Drop the personal tone in technical writing.
- You don't need Spring, REST etc in the glossary. keep that to the domain objects.

## Comments
