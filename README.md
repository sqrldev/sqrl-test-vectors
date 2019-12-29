# SQRL Test Vectors
A suite of test vectors to aid developers of SQRL clients (and possibly servers?)

## Vector files

- **enscrypt-vectors.txt** - A CSV text file of 80 test vectors for EnScrypt varying 
  in number of iterations, salt, and password. *Created by Shane Killian. Verified
  by PHolder and Alex Hauser.*
- **enhash-vectors.txt** - A CSV file of 1000 test vectors for EnHash, encoded in
  Base64URL. *Created by Adam Comley. Verified by Shane Killian.*
- **identity-vectors.txt** - A CSV file of 80 test vectors for creation of identity
  keys. Given the Identity Unlock Key (IUK), the Identity Lock Key (ILK) and the
  Identity Master Key (IMK) are derived. The IMK is then combined with a domain 
  name (and, in some cases, extensions) and an Alt-ID (if it exists) to result in 
  the website's public key identifying the user (the IDK). The IUK, ILK, IMK and 
  IDK are Base64URL-encoded. *Created by Shane Killian. Corrected by Alex Hauser.*
- **ins-vectors.txt** - A CSV file of 48 test vectors for creation of the INS
  (INdexed Secret) given the user's IMK (base64-URL encoded), the domain name, and 
  the SIN (Secret INdex) provided by the server as a string. The resulting INS is
  Base64URL-encoded. *Created by Shane Killian.  Verified by Alex Hauser.*
- **identity-lock-vectors.txt** - A CSV file of 14 vectors for testing the
  Identity Lock protocol. Given an Identity Unlock Key (IUK) and a Random Lock
  Value (RLV), test the results of the Identity Lock Key (ILK), the Server Unlock
  Key (SUK), the Diffie-Hellman Key Agreement for unlocking the identity (DHKA),
  and the Verify Unlock Key (VUK). All values hex-encoded. *Created by PHolder.*

## Needed

If any other test vectors are needed by developers, please post in the 
  [Issues](../../issues) tab.
  
## Credits

Initial vectors created by Shane Killian, Adam Comley, Alex Hauser, and PHolder. 
  Additionally, see the list of [contributors](../../graphs/contributors).

## License

To the extent possible under law, the creators have dedicated all copyright and
 related and neighboring rights to these test vectors to the public domain
 worldwide. This software is distributed without any warranty. See the 
 [COPYING.txt](COPYING.txt) file or 
 <[http://creativecommons.org/publicdomain/zero/1.0/](https://creativecommons.org/publicdomain/zero/1.0/)>.
