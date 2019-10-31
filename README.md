# project-2
LetterAvg {
LetterAvg(): The constructor. Sets the values for the already-made variables and calls addStationNames().
addStationNames(): Reads in lines from the file and adds them to the already-created ArrayList.
numberOfStationsWithLetterAvg(): Finds all entries in the filled ArrayList that match the desired average.
whichStations(): Fills and returns a new ArrayList for all the stations that match the desired average.

MesoInherit {
MesoInherit(): The constructor. Sets the values for the already-made variables.
calAverage(): Sets the abstract calAverage method. Uses the letters from the given station name to calculate the ASCII average,
including the floor, ceiling, and average.
letterAverage(): Sets the abstract letterAverage method. Returns the ASCII average from calAverage().

PosAvg {
PosAvg(): The constructor. Sets the values for the already-made variables and calls addStationNames().
addStationNames(): Reads in lines from the file and adds them to the already-created ArrayList.
averageIndex(): Creates and fills an array with station names with indexes dependent on the given station.
indexOfStation(): Returns the index of the given station.
