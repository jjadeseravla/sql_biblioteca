For all questions I opened the Sqlite power shell:
``` $ sqlite ```

Opened up the Biblioteca database:
```$ .open biblioteca.sqlite```

Looked at the list of all the tables:
```$ .schema ```

## Question 1

 ```$ SELECT * FROM book;```

I can see the Hobbit is book 5.

```$ SELECT id FROM book WHERE title="The Hobbit";```

= 5

```$ SELECT member_id FROM checkout_item WHERE book_id=5;```

= 1

```$ SELECT * FROM member WHERE id = 1;```

### Answer: Anand Beck

## Question 2

 ```$ SELECT * FROM member;```

shows me 42 people

```$ SELECT * FROM checkout_item```

shows 5 people.  Therefore 42-5 is 37.

### Answer: 37 people have not checked out anything.

## Question 3

```$ SELECT * FROM checkout_item;```

Gave me a table and allowed me to see which id's for specific books and movies were not there.


Books not checked out are The Fellowship of the Ring, 1984, Tome Sawyer, Catcher in the Rye, To Kill a Mockingbird, Domain Driven Design.
Movies not checked out are Thin Red Line, Crouching Tiger Hidden Dragon, Lawrence of Arabia and Office Space.

### Answer: 6 books and 4 movies are not checked out.

## Question 4

```$ INSERT INTO book VALUES(11, "The Pragmatic Programmer");```

```$ INSERT INTO member VALUES(43, "Jade Alvares");```

```$ INSERT INTO checkout_item(member_id, book_id) VALUES(43, 11);```

```$ .headers on```

```$ SELECT * FROM checkout_item;```

Check that I have added my book and added myself as a member and checked out the book I added.

## Question 5

Look at checked_out table again and see which name corresponds to the member_id that appears two or more times in the table.

### Answer: Anand Beck(member_id 1) and Frank Smith(member_id 6)
