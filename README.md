[![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg)](http://creativecommons.org/licenses/by-sa/4.0/)

# Password_Rule_Blame
Repository of web services enforcing bad password rules along with emails sent to their CIOs and their responses. Feel free to grab one of these emails and re-send them to put more pressure on these companies to switch to a decent password scheme.

## Things to look out for when using web services

* Is there a limit to the character count of a password?
* Is it prohibited to use any class of characters (lowercase letters, uppercase letters, numbers, symbols)?
* Is the minimum length of a password below 8 characters?
* If a plain-text password is mailed to you, are you forced to change it after your first login (one-time password)?

## What is a "decent" password scheme?
Opinions vary, especially when it comes to enforcing minimum standards. It is understandable to a certain degree when companies allow their users to choose simple passwords they can remember. It is, however, completely inscrutable to enforce limits to the character classes or number of characters a password may contain. Hence, this is what I consider a "decent" password scheme:
* 12 characters at minimum
* At least three out of four character classes (lowercase letters, uppercase letters, numbers, symbols)
* No Limit in password length
* No character-class restriction 

Additionally, I expect web services to take the following measures when storing passwords:
* Hash them using an up-to-date cryptographic hash function (e.g. [sha3](https://en.wikipedia.org/wiki/SHA-3), [whirlpool](https://en.wikipedia.org/wiki/Whirlpool_(cryptography)), or [RipeMD](https://en.wikipedia.org/wiki/RIPEMD) not [md5](https://en.wikipedia.org/wiki/MD5) or [sha1](https://en.wikipedia.org/wiki/SHA-1) but )

## Web resources 

* [BSI IT Grundschutz Katalog M 2.11 Regelung des Passwortgebrauchs](https://www.bsi.bund.de/DE/Themen/ITGrundschutz/ITGrundschutzKataloge/Inhalt/_content/m/m02/m02011.html) (German)
* [Salted Password Hashing - Doing it Right](https://crackstation.net/hashing-security.htm)
