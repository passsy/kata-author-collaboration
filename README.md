# Author collaboration Kata


To celebrate collaboration (and to boost sales), a bookshop has decided to offer discounts of books with multiple authors, when bought in pairs.

The bookstore sells second-hand books only, therefore prices are fixed at 8 EUR.

If you buy pairs of different books with multiple authors, you get a 10% discount on those two books.

If you buy 4 different books with multiple authors, you get a huge 25% discount on those four books.

Note that if you buy, say, four books, of which 3 are different titles and multiple authors, you get a 10% discount on two of them.
It’s only one pair of books with multiple authors. The third and fourth book costs its original price.

Your mission is to write a piece of code to calculate the price of any conceivable shopping basket containing books, giving as big a discount as possible.

### Example 1

For example, how much does this basket of books cost?

```
2 copies of "A Introduction to Computer Science Using Python 3.6" (3 authors)
1 copy of "The Mythical Man Month" (1 author)
1 copy of "Programming in C++" (2 authors)

Answer: 30.40 EUR
```

### Example 2

For example, how much does this basket of books cost?

```
2 copies of "The Pragmatic Programmer" (2 authors)
2 copies of "Kotlin in Action" (2 authors)
2 copies of "The Mythical Man Month" (1 author)
1 copy of "A Practical Handbook of Software Construction" (1 author)
1 copy of "A Introduction to Computer Science Using Python 3.6" (3 authors)
1 copy of "Programming in C++" (2 authors)

Answer: 62.40 EUR
```

### Example book data


```
(1) A Practical Handbook of Software Construction - Steve McConnell
(1) The Mythical Man Month - Frederick P. Brooks Jr.
(2) The Pragmatic Programmer: From Journeyman to Master - Andrew Hunt, David Thomas
(2) Kotlin in Action - Dmitry Jemerov, Svetlana Isakova
(2) Programming in C++ - Stephen C. Dewhurst, Kathy T. Stark
(2) Haskell Programming from first principles - Christopher Allen, Julie Moronuki
(2) Introduction to Python Programming - Gowrishankar S., Veena A.
(3) A Introduction to Computer Science Using Python 3.6 - Paul Gries, Jenniffer Campbell, Jason Montojo
```

