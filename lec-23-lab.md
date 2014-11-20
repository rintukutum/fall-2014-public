# Lab for lecture 23 -- SQL

* Donwload the chinook database from here <br>
http://chinookdatabase.codeplex.com/downloads/get/557773/

* From the terminal
```
 sqlite3 Chinook_Sqlite.sqlite
```
Write SQL queries to answer the following:
1. Which artists did not make any albums at all? Include their names in your answer.
2. Which video track is the longest?
3. Find the names of customers who live in the same city as the top employee (The one not managed by anyone).
4. How many audio tracks in total were bought by German customers? And what was the total price paid for them?
5. Which playlists have no Latin tracks?
6. What is the space, in bytes, occupied by the playlist “Grunge”, and how much would it cost? (Assume that the cost of a playlist is the sum of the price of its constituent tracks).
7. Which playlists do not contain any tracks for the artists “Black Sabbath” nor “Chico Buarque” ?
8. Find audio tracks which have a length longer than the average length of all the audio tracks;
9. Which playlist(s) contain the largest number of pop tracks;
10. Which artist(s) has the most tracks classified as Jazz;
11. Find the name of the German customer(s) who has paid the most in total and is not associated with a company.
12. List the name and age of the employees who support more than 5 customers (Hint: You can use CURDATE() function to get the current date, and use a function from last assignment to calculate ages);
13. Find the manger who manages most employees but also being managed by someone else (Note: there are employees who do not have managers, i.e., there may be NULL values in ReportsTo column);
14. List the name of the artists with more than 5 tracks;
15. Find the playlist(s) which contains most tracks by artist “AC/DC”;
