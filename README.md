## Parameters

Curve256189 is defined over $GF(p)$  with $p = 2^{256} - 189$ as

$$ y^2 = x^3 + 61370*x^2 + x $$

 It has $2^2 \times 28948022309329048855892746252171976963404671476872247083542990644359122995957$ affine points, with the large integer a prime number.

 Its twist has $2^2 \times 28948022309329048855892746252171976963230320855948034936185801359597441823917$ affine points, again with the large integer a prime number.

 Curve189 has the same security properties as Curve25519. Note that with A = 61370 we have (A-2)/4 = 15342 is small. As described in [1], this provides speed benefits in implementations.

 Note that there is no reason to use Curve256189 over Curve25519, generating this curve was done pure for educational purposes.

## References

[1] D. J. Bernstein. Curve25519: new Diffie-Hellman speed records. Proceedings of PKC 2006, pp. 207-228.
