# cipher
A simple cipher for encoding messages

It works by multiplying each letter of the alphabet by a number and adding another number to it (ax+b --> c (mod 25))
Using modular arithmetic each letter gets mapped to a unique other letter

To decript you reverse the transformation by subtracting the number added and then multiplying by the modular inverse (c - b)*(inv(a)) (mod 25)


