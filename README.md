# Python-Program-for-Finding-Maximum-Number-Of-Handshakes

Maximum Number Of Handshakes in Python
Here, in this page we will discuss the program to find the maximum number of handshakes in python.

For the number of handshakes to be maximum, every person should handshake with every other person in the room i.e. all persons present should shake hands.

Maximum number of handshakes in python

Approach :
For the number of handshakes to be maximum, every person should hand-shake with every other person in the room

i.e. all persons present should shake hands.

For the first person, there will be N-1 people to shake hands with
For second person, there will be N -1 people available but as he has already shaken hands with the first person, there will be N-1-1 = N-2 shake-hands
For third person, there will be N-1-1-1 = N-3, and So On…
Therefore the total number of handshake   =   ( N – 1 + N – 2 +….+ 1 + 0 )   =   ( (N-1) * N ) / 2.

Algorithm
For N = 8
handshakes  =  ( (N-1) * N ) / 2  =  ( 8 x 7 )/2  =  28
Print Result
Related Pages
Quadrants in which a given coordinate lies
 
Permutations in which n people can occupy r seats in a classroom
 
Addition of two fractions

Replace all 0’s with 1 in a given integer

Can a number be expressed as a sum of two prime numbers

Maximum number of handshakes
Python Code
Run
# number of people
N = 30

# formula
no_of_handshakes = int(N * ((N - 1) / 2))

# print number of handshakes
print('Maximum number of handshakes possible for', N, 'pople are', no_of_handshakes)
Output
Maximum number of handshakes for 30 people are 435
