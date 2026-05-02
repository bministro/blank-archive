Blank Archive  
Bruno Ministro  

<img width="972" height="560" alt="screenshot_landing" src="https://github.com/user-attachments/assets/f0485d00-9bf4-4714-9f28-e983c6aa860a" />


This work will appear soon in  
[Compoetics](https://compoetics.com/) - a journal of poetry, computation, intermedia, and communities  
edited by Chris Tanasescu aka MARGENTO  
(Thanks for the invitation and exchange, Chris!)  

Created: March-May 2026  
Published: tba  

## About this work  

Blank Archive explores the conditions of writing and reading in natural and programming languages in times of generative AI. A minimal interface displays the sentence “This page intentionally left blank,” followed by a continuous permutation of related statements. The work exists in six parallel versions, each generated from the same prompt by different language models and selected at random on each refresh.  

See my full note published in Compoetics: tba  

## Some specs and details  

**Models and permutation algorithms used**  
Claude Sonnet 4.5 → Steinhaus–Johnson–Trotter  
Gemini 3.1 Pro → Fisher–Yates shuffle  
GPT 5.4 → Lexicographic (Knuth’s Algorithm L)  
Nemotron 3 Super → Heap’s algorithm  
Perplexity Sonar 2 → Sattolo’s algorithm  
DeepSeek 3.2 → Plain changes (change-ringing)  

Here’s a compact differentiation:  

**Heap’s algorithm** — generates all permutations through recursive swaps, emphasizing systematic exhaustiveness rather than perceptual order  

**Steinhaus–Johnson–Trotter** — produces permutations by swapping adjacent elements only, so each step is a minimal local change (very “smooth” transitions)  

**Lexicographic (Knuth’s Algorithm L)** — lists permutations in sorted alphabetical order, giving a clear, ordered progression with a defined beginning and end  

**Fisher–Yates shuffle** — produces a uniformly random permutation each time, with no memory or continuity between states  

**Sattolo’s algorithm** — like Fisher–Yates but ensures a single cyclic permutation (no element stays in its original position), creating a closed loop  

**Plain changes (change-ringing)** — a method where each permutation differs by small, rule-based swaps, producing rhythmic, almost ritualistic sequences  

