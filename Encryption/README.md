This program encrypts and decrypts using several different ciphers.
  a) substitution cipher,

  b) Caesar cipher,

  c) ROT13 cipher,

  d) Running Key cipher, and

  e) Vigenere cipher.

TESTING:
./cipher -m c -i caesar.txt -o caesar_out.txt

  a) In the above example, '-m c' means you are using the Caesar cipher method.

  b) '-i caesar.txt' specifies that caesar.txt is the input file and it should contain the shift distance in the first line, and the plain text you want to encrypt in the second line.

  c) '-o caesar_out.txt' specifies that caesar_out.txt is the output file and it should contain the cipher text (text after encryption) in the first line, and the decrypted text in the second line.

  d) The program will also generate def_caesar_out.txt which contains the cipher text and decrypted text when the Caesar cipher object was created using the default constructor (i.e., encryption is done using 0 shift).