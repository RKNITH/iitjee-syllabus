# 📐 Class 11 IIT JEE Mathematics — Complete Theory & Formula Sheet

> **Coverage:** All chapters as per NCERT + JEE Advanced/Mains syllabus  
> **Level:** Class 11 | **Exam:** IIT JEE Mains & Advanced  
> **Author:** Study Reference Guide  

---

## 📋 Table of Contents

1. [Sets](#1-sets)
2. [Relations and Functions](#2-relations-and-functions)
3. [Trigonometric Functions](#3-trigonometric-functions)
4. [Complex Numbers and Quadratic Equations](#4-complex-numbers-and-quadratic-equations)
5. [Linear Inequalities](#5-linear-inequalities)
6. [Permutations and Combinations](#6-permutations-and-combinations)
7. [Binomial Theorem](#7-binomial-theorem)
8. [Sequences and Series](#8-sequences-and-series)
9. [Straight Lines](#9-straight-lines)
10. [Conic Sections](#10-conic-sections)
11. [Introduction to Three Dimensional Geometry](#11-introduction-to-three-dimensional-geometry)
12. [Limits and Derivatives](#12-limits-and-derivatives)
13. [Statistics](#13-statistics)
14. [Probability (Class 11)](#14-probability-class-11)

---

## 1. Sets

### 📖 Theory

| Term | Definition |
|------|-----------|
| **Set** | Well-defined collection of distinct objects |
| **Subset** | A ⊆ B if every element of A is in B |
| **Proper Subset** | A ⊂ B if A ⊆ B and A ≠ B |
| **Power Set** | P(A) = set of all subsets of A |
| **Universal Set (U)** | Set containing all elements under consideration |
| **Complement (A')** | U – A = {x : x ∈ U, x ∉ A} |

### Types of Sets
- **Empty/Null Set (∅):** No elements; n(∅) = 0
- **Singleton Set:** Exactly one element
- **Finite Set:** Countable elements
- **Infinite Set:** Uncountable elements
- **Equal Sets:** Same elements (A = B)
- **Equivalent Sets:** Same cardinality (n(A) = n(B))

### 📐 Key Formulas

#### Set Operations
```
Union:        A ∪ B = {x : x ∈ A or x ∈ B}
Intersection: A ∩ B = {x : x ∈ A and x ∈ B}
Difference:   A – B = {x : x ∈ A, x ∉ B}
Complement:   A' = U – A
```

#### De Morgan's Laws
```
(A ∪ B)' = A' ∩ B'
(A ∩ B)' = A' ∪ B'
```

#### Distributive Laws
```
A ∪ (B ∩ C) = (A ∪ B) ∩ (A ∪ C)
A ∩ (B ∪ C) = (A ∩ B) ∪ (A ∩ C)
```

#### Associative & Commutative
```
A ∪ B = B ∪ A,    A ∩ B = B ∩ A
(A ∪ B) ∪ C = A ∪ (B ∪ C)
(A ∩ B) ∩ C = A ∩ (B ∩ C)
```

#### Cardinality Formulas
```
n(A ∪ B) = n(A) + n(B) – n(A ∩ B)

n(A ∪ B ∪ C) = n(A) + n(B) + n(C)
              – n(A∩B) – n(B∩C) – n(A∩C)
              + n(A∩B∩C)

n(A – B) = n(A) – n(A ∩ B)
n(A') = n(U) – n(A)

Number of subsets of A = 2^n(A)
Number of proper subsets = 2^n(A) – 1
Number of non-empty subsets = 2^n(A) – 1
```

#### Cartesian Product
```
A × B = {(a, b) : a ∈ A, b ∈ B}
n(A × B) = n(A) × n(B)
A × B ≠ B × A (in general)
(A × B) ∩ (C × D) = (A ∩ C) × (B ∩ D)
```

---

## 2. Relations and Functions

### 📖 Theory

- **Relation:** R ⊆ A × B; set of ordered pairs
- **Domain of R:** {a : (a,b) ∈ R}
- **Range of R:** {b : (a,b) ∈ R}
- **Function:** Every element of domain has exactly one image

### Types of Functions

| Type | Condition |
|------|-----------|
| **Constant** | f(x) = c for all x |
| **Identity** | f(x) = x |
| **Polynomial** | f(x) = aₙxⁿ + ... + a₀ |
| **Rational** | f(x) = p(x)/q(x), q(x) ≠ 0 |
| **Modulus** | f(x) = |x| |
| **Signum** | f(x) = 1 if x>0, 0 if x=0, -1 if x<0 |
| **Greatest Integer** | f(x) = ⌊x⌋ (floor function) |

### 📐 Key Formulas

#### Modulus Function
```
|x| = x   if x ≥ 0
    = -x  if x < 0

|x| ≥ 0
|x·y| = |x|·|y|
|x/y| = |x|/|y|
|x + y| ≤ |x| + |y|  (Triangle inequality)
||x| – |y|| ≤ |x – y|
```

#### Greatest Integer (Floor) Function
```
⌊x⌋ = n if n ≤ x < n+1
⌊x + n⌋ = ⌊x⌋ + n    (n integer)
⌊x⌋ + ⌊x + 1/2⌋ = ⌊2x⌋
x – 1 < ⌊x⌋ ≤ x
```

#### Algebra of Functions
```
(f + g)(x) = f(x) + g(x)
(f – g)(x) = f(x) – g(x)
(f·g)(x)  = f(x)·g(x)
(f/g)(x)  = f(x)/g(x),  g(x) ≠ 0
(cf)(x)   = c·f(x)
```

#### Even and Odd Functions
```
Even: f(-x) = f(x)   (symmetric about y-axis)
Odd:  f(-x) = -f(x)  (symmetric about origin)

Even × Even = Even
Odd × Odd   = Even
Even × Odd  = Odd
Even + Odd  = Neither (in general)
```

---

## 3. Trigonometric Functions

### 📖 Theory

#### Angle Measurement
```
π radians = 180°
1 radian = 180°/π ≈ 57°17'45"
1° = π/180 radians

Arc length: l = rθ  (θ in radians)
Area of sector = (1/2)r²θ
```

#### Signs in Quadrants (CAST Rule)
```
QI  (0 to π/2):   All +ve
QII (π/2 to π):   Sin +ve
QIII(π to 3π/2):  Tan +ve
QIV (3π/2 to 2π): Cos +ve
```

### 📐 Trigonometric Values Table

| Angle | 0° | 30° | 45° | 60° | 90° | 120° | 135° | 150° | 180° |
|-------|----|-----|-----|-----|-----|------|------|------|------|
| sin | 0 | 1/2 | 1/√2 | √3/2 | 1 | √3/2 | 1/√2 | 1/2 | 0 |
| cos | 1 | √3/2 | 1/√2 | 1/2 | 0 | -1/2 | -1/√2 | -√3/2 | -1 |
| tan | 0 | 1/√3 | 1 | √3 | ∞ | -√3 | -1 | -1/√3 | 0 |

### 📐 Key Formulas

#### Fundamental Identities
```
sin²θ + cos²θ = 1
1 + tan²θ = sec²θ
1 + cot²θ = cosec²θ

sinθ·cosecθ = 1
cosθ·secθ = 1
tanθ·cotθ = 1
tanθ = sinθ/cosθ
cotθ = cosθ/sinθ
```

#### Allied Angle Formulas
```
Angle      sin         cos         tan
–θ         –sinθ       cosθ        –tanθ
90°–θ      cosθ        sinθ        cotθ
90°+θ      cosθ        –sinθ       –cotθ
180°–θ     sinθ        –cosθ       –tanθ
180°+θ     –sinθ       –cosθ       tanθ
270°–θ     –cosθ       –sinθ       cotθ
270°+θ     –cosθ       sinθ        –cotθ
360°–θ     –sinθ       cosθ        –tanθ
```

#### Addition and Subtraction Formulas
```
sin(A+B) = sinA cosB + cosA sinB
sin(A–B) = sinA cosB – cosA sinB
cos(A+B) = cosA cosB – sinA sinB
cos(A–B) = cosA cosB + sinA sinB
tan(A+B) = (tanA + tanB) / (1 – tanA tanB)
tan(A–B) = (tanA – tanB) / (1 + tanA tanB)
cot(A+B) = (cotA cotB – 1) / (cotA + cotB)
cot(A–B) = (cotA cotB + 1) / (cotB – cotA)
```

#### Double Angle Formulas
```
sin 2A = 2 sinA cosA = 2tanA/(1+tan²A)
cos 2A = cos²A – sin²A
       = 2cos²A – 1
       = 1 – 2sin²A
       = (1–tan²A)/(1+tan²A)
tan 2A = 2tanA / (1–tan²A)

sin²A = (1 – cos2A)/2
cos²A = (1 + cos2A)/2
```

#### Triple Angle Formulas
```
sin 3A = 3sinA – 4sin³A
cos 3A = 4cos³A – 3cosA
tan 3A = (3tanA – tan³A) / (1 – 3tan²A)
```

#### Half Angle Formulas
```
sin(A/2) = ±√((1–cosA)/2)
cos(A/2) = ±√((1+cosA)/2)
tan(A/2) = ±√((1–cosA)/(1+cosA))
          = sinA/(1+cosA)
          = (1–cosA)/sinA
```

#### Product-to-Sum Formulas
```
2sinA cosB = sin(A+B) + sin(A–B)
2cosA sinB = sin(A+B) – sin(A–B)
2cosA cosB = cos(A+B) + cos(A–B)
2sinA sinB = cos(A–B) – cos(A+B)
```

#### Sum-to-Product Formulas
```
sinC + sinD = 2 sin((C+D)/2) cos((C–D)/2)
sinC – sinD = 2 cos((C+D)/2) sin((C–D)/2)
cosC + cosD = 2 cos((C+D)/2) cos((C–D)/2)
cosC – cosD = –2 sin((C+D)/2) sin((C–D)/2)
```

#### General Solutions
```
sinθ = 0   →   θ = nπ
cosθ = 0   →   θ = (2n+1)π/2
tanθ = 0   →   θ = nπ

sinθ = sinα  →  θ = nπ + (–1)ⁿα
cosθ = cosα  →  θ = 2nπ ± α
tanθ = tanα  →  θ = nπ + α
```

#### Maximum and Minimum Values
```
–1 ≤ sinθ ≤ 1,  –1 ≤ cosθ ≤ 1
–∞ < tanθ < ∞

Max/Min of a sinθ + b cosθ:
  Maximum = +√(a²+b²)
  Minimum = –√(a²+b²)
```

#### a sinθ + b cosθ Form
```
a sinθ + b cosθ = R sin(θ + φ)
where R = √(a²+b²),  tanφ = b/a

OR = R cos(θ – ψ)
where tanψ = a/b
```

#### Conditional Identities (if A+B+C = π)
```
sin A + sin B + sin C = 4 cos(A/2) cos(B/2) cos(C/2)
cos A + cos B + cos C = 1 + 4 sin(A/2) sin(B/2) sin(C/2)
tan A + tan B + tan C = tan A · tan B · tan C
sin 2A + sin 2B + sin 2C = 4 sinA sinB sinC
cos 2A + cos 2B + cos 2C = –1 – 4 cosA cosB cosC
```

---

## 4. Complex Numbers and Quadratic Equations

### 📖 Theory

- **Imaginary Unit:** i = √(–1),  i² = –1,  i³ = –i,  i⁴ = 1
- **Complex Number:** z = a + ib,  a = Re(z),  b = Im(z)
- **Purely Real:** b = 0;  **Purely Imaginary:** a = 0
- **Conjugate:** z̄ = a – ib
- **Modulus:** |z| = √(a²+b²)
- **Argument:** arg(z) = θ = tan⁻¹(b/a) (adjusted for quadrant)

### 📐 Key Formulas

#### Powers of i
```
i¹ = i,  i² = –1,  i³ = –i,  i⁴ = 1
iⁿ = iⁿ mod 4  (pattern repeats every 4)
i⁴ᵏ = 1,  i⁴ᵏ⁺¹ = i,  i⁴ᵏ⁺² = –1,  i⁴ᵏ⁺³ = –i
```

#### Algebra of Complex Numbers
```
z₁ + z₂ = (a₁+a₂) + i(b₁+b₂)
z₁ – z₂ = (a₁–a₂) + i(b₁–b₂)
z₁·z₂   = (a₁a₂–b₁b₂) + i(a₁b₂+a₂b₁)
z₁/z₂   = z₁·z̄₂ / |z₂|²
```

#### Properties of Conjugate
```
z + z̄ = 2 Re(z)
z – z̄ = 2i Im(z)
z·z̄ = |z|²
z̄̄ = z
z₁ + z₂ overline = z̄₁ + z̄₂
z₁·z₂ overline = z̄₁·z̄₂
(z₁/z₂) overline = z̄₁/z̄₂
```

#### Properties of Modulus
```
|z| ≥ 0
|z| = |z̄| = |–z|
|z|² = z·z̄
|z₁z₂| = |z₁||z₂|
|z₁/z₂| = |z₁|/|z₂|
|z₁+z₂| ≤ |z₁| + |z₂|   (Triangle inequality)
||z₁|–|z₂|| ≤ |z₁–z₂|
```

#### Polar / Euler Form
```
z = r(cosθ + i sinθ) = r·e^(iθ)
where r = |z|,  θ = arg(z)

Principal argument: θ ∈ (–π, π]

Euler's Formula: e^(iθ) = cosθ + i sinθ
e^(iπ) + 1 = 0   (Euler's Identity)
```

#### De Moivre's Theorem
```
(cosθ + i sinθ)ⁿ = cos(nθ) + i sin(nθ)
(r·e^(iθ))ⁿ = rⁿ e^(inθ)

nth roots of unity: zₖ = e^(i2πk/n),  k = 0,1,...,n–1
Sum of all nth roots of unity = 0
Product of all nth roots of unity = (–1)^(n+1)
```

#### Cube Roots of Unity
```
1, ω, ω²  where ω = e^(i2π/3) = (–1+i√3)/2
1 + ω + ω² = 0
ω³ = 1
ω̄ = ω²

Important:
(1–ω)(1–ω²) = 3
(1+ω²) = –ω
(1+ω) = –ω²
a³+b³+c³–3abc = (a+b+c)(a+bω+cω²)(a+bω²+cω)
```

#### Quadratic Equations
```
ax² + bx + c = 0
x = [–b ± √(b²–4ac)] / 2a

Discriminant D = b²–4ac
D > 0: Two distinct real roots
D = 0: Equal real roots
D < 0: Two complex conjugate roots

Sum of roots:    α + β = –b/a
Product of roots: αβ = c/a

Equation from roots: x² – (α+β)x + αβ = 0
```

#### Nature of Roots
```
If a, b, c ∈ Q and D is a perfect square → rational roots
If one root is p+√q → other root is p–√q  (irrational conjugate pair)
If one root is p+iq → other root is p–iq   (complex conjugate pair)
```

---

## 5. Linear Inequalities

### 📖 Theory

- **Linear inequality:** ax + b > 0 (or <, ≥, ≤)
- **Solution Set:** Set of all x satisfying the inequality
- **Feasible Region:** For two-variable inequalities, region on coordinate plane

### 📐 Key Rules

```
Adding/subtracting same number to both sides: inequality unchanged
Multiplying/dividing by positive number: inequality unchanged
Multiplying/dividing by negative number: inequality REVERSES

a < b ⟹ –a > –b
a < b and b < c ⟹ a < c  (transitivity)
a < b ⟹ a+c < b+c
a < b, c > 0 ⟹ ac < bc
a < b, c < 0 ⟹ ac > bc
```

#### Solution of |x| < a and |x| > a
```
|x| < a   ⟺   –a < x < a        (a > 0)
|x| > a   ⟺   x < –a or x > a   (a > 0)
|x| ≤ a   ⟺   –a ≤ x ≤ a
|x| ≥ a   ⟺   x ≤ –a or x ≥ a
|x – k| < a   ⟺   k–a < x < k+a
```

---

## 6. Permutations and Combinations

### 📖 Theory

- **Fundamental Principle of Counting (FPC):** If event A can occur in m ways and then B in n ways, total = m × n
- **Permutation:** Arrangement (order matters)
- **Combination:** Selection (order doesn't matter)

### 📐 Key Formulas

#### Factorial
```
n! = n × (n–1) × (n–2) × ... × 2 × 1
0! = 1
1! = 1
n! = n × (n–1)!
```

#### Permutations
```
P(n, r) = ⁿPᵣ = n! / (n–r)!        (r ≤ n)
P(n, n) = n!

Permutations of n objects:
  All distinct: n!
  With repetition allowed: nʳ (choosing r from n)
  With p alike, q alike, r alike: n! / (p! q! r!)

Circular permutations: (n–1)!
Circular (necklace/no flip distinction): (n–1)!/2
```

#### Combinations
```
C(n, r) = ⁿCᵣ = n! / [r!(n–r)!]

C(n, 0) = C(n, n) = 1
C(n, 1) = n
C(n, r) = C(n, n–r)               (Symmetry)
C(n, r) + C(n, r–1) = C(n+1, r)   (Pascal's Rule)
C(n, r) = C(n–1, r–1) + C(n–1, r)

ⁿPᵣ = ⁿCᵣ × r!
```

#### Important Counting Results
```
Sum of all ⁿCᵣ (r = 0 to n): 2ⁿ
Sum of odd-r ⁿCᵣ = Sum of even-r ⁿCᵣ = 2^(n–1)
C(n,1)+2C(n,2)+...+nC(n,n) = n·2^(n–1)

Number of diagonals of n-gon = C(n,2) – n = n(n–3)/2
Number of triangles from n points = C(n,3)  [no 3 collinear]
```

#### Multinomial Theorem (Arrangement)
```
Number of arrangements of n objects in n places
with p₁ alike, p₂ alike, ..., pₖ alike:
= n! / (p₁! p₂! ... pₖ!)
```

#### Division into Groups
```
Dividing (m+n) into groups of m and n:
= C(m+n, m) = (m+n)!/(m!n!)

Dividing 3n into 3 equal groups:
= (3n)! / (n!)³  if groups are distinct
= (3n)! / [3!(n!)³]  if groups are identical
```

---

## 7. Binomial Theorem

### 📖 Theory

- Valid for any n ∈ ℕ (positive integer)
- Total number of terms in expansion of (a+b)ⁿ = n+1
- Coefficients are binomial coefficients C(n,r)

### 📐 Key Formulas

#### Binomial Expansion
```
(a+b)ⁿ = Σ C(n,r) aⁿ⁻ʳ bʳ   [r = 0 to n]
        = C(n,0)aⁿ + C(n,1)aⁿ⁻¹b + C(n,2)aⁿ⁻²b² + ... + C(n,n)bⁿ
```

#### General Term
```
Tᵣ₊₁ = C(n,r) · aⁿ⁻ʳ · bʳ    (r = 0,1,2,...,n)
```

#### Important Expansions
```
(1+x)ⁿ = Σ C(n,r) xʳ
(1–x)ⁿ = Σ C(n,r) (–x)ʳ = Σ (–1)ʳ C(n,r) xʳ
(a–b)ⁿ = Σ (–1)ʳ C(n,r) aⁿ⁻ʳ bʳ
(1+x)ⁿ + (1–x)ⁿ = 2[C(n,0) + C(n,2)x² + C(n,4)x⁴ + ...]
(1+x)ⁿ – (1–x)ⁿ = 2[C(n,1)x + C(n,3)x³ + ...]
```

#### Middle Term
```
If n is even: Only one middle term = T_{n/2+1}
If n is odd:  Two middle terms = T_{(n+1)/2} and T_{(n+3)/2}
```

#### Properties of Binomial Coefficients
```
C(n,0) + C(n,1) + C(n,2) + ... + C(n,n) = 2ⁿ
C(n,0) – C(n,1) + C(n,2) – ... = 0
C(n,0) + C(n,2) + C(n,4) + ... = 2^(n–1)
C(n,1) + C(n,3) + C(n,5) + ... = 2^(n–1)

C(n,0)² + C(n,1)² + ... + C(n,n)² = C(2n,n)

C(n,1) + 2C(n,2) + 3C(n,3) + ... = n·2^(n–1)
```

#### Term Independent of x
```
In (xᵃ + 1/xᵇ)ⁿ:
General term: C(n,r) x^{a(n–r)–br}
For independent term: a(n–r) – br = 0 → r = an/(a+b)
```

#### Greatest Term (Numerically)
```
In (1+x)ⁿ, find r such that T_{r+1}/T_r ≥ 1
Solve: C(n,r)|x|ʳ ≥ C(n,r–1)|x|^{r–1}
```

---

## 8. Sequences and Series

### 📖 Theory

- **Sequence:** Ordered list of numbers following a pattern
- **Series:** Sum of terms of a sequence
- **AP:** Arithmetic Progression — constant difference d
- **GP:** Geometric Progression — constant ratio r
- **HP:** Harmonic Progression — reciprocals form AP

### 📐 Key Formulas

#### Arithmetic Progression (AP)
```
General term:     aₙ = a + (n–1)d
Sum of n terms:   Sₙ = n/2[2a + (n–1)d] = n/2[a + l]

where a = first term, d = common difference, l = last term

d = aₙ – aₙ₋₁ = (Sₙ – Sₙ₋₁) for n ≥ 2
aₙ = Sₙ – Sₙ₋₁

Arithmetic Mean (AM): A = (a+b)/2
n AMs between a and b: Aₖ = a + k·(b–a)/(n+1)
```

#### Properties of AP
```
If a, b, c are in AP: 2b = a + c
Sum of n terms from both ends: aₖ + aₙ₋ₖ₊₁ = a + l (constant)
If AP multiplied/divided by constant → still AP
Reciprocals of AP → HP
```

#### Geometric Progression (GP)
```
General term:     aₙ = arⁿ⁻¹
Sum of n terms:   Sₙ = a(rⁿ–1)/(r–1)    if r ≠ 1
                     = na                  if r = 1
Sum of infinite GP: S∞ = a/(1–r)          if |r| < 1

Geometric Mean (GM): G = √(ab)
n GMs between a and b: Gₖ = a·(b/a)^{k/(n+1)}
```

#### Properties of GP
```
If a, b, c are in GP: b² = ac
Product of equidistant terms from start and end = a·l (constant)
If GP raised to same power → still GP
```

#### Harmonic Progression (HP)
```
If a, b, c are in HP: 1/a, 1/b, 1/c are in AP → 2/b = 1/a + 1/c

Harmonic Mean (HM): H = 2ab/(a+b)

Relation between AM, GM, HM:
  AM ≥ GM ≥ HM   (for positive numbers)
  GM² = AM × HM
```

#### Arithmetic-Geometric Progression (AGP)
```
Sum of AGP: a + (a+d)r + (a+2d)r² + ...
Use S – rS method:
Sₙ = a/(1–r) + dr(1–rⁿ⁻¹)/[(1–r)²] – (a+(n–1)d)rⁿ/(1–r)

S∞ = a/(1–r) + dr/(1–r)²    [|r| < 1]
```

#### Standard Summation Formulas
```
Σk       = n(n+1)/2
Σk²      = n(n+1)(2n+1)/6
Σk³      = [n(n+1)/2]²
Σk⁴      = n(n+1)(2n+1)(3n²+3n–1)/30
Σ1       = n
Σ(2k–1)  = n²         (sum of n odd numbers)
Σk(k+1)  = n(n+1)(n+2)/3
Σk(k+1)(k+2) = n(n+1)(n+2)(n+3)/4
```

#### Telescoping Series
```
Σ [f(k) – f(k+1)] = f(1) – f(n+1)
Σ [f(k+1) – f(k)] = f(n+1) – f(1)
```

#### Special Series
```
Geometric: a + ar + ar² + ... + arⁿ⁻¹ = a(rⁿ–1)/(r–1)
Exponential: eˣ = 1 + x + x²/2! + x³/3! + ...
             e  = 1 + 1 + 1/2! + 1/3! + ... ≈ 2.71828
ln(1+x) = x – x²/2 + x³/3 – ...   (|x| ≤ 1)
```

---

## 9. Straight Lines

### 📖 Theory

- **Slope (m):** m = tanθ, where θ is angle with positive x-axis
- **Collinear points:** Slope between any two pairs is equal
- **Parallel lines:** m₁ = m₂
- **Perpendicular lines:** m₁ × m₂ = –1

### 📐 Key Formulas

#### Slope
```
Slope through (x₁,y₁) and (x₂,y₂):
m = (y₂–y₁)/(x₂–x₁)

Angle between two lines:
tanθ = |(m₁–m₂)/(1+m₁m₂)|

Acute angle: take positive value
```

#### Equations of Lines
```
Slope-intercept form:     y = mx + c
Point-slope form:         y – y₁ = m(x – x₁)
Two-point form:           (y–y₁)/(y₂–y₁) = (x–x₁)/(x₂–x₁)
Intercept form:           x/a + y/b = 1
Normal form:              x cosα + y sinα = p
General form:             ax + by + c = 0  (slope = –a/b)
Parametric form:          x = x₁ + rcosθ,  y = y₁ + rsinθ
```

#### Distance Formulas
```
Distance between two points:
d = √[(x₂–x₁)² + (y₂–y₁)²]

Distance of point (x₁,y₁) from line ax+by+c=0:
d = |ax₁+by₁+c| / √(a²+b²)

Distance between parallel lines ax+by+c₁=0 and ax+by+c₂=0:
d = |c₁–c₂| / √(a²+b²)
```

#### Section Formulas
```
Midpoint of (x₁,y₁) and (x₂,y₂):
  M = ((x₁+x₂)/2, (y₁+y₂)/2)

Division in ratio m:n (internally):
  P = ((mx₂+nx₁)/(m+n), (my₂+ny₁)/(m+n))

Division externally:
  P = ((mx₂–nx₁)/(m–n), (my₂–ny₁)/(m–n))
```

#### Special Points of Triangle
```
Centroid G = ((x₁+x₂+x₃)/3, (y₁+y₂+y₃)/3)

Incenter I = (ax₁+bx₂+cx₃)/(a+b+c), (ay₁+by₂+cy₃)/(a+b+c))
            [a,b,c = side lengths opposite to vertices]

Circumcenter: equidistant from all three vertices
Orthocentre H: intersection of altitudes
O, G, H are collinear (Euler Line): OG:GH = 1:2
```

#### Area of Triangle
```
Area = (1/2)|x₁(y₂–y₃) + x₂(y₃–y₁) + x₃(y₁–y₂)|

Condition of collinearity:
x₁(y₂–y₃) + x₂(y₃–y₁) + x₃(y₁–y₂) = 0
```

#### Intersection and Concurrency
```
Intersection of L₁ and L₂: solve simultaneously

Family of lines through intersection of L₁ and L₂:
L₁ + λL₂ = 0

Condition for three lines to be concurrent:
|a₁ b₁ c₁|
|a₂ b₂ c₂| = 0
|a₃ b₃ c₃|
```

---

## 10. Conic Sections

### 📖 Theory

A conic section is the locus of a point P such that:
**SP / PM = e (eccentricity)**
- e = 0: Circle
- e < 1: Ellipse
- e = 1: Parabola
- e > 1: Hyperbola

### 📐 Key Formulas

#### Circle
```
Standard form (center origin): x² + y² = r²
General form: x² + y² + 2gx + 2fy + c = 0
  Center = (–g, –f),  radius = √(g²+f²–c)
Center-radius form: (x–h)² + (y–k)² = r²

Condition: g²+f²–c > 0 (real circle)
           g²+f²–c = 0 (point circle)
           g²+f²–c < 0 (imaginary circle)

Parametric: x = h + rcosθ,  y = k + rsinθ

Equation of tangent at (x₁,y₁) on x²+y²=r²:
  xx₁ + yy₁ = r²

Length of tangent from external point (x₁,y₁):
  L = √(x₁²+y₁²–r²)

Condition for line y=mx+c to be tangent to x²+y²=r²:
  c² = r²(1+m²)  i.e.,  c = ±r√(1+m²)

Equation of chord of contact from (x₁,y₁):
  xx₁ + yy₁ = r²
```

#### Parabola
```
Standard form: y² = 4ax   (a > 0, opens right)

Vertex: (0,0)
Focus: S = (a, 0)
Directrix: x = –a
Axis: y = 0 (x-axis)
Latus Rectum length: 4a
Endpoints of LR: (a, 2a) and (a, –2a)

Other standard forms:
y² = –4ax  (opens left)  → Focus (–a,0), Directrix x=a
x² = 4ay   (opens up)    → Focus (0,a),  Directrix y=–a
x² = –4ay  (opens down)  → Focus (0,–a), Directrix y=a

Parametric: x = at², y = 2at

Focal distance of point (x₁,y₁): r = x₁ + a

Tangent at (at², 2at): ty = x + at²
Tangent at (x₁,y₁): yy₁ = 2a(x+x₁)
Condition for y=mx+c to be tangent: c = a/m

Normal at (at², 2at): y = –tx + 2at + at³
Chord of contact from (x₁,y₁): yy₁ = 2a(x+x₁)
```

#### Ellipse
```
Standard form: x²/a² + y²/b² = 1   (a > b > 0)

Center: (0,0)
Vertices: (±a, 0)
Co-vertices: (0, ±b)
Foci: S = (±ae, 0)  where e = c/a, c = √(a²–b²)
Directrices: x = ±a/e

Eccentricity: e = c/a = √(1–b²/a²) < 1
Relationship: b² = a²(1–e²) = a²–c²

Latus Rectum length = 2b²/a
Endpoints of LR: (ae, ±b²/a) and (–ae, ±b²/a)

Focal radii: r₁ + r₂ = 2a (sum = major axis)
SP + S'P = 2a

Parametric: x = a cosθ,  y = b sinθ

Tangent at (x₁,y₁): xx₁/a² + yy₁/b² = 1
Tangent: y = mx ± √(a²m²+b²)
Condition for y=mx+c to be tangent: c² = a²m²+b²

Normal at (x₁,y₁): a²x/x₁ – b²y/y₁ = a²–b²

For x²/b² + y²/a² = 1 (a > b, major axis along y):
Vertices (0,±a), Foci (0,±c), e = c/a
```

#### Hyperbola
```
Standard form: x²/a² – y²/b² = 1

Center: (0,0)
Vertices: (±a, 0)
Foci: S = (±ae, 0)  where e = c/a, c = √(a²+b²)
Directrices: x = ±a/e

Eccentricity: e = c/a = √(1+b²/a²) > 1
Relationship: b² = a²(e²–1) = c²–a²

Asymptotes: y = ±(b/a)x   i.e.,  bx ± ay = 0
Asymptote angle: tanθ = b/a

Latus Rectum length = 2b²/a
Focal radii: |SP – S'P| = 2a

Parametric: x = a secθ,  y = b tanθ
OR:         x = a coshθ, y = b sinhθ

Tangent at (x₁,y₁): xx₁/a² – yy₁/b² = 1
Tangent: y = mx ± √(a²m²–b²)
Condition for tangency: c² = a²m²–b²

Conjugate Hyperbola: –x²/a² + y²/b² = 1
Rectangular Hyperbola: a = b → x²–y² = a² (asymptotes ⊥)
  OR: xy = c² (standard form)
    Parametric: x = ct, y = c/t
    Tangent: x/t² + yt = 2c
    Eccentricity of rectangular hyperbola = √2

Combined equation of asymptotes: x²/a² – y²/b² = 0
(Hyperbola – Conjugate)/2 = Asymptotes pair
```

---

## 11. Introduction to Three Dimensional Geometry

### 📐 Key Formulas

#### Coordinates
```
Point P = (x, y, z)
x: distance from YZ-plane
y: distance from XZ-plane
z: distance from XY-plane
```

#### Distance Formula
```
PQ = √[(x₂–x₁)² + (y₂–y₁)² + (z₂–z₁)²]
```

#### Section Formula
```
Internal division in ratio m:n:
P = ((mx₂+nx₁)/(m+n), (my₂+ny₁)/(m+n), (mz₂+nz₁)/(m+n))

Midpoint:
M = ((x₁+x₂)/2, (y₁+y₂)/2, (z₁+z₂)/2)

External division in ratio m:n:
P = ((mx₂–nx₁)/(m–n), (my₂–ny₁)/(m–n), (mz₂–nz₁)/(m–n))
```

#### Centroid of Triangle/Tetrahedron
```
Centroid of triangle with vertices A(x₁,y₁,z₁), B(x₂,y₂,z₂), C(x₃,y₃,z₃):
G = ((x₁+x₂+x₃)/3, (y₁+y₂+y₃)/3, (z₁+z₂+z₃)/3)

Centroid of tetrahedron:
G = ((x₁+x₂+x₃+x₄)/4, ..., ...)
```

#### Axes and Planes
```
x-axis: y=0, z=0
y-axis: x=0, z=0
z-axis: x=0, y=0

XY-plane: z=0
YZ-plane: x=0
XZ-plane: y=0
```

---

## 12. Limits and Derivatives

### 📖 Theory

#### Limit
```
lim(x→a) f(x) = L means f(x) approaches L as x → a

Left-hand limit (LHL): lim(x→a⁻) f(x)
Right-hand limit (RHL): lim(x→a⁺) f(x)
Limit exists iff LHL = RHL = L
```

### 📐 Key Formulas

#### Standard Limits
```
lim(x→0) sinx/x = 1
lim(x→0) tanx/x = 1
lim(x→0) (1–cosx)/x² = 1/2
lim(x→0) (eˣ–1)/x = 1
lim(x→0) (aˣ–1)/x = ln a
lim(x→0) ln(1+x)/x = 1
lim(x→∞) (1+1/x)ˣ = e
lim(x→0) (1+x)^{1/x} = e
lim(x→a) (xⁿ–aⁿ)/(x–a) = naⁿ⁻¹
lim(x→0) sin(ax)/sin(bx) = a/b  (b ≠ 0)
```

#### Limit Laws
```
lim[f(x) ± g(x)] = lim f(x) ± lim g(x)
lim[f(x)·g(x)]  = lim f(x) · lim g(x)
lim[f(x)/g(x)]  = lim f(x) / lim g(x)  [lim g(x) ≠ 0]
lim[c·f(x)]     = c · lim f(x)
lim[f(x)]ⁿ      = [lim f(x)]ⁿ
```

#### Indeterminate Forms
```
0/0,  ∞/∞,  0×∞,  ∞–∞,  0⁰,  1^∞,  ∞⁰
Use L'Hôpital's Rule or algebraic manipulation
```

#### L'Hôpital's Rule
```
If lim f(x)/g(x) is 0/0 or ∞/∞:
lim f(x)/g(x) = lim f'(x)/g'(x)
```

#### Continuity
```
f is continuous at x=a if:
  lim(x→a) f(x) = f(a)
  i.e., LHL = RHL = f(a)
```

#### Derivatives from First Principles
```
f'(x) = lim(h→0) [f(x+h) – f(x)] / h

d/dx(xⁿ) = nxⁿ⁻¹
d/dx(sinx) = cosx
d/dx(cosx) = –sinx
d/dx(tanx) = sec²x
d/dx(cotx) = –cosec²x
d/dx(secx) = secx tanx
d/dx(cosecx) = –cosecx cotx
d/dx(eˣ) = eˣ
d/dx(ln x) = 1/x
d/dx(c) = 0
d/dx(aˣ) = aˣ ln a
```

#### Rules of Differentiation
```
(u ± v)' = u' ± v'
(uv)'    = u'v + uv'               (Product Rule)
(u/v)'   = (u'v – uv') / v²       (Quotient Rule)
d/dx[f(g(x))] = f'(g(x))·g'(x)   (Chain Rule)
```

---

## 13. Statistics

### 📖 Theory

- **Mean:** Arithmetic average
- **Median:** Middle value when sorted
- **Mode:** Most frequent value
- **Range:** Max – Min
- **Variance:** Average of squared deviations from mean
- **Standard Deviation:** √Variance

### 📐 Key Formulas

#### Measures of Central Tendency

**Mean:**
```
x̄ = (Σxᵢ) / n                    [Ungrouped]
x̄ = (Σfᵢxᵢ) / (Σfᵢ)             [Grouped]
x̄ = a + (Σfᵢdᵢ)/N × h           [Step deviation, dᵢ=(xᵢ–a)/h]
```

**Median:**
```
Ungrouped (sorted data):
  Odd n:   M = x_{(n+1)/2}
  Even n:  M = (x_{n/2} + x_{n/2+1}) / 2

Grouped: M = l + [(N/2 – cf)/f] × h
  l = lower class boundary of median class
  cf = cumulative frequency before median class
  f = frequency of median class, h = class width
```

**Mode:**
```
Grouped: Z = l + [(f₁–f₀)/(2f₁–f₀–f₂)] × h
  f₁ = frequency of modal class
  f₀ = frequency of class before modal class
  f₂ = frequency of class after modal class
  l = lower boundary of modal class

Empirical relation: Mode = 3Median – 2Mean
```

#### Measures of Dispersion

**Range:** L – S (Largest – Smallest)

**Mean Deviation:**
```
MD (about mean) = Σ|xᵢ – x̄| / n
MD (about median) = Σ|xᵢ – M| / n
MD (grouped) = Σfᵢ|xᵢ – x̄| / N
```

**Variance:**
```
σ² = Σ(xᵢ – x̄)² / n              [Ungrouped]
   = Σxᵢ²/n – (x̄)²
   = Σxᵢ²/n – (Σxᵢ/n)²

σ² = Σfᵢ(xᵢ–x̄)² / N             [Grouped]

Step deviation method:
σ² = h²[Σfᵢdᵢ²/N – (Σfᵢdᵢ/N)²]
```

**Standard Deviation:**
```
σ = √(σ²)
```

**Coefficient of Variation (CV):**
```
CV = (σ/x̄) × 100
Lower CV → more consistent
```

---

## 14. Probability (Class 11)

### 📖 Theory

- **Random Experiment:** Outcome cannot be predicted with certainty
- **Sample Space S:** Set of all possible outcomes
- **Event:** Subset of sample space
- **Equally Likely Events:** Each has same probability
- **Mutually Exclusive Events:** A ∩ B = ∅
- **Exhaustive Events:** A₁ ∪ A₂ ∪ ... = S

### 📐 Key Formulas

#### Classical Definition
```
P(A) = n(A) / n(S) = (favorable outcomes) / (total outcomes)
0 ≤ P(A) ≤ 1
P(S) = 1,  P(∅) = 0
```

#### Basic Laws
```
P(A') = 1 – P(A)
P(A ∪ B) = P(A) + P(B) – P(A ∩ B)
P(A ∪ B ∪ C) = P(A)+P(B)+P(C)–P(A∩B)–P(B∩C)–P(A∩C)+P(A∩B∩C)

Mutually exclusive: P(A ∪ B) = P(A) + P(B)
Exhaustive & ME:    P(A₁)+P(A₂)+...+P(Aₙ) = 1
```

#### Odds
```
Odds in favour of A = P(A) / P(A') = m : n
Odds against A = P(A') / P(A) = n : m
P(A) = m/(m+n)
```

#### Probability of Common Events
```
Cards (52):
  P(ace) = 4/52 = 1/13
  P(red) = 26/52 = 1/2
  P(face card) = 12/52 = 3/13
  P(king of red) = 2/52 = 1/26

Dice (1 die):
  P(number k) = 1/6
  P(even) = 3/6 = 1/2

Two dice:
  Total outcomes = 36
  P(sum = 7) = 6/36 = 1/6
  P(doublet) = 6/36 = 1/6
```

---

## 🎯 Important JEE Tips & Tricks (Class 11)

### Quick Recognition Patterns

```
✦ In Trigonometry: a sinθ + b cosθ → convert to R sin(θ+φ); R = √(a²+b²)
✦ GP sum infinite: only valid if |r| < 1
✦ For n terms of AP + GP, write general term and sum
✦ In combination, selecting r from n: ⁿCᵣ (order irrelevant)
✦ Binomial middle term: (n/2+1)th if n is even
✦ Complex: always check quadrant for correct argument
✦ Conic: identify type from general equation ax²+bxy+cy²+...=0
     b²–4ac < 0 → Ellipse/Circle
     b²–4ac = 0 → Parabola
     b²–4ac > 0 → Hyperbola
✦ Parabola focal chord: t₁t₂ = –1
✦ Limit of form 1^∞: use e^{lim(f(x)–1)·g(x)}
✦ Variance is always non-negative
✦ For AP: if 3 terms → take a–d, a, a+d (sum = 3a)
✦ For GP: if 3 terms → take a/r, a, ar (product = a³)
```

### Memory Aids

```
CAST rule → quadrant sign of trig functions: All, Sin, Tan, Cos
Sum-to-Product: "2 sin cos = sin(A+B) + sin(A–B)"
AM ≥ GM ≥ HM  →  always holds for positive numbers
De Morgan's: "NOT(A OR B) = (NOT A) AND (NOT B)"
Conic eccentricity: circle=0, ellipse<1, parabola=1, hyperbola>1
For GP: b² = ac (geometric mean condition)
Euler's: e^(iπ) + 1 = 0 — the most beautiful equation
```

---

## 📊 Summary Table: Chapters vs JEE Weightage (Class 11)

| Chapter | Approximate Weightage |
|---------|----------------------|
| Trigonometric Functions | ~10-14% |
| Sequences & Series | ~8-12% |
| Complex Numbers & Quadratic | ~8-10% |
| Conic Sections | ~8-12% |
| Permutations & Combinations | ~6-8% |
| Binomial Theorem | ~5-8% |
| Limits & Derivatives | ~7-10% |
| Straight Lines | ~6-8% |
| Statistics | ~4-6% |
| Sets | ~2-4% |
| Relations & Functions | ~2-4% |
| Probability (Class 11) | ~4-6% |
| Linear Inequalities | ~2-3% |
| 3D Geometry (Intro) | ~2-4% |

---


# 📐 Class 12 IIT JEE Mathematics — Complete Theory & Formula Sheet

> **Coverage:** All chapters as per NCERT + JEE Advanced/Mains syllabus  
> **Level:** Class 12 | **Exam:** IIT JEE Mains & Advanced  
> **Author:** Study Reference Guide  

---

## 📋 Table of Contents

1. [Relations and Functions](#1-relations-and-functions)
2. [Inverse Trigonometric Functions](#2-inverse-trigonometric-functions)
3. [Matrices](#3-matrices)
4. [Determinants](#4-determinants)
5. [Continuity and Differentiability](#5-continuity-and-differentiability)
6. [Applications of Derivatives](#6-applications-of-derivatives)
7. [Integrals (Indefinite)](#7-integrals-indefinite)
8. [Definite Integrals](#8-definite-integrals)
9. [Applications of Integrals](#9-applications-of-integrals)
10. [Differential Equations](#10-differential-equations)
11. [Vector Algebra](#11-vector-algebra)
12. [Three Dimensional Geometry](#12-three-dimensional-geometry)
13. [Linear Programming](#13-linear-programming)
14. [Probability](#14-probability)

---

## 1. Relations and Functions

### 📖 Theory

| Term | Definition |
|------|-----------|
| **Relation** | A subset R of A × B. If (a, b) ∈ R, we write aRb. |
| **Function** | A relation where every element of domain has exactly one image. |
| **Domain** | Set of all first elements (inputs). |
| **Codomain** | Set from which outputs are taken. |
| **Range** | Set of all actual outputs. |

### Types of Relations
- **Reflexive:** aRa ∀ a ∈ A
- **Symmetric:** aRb ⟹ bRa
- **Transitive:** aRb and bRc ⟹ aRc
- **Equivalence:** Reflexive + Symmetric + Transitive

### Types of Functions
- **One-One (Injective):** f(a) = f(b) ⟹ a = b
- **Onto (Surjective):** Range = Codomain
- **Bijective:** One-One + Onto
- **Many-One:** Two or more elements map to same image

### 📐 Key Formulas

```
Number of relations from A to B = 2^(|A| × |B|)
Number of functions from A to B = |B|^|A|
Number of one-one functions (|A| ≤ |B|) = P(|B|, |A|) = |B|! / (|B|-|A|)!
Number of onto functions from A(m) to B(n):
  = Σ(-1)^r × C(n,r) × (n-r)^m  [r from 0 to n]
```

### Composition of Functions
```
(g∘f)(x) = g(f(x))
(f∘g)(x) = f(g(x))
(g∘f) ≠ (f∘g) in general
```

### Inverse Function
```
If f: A → B is bijective, then f⁻¹: B → A exists.
f(f⁻¹(y)) = y and f⁻¹(f(x)) = x
(f∘g)⁻¹ = g⁻¹∘f⁻¹
```

---

## 2. Inverse Trigonometric Functions

### 📖 Theory

| Function | Domain | Range (Principal Value) |
|----------|--------|------------------------|
| sin⁻¹(x) | [-1, 1] | [-π/2, π/2] |
| cos⁻¹(x) | [-1, 1] | [0, π] |
| tan⁻¹(x) | ℝ | (-π/2, π/2) |
| cot⁻¹(x) | ℝ | (0, π) |
| sec⁻¹(x) | (-∞,-1]∪[1,∞) | [0,π] - {π/2} |
| cosec⁻¹(x) | (-∞,-1]∪[1,∞) | [-π/2,π/2] - {0} |

### 📐 Key Formulas

#### Negative Argument Properties
```
sin⁻¹(-x) = -sin⁻¹(x)
cos⁻¹(-x) = π - cos⁻¹(x)
tan⁻¹(-x) = -tan⁻¹(x)
cot⁻¹(-x) = π - cot⁻¹(x)
sec⁻¹(-x) = π - sec⁻¹(x)
cosec⁻¹(-x) = -cosec⁻¹(x)
```

#### Complementary Angle Identities
```
sin⁻¹(x) + cos⁻¹(x) = π/2      (for x ∈ [-1,1])
tan⁻¹(x) + cot⁻¹(x) = π/2      (for x ∈ ℝ)
sec⁻¹(x) + cosec⁻¹(x) = π/2    (for |x| ≥ 1)
```

#### Reciprocal Relations
```
sin⁻¹(1/x) = cosec⁻¹(x)        (|x| ≥ 1)
cos⁻¹(1/x) = sec⁻¹(x)          (|x| ≥ 1)
tan⁻¹(1/x) = cot⁻¹(x)          (x > 0)
tan⁻¹(1/x) = -π + cot⁻¹(x)    (x < 0)
```

#### Addition Formulas
```
sin⁻¹(x) + sin⁻¹(y) = sin⁻¹(x√(1-y²) + y√(1-x²))    [if x²+y² ≤ 1]
                      = π - sin⁻¹(x√(1-y²) + y√(1-x²))  [if x²+y² > 1, x,y > 0]

cos⁻¹(x) + cos⁻¹(y) = cos⁻¹(xy - √(1-x²)√(1-y²))     [x+y ≥ 0]
                      = 2π - cos⁻¹(xy - √(1-x²)√(1-y²)) [x+y < 0]

tan⁻¹(x) + tan⁻¹(y) = tan⁻¹((x+y)/(1-xy))             [xy < 1]
                      = π + tan⁻¹((x+y)/(1-xy))          [xy > 1, x > 0]
                      = -π + tan⁻¹((x+y)/(1-xy))         [xy > 1, x < 0]

tan⁻¹(x) - tan⁻¹(y) = tan⁻¹((x-y)/(1+xy))             [xy > -1]
```

#### Double & Triple Angle
```
2sin⁻¹(x) = sin⁻¹(2x√(1-x²))          [|x| ≤ 1/√2]
2cos⁻¹(x) = cos⁻¹(2x²-1)              [0 ≤ x ≤ 1]
2tan⁻¹(x) = tan⁻¹(2x/(1-x²))          [|x| < 1]
           = sin⁻¹(2x/(1+x²))
           = cos⁻¹((1-x²)/(1+x²))

3sin⁻¹(x) = sin⁻¹(3x - 4x³)
3cos⁻¹(x) = cos⁻¹(4x³ - 3x)
3tan⁻¹(x) = tan⁻¹((3x-x³)/(1-3x²))
```

---

## 3. Matrices

### 📖 Theory

- **Matrix:** Rectangular array of numbers arranged in rows and columns.
- **Order:** m × n (m rows, n columns)
- **Square Matrix:** m = n
- **Diagonal Matrix:** aᵢⱼ = 0 for i ≠ j
- **Scalar Matrix:** Diagonal matrix with all diagonal elements equal
- **Identity Matrix (I):** Diagonal matrix with all diagonal elements = 1
- **Zero Matrix (O):** All elements = 0
- **Symmetric Matrix:** A = Aᵀ (aᵢⱼ = aⱼᵢ)
- **Skew-Symmetric:** A = -Aᵀ (aᵢⱼ = -aⱼᵢ, diagonal elements = 0)

### 📐 Key Formulas

#### Basic Operations
```
(A + B)ᵀ = Aᵀ + Bᵀ
(AB)ᵀ = BᵀAᵀ        (Reversal law)
(kA)ᵀ = kAᵀ
(Aᵀ)ᵀ = A
(AB)C = A(BC)        (Associative)
A(B+C) = AB + AC     (Distributive)
AI = IA = A
```

#### Symmetric / Skew Decomposition
```
Every square matrix A can be written as:
A = P + Q
where P = (A + Aᵀ)/2   [Symmetric part]
      Q = (A - Aᵀ)/2   [Skew-Symmetric part]
```

#### Trace of Matrix
```
tr(A) = sum of diagonal elements
tr(A+B) = tr(A) + tr(B)
tr(kA) = k·tr(A)
tr(AB) = tr(BA)
```

### Invertible Matrix
```
AA⁻¹ = A⁻¹A = I
(AB)⁻¹ = B⁻¹A⁻¹      (Reversal law)
(Aᵀ)⁻¹ = (A⁻¹)ᵀ
(A⁻¹)⁻¹ = A
det(A⁻¹) = 1/det(A)
```

### Elementary Row/Column Operations
```
Rᵢ ↔ Rⱼ   (Interchange)
Rᵢ → kRᵢ  (Scalar multiplication)
Rᵢ → Rᵢ + kRⱼ  (Row addition)
```

---

## 4. Determinants

### 📖 Theory

- Determinant is a scalar associated with every square matrix.
- Determinant of order 1: |a| = a
- Singular Matrix: det(A) = 0 (not invertible)
- Non-Singular: det(A) ≠ 0

### 📐 Key Formulas

#### 2×2 Determinant
```
|a  b|
|c  d| = ad - bc
```

#### 3×3 Determinant (Expansion along R₁)
```
|a₁ b₁ c₁|
|a₂ b₂ c₂| = a₁(b₂c₃ - b₃c₂) - b₁(a₂c₃ - a₃c₂) + c₁(a₂b₃ - a₃b₂)
|a₃ b₃ c₃|
```

#### Properties of Determinants
```
det(Aᵀ) = det(A)
det(AB) = det(A)·det(B)
det(kA) = kⁿ·det(A)    [n = order of matrix]
det(A⁻¹) = 1/det(A)
det(Aⁿ) = [det(A)]ⁿ
```

- If two rows/columns are identical → det = 0
- If any row/column is all zero → det = 0
- Interchanging two rows/columns → det changes sign
- Multiplying a row/column by k → det multiplied by k

#### Cofactor & Adjoint
```
Cofactor Cᵢⱼ = (-1)^(i+j) × Mᵢⱼ   (Mᵢⱼ = minor)

adj(A) = transpose of cofactor matrix

A⁻¹ = adj(A) / det(A)

A · adj(A) = adj(A) · A = det(A) · I

det(adj A) = [det(A)]^(n-1)

adj(adj A) = [det(A)]^(n-2) · A
```

#### Cramer's Rule (for AX = B)
```
x = D₁/D,   y = D₂/D,   z = D₃/D
where D = det(A), and D₁, D₂, D₃ replace respective columns with B
```

#### Area of Triangle
```
Area = (1/2)|x₁(y₂-y₃) + x₂(y₃-y₁) + x₃(y₁-y₂)|

In determinant form:
Area = (1/2)|x₁ y₁ 1|
            |x₂ y₂ 1|
            |x₃ y₃ 1|

Collinear condition: Area = 0
```

---

## 5. Continuity and Differentiability

### 📖 Theory

#### Continuity at a Point
```
f(x) is continuous at x = a if:
1. f(a) is defined
2. lim(x→a) f(x) exists
3. lim(x→a) f(x) = f(a)

i.e., LHL = RHL = f(a)
```

#### Differentiability at a Point
```
f'(a) = lim(h→0) [f(a+h) - f(a)] / h

LHD = lim(h→0⁻) [f(a+h) - f(a)] / h
RHD = lim(h→0⁺) [f(a+h) - f(a)] / h

Differentiable ⟹ Continuous (converse not always true)
```

### 📐 Differentiation Formulas

#### Standard Derivatives
```
d/dx (xⁿ) = nxⁿ⁻¹
d/dx (eˣ) = eˣ
d/dx (aˣ) = aˣ ln a
d/dx (ln x) = 1/x
d/dx (logₐ x) = 1/(x ln a)
d/dx (sin x) = cos x
d/dx (cos x) = -sin x
d/dx (tan x) = sec²x
d/dx (cot x) = -cosec²x
d/dx (sec x) = sec x tan x
d/dx (cosec x) = -cosec x cot x
```

#### Inverse Trig Derivatives
```
d/dx (sin⁻¹ x) = 1/√(1-x²)
d/dx (cos⁻¹ x) = -1/√(1-x²)
d/dx (tan⁻¹ x) = 1/(1+x²)
d/dx (cot⁻¹ x) = -1/(1+x²)
d/dx (sec⁻¹ x) = 1/(|x|√(x²-1))
d/dx (cosec⁻¹x) = -1/(|x|√(x²-1))
```

#### Rules of Differentiation
```
(u ± v)' = u' ± v'
(uv)' = u'v + uv'                 (Product Rule)
(u/v)' = (u'v - uv') / v²        (Quotient Rule)
dy/dx = (dy/du)·(du/dx)           (Chain Rule)
```

#### Logarithmic Differentiation
```
If y = [f(x)]^g(x), take ln both sides:
ln y = g(x) · ln[f(x)]
Then differentiate both sides.
```

#### Parametric Differentiation
```
If x = f(t), y = g(t):
dy/dx = (dy/dt)/(dx/dt) = g'(t)/f'(t)

d²y/dx² = d/dx(dy/dx) = [d/dt(dy/dx)] / (dx/dt)
```

#### Implicit Differentiation
```
For F(x,y) = 0:
dy/dx = -∂F/∂x / ∂F/∂y
```

#### Higher Order Derivatives
```
y'' = d²y/dx² = d/dx(dy/dx)
Leibnitz Theorem:
(uv)ⁿ = Σ C(n,r) · u^(n-r) · v^(r)   [r = 0 to n]
```

#### Rolle's Theorem
```
If f is continuous on [a,b], differentiable on (a,b), and f(a) = f(b)
Then ∃ c ∈ (a,b) such that f'(c) = 0
```

#### Lagrange's Mean Value Theorem (LMVT)
```
If f is continuous on [a,b] and differentiable on (a,b):
∃ c ∈ (a,b) such that f'(c) = [f(b) - f(a)] / (b - a)
```

---

## 6. Applications of Derivatives

### 📖 Theory

#### Rate of Change
```
Rate of change of y w.r.t. x = dy/dx
```

#### Tangent and Normal
```
Slope of tangent at (x₁, y₁) = m = [dy/dx] at (x₁,y₁)

Equation of tangent: y - y₁ = m(x - x₁)
Equation of normal: y - y₁ = -1/m · (x - x₁)

Length of tangent  = y√(1 + (dx/dy)²)
Length of normal   = y√(1 + (dy/dx)²)
Length of subtangent = |y/(dy/dx)|
Length of subnormal  = |y·(dy/dx)|
```

#### Increasing / Decreasing
```
f'(x) > 0 → f is strictly increasing on interval
f'(x) < 0 → f is strictly decreasing on interval
f'(x) = 0 → critical point (check further)
```

#### Maxima and Minima
```
First Derivative Test:
  f'(x) changes + to - at x=c → Local Maximum
  f'(x) changes - to + at x=c → Local Minimum
  f'(x) doesn't change sign   → Neither (point of inflection)

Second Derivative Test:
  f'(c) = 0 and f''(c) < 0 → Local Maximum
  f'(c) = 0 and f''(c) > 0 → Local Minimum
  f'(c) = 0 and f''(c) = 0 → Test fails, use higher derivatives

Absolute max/min: Evaluate f at critical points + endpoints of [a,b]
```

#### Approximation
```
f(x + Δx) ≈ f(x) + Δx · f'(x)
Δy ≈ dy = f'(x)·dx
```

---

## 7. Integrals (Indefinite)

### 📐 Standard Integration Formulas

#### Basic Forms
```
∫ xⁿ dx = xⁿ⁺¹/(n+1) + C    (n ≠ -1)
∫ 1/x dx = ln|x| + C
∫ eˣ dx = eˣ + C
∫ aˣ dx = aˣ/ln(a) + C
∫ 1 dx = x + C
```

#### Trigonometric
```
∫ sin x dx = -cos x + C
∫ cos x dx = sin x + C
∫ tan x dx = ln|sec x| + C  = -ln|cos x| + C
∫ cot x dx = ln|sin x| + C
∫ sec x dx = ln|sec x + tan x| + C
∫ cosec x dx = ln|cosec x - cot x| + C
∫ sec²x dx = tan x + C
∫ cosec²x dx = -cot x + C
∫ sec x tan x dx = sec x + C
∫ cosec x cot x dx = -cosec x + C
```

#### Inverse Trigonometric Forms
```
∫ 1/√(1-x²) dx = sin⁻¹(x) + C
∫ -1/√(1-x²) dx = cos⁻¹(x) + C
∫ 1/(1+x²) dx = tan⁻¹(x) + C
∫ -1/(1+x²) dx = cot⁻¹(x) + C
∫ 1/(|x|√(x²-1)) dx = sec⁻¹(x) + C
```

#### Important Standard Integrals
```
∫ 1/(x²-a²) dx = 1/(2a) ln|(x-a)/(x+a)| + C
∫ 1/(a²-x²) dx = 1/(2a) ln|(a+x)/(a-x)| + C
∫ 1/(x²+a²) dx = 1/a tan⁻¹(x/a) + C
∫ 1/√(x²-a²) dx = ln|x + √(x²-a²)| + C
∫ 1/√(x²+a²) dx = ln|x + √(x²+a²)| + C
∫ 1/√(a²-x²) dx = sin⁻¹(x/a) + C
∫ √(a²-x²) dx = (x/2)√(a²-x²) + (a²/2)sin⁻¹(x/a) + C
∫ √(x²+a²) dx = (x/2)√(x²+a²) + (a²/2)ln|x+√(x²+a²)| + C
∫ √(x²-a²) dx = (x/2)√(x²-a²) - (a²/2)ln|x+√(x²-a²)| + C
```

#### Integration Techniques

**Substitution:**
```
∫ f(g(x))·g'(x) dx = F(g(x)) + C
Put t = g(x)
```

**Integration by Parts:**
```
∫ u·v dx = u·∫v dx - ∫[u'·∫v dx] dx

ILATE rule (priority for u):
I – Inverse Trig
L – Logarithmic
A – Algebraic
T – Trigonometric
E – Exponential
```

**Special Integration by Parts:**
```
∫ eˣ[f(x) + f'(x)] dx = eˣ f(x) + C
∫ [xf'(x) + f(x)] dx = xf(x) + C
```

**Partial Fractions:**
```
For (px+q)/[(x-a)(x-b)] = A/(x-a) + B/(x-b)
For (px+q)/[(x-a)²] = A/(x-a) + B/(x-a)²
For (px²+qx+r)/[(x-a)(x²+bx+c)] = A/(x-a) + (Bx+C)/(x²+bx+c)
```

**Trigonometric Substitutions:**
```
√(a²-x²) → x = a sinθ
√(a²+x²) → x = a tanθ
√(x²-a²) → x = a secθ
```

**Integrals of type ∫ sin^m(x) cos^n(x) dx:**
```
If m or n is odd → substitute the other function
If both even → use half-angle formulas:
  sin²x = (1-cos2x)/2
  cos²x = (1+cos2x)/2
  sinx·cosx = sin2x/2
```

**Type: ∫(a·sin x + b·cos x)/(c·sin x + d·cos x) dx**
```
Write numerator = A·(denominator) + B·(derivative of denominator)
Solve for A and B
```

**Type: ∫ dx/(a + b·sin²x) or ∫ dx/(a + b·cos²x)**
```
Divide num and den by cos²x, then substitute t = tan x
```

**Type: ∫ dx/(a·sinx + b·cosx)**
```
Use: a·sinx + b·cosx = R·sin(x+φ)
where R = √(a²+b²), tanφ = b/a
```

---

## 8. Definite Integrals

### 📐 Key Formulas

#### Fundamental Theorem
```
∫[a to b] f(x) dx = F(b) - F(a)   where F'(x) = f(x)
```

#### Properties of Definite Integrals
```
P1: ∫[a to b] f(x) dx = -∫[b to a] f(x) dx

P2: ∫[a to b] f(x) dx = ∫[a to c] f(x) dx + ∫[c to b] f(x) dx

P3: ∫[a to b] f(x) dx = ∫[a to b] f(a+b-x) dx

P4: ∫[0 to a] f(x) dx = ∫[0 to a] f(a-x) dx

P5: ∫[0 to 2a] f(x) dx = 2∫[0 to a] f(x) dx   if f(2a-x) = f(x)
                        = 0                        if f(2a-x) = -f(x)

P6 (Even/Odd functions):
    ∫[-a to a] f(x) dx = 2∫[0 to a] f(x) dx   if f(-x) = f(x) [Even]
                       = 0                        if f(-x) = -f(x) [Odd]

P7 (Periodicity):
    ∫[0 to nT] f(x) dx = n·∫[0 to T] f(x) dx   [T = period]
    ∫[a to a+T] f(x) dx = ∫[0 to T] f(x) dx
```

#### Leibnitz Rule (Differentiation under integral)
```
d/dx [∫[g(x) to h(x)] f(t) dt] = f(h(x))·h'(x) - f(g(x))·g'(x)
```

#### Walli's Formula
```
∫[0 to π/2] sinⁿx dx = ∫[0 to π/2] cosⁿx dx

If n is even: = [(n-1)(n-3)...2·1] / [n(n-2)...3·1] × π/2
If n is odd:  = [(n-1)(n-3)...3·1] / [n(n-2)...4·2]
```

---

## 9. Applications of Integrals

### 📐 Key Formulas

#### Area Under Curve
```
Area between y = f(x) and x-axis from x=a to x=b:
A = ∫[a to b] |f(x)| dx

If f(x) ≥ 0: A = ∫[a to b] f(x) dx
If f(x) ≤ 0: A = -∫[a to b] f(x) dx
```

#### Area Between Two Curves
```
A = ∫[a to b] [f(x) - g(x)] dx    where f(x) ≥ g(x) on [a,b]
```

#### Area w.r.t. Y-axis
```
A = ∫[c to d] |x| dy = ∫[c to d] |g(y)| dy
```

#### Standard Areas
```
Area of circle x²+y² = a²:           πa²
Area of ellipse x²/a² + y²/b² = 1:   πab
Area of parabola y² = 4ax (up to x=h): (8/3)a·h^(3/2) ... generally computed by integration
```

---

## 10. Differential Equations

### 📖 Theory

- **Order:** Highest derivative present
- **Degree:** Power of highest derivative (after making it polynomial in derivatives)
- **Linear DE:** Highest power of dependent variable and its derivatives = 1
- **General Solution:** Contains arbitrary constants equal to order
- **Particular Solution:** Constants determined using initial conditions

### 📐 Key Formulas

#### Variable Separable
```
f(x) dx = g(y) dy
∫f(x) dx = ∫g(y) dy + C
```

#### Homogeneous DE (dy/dx = f(y/x))
```
Substitute y = vx → dy/dx = v + x·dv/dx
Separate variables in v and x
```

#### Linear DE of First Order
```
Form: dy/dx + Py = Q    (P, Q functions of x)

Integrating Factor (IF) = e^(∫P dx)
Solution: y × IF = ∫(Q × IF) dx + C

Form: dx/dy + Px = Q    (P, Q functions of y)
IF = e^(∫P dy)
```

#### Bernoulli's Equation
```
dy/dx + Py = Qyⁿ
Divide by yⁿ, substitute z = y^(1-n)
Reduces to linear DE.
```

#### Second Order Linear DE (Constant Coefficients)
```
ay'' + by' + cy = 0

Auxiliary equation: am² + bm + c = 0
Roots m₁, m₂:
  - Real & distinct: y = C₁e^(m₁x) + C₂e^(m₂x)
  - Real & equal:    y = (C₁ + C₂x)e^(mx)
  - Complex (α±iβ):  y = eᵅˣ(C₁cosβx + C₂sinβx)
```

#### Exact DE
```
M dx + N dy = 0 is exact if ∂M/∂y = ∂N/∂x
Solution: ∫M dx (treating y as const) + ∫(terms of N not containing x) dy = C
```

---

## 11. Vector Algebra

### 📖 Theory

- **Scalar:** Magnitude only (e.g., mass, temperature)
- **Vector:** Magnitude + Direction (e.g., force, velocity)
- **Position Vector:** Vector from origin O to point P = **OP**
- **Unit Vector:** â = **a**/|**a**| (magnitude = 1)
- **Zero Vector:** Magnitude = 0

### 📐 Key Formulas

#### Magnitude
```
If a = a₁î + a₂ĵ + a₃k̂
|a| = √(a₁² + a₂² + a₃²)
```

#### Section Formula
```
Point dividing PQ in ratio m:n (internally):
r = (m·b + n·a) / (m+n)

Externally:
r = (m·b - n·a) / (m-n)

Midpoint: r = (a+b)/2
```

#### Dot Product (Scalar Product)
```
a·b = |a||b|cosθ
a·b = a₁b₁ + a₂b₂ + a₃b₃

cosθ = (a·b) / (|a||b|)

a·a = |a|²
î·î = ĵ·ĵ = k̂·k̂ = 1
î·ĵ = ĵ·k̂ = k̂·î = 0

Projection of a on b = (a·b)/|b|
Projection vector = [(a·b)/|b|²] b

a⊥b ⟺ a·b = 0
```

#### Cross Product (Vector Product)
```
a×b = |a||b|sinθ n̂

a×b = |î  ĵ  k̂ |
      |a₁ a₂ a₃|
      |b₁ b₂ b₃|

î×î = ĵ×ĵ = k̂×k̂ = 0
î×ĵ = k̂,  ĵ×k̂ = î,  k̂×î = ĵ
ĵ×î = -k̂, k̂×ĵ = -î, î×k̂ = -ĵ

|a×b| = Area of parallelogram with sides a and b
Area of triangle = (1/2)|a×b|

a∥b ⟺ a×b = 0

(a×b)·c = a·(b×c)   [Scalar Triple Product]
```

#### Scalar Triple Product (Box Product)
```
[a b c] = a·(b×c) = b·(c×a) = c·(a×b)

[a b c] = |a₁ a₂ a₃|
           |b₁ b₂ b₃|
           |c₁ c₂ c₃|

Volume of parallelepiped = |[a b c]|
Volume of tetrahedron = (1/6)|[a b c]|
Coplanar vectors: [a b c] = 0
```

#### Vector Triple Product
```
a×(b×c) = (a·c)b - (a·b)c
(a×b)×c = (a·c)b - (b·c)a
```

---

## 12. Three Dimensional Geometry

### 📖 Theory

#### Direction Cosines & Ratios
```
Direction cosines: l = cosα, m = cosβ, n = cosγ
l² + m² + n² = 1

If direction ratios are a, b, c:
l = a/√(a²+b²+c²), m = b/√(a²+b²+c²), n = c/√(a²+b²+c²)
```

### 📐 Key Formulas

#### Equation of a Line

**Vector Form:**
```
r = a + λb
where a = position vector of a point, b = direction vector
```

**Cartesian Form:**
```
(x-x₁)/l = (y-y₁)/m = (z-z₁)/n = λ
```

**Line through two points:**
```
(x-x₁)/(x₂-x₁) = (y-y₁)/(y₂-y₁) = (z-z₁)/(z₂-z₁)
```

#### Angle Between Lines
```
cosθ = |l₁l₂ + m₁m₂ + n₁n₂|
cosθ = |a₁a₂ + b₁b₂ + c₁c₂| / (√(a₁²+b₁²+c₁²) × √(a₂²+b₂²+c₂²))

Parallel:   a₁/a₂ = b₁/b₂ = c₁/c₂
Perpendicular: a₁a₂ + b₁b₂ + c₁c₂ = 0
```

#### Distance Formulas
```
Distance of point P(x₁,y₁,z₁) from line:
d = |b × (a₁-a)| / |b|

Distance between parallel lines:
d = |b × (a₂-a₁)| / |b|

Shortest distance between skew lines:
r = a₁ + λb₁ and r = a₂ + μb₂
SD = |(a₂-a₁)·(b₁×b₂)| / |b₁×b₂|

Lines are coplanar if: (a₂-a₁)·(b₁×b₂) = 0
```

#### Equation of a Plane

**Vector Form:**
```
r·n̂ = d    (n̂ = unit normal)
r·n = p     (n = normal vector)
```

**Cartesian/Normal Form:**
```
ax + by + cz = d
lx + my + nz = p   (l,m,n = direction cosines of normal)
```

**Plane through 3 points:**
```
|x-x₁  y-y₁  z-z₁|
|x₂-x₁ y₂-y₁ z₂-z₁| = 0
|x₃-x₁ y₃-y₁ z₃-z₁|
```

**Intercept Form:**
```
x/a + y/b + z/c = 1
```

#### Angle Between Plane and Line
```
sinθ = |a·b| / (|a||b|)
where a = normal to plane, b = direction of line

Line ⊥ plane: direction of line ∥ normal
Line ∥ plane: direction of line ⊥ normal → a·b = 0
```

#### Angle Between Two Planes
```
cosθ = |n₁·n₂| / (|n₁||n₂|)
     = |a₁a₂+b₁b₂+c₁c₂| / (√(a₁²+b₁²+c₁²) × √(a₂²+b₂²+c₂²))

Planes ∥: a₁/a₂ = b₁/b₂ = c₁/c₂
Planes ⊥: a₁a₂ + b₁b₂ + c₁c₂ = 0
```

#### Distance Formulas (Planes)
```
Distance of point (x₁,y₁,z₁) from plane ax+by+cz+d=0:
D = |ax₁+by₁+cz₁+d| / √(a²+b²+c²)

Distance between parallel planes ax+by+cz=d₁ and ax+by+cz=d₂:
D = |d₁-d₂| / √(a²+b²+c²)
```

---

## 13. Linear Programming

### 📖 Theory

- **Objective Function:** Linear function Z = ax + by to be optimized (max/min)
- **Constraints:** Linear inequalities in x, y
- **Feasible Region:** Set of all points satisfying all constraints
- **Feasible Solution:** Point in feasible region
- **Optimal Solution:** Feasible solution that optimizes Z
- **Corner Point Method:** Optimal value of Z always occurs at a corner (vertex) of feasible region

### Key Theorems
```
Theorem 1: If the feasible region is bounded, optimal solution exists at a corner point.

Theorem 2: If Z = ax+by is max at two adjacent corners, it is max at all points on
           the line segment joining those corners.

Theorem 3: If feasible region is unbounded, optimal solution may or may not exist.
```

### Steps to Solve LPP
```
1. Identify decision variables (x, y)
2. Formulate objective function Z = ax + by
3. Write all constraints as linear inequalities
4. Add non-negativity constraints x ≥ 0, y ≥ 0
5. Graph the feasible region
6. Find corner points (vertices)
7. Evaluate Z at each corner point
8. Choose optimal value
```

---

## 14. Probability

### 📖 Theory

- **Sample Space (S):** Set of all possible outcomes
- **Event (E):** Subset of sample space
- **Probability:** P(E) = n(E)/n(S), 0 ≤ P(E) ≤ 1
- **Complementary Event:** P(E') = 1 - P(E)

### 📐 Key Formulas

#### Basic Laws
```
P(A ∪ B) = P(A) + P(B) - P(A ∩ B)
P(A ∩ B') = P(A) - P(A ∩ B)
P(A' ∩ B) = P(B) - P(A ∩ B)
P(A' ∩ B') = 1 - P(A ∪ B)

For mutually exclusive events A and B:
P(A ∩ B) = 0 → P(A ∪ B) = P(A) + P(B)
```

#### Conditional Probability
```
P(A|B) = P(A ∩ B) / P(B)    [P(B) ≠ 0]
P(B|A) = P(A ∩ B) / P(A)    [P(A) ≠ 0]

P(A ∩ B) = P(A|B) × P(B) = P(B|A) × P(A)
```

#### Independent Events
```
A and B are independent if:
P(A ∩ B) = P(A) × P(B)
P(A|B) = P(A)
P(B|A) = P(B)

For n independent events:
P(A₁ ∩ A₂ ∩ ... ∩ Aₙ) = P(A₁)×P(A₂)×...×P(Aₙ)
```

#### Total Probability Theorem
```
If B₁, B₂, ..., Bₙ are mutually exclusive and exhaustive events:
P(A) = Σ P(Bᵢ) × P(A|Bᵢ)   [i = 1 to n]
```

#### Bayes' Theorem
```
P(Bᵢ|A) = [P(Bᵢ) × P(A|Bᵢ)] / [Σ P(Bⱼ) × P(A|Bⱼ)]
```

#### Binomial Distribution
```
X ~ B(n, p)  →  n = trials, p = success probability, q = 1-p

P(X = r) = C(n,r) × pʳ × qⁿ⁻ʳ   (r = 0,1,2,...,n)

Mean:     μ = E(X) = np
Variance: σ² = Var(X) = npq
Std Dev:  σ = √(npq)

Mode: 
  If (n+1)p is not integer → mode = ⌊(n+1)p⌋
  If (n+1)p is integer → two modes: (n+1)p and (n+1)p - 1
```

#### Random Variable and Expectation
```
E(X) = Σ xᵢ P(xᵢ)
E(X²) = Σ xᵢ² P(xᵢ)
Var(X) = E(X²) - [E(X)]²
E(aX + b) = aE(X) + b
Var(aX + b) = a²Var(X)
```

---

## 🎯 Important JEE Tips & Tricks

### Quick Recognition Patterns

```
✦ If integrand has √(a²-x²) → use x = a sinθ
✦ If integrand has √(a²+x²) → use x = a tanθ
✦ If integrand has √(x²-a²) → use x = a secθ
✦ For det shortcuts: if any 2 rows same → det = 0
✦ For probability: when events are said "at least once", use complement
✦ For 3D: shortest distance between lines involves cross product
✦ Rolle's Theorem requires f(a) = f(b) — check this first!
✦ For maxima/minima: always verify endpoints too
✦ Binomial theorem probability: expand (p+q)ⁿ where p+q=1
✦ Two planes always intersect in a line unless parallel
```

### Memory Aids

```
ILATE for Integration by Parts
PEMDAS for order of operations
"Reversal Law" for transpose: (AB)ᵀ = BᵀAᵀ, (AB)⁻¹ = B⁻¹A⁻¹
sin⁻¹ + cos⁻¹ = π/2 (complementary pair)
Direction cosines: l² + m² + n² = 1 (always!)
```

---

## 📊 Summary Table: Chapters vs JEE Weightage

| Chapter | Approximate Weightage |
|---------|----------------------|
| Integrals (Indef + Def) | ~15-20% |
| Probability | ~10-12% |
| 3D Geometry | ~10-12% |
| Differential Equations | ~8-10% |
| Matrices & Determinants | ~8-10% |
| Vectors | ~8-10% |
| Application of Derivatives | ~8-10% |
| Continuity & Differentiability | ~6-8% |
| Inverse Trig Functions | ~4-6% |
| Relations & Functions | ~3-5% |
| Application of Integrals | ~3-5% |
| Linear Programming | ~3-4% |

---

# 🚀 IIT JEE CLASS 11 PHYSICS — COMPLETE NOTES
### Every Concept | Every Formula | Every Detail

> **Syllabus Coverage:** Complete NCERT + JEE Advanced Level  
> **Chapters:** Units & Measurement → Thermodynamics → Kinetic Theory → Oscillations → Waves

---

## 📚 TABLE OF CONTENTS

1. [Units & Measurements](#1-units--measurements)
2. [Motion in a Straight Line (Kinematics 1D)](#2-motion-in-a-straight-line)
3. [Motion in a Plane (Kinematics 2D)](#3-motion-in-a-plane)
4. [Laws of Motion (Newton's Laws)](#4-laws-of-motion)
5. [Work, Energy & Power](#5-work-energy--power)
6. [System of Particles & Rotational Motion](#6-system-of-particles--rotational-motion)
7. [Gravitation](#7-gravitation)
8. [Mechanical Properties of Solids](#8-mechanical-properties-of-solids)
9. [Mechanical Properties of Fluids](#9-mechanical-properties-of-fluids)
10. [Thermal Properties of Matter](#10-thermal-properties-of-matter)
11. [Thermodynamics](#11-thermodynamics)
12. [Kinetic Theory of Gases](#12-kinetic-theory-of-gases)
13. [Oscillations (SHM)](#13-oscillations-shm)
14. [Waves](#14-waves)

---

# 1. UNITS & MEASUREMENTS

## 1.1 Physical Quantities

A **physical quantity** is anything that can be measured. Every physical quantity = **Numerical value × Unit**

### Types:
| Type | Definition | Examples |
|------|-----------|---------|
| **Fundamental (Base)** | Cannot be expressed in terms of others | Mass, Length, Time, Temperature, Current, Amount of substance, Luminous intensity |
| **Derived** | Expressed using fundamental quantities | Force, Velocity, Pressure, Energy |
| **Supplementary** | Plane angle (radian), Solid angle (steradian) |

## 1.2 SI System — 7 Base Units

| Quantity | Unit | Symbol |
|----------|------|--------|
| Length | metre | m |
| Mass | kilogram | kg |
| Time | second | s |
| Electric current | ampere | A |
| Temperature | kelvin | K |
| Amount of substance | mole | mol |
| Luminous intensity | candela | cd |

## 1.3 Dimensions

**Dimensional formula** expresses a physical quantity in terms of **M** (Mass), **L** (Length), **T** (Time), **A** (current), **K** (temperature), etc.

### Key Dimensional Formulas:

| Quantity | Formula | Dimensions |
|---------|---------|-----------|
| Velocity | v = L/T | [M⁰L¹T⁻¹] |
| Acceleration | a = L/T² | [M⁰L¹T⁻²] |
| Force | F = ma | [M¹L¹T⁻²] |
| Work/Energy | W = F·d | [M¹L²T⁻²] |
| Power | P = W/t | [M¹L²T⁻³] |
| Pressure | P = F/A | [M¹L⁻¹T⁻²] |
| Momentum | p = mv | [M¹L¹T⁻¹] |
| Impulse | J = F·t | [M¹L¹T⁻¹] |
| Torque | τ = r × F | [M¹L²T⁻²] |
| Angular Momentum | L = mvr | [M¹L²T⁻¹] |
| Gravitational Constant G | F = Gm₁m₂/r² | [M⁻¹L³T⁻²] |
| Planck's Constant h | E = hν | [M¹L²T⁻¹] |
| Boltzmann Constant k | PV = nkT | [M¹L²T⁻²K⁻¹] |
| Stefan's Constant σ | E = σT⁴ | [M¹L⁰T⁻³K⁻⁴] |
| Coefficient of Viscosity η | F = ηA(dv/dx) | [M¹L⁻¹T⁻¹] |
| Surface Tension | T = F/L | [M¹L⁰T⁻²] |

### Dimensional Analysis Applications:
1. **Checking correctness** — both sides must have same dimensions
2. **Deriving formulas** — find unknown exponents
3. **Unit conversion** — between systems

### Conversion Formula:
```
n₁u₁ = n₂u₂
n₂ = n₁ × [M₁/M₂]^a × [L₁/L₂]^b × [T₁/T₂]^c
```

### Limitations of Dimensional Analysis:
- Cannot determine dimensionless constants (like 2π, ½)
- Cannot distinguish between quantities with same dimensions (Work vs Torque)
- Cannot analyze equations with + or − of quantities

## 1.4 Significant Figures

**Rules:**
1. All non-zero digits are significant: 1234 → 4 sig figs
2. Zeros between non-zero digits: 1002 → 4 sig figs
3. Leading zeros (before non-zero): 0.0045 → 2 sig figs
4. Trailing zeros with decimal: 3.200 → 4 sig figs
5. Trailing zeros without decimal: 200 → ambiguous (use scientific notation)

### Operations:
- **Addition/Subtraction:** Result has same number of decimal places as the least precise operand
- **Multiplication/Division:** Result has same number of significant figures as the least precise operand

## 1.5 Errors in Measurement

### Types of Errors:
| Type | Description | Example |
|------|-------------|---------|
| **Systematic Error** | Consistent, one-directional | Instrument zero error, personal bias |
| **Random Error** | Irregular, unpredictable | Fluctuations in reading |
| **Gross Error** | Blunders by observer | Misreading scale |
| **Least Count Error** | Due to instrument resolution | ½ of smallest division |

### Error Formulas:

**Absolute Error:** `Δa = |a_mean - aᵢ|`

**Mean Absolute Error:** `Δā = (Δa₁ + Δa₂ + ... + Δaₙ) / n`

**Relative (Fractional) Error:** `Δa/a`

**Percentage Error:** `(Δa/a) × 100%`

### Error Propagation:
- **Sum/Difference:** `Z = A ± B` → `ΔZ = ΔA + ΔB`
- **Product/Division:** `Z = A × B or A/B` → `ΔZ/Z = ΔA/A + ΔB/B`
- **Power:** `Z = Aᵐ Bⁿ / Cᵖ` → `ΔZ/Z = m(ΔA/A) + n(ΔB/B) + p(ΔC/C)`

> **JEE Tip:** Maximum possible error always uses sum of individual errors.

---

# 2. MOTION IN A STRAIGHT LINE

## 2.1 Definitions

| Term | Definition | Formula |
|------|-----------|---------|
| **Distance** | Total path length (scalar) | Always ≥ 0 |
| **Displacement** | Shortest path from start to end (vector) | Can be +, −, 0 |
| **Speed** | Distance/Time (scalar) | s = d/t |
| **Velocity** | Displacement/Time (vector) | v = Δx/Δt |
| **Acceleration** | Rate of change of velocity | a = Δv/Δt |

### Average vs Instantaneous:
```
v_avg = Total Displacement / Total Time = Δx/Δt

v_inst = lim(Δt→0) Δx/Δt = dx/dt

a_avg = Δv/Δt

a_inst = dv/dt = d²x/dt²
```

## 2.2 Equations of Motion (Uniform Acceleration)

These are the **5 golden equations** — valid only when acceleration is constant:

```
① v = u + at
② s = ut + ½at²
③ v² = u² + 2as
④ s = (u + v)/2 × t
⑤ sₙ = u + a(2n − 1)/2   [Distance in nth second]
```

Where: u = initial velocity, v = final velocity, a = acceleration, t = time, s = displacement

## 2.3 Motion Under Gravity (Free Fall)

Take **downward as positive** (or upward positive — be consistent):

```
Taking upward as positive:
a = −g = −9.8 m/s² ≈ −10 m/s²

v = u − gt
h = ut − ½gt²
v² = u² − 2gh

Time to reach max height: t = u/g
Maximum height: H = u²/2g
Time of flight (return to same level): T = 2u/g
```

## 2.4 Relative Motion (1D)

```
Velocity of A relative to B: v_AB = v_A − v_B
Acceleration of A relative to B: a_AB = a_A − a_B
```

## 2.5 Graphs (Critical for JEE)

| Graph | Slope | Area Under Curve |
|-------|-------|-----------------|
| x-t graph | velocity | — |
| v-t graph | acceleration | displacement |
| a-t graph | — | change in velocity |

### Key Graph Shapes:
- **Uniform velocity:** x-t is straight line, v-t is horizontal line
- **Uniform acceleration:** x-t is parabola, v-t is straight line
- **SHM:** x-t is sinusoidal

---

# 3. MOTION IN A PLANE

## 3.1 Vectors

### Basic Operations:
```
Addition: A⃗ + B⃗ (Triangle / Parallelogram law)
Subtraction: A⃗ − B⃗ = A⃗ + (−B⃗)
Scalar multiplication: k·A⃗
```

### Resultant of Two Vectors:
```
R = √(A² + B² + 2AB·cosθ)

tan α = B·sinθ / (A + B·cosθ)
```
Where θ = angle between A⃗ and B⃗, α = angle of R with A⃗

### Dot Product (Scalar Product):
```
A⃗ · B⃗ = AB·cosθ
A⃗ · B⃗ = AₓBₓ + AᵧBᵧ + AᵤBᵤ

Properties:
- Commutative: A⃗ · B⃗ = B⃗ · A⃗
- î·î = ĵ·ĵ = k̂·k̂ = 1
- î·ĵ = ĵ·k̂ = k̂·î = 0
```

### Cross Product (Vector Product):
```
|A⃗ × B⃗| = AB·sinθ (direction: right-hand rule)

A⃗ × B⃗ = |î  ĵ  k̂ |
           |Aₓ Aᵧ Aᵤ|
           |Bₓ Bᵧ Bᵤ|

Properties:
- Anti-commutative: A⃗ × B⃗ = −(B⃗ × A⃗)
- î×î = ĵ×ĵ = k̂×k̂ = 0
- î×ĵ = k̂, ĵ×k̂ = î, k̂×î = ĵ
```

## 3.2 Projectile Motion

**Conditions:** No air resistance, g = constant, horizontal & vertical motions are independent

### Setup:
- Launch angle: θ with horizontal
- Initial velocity: u
- Horizontal: uₓ = u·cosθ (constant throughout)
- Vertical: uᵧ = u·sinθ (changes due to g)

### Key Equations:
```
Horizontal: x = u·cosθ·t
Vertical: y = u·sinθ·t − ½gt²

Equation of trajectory:
y = x·tanθ − gx²/(2u²cos²θ)   ← This is a PARABOLA

Time of flight: T = 2u·sinθ / g

Maximum Height: H = u²·sin²θ / 2g

Horizontal Range: R = u²·sin2θ / g

Maximum Range: R_max = u²/g (when θ = 45°)
```

### Important Relations:
```
R = 4H·cotθ
H/R = tanθ/4

Same range for angles: θ and (90° − θ)
```

### Projectile on Inclined Plane:
```
Range along incline:
R = 2u²·sin(α − β)·cosα / (g·cos²β)

where α = angle with incline, β = incline angle

Maximum range on incline: R_max = u²/[g(1 + sinβ)]
```

## 3.3 Circular Motion

### Angular Quantities:
```
Angular displacement: θ (radians)
Angular velocity: ω = dθ/dt (rad/s)
Angular acceleration: α = dω/dt (rad/s²)

Relation with linear: v = rω, a_t = rα
```

### Equations for Uniform Angular Acceleration:
```
ω = ω₀ + αt
θ = ω₀t + ½αt²
ω² = ω₀² + 2αθ
```

### Centripetal Acceleration:
```
a_c = v²/r = ω²r = vω

Centripetal Force: F_c = mv²/r = mω²r
```
> **Direction:** Always toward center (centripetal = center-seeking)

### Non-Uniform Circular Motion:
```
Total acceleration:
|a| = √(a_c² + a_t²)

a_c = v²/r (centripetal, toward center)
a_t = dv/dt (tangential, along velocity)

Angle of net acceleration with radius:
tanφ = a_t/a_c
```

### Banking of Roads:
```
Without friction:
tanθ = v²/rg   →   v_optimal = √(rg·tanθ)

With friction (maximum speed):
v_max = √[rg·(tanθ + μ)/(1 − μtanθ)]

With friction (minimum speed):
v_min = √[rg·(tanθ − μ)/(1 + μtanθ)]
```

### Vertical Circular Motion:
```
At bottom of circle:
N − mg = mv²_bottom/r
N = mg + mv²/r (N is maximum here)

At top of circle:
mg + N = mv²_top/r
N = mv²/r − mg

Minimum speed at top (N = 0):
v_top(min) = √(gr)

Minimum speed at bottom (to complete circle):
v_bottom(min) = √(5gr)

Speed relation (energy conservation):
v_bottom² = v_top² + 4gr
```

---

# 4. LAWS OF MOTION

## 4.1 Newton's Three Laws

### First Law (Law of Inertia):
> "A body continues in its state of rest or uniform motion unless acted upon by a net external force."

- Defines **inertia** (resistance to change in motion)
- Inertia ∝ Mass
- Defines concept of inertial frame of reference

### Second Law:
> "Rate of change of momentum = Net external force"

```
F⃗_net = dp⃗/dt = m·a⃗  (when mass is constant)

F⃗ = ma⃗

In components:
Fₓ = maₓ
Fᵧ = maᵧ
Fᵤ = maᵤ
```

### Third Law:
> "For every action there is an equal and opposite reaction."

```
F⃗_AB = −F⃗_BA
```
- Action and reaction act on **different** bodies
- They are always equal in magnitude, opposite in direction
- They act simultaneously

## 4.2 Momentum & Impulse

```
Linear Momentum: p⃗ = mv⃗  [M¹L¹T⁻¹]

Impulse: J⃗ = F⃗·Δt = Δp⃗  [M¹L¹T⁻¹]

Impulse-Momentum Theorem:
J = F_avg × Δt = m(v − u)
```

### Law of Conservation of Momentum:
> If net external force = 0, total momentum of system is conserved.

```
p⃗_initial = p⃗_final
m₁u₁ + m₂u₂ = m₁v₁ + m₂v₂
```

## 4.3 Friction

### Types:
| Type | Description | Formula |
|------|-------------|---------|
| Static friction | Prevents relative motion | 0 ≤ f_s ≤ μ_s·N |
| Kinetic friction | Opposes sliding motion | f_k = μ_k·N |
| Rolling friction | Opposes rolling | f_r = μ_r·N |

**Always: μ_s > μ_k > μ_r**

### Key Points:
- Friction is **self-adjusting** up to its maximum (static)
- Maximum static friction = μ_s × N (normal force)
- **Limiting friction** = just before sliding begins
- Kinetic friction is constant and independent of speed

### Angle of Friction (λ):
```
tanλ = μ_s
```

### Angle of Repose (θ_r):
```
tanθ_r = μ_s
(angle at which block just starts sliding on incline)
```

## 4.4 Constraint Motions

### Atwood Machine:
```
Two masses m₁ and m₂ over a pulley:

a = (m₁ − m₂)g / (m₁ + m₂)

T = 2m₁m₂g / (m₁ + m₂)
```

### Wedge-Block System:
Use constraint: acceleration of block relative to wedge = −acceleration of wedge

## 4.5 Pseudo Force (Non-Inertial Frames)

In an accelerating frame (acceleration = a₀):
```
F_pseudo = −m·a⃗₀

(acts on every object, opposite to frame's acceleration)
```

**Examples:**
- Person in lift: Apparent weight = m(g ± a)
  - Going up with acceleration: W_app = m(g + a)
  - Going down with acceleration: W_app = m(g − a)
  - Free fall: W_app = 0 (weightlessness)

## 4.6 Pulley Problems — Strategy

1. Identify all forces on each mass
2. Choose positive direction for each mass
3. Write F = ma for each mass
4. Use constraint equations (string inextensible)
5. Solve simultaneously

---

# 5. WORK, ENERGY & POWER

## 5.1 Work

```
W = F⃗ · d⃗ = Fd·cosθ

where θ = angle between F⃗ and displacement d⃗
```

### Cases:
| θ | Work |
|---|------|
| 0° | W = Fd (maximum positive) |
| 90° | W = 0 (no work) |
| 180° | W = −Fd (maximum negative) |

### Work Done by Variable Force:
```
W = ∫F·dx  (area under F-x graph)
```

### Work-Energy Theorem:
```
W_net = ΔKE = ½mv² − ½mu²

(Net work done = Change in kinetic energy)
```

## 5.2 Kinetic Energy

```
KE = ½mv² = p²/2m

Relation: p = √(2m·KE)

If KE increases by n times: v increases by √n times
```

## 5.3 Potential Energy

```
Gravitational PE: U = mgh (near Earth's surface)

Elastic PE (spring): U = ½kx²

Electric PE: U = kq₁q₂/r
```

### Relation between Force and PE:
```
F = −dU/dx

(Force = negative gradient of PE)

In 3D: F⃗ = −∇U = −(∂U/∂x î + ∂U/∂y ĵ + ∂U/∂z k̂)
```

## 5.4 Conservation of Mechanical Energy

```
KE + PE = constant  (when only conservative forces act)

½mv₁² + U₁ = ½mv₂² + U₂
```

**Conservative forces:** Gravity, Spring force, Electrostatic force (path independent)

**Non-conservative forces:** Friction, Air drag (path dependent) — they dissipate energy

## 5.5 Spring Force

```
F = −kx  (Hooke's Law, k = spring constant)

Work done in stretching/compressing by x:
W = ½kx²

Spring constant combinations:
Series: 1/k_eff = 1/k₁ + 1/k₂
Parallel: k_eff = k₁ + k₂
```

## 5.6 Power

```
P = W/t = F·v·cosθ

Instantaneous Power: P = F⃗ · v⃗

Unit: Watt (W) = J/s
1 horsepower (hp) = 746 W
```

## 5.7 Collisions

### Elastic Collision (KE conserved, momentum conserved):
```
v₁ = [(m₁ − m₂)u₁ + 2m₂u₂] / (m₁ + m₂)
v₂ = [(m₂ − m₁)u₂ + 2m₁u₁] / (m₁ + m₂)

Special case (m₁ = m₂): velocities exchange!
v₁ = u₂, v₂ = u₁

Special case (m₂ >> m₁, m₂ stationary):
v₁ ≈ −u₁ (bounces back)
v₂ ≈ 0 (barely moves)
```

### Inelastic Collision (KE not conserved, momentum conserved):
```
Perfectly inelastic (stick together):
m₁u₁ + m₂u₂ = (m₁ + m₂)v_common

Energy lost: ΔKE = m₁m₂(u₁ − u₂)² / [2(m₁ + m₂)]
```

### Coefficient of Restitution (e):
```
e = (v₂ − v₁)/(u₁ − u₂) = Relative velocity after / Relative velocity before

e = 1: Perfectly elastic
e = 0: Perfectly inelastic
0 < e < 1: Partially elastic
```

### Height after bounce:
```
After n bounces: h_n = e^(2n) × h₀
```

---

# 6. SYSTEM OF PARTICLES & ROTATIONAL MOTION

## 6.1 Centre of Mass

```
For discrete system:
x_cm = (m₁x₁ + m₂x₂ + ... + mₙxₙ) / (m₁ + m₂ + ... + mₙ)
     = Σmᵢxᵢ / Σmᵢ

Similarly for y_cm and z_cm

For continuous body:
x_cm = ∫x·dm / ∫dm
```

### CM of Common Shapes:
| Shape | CM Position |
|-------|------------|
| Uniform rod | Midpoint |
| Triangle | Intersection of medians (centroid) — at H/3 from base |
| Semicircle (arc) | 2R/π from center |
| Semicircular disc | 4R/3π from center |
| Hemisphere (solid) | 3R/8 from flat face |
| Hemisphere (shell) | R/2 from flat face |
| Cone (solid) | H/4 from base |
| Cone (shell) | H/3 from base |

### Motion of CM:
```
v_cm = Σmᵢvᵢ / M = p_total / M

a_cm = Σmᵢaᵢ / M = F_ext / M

F_ext = M·a_cm  (Newton's 2nd law for system)
```

> **Key:** Internal forces don't move the CM. Only external forces do.

## 6.2 Angular Quantities

```
Angular velocity: ω = dθ/dt  (rad/s)
Angular acceleration: α = dω/dt  (rad/s²)

Relation with linear:
v = rω
a_t = rα
a_c = rω²
```

## 6.3 Torque

```
τ⃗ = r⃗ × F⃗
|τ| = rF·sinθ = F × (perpendicular distance)

τ_net = I·α  (rotational analog of F = ma)
```

## 6.4 Moment of Inertia (MI)

```
For discrete: I = Σmᵢrᵢ²
For continuous: I = ∫r²·dm
```

### Moments of Inertia of Common Bodies:

| Body | Axis | MI (I) |
|------|------|--------|
| Thin rod (length L) | Through center ⊥ rod | ML²/12 |
| Thin rod | Through end ⊥ rod | ML²/3 |
| Ring (radius R) | Through center ⊥ plane | MR² |
| Ring | Diameter | MR²/2 |
| Disc (radius R) | Through center ⊥ plane | MR²/2 |
| Disc | Diameter | MR²/4 |
| Solid sphere | Through center | 2MR²/5 |
| Hollow sphere (shell) | Through center | 2MR²/3 |
| Solid cylinder | Own axis | MR²/2 |
| Hollow cylinder | Own axis | MR² |
| Rectangle (a × b) | Through center ⊥ plane | M(a² + b²)/12 |

### Parallel Axis Theorem:
```
I = I_cm + Md²

where d = distance between the two parallel axes
I_cm = MI about axis through CM
```

### Perpendicular Axis Theorem (for laminar/flat bodies only):
```
I_z = I_x + I_y

where z ⊥ plane of lamina, x and y are in plane
```

## 6.5 Angular Momentum

```
For a particle: L⃗ = r⃗ × p⃗ = m(r⃗ × v⃗)
|L| = mvr·sinθ = m·v·d   (d = perpendicular distance)

For rotating body: L = Iω

Relation: τ = dL/dt

Conservation: If τ_ext = 0, then L = constant
```

> **Classic JEE Example:** Ice skater pulls arms in → I decreases → ω increases (L conserved)

## 6.6 Rolling Motion

### Pure Rolling (no slipping):
```
v_cm = Rω  (rolling condition)

KE_total = KE_translation + KE_rotation
         = ½Mv_cm² + ½Iω²
         = ½Mv_cm²(1 + I/MR²)
         = ½Mv_cm²(1 + k²/R²)

where k = radius of gyration, I = Mk²
```

### Rolling on inclined plane:
```
Acceleration:
a = g·sinθ / (1 + I/MR²) = g·sinθ / (1 + k²/R²)

Speed at bottom (height h):
v = √[2gh/(1 + k²/R²)]

For comparison: Solid sphere > Solid cylinder > Hollow sphere > Hollow cylinder
```

### k²/R² values:
- Solid sphere: 2/5
- Solid cylinder/disc: 1/2
- Hollow sphere: 2/3
- Hollow cylinder/ring: 1

## 6.7 Equilibrium of Rigid Body

For static equilibrium:
```
ΣF = 0  (translational equilibrium)
Στ = 0  (rotational equilibrium, about any point)
```

---

# 7. GRAVITATION

## 7.1 Newton's Law of Gravitation

```
F = Gm₁m₂/r²

G = 6.674 × 10⁻¹¹ N·m²/kg²

Vector form: F⃗₁₂ = −Gm₁m₂r̂₁₂/r²
```

> Gravitational force is: Universal, always attractive, central, conservative, weakest fundamental force

## 7.2 Gravitational Field

```
g⃗ = F⃗/m = gravitational field intensity

Due to point mass M at distance r:
g = GM/r²  (toward M)
```

### Variation of g:

**With Altitude (h above surface):**
```
g_h = g(1 + h/R)⁻² ≈ g(1 − 2h/R)  for h << R

g_h = GM/(R + h)² = gR²/(R + h)²
```

**With Depth (d below surface):**
```
g_d = g(1 − d/R)

At center: g = 0
```

**With Latitude (φ):**
```
g_φ = g − Rω²cos²φ

At poles (φ = 90°): g_pole = g (maximum)
At equator (φ = 0°): g_eq = g − Rω² (minimum)
```

**Due to shape of Earth (oblate spheroid):**
g_pole > g_equator

## 7.3 Gravitational Potential Energy

```
U = −GMm/r  (zero reference at infinity)

Escape velocity: v_e = √(2GM/R) = √(2gR) ≈ 11.2 km/s

Note: U is always negative (bound system)
```

## 7.4 Gravitational Potential

```
V = −GM/r  (potential at distance r from mass M)

Relation: g = −dV/dr

V due to shell:
- Outside (r > R): V = −GM/r
- On surface (r = R): V = −GM/R
- Inside (r < R): V = −GM/R (constant!)

g due to shell:
- Outside: g = GM/r²
- Inside: g = 0
```

## 7.5 Satellites & Orbital Motion

### Orbital Velocity:
```
mv²/r = GMm/r²

v_o = √(GM/r) = √(gR²/r)

At surface: v_o = √(gR) ≈ 7.9 km/s
```

### Time Period of Satellite:
```
T = 2πr/v_o = 2π√(r³/GM)

Kepler's 3rd Law: T² ∝ r³

T²/r³ = 4π²/GM = constant (for same central body)
```

### Energy of Satellite:
```
KE = ½mv_o² = GMm/2r

PE = −GMm/r

Total Energy: E = KE + PE = −GMm/2r

Note: |PE| = 2KE (always), E = −KE (always negative = bound)
```

### Binding Energy:
```
BE = −E = GMm/2r
(energy needed to free the satellite)
```

### Geostationary Satellite:
- T = 24 hours (same as Earth's rotation)
- Orbit is in equatorial plane
- Height ≈ 36,000 km above Earth
- Appears stationary from Earth

### Escape Velocity vs Orbital Velocity:
```
v_e = √2 × v_o  (at same height)
v_e/v_o = √2
```

## 7.6 Kepler's Laws

1. **Law of Orbits:** Planets move in elliptical orbits with Sun at one focus

2. **Law of Areas:** A line joining Sun and planet sweeps equal areas in equal times
   ```
   dA/dt = L/2m = constant  (L = angular momentum)
   At perihelion: v_max, r_min → v·r = constant
   At aphelion: v_min, r_max
   ```

3. **Law of Periods:** T² ∝ a³ (a = semi-major axis)
   ```
   T₁²/T₂² = a₁³/a₂³
   ```

---

# 8. MECHANICAL PROPERTIES OF SOLIDS

## 8.1 Stress

```
Stress = Force / Area = F/A

Unit: N/m² = Pascal (Pa)
Dimensions: [M¹L⁻¹T⁻²]
```

### Types:
| Type | Description | Formula |
|------|-------------|---------|
| **Tensile/Compressive** | Normal to surface | F/A |
| **Shear** | Tangential to surface | F/A |
| **Volumetric/Hydraulic** | Equal from all sides | F/A |

## 8.2 Strain

```
Strain = Change / Original = ΔX/X
(dimensionless)
```

### Types:
```
Longitudinal strain = ΔL/L
Shear strain = tanφ ≈ φ (for small angles)
Volumetric strain = ΔV/V
```

## 8.3 Elastic Moduli

### Young's Modulus (Y):
```
Y = Longitudinal Stress / Longitudinal Strain
Y = (F/A) / (ΔL/L) = FL/(AΔL)

Unit: N/m² or Pa
Steel: ~2 × 10¹¹ Pa
```

### Shear Modulus (G) / Rigidity Modulus:
```
G = Shear Stress / Shear Strain
G = (F/A) / φ = F/(Aφ)
```

### Bulk Modulus (B):
```
B = Volumetric Stress / Volumetric Strain
B = −P / (ΔV/V)   (negative sign: pressure increase → volume decrease)

Compressibility = 1/B
```

### Poisson's Ratio (σ):
```
σ = Lateral strain / Longitudinal strain
σ = −(Δd/d) / (ΔL/L)

Range: −1 < σ < 0.5
Rubber: ~0.5 (nearly incompressible)
```

### Relations between elastic constants:
```
Y = 3B(1 − 2σ)
Y = 2G(1 + σ)
Y = 9BG/(3B + G)
```

## 8.4 Elastic Potential Energy

```
Energy stored per unit volume:
u = ½ × stress × strain = ½ × Y × (strain)² = (stress)²/2Y

Total energy stored in wire:
U = ½ × Stress × Strain × Volume
U = ½ × (F/A) × (ΔL/L) × (AL)
U = ½FΔL
```

## 8.5 Stress-Strain Curve

```
O→A: Proportionality limit (Hooke's law valid)
A→B: Elastic limit (no permanent deformation)
B→C: Yield point (plastic deformation begins)
C→D: Strain hardening
D: Ultimate tensile strength
D→E: Necking
E: Breaking point (fracture)
```

---

# 9. MECHANICAL PROPERTIES OF FLUIDS

## 9.1 Pressure in Fluids

```
P = F/A

Pressure at depth h:
P = P₀ + ρgh

where P₀ = atmospheric pressure, ρ = fluid density

Gauge pressure: P_gauge = P − P₀ = ρgh
```

### Pascal's Law:
> Pressure applied to an enclosed fluid is transmitted equally in all directions.

```
F₁/A₁ = F₂/A₂   (hydraulic machines)
```

## 9.2 Archimedes' Principle

> A body immersed in fluid experiences an upward buoyant force = weight of fluid displaced.

```
F_buoyancy = ρ_fluid × V_submerged × g

Floating condition: F_buoyancy = Weight
ρ_fluid × V_sub × g = ρ_body × V_body × g
V_sub/V_body = ρ_body/ρ_fluid
```

## 9.3 Equation of Continuity

For steady, incompressible fluid flow:
```
A₁v₁ = A₂v₂ = constant  (Conservation of mass)

where A = cross-sectional area, v = velocity
```

## 9.4 Bernoulli's Theorem

For ideal fluid (non-viscous, incompressible, steady flow):
```
P + ½ρv² + ρgh = constant

P₁ + ½ρv₁² + ρgh₁ = P₂ + ½ρv₂² + ρgh₂
```

**Physical meaning:** Sum of pressure energy + kinetic energy + potential energy per unit volume = constant

### Applications:

**Venturimeter:**
```
v₁ = A₂√[2gh/(A₁² − A₂²)] × √(ρ_Hg/ρ_fluid − 1)
```

**Torricelli's Theorem** (speed of efflux):
```
v = √(2gh)

(speed of liquid from a hole at depth h below free surface)
```

**Lift on aircraft wing:**
```
F_lift = ½ρ(v_upper² − v_lower²) × A
```

## 9.5 Viscosity

```
F = ηA(dv/dx)   (Newton's law of viscosity)

η = viscosity coefficient
Unit: Pa·s or N·s/m² or Poise (CGS: 1 Pa·s = 10 Poise)
```

### Stokes' Law:
```
F_drag = 6πηrv

Terminal velocity (when drag + buoyancy = gravity):
v_t = 2r²(ρ_body − ρ_fluid)g / 9η
```

### Reynold's Number:
```
Re = ρvd/η

Re < 1000: Laminar flow
Re > 2000: Turbulent flow
1000 < Re < 2000: Transition
```

## 9.6 Surface Tension

### Definitions:
```
Surface Tension T = F/L = W/A

Unit: N/m or J/m²
```

### Excess Pressure:
```
Soap bubble (2 surfaces): ΔP = 4T/R
Liquid drop (1 surface): ΔP = 2T/R
Air bubble in liquid (1 surface): ΔP = 2T/R
```

### Capillary Rise/Fall:
```
h = 2T·cosθ / ρgr

θ < 90°: liquid rises (wets glass, e.g., water)
θ > 90°: liquid falls (doesn't wet, e.g., mercury)

Jurin's Law: h·r = constant (for same liquid)
```

### Energy of Surface:
```
Work done in forming surface:
W = T × ΔA  (increase in surface area)
```

---

# 10. THERMAL PROPERTIES OF MATTER

## 10.1 Temperature Scales

```
Celsius to Kelvin: T(K) = T(°C) + 273.15

Celsius to Fahrenheit: F = (9/5)C + 32

K/5 = (C + 40)/9 = (F + 40)/5  ← Memory trick!
```

## 10.2 Thermal Expansion

### Linear Expansion:
```
ΔL = L₀αΔT
L = L₀(1 + αΔT)
α = coefficient of linear expansion (K⁻¹)
```

### Area Expansion:
```
ΔA = A₀βΔT
β = 2α
```

### Volume Expansion:
```
ΔV = V₀γΔT
γ = 3α

Relation: γ = 3α, β = 2α
```

### Anomalous Expansion of Water:
- Maximum density at 4°C: ρ_max = 1000 kg/m³
- Expands both above and below 4°C
- This is why ice forms at top of lakes

## 10.3 Specific Heat Capacity

```
Q = mcΔT

c = Q/(mΔT)

Unit: J/(kg·K) or J/(kg·°C)

Water: c = 4186 J/(kg·K) = 1 cal/(g·°C)
```

### Calorimetry (Method of Mixtures):
```
Heat lost = Heat gained
m₁c₁(T₁ − T_mix) = m₂c₂(T_mix − T₂)
```

### Latent Heat:
```
Q = mL

Latent heat of fusion (ice → water at 0°C): L_f = 3.36 × 10⁵ J/kg = 80 cal/g
Latent heat of vaporization (water → steam at 100°C): L_v = 2.26 × 10⁶ J/kg = 540 cal/g
```

## 10.4 Heat Transfer

### Conduction:
```
Rate of heat flow: dQ/dt = −KA(dT/dx)

where K = thermal conductivity (W/m·K)

For steady state, slab of thickness L:
dQ/dt = KA(T₁ − T₂)/L

Thermal Resistance: R = L/(KA)

Slabs in series: R_total = R₁ + R₂
Slabs in parallel: 1/R_total = 1/R₁ + 1/R₂
```

### Convection:
Heat transfer through movement of fluid itself. Newton's law of cooling is an approximation for convection.

### Radiation:
```
Stefan-Boltzmann Law:
P = εσAT⁴

σ = Stefan's constant = 5.67 × 10⁻⁸ W/m²·K⁴
ε = emissivity (0 to 1; 1 for black body)

Net radiation from body at T in surrounding T₀:
P_net = εσA(T⁴ − T₀⁴)
```

### Wien's Displacement Law:
```
λ_max × T = b = 2.898 × 10⁻³ m·K

(wavelength of peak emission × temperature = constant)
```

### Newton's Law of Cooling:
```
dT/dt = −k(T − T_s)

T(t) = T_s + (T₀ − T_s)e^(−kt)

Approximate formula: (T₁ − T₂)/t = k × [(T₁ + T₂)/2 − T_s]
```

### Kirchhoff's Law:
```
Good absorbers are good emitters:
a_λ = e_λ  (at same wavelength and temperature)

Black body: a = 1, e = 1 (perfect absorber and emitter)
```

---

# 11. THERMODYNAMICS

## 11.1 Zeroth Law

> If A is in thermal equilibrium with C, and B is in thermal equilibrium with C, then A and B are in thermal equilibrium with each other.

This defines **temperature**.

## 11.2 First Law of Thermodynamics

```
ΔU = Q − W

Q = heat added to system
W = work done BY the system
ΔU = change in internal energy

Sign convention:
Q > 0: heat absorbed by system
Q < 0: heat released by system
W > 0: work done BY system (expansion)
W < 0: work done ON system (compression)
```

### Work done by gas:
```
W = ∫P·dV  (area under P-V graph)
```

## 11.3 Thermodynamic Processes

### Isothermal Process (T = constant):
```
PV = constant  (Boyle's Law)
P₁V₁ = P₂V₂
ΔU = 0 (for ideal gas)
Q = W = nRT·ln(V₂/V₁)
```

### Adiabatic Process (Q = 0):
```
PVᵞ = constant
TV^(γ−1) = constant
T^γ P^(1−γ) = constant

W = −ΔU = −nCᵥΔT = (P₁V₁ − P₂V₂)/(γ − 1) = nR(T₁ − T₂)/(γ − 1)
Q = 0, ΔU = −W
```

### Isochoric Process (V = constant):
```
W = 0
Q = ΔU = nCᵥΔT

Charles' Law at constant V: P/T = constant
P₁/T₁ = P₂/T₂
```

### Isobaric Process (P = constant):
```
W = PΔV = nRΔT
Q = nCₚΔT
ΔU = nCᵥΔT

Charles' Law: V/T = constant
V₁/T₁ = V₂/T₂
```

## 11.4 Specific Heats of Ideal Gas

```
Cᵥ = (f/2)R   (molar specific heat at constant volume)
Cₚ = (f/2 + 1)R = Cᵥ + R   (molar specific heat at constant pressure)

γ = Cₚ/Cᵥ = (f + 2)/f

where f = degrees of freedom
```

| Gas Type | f | Cᵥ | Cₚ | γ |
|----------|---|----|----|---|
| Monoatomic (He, Ar) | 3 | 3R/2 | 5R/2 | 5/3 ≈ 1.67 |
| Diatomic (H₂, O₂, N₂) at room T | 5 | 5R/2 | 7R/2 | 7/5 = 1.4 |
| Diatomic (high T) | 7 | 7R/2 | 9R/2 | 9/7 |
| Triatomic (CO₂) | 6 | 3R | 4R | 4/3 ≈ 1.33 |

### Mayer's Relation:
```
Cₚ − Cᵥ = R
```

## 11.5 Second Law of Thermodynamics

**Kelvin-Planck Statement:**
> It is impossible to construct a device that, operating in a cycle, absorbs heat from a single reservoir and converts it entirely to work.

**Clausius Statement:**
> It is impossible to transfer heat from a colder body to a hotter body without external work.

## 11.6 Heat Engines

```
Efficiency: η = W/Q_H = 1 − Q_L/Q_H

where Q_H = heat absorbed from hot reservoir
      Q_L = heat rejected to cold reservoir
      W = useful work = Q_H − Q_L
```

### Carnot Engine (maximum efficiency):
```
η_Carnot = 1 − T_L/T_H = (T_H − T_L)/T_H

T_H = temperature of hot reservoir (K)
T_L = temperature of cold reservoir (K)
```

> **Critical JEE Point:** No real engine can be more efficient than Carnot engine operating between same temperatures.

### Refrigerator (Coefficient of Performance):
```
COP = Q_L/W = Q_L/(Q_H − Q_L) = T_L/(T_H − T_L)

(Carnot refrigerator has maximum COP)
```

## 11.7 Entropy

```
ΔS = Q_reversible/T

For irreversible process: ΔS_universe > 0
Second Law: Total entropy of universe always increases
```

---

# 12. KINETIC THEORY OF GASES

## 12.1 Ideal Gas Law

```
PV = nRT = NkT

R = 8.314 J/(mol·K) = universal gas constant
k = R/Nₐ = 1.38 × 10⁻²³ J/K = Boltzmann constant
Nₐ = 6.022 × 10²³ = Avogadro's number
n = number of moles
N = number of molecules
```

## 12.2 Kinetic Theory Assumptions

1. Gases consist of large number of molecules in random motion
2. Molecules are point masses (negligible volume)
3. No intermolecular forces except during collision
4. Collisions are perfectly elastic
5. Molecules obey Newton's laws

## 12.3 Pressure of Ideal Gas

```
P = ⅓ρv̄² = ⅓(mn/V)v̄²

where v̄² = mean square speed
m = mass of one molecule
n = number density
```

## 12.4 Temperature and Kinetic Energy

```
Average KE per molecule: ½mv̄² = (3/2)kT

For f degrees of freedom:
KE per molecule = (f/2)kT

Per mole: KE = (f/2)RT

For ideal gas: KE_total = (f/2)nRT = (f/2)NkT = (f/2)PV
```

## 12.5 Molecular Speeds

### Root Mean Square (RMS) Speed:
```
v_rms = √(3kT/m) = √(3RT/M) = √(3P/ρ)

where M = molar mass
```

### Average Speed:
```
v_avg = √(8kT/πm) = √(8RT/πM)
```

### Most Probable Speed:
```
v_mp = √(2kT/m) = √(2RT/M)
```

### Comparison:
```
v_mp : v_avg : v_rms = √2 : √(8/π) : √3
                      = 1 : 1.128 : 1.225
                      ≈ 1 : 1.13 : 1.22
```

> **Memory Trick:** v_mp < v_avg < v_rms (alphabetical order of their prefix)

## 12.6 Mean Free Path

```
λ = 1/(√2 × n × πd²)

= kT/(√2 × πd² × P)

where n = number density, d = diameter of molecule

Collision frequency: Z = n × πd² × v_avg × √2
```

## 12.7 Degrees of Freedom

- **Monoatomic** (He, Ne, Ar): f = 3 (3 translational)
- **Diatomic** (H₂, O₂, N₂) at room temperature: f = 5 (3 trans + 2 rotational)
- **Diatomic at high T:** f = 7 (+ 2 vibrational)
- **Non-linear triatomic** (H₂O): f = 6

### Equipartition Theorem:
> Each degree of freedom contributes ½kT of energy per molecule (or ½RT per mole)

---

# 13. OSCILLATIONS (SHM)

## 13.1 Simple Harmonic Motion

### Definition:
A particle undergoes SHM if restoring force ∝ displacement from equilibrium

```
F = −kx
a = −ω²x

where ω = √(k/m) = angular frequency
```

### General Equations:
```
x(t) = A·sin(ωt + φ)   or   A·cos(ωt + φ)

v(t) = Aω·cos(ωt + φ) = ω√(A² − x²)

a(t) = −Aω²·sin(ωt + φ) = −ω²x

where A = amplitude, φ = initial phase, ω = angular frequency
```

### Time Period and Frequency:
```
T = 2π/ω = 2π√(m/k)

f = 1/T = ω/2π

ω = √(k/m) = 2π/T = 2πf
```

## 13.2 Energy in SHM

```
KE = ½mv² = ½mω²(A² − x²) = ½k(A² − x²)

PE = ½kx² = ½mω²x²

Total Energy: E = ½kA² = ½mω²A²  (constant)

At x = 0 (equilibrium): KE = max = ½kA², PE = 0
At x = ±A (extreme): PE = max = ½kA², KE = 0

When KE = PE: x = A/√2 = 0.707A
```

## 13.3 Simple Pendulum

```
T = 2π√(L/g)

For small angles: F = −mg·sinθ ≈ −mgθ (for small θ)
ω = √(g/L)

Effective g in accelerating lift:
g_eff = g + a (lift going up)
g_eff = g − a (lift going down)
g_eff = 0 (free fall — pendulum doesn't oscillate!)

At height h: g_h = g(1 − 2h/R) → T increases
Underground: g_d = g(1 − d/R) → T increases
```

## 13.4 Spring-Mass Systems

### Horizontal spring:
```
T = 2π√(m/k)
```

### Vertical spring:
```
T = 2π√(m/k)  [same! gravity doesn't affect T]

At equilibrium: mg = kx₀  (static extension)
```

### Spring Combinations:
```
Series: T = 2π√[m(1/k₁ + 1/k₂)] = 2π√[m(k₁+k₂)/(k₁k₂)]
Parallel: T = 2π√[m/(k₁ + k₂)]
```

### Spring cut into n equal pieces:
```
k_new = nk  (spring constant increases)
```

## 13.5 Other SHM Systems

### Physical (Compound) Pendulum:
```
T = 2π√(I/mgd)

where I = MI about pivot, d = distance of CM from pivot

Equivalent simple pendulum length: L_eq = I/(md)
```

### Liquid in U-tube:
```
T = 2π√(L/2g)

where L = total length of liquid column
```

### Floating Body:
```
T = 2π√(m/A·ρ·g) = 2π√(h/g)

where h = length submerged, A = cross-section area
```

## 13.6 Damped Oscillations

```
x(t) = Ae^(−bt/2m) · cos(ω'd·t + φ)

ω'd = √(ω₀² − b²/4m²)

where b = damping coefficient

Energy: E(t) = E₀ · e^(−bt/m)
```

### Types:
- **Underdamped:** b < 2mω₀ (oscillates with decreasing amplitude)
- **Critically damped:** b = 2mω₀ (returns to equilibrium fastest, no oscillation)
- **Overdamped:** b > 2mω₀ (slow return, no oscillation)

## 13.7 Resonance

```
Driven oscillation frequency: ω_d

Resonance when: ω_d = ω₀ (natural frequency)

At resonance: Amplitude is maximum, energy transfer is maximum
```

---

# 14. WAVES

## 14.1 Wave Motion

A **wave** is a disturbance that transfers energy without transfer of matter.

### Types:
| Property | Transverse | Longitudinal |
|----------|-----------|-------------|
| Particle motion | ⊥ to wave | ∥ to wave |
| Examples | Light, string waves | Sound, spring waves |
| Can travel in | Solid, surface | All media |
| Polarization | Possible | Not possible |

## 14.2 Wave Equation

### Sinusoidal Wave:
```
y(x, t) = A·sin(kx − ωt + φ)   ← wave moving in +x direction
y(x, t) = A·sin(kx + ωt + φ)   ← wave moving in −x direction

where:
A = amplitude
k = wave number = 2π/λ
ω = angular frequency = 2πf
λ = wavelength
f = frequency
T = time period = 1/f
v = wave speed = λf = ω/k
```

### General Wave Equation (Differential):
```
∂²y/∂x² = (1/v²) · ∂²y/∂t²
```

## 14.3 Speed of Waves

### On a String:
```
v = √(T/μ)

T = tension, μ = linear mass density (kg/m)
```

### Sound in a Medium:
```
v = √(B/ρ)   (Newton's formula, isothermal)

v = √(γP/ρ) = √(γRT/M)   (Laplace correction, adiabatic)

In air at 0°C: v ≈ 331 m/s
Effect of temperature: v ∝ √T → v_t = v₀√(T/273) = 331√(T/273)
```

> **Laplace Correction:** Sound propagation is adiabatic (not isothermal), so multiply Newton's result by √γ

### Speed of Sound in different media:
- Gases: v = √(γRT/M) ≈ 300-350 m/s
- Liquids: v ≈ 1500 m/s (water)
- Solids: v = √(Y/ρ) ≈ 5000 m/s (steel)

## 14.4 Intensity and Loudness

```
Intensity: I = P/A = ½ρv·ω²A²

Intensity ∝ A² (square of amplitude)
Intensity ∝ f² (square of frequency)
Intensity ∝ 1/r² (inverse square law for point source)

Sound Level (Decibels):
β = 10·log₁₀(I/I₀)  dB

I₀ = 10⁻¹² W/m² (threshold of hearing)
```

## 14.5 Superposition & Interference

```
Principle of Superposition:
y = y₁ + y₂ (displacements add)

For two waves: y₁ = A·sin(kx − ωt) and y₂ = A·sin(kx − ωt + φ)
Resultant: y = 2A·cos(φ/2)·sin(kx − ωt + φ/2)
Resultant amplitude: A_R = 2A·cos(φ/2)
```

### Constructive Interference:
```
φ = 2nπ (even multiples of π)  or  Δx = nλ
A_R = 2A (maximum)
I_max = 4I₀
```

### Destructive Interference:
```
φ = (2n+1)π (odd multiples of π)  or  Δx = (2n+1)λ/2
A_R = 0 (minimum)
I_min = 0
```

## 14.6 Standing Waves (Stationary Waves)

```
y₁ = A·sin(kx − ωt)   (incident)
y₂ = A·sin(kx + ωt)   (reflected)

Superposition:
y = 2A·sin(kx)·cos(ωt)

Nodes (zero displacement): kx = nπ → x = nλ/2
Antinodes (max displacement): kx = (2n+1)π/2 → x = (2n+1)λ/4
```

**Distance between consecutive nodes = λ/2**  
**Distance between node and adjacent antinode = λ/4**

## 14.7 Standing Waves in Strings

### Both ends fixed:
```
L = nλ/2  →  λ_n = 2L/n

f_n = nv/2L = n·f₁

Fundamental: f₁ = v/2L (n = 1)
1st overtone: f₂ = 2v/2L = 2f₁ (n = 2)
2nd overtone: f₃ = 3f₁ (n = 3)

All harmonics present: f₁ : f₂ : f₃ : ... = 1 : 2 : 3 : ...
```

## 14.8 Standing Waves in Air Columns

### Open Pipe (both ends open):
```
L = nλ/2  →  λ_n = 2L/n

f_n = nv/2L

All harmonics: 1, 2, 3, ... × f₁
```

### Closed Pipe (one end closed):
```
L = (2n−1)λ/4  →  λ_n = 4L/(2n−1)

f_n = (2n−1)v/4L

Only ODD harmonics: 1, 3, 5, ... × f₁

Fundamental f₁ = v/4L (half that of open pipe!)
```

### End Correction (e):
```
Effective length = L + e (for closed end) = L + 2e (for open pipe)
e ≈ 0.6r  where r = radius of pipe
```

## 14.9 Beats

```
Beats occur when two waves of slightly different frequencies superpose.

Beat frequency: f_beat = |f₁ − f₂|

Beat time period: T_beat = 1/f_beat

y = 2A·cos[2π(f₁−f₂)t/2]·sin[2π(f₁+f₂)t/2]
```

## 14.10 Doppler Effect

### General Formula:
```
f_observed = f_source × (v ± v_observer)/(v ∓ v_source)

Convention:
- Upper sign when approaching each other
- Lower sign when moving away
```

### Cases:

| Situation | Formula |
|-----------|---------|
| Observer moves toward stationary source | f' = f(v + v_o)/v |
| Observer moves away from stationary source | f' = f(v − v_o)/v |
| Source moves toward stationary observer | f' = fv/(v − v_s) |
| Source moves away from stationary observer | f' = fv/(v + v_s) |
| Both moving toward each other | f' = f(v + v_o)/(v − v_s) |
| Both moving away from each other | f' = f(v − v_o)/(v + v_s) |

```
v = speed of sound
v_o = speed of observer
v_s = speed of source
```

### Apparent Wavelength:
```
λ' = (v − v_s)/f   (source approaching)
λ' = (v + v_s)/f   (source receding)
```

### Doppler Effect for Light (Relativistic):
```
f_observed = f_source × √[(c − v)/(c + v)]  (source moving away)
```

---

# 📊 QUICK REFERENCE — IMPORTANT CONSTANTS

| Constant | Value |
|----------|-------|
| g (Earth's surface) | 9.8 m/s² ≈ 10 m/s² |
| G (Gravitational constant) | 6.674 × 10⁻¹¹ N·m²/kg² |
| R (Gas constant) | 8.314 J/(mol·K) |
| k (Boltzmann) | 1.38 × 10⁻²³ J/K |
| Nₐ (Avogadro) | 6.022 × 10²³ mol⁻¹ |
| σ (Stefan-Boltzmann) | 5.67 × 10⁻⁸ W/(m²·K⁴) |
| Speed of sound in air (0°C) | 331 m/s |
| Speed of light | 3 × 10⁸ m/s |
| Radius of Earth | 6.4 × 10⁶ m |
| Mass of Earth | 6 × 10²⁴ kg |
| Escape velocity (Earth) | 11.2 km/s |
| 1 atm | 1.013 × 10⁵ Pa |
| 1 cal | 4.186 J |

---

# 🎯 JEE-SPECIFIC TIPS & TRICKS

## High-Weightage Topics (based on past trends):
1. **Rotational Mechanics** — highest weightage, most questions
2. **Waves & SHM** — frequently tested together
3. **Thermodynamics** — numerical-heavy, formula-based
4. **Gravitation** — conceptual + numerical
5. **Laws of Motion + Friction** — tricky scenarios

## Common Mistakes to Avoid:
- In projectile, forgetting that range is same for θ and (90−θ)
- Using g = 10 instead of 9.8 when precision matters
- Forgetting end correction in resonance tube problems
- Confusing Cᵥ and Cₚ in adiabatic processes
- Not using constraint equations in pulley problems
- Forgetting pseudo force in non-inertial frame problems

## Dimensional Analysis Hacks:
- All energy terms: [ML²T⁻²]
- All power terms: [ML²T⁻³]
- All pressure/modulus terms: [ML⁻¹T⁻²]
- If in doubt, check both sides have same dimensions

## SHM Memory:
- x: oscillates as sin/cos
- v: 90° ahead of x
- a: 180° (opposite) to x
- KE + PE = constant = ½kA²

## Waves Memory:
- Open pipe: ALL harmonics (like string fixed at both ends)
- Closed pipe: ODD harmonics ONLY
- Fundamental freq of closed = HALF of open (same length)

---

# 📝 FORMULA SHEET — ONE-PAGE SUMMARY

```
KINEMATICS
v = u + at | s = ut + ½at² | v² = u² + 2as
Projectile: R = u²sin2θ/g | H = u²sin²θ/2g | T = 2usinθ/g
Circular: a_c = v²/r | F_c = mv²/r

LAWS OF MOTION
F = ma | f_k = μN | f_s ≤ μ_sN

WORK-ENERGY-POWER
W = Fd·cosθ | KE = ½mv² | PE = mgh | W_net = ΔKE
P = F·v | e = v_rel_after / v_rel_before

ROTATION
τ = Iα | L = Iω | KE_rot = ½Iω²
v_cm = rω (rolling) | Parallel axis: I = I_cm + Md²

GRAVITATION
F = Gm₁m₂/r² | g = GM/R² | v_e = √(2gR)
v_o = √(GM/r) | T = 2π√(r³/GM) | E = -GMm/2r

THERMODYNAMICS
PV = nRT | Q = mcΔT | ΔU = Q - W
η_Carnot = 1 - T_L/T_H | Cₚ - Cᵥ = R | γ = Cₚ/Cᵥ

KINETIC THEORY
v_rms = √(3RT/M) | v_avg = √(8RT/πM) | v_mp = √(2RT/M)
KE = (f/2)kT per molecule = (f/2)RT per mole

SHM
x = A·sin(ωt+φ) | T = 2π/ω | ω = √(k/m)
T_pendulum = 2π√(L/g) | E = ½kA²

WAVES
v = fλ | v_string = √(T/μ) | v_sound = √(γRT/M)
Open pipe: f_n = nv/2L | Closed pipe: f_n = (2n-1)v/4L
Doppler: f' = f(v ± v_o)/(v ∓ v_s)
```

---

