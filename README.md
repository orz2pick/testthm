## Fermat’s Little Theorem

Theorem: Let p be a prime and a in Z such that p 不整除 a. Then,a^(p-1) ≡1 mod p.


##Proof:
Consider the following two sets of equivalence classes :
A = {[a], [2a], [3a], [4a], . . . , [(p − 1)a]}
B={[1],[2],[3],[4],...,[p−1]}=Zp −{[0]}
First, we want to show that A = B.
Clearly, A ⊆ B since p devides a and p divides none of 1, 2, 3, . . . , p − 1.
Now, suppose that ∃ r, s in N such that 1 ≤ r ≤ s ≤ p − 1 and [ra] = [sa].Then,
[ra] − [sa] = 0
r[a] − s[a] = 0
(r−s)[a] = 0
r−s=0,since[a] not congruent(同余) to 0 modp(sincep a)
But,since r≤p and s≤p, r−s≡0（ modp） ⇒r=s.
So, [a], [2a], [3a], · · · , [(p − 1)a] are all different mod p, which means that the cardinality of A is p − 1.
And, since ♯A = p − 1, ♯B = p − 1 and A ⊆ B, we can conclude that A = B,that is the equivalence classes in A are congruent to the equivalence classes [等价类] of B under a certain rearrangement.
Hence,
a∗2a∗3a∗···∗(p−1)a = 1∗2∗3∗···∗p−1 （mod p）
a^(p-1) ∗(p−1)! = (p−1)!
a^(p-1) =1,since (p−1)!不等于0（mod p）.
