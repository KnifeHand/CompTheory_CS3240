# CompTheory_CS3240

Assignment Directions:

D1. Consider the language L1 over alphabet Σ = { a, b }, L1 = { w ∈ Σ* | w is a palindrome of even length}. Recall that a palindrome is a string of characters that reads the same forwards and backwards. For example, abba, aa, λ, ababbaba ∈ L1, but a, aba, abbbab ∉ L1.

Demonstrate that L1 is context-free by constructing a PDA that recognizes L1.

Implement that PDA in JFLAP and upload the PDA as a file named d1evenpda.jff

 

D2. Consider the language L2 over alphabet Σ = { a, b }, L2 = { w ∈ Σ* | w is a palindrome of odd length}. 
For example: abbba, a, abababa ∈ L2,  but aa, abba, abbbab ∉ L2.

Demonstrate that L2 is context-free by constructing a PDA that recognizes L2.

Implement that PDA in JFLAP and upload the PDA as a file named d2oddpda.jff

 

D3. Consider the language L3 over alphabet Σ = { a, b }, L3 = { w ∈ Σ* | w is a palindrome of any length}.

Construct a PDA that recognizes L3.

Implement that PDA in JFLAP, and upload the PDA as a file named d3allpda.jff

D123r. Use Online Text to report observations and insights about your learning associated with the 
design and construction of these PDA.

D4. Consider a language that models a subset of simple English sentences. 
In particular, the sentences are of the form <article> <noun> <verb>, where <article> 
is either of the words "a" or "the", <noun> is either of the words "dog" or "cat", and 
<verb> is either of the words "ran" or "walked". 

For example, "the dog ran" and "a dog walked" are both in the language but "a walked cat" is not.

Define the rules of a context-free grammar equivalent to this language with the 
set of variables V = { S, A, N, V }, the set of terminals T = { a, c, d, r, t, w }, 
and the start symbol S. Note the following interpretations of these symbols:
A : <Article>
N : <Noun>
S : <Sentence>
V : <Verb>
a : "a"
c : "cat"
d : "dog"
r : "ran"
t : "the"
w : "walked"

For example, the string "tdw" in this language would correspond to the English sentence "the dog walked".

Implement the grammar in JFLAP and upload the implementation as a file named d4cfg.jff
