*Numpy* is so important for numerical computations in python is because it is designed for efficiency on large arrays of data. NumPy operations perd=form complex computations on entire arrays without the need for python for loops.
- An ndarray is a generic multidimensional container for homogeneous data; that is, all of the elements must be the same type.
Every array has a shape, a tuple indicationg the size of each dimension, and a dtype, an object describing the data type of the array.

*.astype* - By using astype you can cast or convert an array from one data type to another.
# *np.strings_* is remove from python 2.0 instead of use this *np.bytes_* #

* If casting were to fail for some reason(like string that cannot be converted to float 64, a *ValueError will be raised*)
- Calling astype always create new array(a copy of the data), even if the new data type is the same as the old data type.