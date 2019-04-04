# skyward-scoring
Fork of jpraet/fantasy-realms to make scoring calculator for Skyward (designed by Brendan Evans, published by Rule & Make). Not yet implemented. Currently building and testing locally. Please contact me if you'd like to help out.

## Development Plan
1. Import card data, or at least a subset for testing
2. Visual redesign to incorporate Skyward assets
3. Include animation elements to spark joy
4. Make scoring hidden until calculated

## Possible feature plan
* Convert deck.js to a more non-code friendly file format, probably establish a .csv to .json process
* Do separate type counts, currently just removed constraint
* Implement multiple card copies
..* Ideally in the data without duplicating entries, but being able to space IDs to create a Dewey style system might be good enough
..* Alternatively, or in addition, work out a way to loop through placeholder IDs and replace with sequential numbers. Not necessary if able to move to csv.
* Visual feedback for adding card to hand, i.e. add an "inhand" class when added to hand, remove "inhand" class from matching id when removed
* Store score entry to allow multiple players to input cards and then announce winner
* Convert css to scss - try to keep everything pretty well-scoped with variables
* Record scores with user consent to build scoring data
* Deal with tricky cards - temp fix, ask for user input
..* Dojo should be doable - similar cards in Fantasy Realm, just no scoring
..* Observatory requires entry - should be able to do a dropdown or validate as number, so not too dangerous
....* Also, option to implement with multiple players
..* Temple requires a Yes/No
....* Also, option to implement with multiple players
* Gem Refinery - just need an input for Gems. Should be easy
