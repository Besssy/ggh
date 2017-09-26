# GGH
Implementation of the Goldreich - Goldwasser - Halevi (GGH) Cryptosystem.

The GGH cryptosystem makes use of the fact that the closest vector problem can be a hard problem. It uses a trapdoor one-way function that is relying on the difficulty of lattice reduction.

I used NTL (Number Theory Library) because it contains useful methods for vectors,matrices and rounding. If you want to use prime numbers you can combine NTL with GMP as described in the [documentation](http://www.shoup.net/ntl/doc/tour-gmp.html).

You can find a presentation for Lattice-based Cryptography [here](https://www.slideshare.net/jangavarun/lattice-based-cryptography-ggh-cryptosystem).

