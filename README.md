# AnsNorm_Similarity
Determining the distance (dissimilarity) between two vectors: showcase of problems in classic approaches and the solution - AnsNorm distance combining the advantages of euclidean and cosine distances.

Consider computing the distance (non-similarity) between the two given vectors<br>
of length normalized from -1 to 1 in user preference applications.<br>
Distance of 0 between the two must mean that they are completely the same,<br>
larger distances mean less similarity.<br><br>

Classical methods such as Euclidean distance and Cosine similarity<br>
have their limitations and downsides.<br>
Calculating the dot product as a similarity mesaure is even farther from being ideal.<br><br>

Euclidean distance does not pay attention to the direction of vectors<br>
while cosine distance ignores the magnitude. Meanwhile dot product as a measure<br>
ignores the common sense.<br><br>

One possible solution to the problem of evaluating how similar two vectorised personalities are<br>
is AnsNorm Similarity method given below.<br><br>

Here you can find several cases when the classics aren't ideal<br>
and test ansnorm() function on the same given examples.<br><br>

FYI:<br>
cosine returns values from 0 to 2<br>
euclidean returns values from 0 to +inf<br>
dot product is any number from -inf to +inf<br><br>
As for <b>ansnorm</b>,<br>
for input vectors normalised from -1 to 1<br>
it outputs distance values from 0 to 1:<br>
0 for identical entities and 1 for the most dissimilar.
