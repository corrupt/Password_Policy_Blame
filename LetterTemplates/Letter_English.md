__Subject:__ Chief Privacy Officer Inquiry

Dear Sir or Madam,

as a user of your service I have recently become aware of your website enforcing the following password policy:

* A limitation to __XX__ characters
* A minimum length of only __XX__ characters
* A restriction or constraint of special characters

As you are likely aware, the NIST recommends to consider maximum keyspace and no length restriction in their Guide to Enterprise Password Management [1]. It is therefore recommended to enforce the following as a password policy:

* At lease 8 characters
* Usage of upper- and lowercase letters, numbers and symbols
* no length restriction

From a technical point of view there is no reason to constrain these rules artificially if passwords in a database are properly hashed and salted. Both practices are also recommended by NIST. Therefore I would like to have the following questions answered to help me understand how your company manages passwords and ultimately decide whether I want to continue using your services:

* Are passwords stored hashed and salted?
* Which hash function is used for this purpose?
* What is the reasoning behind violating the aforementioned policy guidelines at your company.

Best Regards

[1] http://csrc.nist.gov/publications/drafts/800-118/draft-sp800-118.pdf
