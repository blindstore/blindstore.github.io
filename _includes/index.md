
Low-level private query datastore. Uses cryptographic [Private Information Retrieval](http://www.cs.ut.ee/~lipmaa/crypto/link/protocols/oblivious.php) protocol that ensures that server doesn't know the query yet answers correctly.


## Usage


Blindstore __is a prototype__. Don't even think about pushing it to production as it is.


## Technical details


Blindstore's PIR protocol is based on [Single-Database Private Information Retrieval from Fully Homomorphic Encryption](http://ieeexplore.ieee.org/xpl/articleDetails.jsp?arnumber=6189348) by Xun Yi, Mohammed Golam Kaosar, Russell Paulet, and Elisa Bertino. It uses the [Scarab](https://hcrypt.com/scarab-library/) library for Smart-Vercauteren scheme FHE ([N. Smart and F. Vercauteren, Fully Homomorphic Encryption with Relatively Small Key and Ciphertext Sizes](http://dl.acm.org/citation.cfm?id=2163650))


## Authors


Blindstore started at the [CERN Webfest](http://webfest.web.cern.ch/) Hackathon.


### License

MIT License

