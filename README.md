# 3apedia-finding-neo

## Workshop excercises

### Excercise 1

If contact A has a contact with B and B has a contact with C, return the names of the people.

### Excercise 2

Find all of Tom Hanks' actor contacts that were born in 1960 or later and have earnt over $10M from a single movie and return the contact names, birth year and earnings.

### Excercise 3

Who are the 5 top rich contacts of Tom Hanks? Return the contact name as ContactName and their birth year as Born.

💡 You can sort the result.

### Excercise 4

Find the actor with the highest average earnings in the movie they acted in, round the earnings and display the actor's name in uppercase.

💡 Use the `round()` and `toUpper()` functions.

### Excercise 5

Find the top 5 movies with the highest paid actors.

💡It's the earnings we are interested in.

### Excercise 6

Find all actors who have earnt over 50M from all of their movies and add the label "Rich" and the total_earnings as a property to the person.

💡 Dynamic properties 🤔.

### Excercise 7

Undo the previous excercise.

### Excercise 8

Find all movies that the director also acted in. Return the movie title and the director's name.

Find all movies that the director might have acted in. Return the movie title and the director's name.

### Excercise 9

Find all movies which were directed by a contact of a person. Return the person and contact's name and the movie they directed.

Find all movies which might have been directed by a contact of a person. Return the person and contact's name and the movie they might have directed.

### Excercise 10

Add your favorite movie and you as its director.

💡 Check to see if the movie already exists 😉 and add the property {"3apedia":true} to your person.

### Excercise 11

Create a query which should run each time you watch your favorite movie.

💡 You should ensure that a relationship VIEWED exists between you and your favorite movie.

### Excercise 12

Add another person as your contact, (e.g. John Doe, born in USA in 1976). Add that person as an actor in your movie with some earnings.

💡 Add the property {"3apedia":true} to the new person.

### Excercise 13

Boycott an actor of your choice. After a recent drunken afair, your actor has lost all respect of all fellow actors.

💡: Delete the contact relationships.

### Excercise 14

Remove your favorite movie from the database, but retain all of the actors and directors.

💡 You cannot delete a node if it has a relationship with another node 🤔.

### Excercise 15

Recommend new co-actors for Tom Hanks.

💡 He didn't work with them.

### Excercise 16

Find someone to introduce Tom Hanks to Tom Cruise.

💡 They worked with the same actors.

### Excercise 17

Movies and actors up to 4 hops away from Kevin Bacon.

💡 Variable length paths.

### Excercise 18

Find the shortest path between actors who acted in the movies The Matrix and Top Gun.

💡Use the `shortestPath()` function.
