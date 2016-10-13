[![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg)](http://creativecommons.org/licenses/by-sa/4.0/)

# Blaming Companies with Bad Password Policies Made Easy.
Repository of web services enforcing bad password policy along with emails sent to their Chief Privacy Officers (CPOs) and their responses. Feel free to grab one of these emails and re-send them to put more pressure on these companies to switch to a decent password scheme, or write a new email to a web service not in this list and create a pull request. You can use one of the given templates.

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

Additionally, I expect web services to take the following measures when storing and handling passwords (a nice guide can be found under [2]):
* Hash them using an up-to-date cryptographic hash function (e.g. [sha3](https://en.wikipedia.org/wiki/SHA-3), [whirlpool](https://en.wikipedia.org/wiki/Whirlpool_(cryptography)), or [RipeMD](https://en.wikipedia.org/wiki/RIPEMD) not [md5](https://en.wikipedia.org/wiki/MD5) or [sha1](https://en.wikipedia.org/wiki/SHA-1))
* Use [salts](https://en.wikipedia.org/wiki/Salt_(cryptography)) to prevent duplicate password hashes for the same plain text.
* Use one-time password-reset links instead of plain one-time passwords via email when users use the _reset password_ function.

## Why creating this repository?
I recently switched to using a password manager. Upon renewing all my passwords to 64-character random strings I realized how many of the web services I used for years have really bad password policies. After contacting a few of them via Twitter, I realized that many lack the willingness to do something about this. I hope that this repository will motivate more people to create and send complaint letters so as to get more and more companies to rethink their habits.

## What can I do to help?
You can always pick one of these web services that you also use, take the email template and send it to their CPO. If you get a response that differs from the one I get, feel free to let me know, or create a pull request with up-to-date information. That also applies to services reworking their password policies without me noticing.  
You can also use the generic mail templates, adapt them to a service you use that isn't listed here, send it, and create a pull request so other people may benefit from your readily-written email.

## Web resources 

1. [BSI IT Grundschutz Katalog M 2.11 Regelung des Passwortgebrauchs](https://www.bsi.bund.de/DE/Themen/ITGrundschutz/ITGrundschutzKataloge/Inhalt/_content/m/m02/m02011.html) (German)
2. [Salted Password Hashing - Doing it Right](https://crackstation.net/hashing-security.htm)
