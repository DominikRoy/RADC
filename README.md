This is the source code used to verify some of the security properties of the PPRA.

The folder contains the ProVerif code and the executable for ProVerif.

- ppra.pv 
The code is meant to verify the secrecy of the randomness used to blind the template hashes (x_i) from the adversary. 
Moreover, we verify if the attacker is able to brute-force/guess x_i. 
We verify with ProVerif if the adversary is able to retrieve the values ri and vi.


To run the scripts:
- compress the archive
- go to ./ProVerif/
- run our protocol by executing the command:
```properties
 ./proverif.exe ppra.pv 
```  


