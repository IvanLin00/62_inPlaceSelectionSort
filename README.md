# in-place selection sort

Rearrange
an unordered `ArrayList<Integer>`
and use it as the data in an `OrderedList_inArraySlots`.

The re-use is probably contrary to Java's conventions
for its built-in classes. But as a pedagogical tool,
it has the advantage of allowing
the User program to check that the sort
is done in-place.

## count the cost

0. If the number of the elements in the input triples,
the time required to run the reigning champ algorithm
will grow by 11 + 3^n+3. The for loop in the reigning 
champ algorithm will triple when the number of elements
is tripled
[Justify, in about 2 sentences.]

0. If the number of the elements in the input triples,
the number of times that the reigning champ algorithm
will be invoked 
will triple. The number of times the algorithm will be
invoked is dependent on the number of times that the 
loop will loop for which is depedent on the number of
elements in the input. Since the number of elements is
tripled, the number of times will also be tripled.
[Justify, in about 2 sentences.]

0. If the number of the elements in the input triples,
the time required for the selection sort
will triple. The time required for sort is dependent
on the number of elements in the input. If the number
of elements is tripled, the amount of time will be tripled
too.
[Justify, in about 2 sentences.]
