# SQL
SQL_Assignments <br>
CSE412 - Database Management <br>

Assignment1: Relational Algebra <br>
Assignment2: Relational Calculus <br>
Assignment3: SQL <br>
Music Rental Agency Relational Database Schema <br>
client(clientID, firstName, lastName, phone, address) <br>
cd(cdCode, cdTitle, numberSold, year, groupCode) <br>
availableCopy(cdCode, seqNum) <br>
rentedBy(cdCode, seqNum, clientID, fromDate, endDate, pricePerDay) <br>
song(songCode, songTitle) <br>
musicalGroup(groupCode, groupName) <br>
artist(artistID, firstName, lastName, yearBorn) <br>
topCDs(cdCode, year, rating) <br>
composedOf (cdCode, songCode, trackNumber) <br>
topSongs(songCode, year, rating) <br>
member(groupCode, artistID, fromDate, toDate) <br>
writtenBy(songCode, artistID) <br>

