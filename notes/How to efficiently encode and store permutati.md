How to efficiently encode and store permutations?
=================================================

  -------------- ---------------------
  **Created:**   *11/1/2019 4:11 PM*
  **Updated:**   *11/1/2019 4:17 PM*
  **Author:**    *Bogdan Bocse*
  -------------- ---------------------

\

How to efficiently encode and store permutations?

In order not to destroy information, all reordering of lists should be
done:

-   with reference to a retrievable certain-state preceding the moment
    of ordering

-   with storing as immutable **the resulting permutation order**
    obtained by apply sorting function Sort with Comparator that makes
    its assumptions on precision/encoding (fixed point, floating point,
    string of enumerated symbols)

\

\

What is the most compact way of storing the permutation order of a list
sort/list reordering? (with storing less than Om(n\*\|addressing
architecture\|) pointers)

\

------------------------------------------------------------------------

\

 
