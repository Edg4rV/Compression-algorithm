# Compression-algorithm
Compression algorithm
Upon learning that DNA is not a random string, freshmen of the Bioinformatics Institute from the informatics group suggested using a compression algorithm that compresses repeated characters in a string.

Encoding is performed as follows:
The string "aaaabbņaa" is converted into "a4b2ņ1a2", that is, the groups of the same characters of the input string are replaced by the symbol and the number of its repetitions in this string.

Write a program, which reads the string, encodes it by this algorithm and outputs the encoded sequence. The encoding must be case sensitive.

Note, string can contain only a single character.


Sample Input:
aaaabbcaa

Sample Output:
a4b2c1a2


Sample Input:
abc

Sample Output:
a1b1c1


Sample Input:
aaaaa

Sample Output:
a5
