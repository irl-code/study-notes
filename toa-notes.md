## Chomsky Normal Form 

A Context Free Grammar(CFG) is in Chomsky Normal Form if:
		Every rule has two Variables or one terminal in the right hand side.
		
**Example:** 

```
S -> AB | c | CD | f
A -> DC | d
D -> b
```

as you can see above every rules has either two variables or one terminal thus the given CFG is in CNF.

**Key Part:**

The rule epsilon is only permitted if it is in the Starting Variable Rule.

```
S -> AB | ε
A -> c
```

since, epsilon (ε) is in the starting variable S it is allowed.\

## Rules
**Method 01:**
Screenshot 2025-06-12 at 15.07.33.png
**Method 02:**
Screenshot 2025-06-12 at 15.08.35.png

## Finite Automata

```
Has two categories Meele and Moore.
```

**Representation**

```
θ, Σ, δ, q₀, Δ, λ

θ → Finite States
Σ → i/p Alphabets
δ → Transition Function
q₀ → Initial States
Δ → o/p Alphabets
λ → o/p Function
```


## lambda Function functionality (Moore):

**Bullets**

- When state(s) functions output will execute.
- When you visit any of the states you’ll get/print output.
- Your ouput is connected with your state **`bullet 2`**.
- Prints ouput inside the state.


```
λ: Q → Δ
```

## lambda Function functionality (Meele):

**Bullets**

- When you do transition from one state to the other you’ll get/print output.
- States `multiply` alphabets will get the ouput.
- Prints ouput on the transition.

```
λ: Q x Σ → Δ
```

## YT Notes

Screenshot 2025-06-16 at 01.03.28.png

**Question No. I**

Screenshot 2025-06-16 at 01.16.43.png

**Question No. II**

Screenshot 2025-06-16 at 01.25.59.png

==Question’s II transition table.==

| States | a | b | Δ |
|:--|:--|:--|:--|
| A | A | B | 0 |
| B | C | B | 0 |
| C | A | D | 0 |
| D | A | B | 1 |






