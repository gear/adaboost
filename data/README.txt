Mushroom Database

From http://www.cs.toronto.edu/~delve/
Originally from the UCI repository of machine learning databases.

Files:

  mushroomB5000.txt: data set (5000 examples)
  mushroomB5000.txt: data set (3000 examples)
  atrinfo.txt: attribute info.
  conv.c: program for conversion to Boolean data

Remark:
The following modifications have been made by O.W for the homework
exercise.

1. Removal of one attribute (#11 in the original data set) since some
   examples have ? value on this attribute.
2. Permute examles randomly and select 5000 examples.
3. Change values to Boolean.  For the class use 1 (= poisonous) and 0
   (= edible) and for attributes use 1 (positive) and 0 (negative); see
   atrinfo.txt for the original attribute information.  (See also
   conv.c for the previse way to convert the data.)
4. The end of data is indicated a line with -1.

END OF README
