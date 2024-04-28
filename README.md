# ModdedDot
Modified dot product that's lossless for LLMs trading space and time efficiency for cohesive information retention-capacity.

E.g. take one matrix say the square matrix (3,5,,7,9) and another matrix (2,8,,22,19) and compute a modified dot product that does the following: For each element of the first matrix multiply the each element of the second matrix. That is to say, (3*(2,8,,22,19), 5*(2,8,,22,19),, 7*(2,8,,22,19), 9*(2,8,,22,19)) to become a new matrix. 

-Computes a corresponding elementwise summation to reduce the 4x4 in this case, back to a 2x2 matrix.
-Works with any matrix size etc.
-Not at all a dot product at this point, but meant to be used like one.

