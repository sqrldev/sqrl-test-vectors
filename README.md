# SQRL Test Vectors
A suite of test vectors to aid developers of SQRL clients (and possibly servers?)

## Vector files

- **enscrypt-vectors.txt** - A CSV text file of 80 test vectors for EnScrypt varying 
  in number of iterations, salt, and password. *Created by Shane Killian. Verified
  by PHolder and ahauser on the [SQRL forum](https://sqrl.grc.com).*
- **enhash-vectors.txt** - 1000 test vectors for EnHash. The first 43 characters of
  each line are the Base64URL-encoded binary number to be hashed; the other 43 are 
  the Base64URL-encoded result. *Created by Adam Comley. Verified by Shane Killian.*
- **identity-vectors.txt** - A CSV file of 80 test vectors for creation of identity
  keys. The Identity Master Key (IMK) is combined with a domain name (as well as
  extensions) and an Alt-ID (if it exists) to result in the website's public key
  identifying the user (the IDK).   The IMK and IDK are Base64URL-encoded. 
  *Created by Shane Killian. Still needs to be verified.*
- **ins-vectors.txt** - A CSV file of 48 test vectors for creation of the INS
  (INdexed Secret) given the user's IMK, the domain name, and the SIN (Secret 
  INdex) provided by the server as a string. The resulting INS is Base64URL-encoded.
  *Created by Shane Killian. Still needs to be verified.*

## Needed

If any other test vectors are needed by developers, please post in the 
  [Issues](../../issues) tab.
  
## Credits

See the list of [contributors](../../graphs/contributors).

## License

To the extent possible under law, the creators have dedicated all copyright and
 related and neighboring rights to these test vectors to the public domain
 worldwide. This software is distributed without any warranty. See the 
 [COPYING.txt](COPYING.txt) file or 
 <[http://creativecommons.org/publicdomain/zero/1.0/](https://creativecommons.org/publicdomain/zero/1.0/)>.