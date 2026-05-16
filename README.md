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

# ⚡ IIT JEE CLASS 12 PHYSICS — COMPLETE NOTES
### Every Concept | Every Formula | Every Detail | JEE Advanced Level

> **Syllabus Coverage:** Complete NCERT + JEE Advanced + Previous Year Patterns  
> **Chapters:** Electrostatics → Current Electricity → Magnetism → EMI → AC → Optics → Modern Physics → Semiconductors

---

## 📚 TABLE OF CONTENTS

1. [Electric Charges & Fields](#1-electric-charges--fields)
2. [Electrostatic Potential & Capacitance](#2-electrostatic-potential--capacitance)
3. [Current Electricity](#3-current-electricity)
4. [Moving Charges & Magnetism](#4-moving-charges--magnetism)
5. [Magnetism & Matter](#5-magnetism--matter)
6. [Electromagnetic Induction (EMI)](#6-electromagnetic-induction)
7. [Alternating Current (AC)](#7-alternating-current)
8. [Electromagnetic Waves](#8-electromagnetic-waves)
9. [Ray Optics & Optical Instruments](#9-ray-optics--optical-instruments)
10. [Wave Optics](#10-wave-optics)
11. [Dual Nature of Radiation & Matter](#11-dual-nature-of-radiation--matter)
12. [Atoms](#12-atoms)
13. [Nuclei](#13-nuclei)
14. [Semiconductor Electronics](#14-semiconductor-electronics)
15. [Communication Systems](#15-communication-systems)

---

# 1. ELECTRIC CHARGES & FIELDS

## 1.1 Electric Charge

**Properties of Charge:**
- Charge is scalar quantity
- SI unit: Coulomb (C)
- Charge is quantized: Q = ne, where e = 1.6 × 10⁻¹⁹ C, n = integer
- Charge is conserved (cannot be created or destroyed)
- Charge is invariant (independent of velocity of observer)
- Two types: positive (+) and negative (−)

### Quantization of Charge:
```
Q = ±ne
n = 1, 2, 3, ...
e = 1.6 × 10⁻¹⁹ C (elementary charge)
```

## 1.2 Coulomb's Law

```
F = kq₁q₂/r²  =  q₁q₂/(4πε₀r²)

k = 1/(4πε₀) = 9 × 10⁹ N·m²/C²
ε₀ = 8.854 × 10⁻¹² C²/(N·m²)  [permittivity of free space]

Vector form:
F⃗₁₂ = kq₁q₂r̂₁₂/r²
```

### In a Medium:
```
F_medium = kq₁q₂/(εᵣr²) = F_vacuum/εᵣ

εᵣ = relative permittivity (dielectric constant)
ε = ε₀εᵣ  (absolute permittivity)
```

### Coulomb vs Gravitational Force:
```
F_E/F_G = ke²/(Gm_e²) ≈ 10⁴²  (electrostatic force is far stronger)
```

## 1.3 Electric Field

```
E⃗ = F⃗/q₀  (force per unit positive test charge)

Unit: N/C = V/m
Dimensions: [M¹L¹T⁻³A⁻¹]
```

### Electric Field due to Point Charge:
```
E = kQ/r²  (magnitude)
E⃗ = kQr̂/r²  (vector, away from +Q, toward −Q)
```

### Superposition Principle:
```
E⃗_total = E⃗₁ + E⃗₂ + E⃗₃ + ...  (vector sum)
```

### Electric Field — Important Cases:

**Along axis of a dipole (end-on position):**
```
E_axial = 2kp/r³  (for r >> a)
```

**Along perpendicular bisector of dipole (broad-on):**
```
E_equatorial = kp/r³  (opposite to dipole moment direction)
```

**At center of uniformly charged ring:**
```
E = 0 (by symmetry)
```

**On axis of charged ring at distance x:**
```
E = kQx / (R² + x²)^(3/2)

Maximum E at x = R/√2, E_max = kQ/(3√3 R²/2)
```

**Infinite line charge (linear charge density λ):**
```
E = λ/(2πε₀r)  (perpendicular to line)
```

**Infinite plane sheet (surface charge density σ):**
```
E = σ/(2ε₀)  (on each side, perpendicular to sheet)
```

**Between two parallel sheets (+σ and −σ):**
```
E = σ/ε₀ (between them, uniform)
E = 0 (outside)
```

## 1.4 Electric Field Lines

- Start from positive, end on negative charge
- Never cross each other
- Tangent at any point = direction of E⃗
- Density ∝ magnitude of E
- Always perpendicular to equipotential surface
- No closed loops in electrostatics

## 1.5 Electric Dipole

```
Electric dipole moment: p⃗ = q × 2a⃗  (from −q to +q)
Unit: C·m

Torque in uniform field: τ⃗ = p⃗ × E⃗ = pE·sinθ
Potential energy: U = −p⃗ · E⃗ = −pE·cosθ

Stable equilibrium: θ = 0 (p⃗ ∥ E⃗)
Unstable equilibrium: θ = 180°
```

## 1.6 Gauss's Law

```
∮E⃗ · dA⃗ = Q_enclosed/ε₀

Φ_E = Q_enc/ε₀  (Total electric flux through closed surface)

Electric flux: Φ = E⃗ · A⃗ = EA·cosθ
Unit: N·m²/C = V·m
```

### Applications of Gauss's Law:

**Uniformly charged sphere (solid, total charge Q, radius R):**
```
Outside (r > R): E = kQ/r²  [same as point charge]
On surface (r = R): E = kQ/R²
Inside (r < R): E = kQr/R³ = ρr/3ε₀  [increases linearly]
```

**Spherical shell (hollow):**
```
Outside (r > R): E = kQ/r²
Inside (r < R): E = 0  [No field inside shell!]
On surface: E = kQ/R² = σ/ε₀
```

**Long straight wire (λ = charge/length):**
```
E = λ/(2πε₀r)
```

**Infinite plane sheet (σ = charge/area):**
```
E = σ/(2ε₀)
```

**Conducting sphere:**
```
E_inside = 0 (electrostatic shielding)
E_surface = σ/ε₀ (normal to surface)
E_outside = kQ/r²
```

---

# 2. ELECTROSTATIC POTENTIAL & CAPACITANCE

## 2.1 Electric Potential

```
V = W/q₀ = U/q₀  (work done per unit charge)

Unit: Volt (V) = J/C
Dimensions: [M¹L²T⁻³A⁻¹]

V is a scalar quantity!
```

### Due to Point Charge:
```
V = kQ/r = Q/(4πε₀r)
```

### Relation between E and V:
```
E = −dV/dr  (in 1D)

E⃗ = −∇V = −(∂V/∂x î + ∂V/∂y ĵ + ∂V/∂z k̂)

(E points from high V to low V)
```

### Potential — Important Cases:

**Due to dipole:**
```
V = kp·cosθ/r²

Axial (θ = 0): V = kp/r²
Equatorial (θ = 90°): V = 0
```

**On axis of charged ring:**
```
V = kQ/√(R² + x²)
```

**Inside uniformly charged solid sphere:**
```
V_inside = kQ(3R² − r²)/(2R³)  [varies as quadratic]
V_surface = kQ/R
V_center = 3kQ/2R = (3/2)V_surface
```

**Inside shell:**
```
V_inside = kQ/R = V_surface = constant
```

## 2.2 Equipotential Surfaces

- All points at same potential
- E⃗ is always perpendicular to equipotential surface
- No work done moving charge along equipotential
- Closer equipotential lines → stronger field
- For point charge: concentric spheres
- For uniform field: parallel planes

## 2.3 Potential Energy

```
System of two charges:
U = kq₁q₂/r

System of multiple charges:
U = k × Σᵢ<ⱼ (qᵢqⱼ/rᵢⱼ)   [sum each pair once]

Work done in moving charge q from A to B:
W = q(V_A − V_B) = −q·ΔV
```

## 2.4 Conductors in Electric Field

1. E = 0 inside conductor
2. All charge resides on surface
3. Surface is equipotential
4. E is perpendicular to surface
5. E_surface = σ/ε₀ (just outside)
6. Charge accumulates more on sharp points (lightning rod principle)

**Electrostatic Shielding:** Hollow conductor shields interior from external fields.

## 2.5 Capacitance

```
C = Q/V

Unit: Farad (F) = C/V
1 μF = 10⁻⁶ F, 1 nF = 10⁻⁹ F, 1 pF = 10⁻¹² F

Capacitance depends ONLY on geometry, not on Q or V.
```

### Capacitance Formulas:

**Isolated sphere:**
```
C = 4πε₀R
```

**Parallel Plate Capacitor:**
```
C = ε₀A/d  (no dielectric)
C = Kε₀A/d  (with dielectric of constant K)

E between plates = σ/ε₀ = V/d
```

**Spherical Capacitor (inner radius a, outer radius b):**
```
C = 4πε₀ab/(b − a)
```

**Cylindrical Capacitor (radii a, b, length L):**
```
C = 2πε₀L/ln(b/a)
```

## 2.6 Combinations of Capacitors

### Series:
```
1/C_eff = 1/C₁ + 1/C₂ + 1/C₃ + ...

Charge same on each: Q₁ = Q₂ = Q
Voltage divides: V₁/V₂ = C₂/C₁
```

### Parallel:
```
C_eff = C₁ + C₂ + C₃ + ...

Voltage same on each: V₁ = V₂ = V
Charge divides: Q₁/Q₂ = C₁/C₂
```

## 2.7 Energy Stored in Capacitor

```
U = ½QV = ½CV² = Q²/2C

Energy density (energy per unit volume):
u = ½ε₀E²  (without dielectric)
u = ½KE₀E²  (with dielectric K)
```

### Energy when capacitors are connected:
```
Common potential: V = (C₁V₁ + C₂V₂)/(C₁ + C₂)  [charge conserved]

Energy lost = ½C₁C₂(V₁−V₂)²/(C₁+C₂)  [always positive!]
```

## 2.8 Dielectrics

```
Dielectric constant: K = C/C₀ = E₀/E

Polarization: P = ε₀(K−1)E = χₑε₀E
χₑ = K − 1 = electric susceptibility

Effect of dielectric:
- C increases by K times
- E decreases by K times
- V decreases by K times (if Q constant)
- Q increases by K times (if V constant)
```

### Dielectric inserted in charged capacitor:
| Condition | C | V | E | Q | U |
|-----------|---|---|---|---|---|
| Battery connected (V const) | KC₀ | V₀ | E₀ | KQ₀ | KU₀ |
| Battery disconnected (Q const) | KC₀ | V₀/K | E₀/K | Q₀ | U₀/K |

---

# 3. CURRENT ELECTRICITY

## 3.1 Electric Current

```
I = dQ/dt = nAve

n = number density of free electrons
A = cross-sectional area
v = drift velocity
e = charge on electron

Unit: Ampere (A) = C/s
```

### Drift Velocity:
```
v_d = eEτ/m = eVτ/(mL)

τ = relaxation time (mean time between collisions)
```

## 3.2 Ohm's Law & Resistance

```
V = IR  (Ohm's Law)
R = ρL/A

ρ = resistivity (Ω·m)
L = length
A = cross-sectional area
```

### Temperature Dependence:
```
R_T = R₀(1 + αΔT) = R₀[1 + α(T − T₀)]

α = temperature coefficient of resistance

Metals: α > 0 (R increases with T)
Semiconductors/insulators: α < 0 (R decreases with T)
Alloys (Nichrome, Manganin): α ≈ 0 (nearly constant R)
```

### Conductance & Conductivity:
```
G = 1/R  (conductance, unit: Siemens = Ω⁻¹)
σ = 1/ρ  (conductivity, unit: S/m or Ω⁻¹m⁻¹)
```

### Relation between σ and microscopic quantities:
```
σ = ne²τ/m  (derived from drift velocity)
```

## 3.3 Combinations of Resistors

### Series:
```
R_eff = R₁ + R₂ + R₃ + ...
I same, V divides
V₁/V₂ = R₁/R₂
```

### Parallel:
```
1/R_eff = 1/R₁ + 1/R₂ + 1/R₃ + ...
V same, I divides
I₁/I₂ = R₂/R₁

For two resistors: R_eff = R₁R₂/(R₁ + R₂)
```

### Special Cases:
```
n identical resistors in series: R_eff = nR
n identical resistors in parallel: R_eff = R/n

Wire of resistance R cut into n equal pieces:
Each piece: R/n
All in parallel: R/n²
```

## 3.4 EMF & Internal Resistance

```
EMF (ε): Work done per unit charge = Energy per unit charge
Terminal voltage: V = ε − Ir  (discharging)
Terminal voltage: V = ε + Ir  (charging)

Current: I = ε/(R + r)

Power delivered to external R: P = I²R = ε²R/(R + r)²
Maximum power: when R = r → P_max = ε²/4r
```

### Cells in Combination:

**Series:**
```
ε_eff = ε₁ + ε₂ + ... (if same polarity)
r_eff = r₁ + r₂ + ...
I = Σε/(R + Σr)
```

**Parallel (identical cells):**
```
ε_eff = ε
r_eff = r/n
I = nε/(nR + r)
```

## 3.5 Kirchhoff's Laws

### KCL (Junction Rule):
```
ΣI_in = ΣI_out  (Conservation of charge)
At any junction: ΣI = 0
```

### KVL (Loop Rule):
```
Σ(ΔV) = 0 around any closed loop  (Conservation of energy)

Sign conventions:
- Cross resistor in direction of I: ΔV = −IR
- Cross resistor against direction of I: ΔV = +IR
- Cross EMF from − to + : ΔV = +ε
- Cross EMF from + to −: ΔV = −ε
```

## 3.6 Wheatstone Bridge

```
Balanced condition: P/Q = R/S  (no current through galvanometer)

If P/Q = R/S → galvanometer reads zero (null condition)
```

### Meter Bridge:
```
R/S = l/(100 − l)
R = S × l/(100 − l)

l = balance length (cm)
```

## 3.7 Potentiometer

**Principle:** The potential drop across a wire of uniform cross-section is proportional to its length.

```
V ∝ l

EMF comparison:
ε₁/ε₂ = l₁/l₂

Internal resistance:
r = R(l₁ − l₂)/l₂

where l₁ = balance length without external R
      l₂ = balance length with external R
```

> **Potentiometer vs Voltmeter:** Potentiometer draws no current → more accurate measurement!

## 3.8 Electrical Power & Energy

```
Power: P = VI = I²R = V²/R

Energy: E = Pt = VIt = I²Rt

Unit: Watt (W), kilowatt-hour (kWh)
1 kWh = 3.6 × 10⁶ J

Joule's Law: Heat produced H = I²Rt
```

---

# 4. MOVING CHARGES & MAGNETISM

## 4.1 Magnetic Force on Moving Charge (Lorentz Force)

```
F⃗ = q(v⃗ × B⃗)
|F| = qvB·sinθ

F⃗_total = q(E⃗ + v⃗ × B⃗)  [Lorentz force — total electromagnetic]
```

### Properties:
- Perpendicular to both v⃗ and B⃗
- Does NO work on the charge (power = F⃗·v⃗ = 0)
- Does NOT change speed, only direction
- Cannot change KE of particle

## 4.2 Motion of Charged Particle in Magnetic Field

### Circular Motion:
```
qvB = mv²/r

Radius: r = mv/(qB)

Time period: T = 2πm/(qB)  [independent of v and r!]

Frequency (cyclotron): f = qB/(2πm)  [independent of v!]

Angular frequency: ω = qB/m
```

### Helical Motion (v has component ∥ to B):
```
Pitch: p = v_∥ × T = 2πmv_∥/(qB)
Radius of helix: r = mv_⊥/(qB)
```

## 4.3 Cyclotron

```
Resonance condition: ν_rf = qB/(2πm)

Maximum KE:
KE_max = q²B²R²/(2m)

where R = radius of dee
```

> **Limitation:** Cannot accelerate electrons (relativistic effects). Works only for heavy positive ions.

## 4.4 Force on Current-Carrying Conductor

```
F⃗ = I(L⃗ × B⃗)
|F| = BIL·sinθ

For curved wire:
F = BI(L_eff)  where L_eff = straight line from start to end
```

### Force Between Two Parallel Wires:
```
F/L = μ₀I₁I₂/(2πd)

Parallel currents → attractive
Anti-parallel currents → repulsive

Definition of 1 Ampere: Current that produces F/L = 2×10⁻⁷ N/m between two parallel wires 1 m apart.
```

## 4.5 Torque on Current Loop

```
τ⃗ = m⃗ × B⃗ = NIAB·sinθ

m⃗ = NIA n̂  [magnetic dipole moment]
|m| = NIA

where N = turns, I = current, A = area

Potential energy: U = −m⃗ · B⃗ = −mB·cosθ
```

## 4.6 Biot-Savart Law

```
dB⃗ = (μ₀/4π) × (Idl⃗ × r̂)/r²

μ₀ = 4π × 10⁻⁷ T·m/A  [permeability of free space]
```

### Magnetic Field — Important Results:

**At center of circular loop (radius R):**
```
B = μ₀I/(2R)  (N turns: B = μ₀NI/2R)
```

**On axis of circular loop at distance x:**
```
B = μ₀IR²/[2(R² + x²)^(3/2)]

At center (x = 0): B = μ₀I/2R  [maximum]
Far away (x >> R): B = μ₀IR²/2x³ = μ₀m/2πx³
```

**Finite straight wire (angle α₁ and α₂):**
```
B = (μ₀I/4πd)(sinα₂ + sinα₁)

where d = perpendicular distance from wire
```

**Infinite straight wire:**
```
B = μ₀I/(2πr)  (circular field lines around wire)
```

**Semi-infinite wire:**
```
B = μ₀I/(4πr)
```

**At center of square loop (side a):**
```
B = 2√2μ₀I/(πa)
```

## 4.7 Ampere's Circuital Law

```
∮B⃗ · dl⃗ = μ₀I_enclosed

(Analogous to Gauss's law for electric field)
```

### Applications:

**Long straight solenoid (n = turns/length):**
```
B_inside = μ₀nI  (uniform, parallel to axis)
B_outside = 0
```

**Toroid (N turns, mean radius R):**
```
B_inside = μ₀NI/(2πR) = μ₀nI  (where n = N/2πR)
B_outside = 0
B in hole = 0
```

**Long coaxial cable (inner radius a, outer radius b):**
```
r < a: B = μ₀Ir/(2πa²)
a < r < b: B = μ₀I/(2πr)
r > b: B = 0 (for coaxial, opposite currents)
```

## 4.8 Galvanometer, Ammeter & Voltmeter

### Galvanometer:
```
Full-scale deflection current: I_g
Coil resistance: G
```

### Conversion to Ammeter (shunt S):
```
S = I_g × G/(I − I_g) = I_g·G/(I − I_g)

Ammeter R_eff = GS/(G+S)  [very small — connected in series]
```

### Conversion to Voltmeter (series resistance R):
```
R = V/I_g − G = (V − I_g·G)/I_g

Voltmeter R_eff = G + R  [very large — connected in parallel]
```

---

# 5. MAGNETISM & MATTER

## 5.1 Bar Magnet

### Magnetic Field of Bar Magnet:

**On axial line (end-on):**
```
B_axial = μ₀/(4π) × 2Mr/(r² − l²)²

For r >> l: B_axial = μ₀/(4π) × 2M/r³ = μ₀m/2πr³
```

**On equatorial line (broad-on):**
```
B_equatorial = μ₀/(4π) × M/(r² + l²)^(3/2)

For r >> l: B_equatorial = μ₀/(4π) × M/r³ = μ₀m/4πr³
```

```
B_axial/B_equatorial = 2  (for r >> l)
```

## 5.2 Gauss's Law for Magnetism

```
∮B⃗ · dA⃗ = 0

(No magnetic monopoles — field lines always form closed loops)
```

## 5.3 Magnetic Quantities

| Quantity | Symbol | Definition | Unit |
|----------|--------|-----------|------|
| Magnetic intensity | H | B/μ − M | A/m |
| Magnetization | M | m/V | A/m |
| Magnetic susceptibility | χ | M/H | dimensionless |
| Relative permeability | μᵣ | μ/μ₀ = 1 + χ | dimensionless |

```
B = μ₀(H + M) = μ₀μᵣH = μH
```

## 5.4 Types of Magnetic Materials

| Property | Diamagnetic | Paramagnetic | Ferromagnetic |
|----------|------------|--------------|---------------|
| χ | Small negative (−10⁻⁶ to −10⁻⁵) | Small positive (10⁻⁵ to 10⁻³) | Very large positive (10² to 10⁵) |
| μᵣ | Slightly < 1 | Slightly > 1 | >> 1 |
| Behavior in field | Weakly repelled | Weakly attracted | Strongly attracted |
| Examples | Bi, Cu, Pb, H₂O, NaCl | Al, Mn, O₂, Pt | Fe, Co, Ni |
| Temperature | Independent | Curie's law: χ ∝ 1/T | Above Curie temp → paramagnetic |

### Curie's Law (paramagnetic):
```
χ = C/T  (C = Curie constant)
```

### Curie-Weiss Law (ferromagnetic, T > T_C):
```
χ = C/(T − T_C)  (T_C = Curie temperature)
```

## 5.5 Hysteresis

- **Hysteresis loop** = B-H curve for ferromagnet
- **Retentivity:** B remaining when H = 0 (remnant magnetism)
- **Coercivity:** H needed to reduce B to zero
- **Area of hysteresis loop** = energy dissipated per cycle per unit volume

| Material | Retentivity | Coercivity | Use |
|---------|------------|-----------|-----|
| Soft iron | High | Low | Electromagnets, transformer cores |
| Steel/Alnico | High | High | Permanent magnets |

## 5.6 Earth's Magnetism

```
Angle of Declination: Angle between geographic north and magnetic north

Angle of Dip (Inclination): Angle of Earth's field with horizontal
- Magnetic poles: dip = 90°
- Magnetic equator: dip = 0°

Horizontal component: B_H = B·cosδ
Vertical component: B_V = B·sinδ
tanδ = B_V/B_H

|B| = √(B_H² + B_V²)
```

---

# 6. ELECTROMAGNETIC INDUCTION

## 6.1 Magnetic Flux

```
Φ_B = ∫B⃗ · dA⃗ = BA·cosθ

Unit: Weber (Wb) = T·m²
Dimensions: [M¹L²T⁻²A⁻¹]
```

## 6.2 Faraday's Laws

### First Law:
> An EMF is induced in a circuit when the magnetic flux through it changes.

### Second Law:
```
ε = −dΦ_B/dt

For N turns: ε = −N(dΦ_B/dt)
```

### Lenz's Law:
> The induced current opposes the change in flux causing it (consequence of energy conservation).

```
ε = −dΦ/dt  (the negative sign represents Lenz's law)
```

## 6.3 Motional EMF

```
EMF in a rod of length L moving with velocity v in field B:
ε = BvL  (when v, B, L are mutually perpendicular)

More generally: ε = ∫(v⃗ × B⃗) · dl⃗
```

### Rotating rod in magnetic field:
```
ε = ½BωL²  (rod rotating about one end)
ε = BωL²/2
```

### Rotating coil:
```
ε = NBAω·sin(ωt) = ε₀·sin(ωt)

ε₀ = NBAω = peak EMF
```

## 6.4 Self-Inductance

```
Φ = LI  →  L = Φ/I = NΦ_B/I

ε = −L(dI/dt)

Unit: Henry (H) = V·s/A = Ω·s
Dimensions: [M¹L²T⁻²A⁻²]
```

### Self-Inductance Formulas:

**Solenoid (n turns/length, length l, area A):**
```
L = μ₀n²Al = μ₀N²A/l
```

**Toroid (N turns, mean radius R, area A):**
```
L = μ₀N²A/(2πR)
```

## 6.5 Mutual Inductance

```
Φ₂₁ = MI₁  →  M = Φ₂₁/I₁

ε₂ = −M(dI₁/dt)

Neumann's formula: M = μ₀N₁N₂A/l  (for coaxial solenoids)
```

### Coupling Coefficient:
```
k = M/√(L₁L₂)   (0 ≤ k ≤ 1)

M_max = √(L₁L₂)  (when k = 1, perfect coupling)
```

## 6.6 Energy Stored in Inductor

```
U = ½LI²

Energy density: u = B²/(2μ₀)  [analogous to ½ε₀E² for capacitor]
```

## 6.7 Growth and Decay of Current (RL Circuit)

### Growth (switch closed):
```
I(t) = I₀(1 − e^(−t/τ))

I₀ = ε/R  (final steady state current)
τ = L/R  (time constant)
```

### Decay (source removed):
```
I(t) = I₀·e^(−t/τ)
```

> At t = τ: current is 63.2% of final (growth) or 36.8% of initial (decay)

## 6.8 Eddy Currents

- Induced currents in bulk conductors by changing B
- Always oppose cause (Lenz's law)
- Cause heating (I²R losses)
- **Applications:** Induction cookers, electromagnetic braking, speedometers, metal detectors
- **Minimization:** Laminated cores (thin sheets with insulation between them)

---

# 7. ALTERNATING CURRENT

## 7.1 AC Fundamentals

```
v(t) = V₀·sin(ωt) = V_m·sin(ωt)
i(t) = I₀·sin(ωt + φ)

V₀ = peak voltage, I₀ = peak current
ω = 2πf = 2π/T
```

### RMS Values:
```
V_rms = V₀/√2 ≈ 0.707 V₀
I_rms = I₀/√2 ≈ 0.707 I₀

Average value over half cycle: V_avg = 2V₀/π ≈ 0.637 V₀

Form factor = V_rms/V_avg = π/(2√2) ≈ 1.11
```

## 7.2 Phasors

- Phasors are rotating vectors representing AC quantities
- Magnitude = amplitude (peak value)
- Angle with x-axis = phase
- x-component = instantaneous value

## 7.3 AC Circuit Elements

### Pure Resistor:
```
v = V₀·sinωt → i = I₀·sinωt  (in phase)
Z_R = R
Power: P = V_rms·I_rms = I²_rms·R  (average power)
```

### Pure Inductor:
```
v = V₀·sinωt → i = I₀·sin(ωt − π/2)  (current LAGS by 90°)
X_L = ωL  (inductive reactance)
Z_L = jωL
Power: P_avg = 0  (purely reactive)
```

### Pure Capacitor:
```
v = V₀·sinωt → i = I₀·sin(ωt + π/2)  (current LEADS by 90°)
X_C = 1/(ωC)  (capacitive reactance)
Z_C = 1/(jωC)
Power: P_avg = 0  (purely reactive)
```

> **Memory:** "ELI the ICE man" — In inductor L, EMF (E) leads I; In capacitor C, I leads E.

## 7.4 Series RLC Circuit

```
Z = √(R² + (X_L − X_C)²) = √(R² + (ωL − 1/ωC)²)

Phase angle: tanφ = (X_L − X_C)/R

I₀ = V₀/Z

If X_L > X_C: inductive (current lags)
If X_L < X_C: capacitive (current leads)
If X_L = X_C: resonance (purely resistive)
```

## 7.5 Resonance in RLC Circuit

```
At resonance: X_L = X_C
ωL = 1/(ωC)
ω₀ = 1/√(LC)   [resonant angular frequency]
f₀ = 1/(2π√(LC))

At resonance:
- Z = R (minimum impedance)
- I = V/R (maximum current)
- φ = 0 (in phase)
- V_L = V_C (but opposite in phase, so they cancel)
```

### Quality Factor (Q-factor):
```
Q = ω₀L/R = 1/(ω₀CR) = (1/R)√(L/C)

Q = Resonant frequency / Bandwidth = ω₀/Δω

Higher Q → sharper resonance, more selective
```

### Bandwidth:
```
Δω = R/L = ω₀/Q
Δf = R/(2πL)
```

## 7.6 Power in AC Circuits

```
Instantaneous power: p = vi = V₀I₀·sinωt·sin(ωt − φ)

Average power: P_avg = ½V₀I₀·cosφ = V_rms·I_rms·cosφ

Power factor: cosφ = R/Z

Apparent power: S = V_rms·I_rms  [VA]
Real power: P = S·cosφ  [W]
Reactive power: Q = S·sinφ  [VAR]
S² = P² + Q²
```

| Circuit | Phase angle φ | Power factor cosφ | Average Power |
|---------|-------------|------------------|--------------|
| Pure R | 0 | 1 | V_rms·I_rms |
| Pure L | 90° | 0 | 0 |
| Pure C | −90° | 0 | 0 |
| RLC at resonance | 0 | 1 | V_rms·I_rms |

## 7.7 Transformer

```
Turns ratio: N₁/N₂ = V₁/V₂ = I₂/I₁

Step-up: N₂ > N₁ → V₂ > V₁, I₂ < I₁
Step-down: N₂ < N₁ → V₂ < V₁, I₂ > I₁

Efficiency: η = P_output/P_input = V₂I₂/(V₁I₁)

For ideal transformer: η = 100%

Power losses: Copper loss (I²R), Core/Iron loss (eddy currents + hysteresis)
```

---

# 8. ELECTROMAGNETIC WAVES

## 8.1 Maxwell's Equations

1. **Gauss's Law (Electric):** ∮E⃗ · dA⃗ = Q/ε₀
2. **Gauss's Law (Magnetic):** ∮B⃗ · dA⃗ = 0
3. **Faraday's Law:** ∮E⃗ · dl⃗ = −dΦ_B/dt
4. **Ampere-Maxwell Law:** ∮B⃗ · dl⃗ = μ₀(I + ε₀ dΦ_E/dt)

### Displacement Current:
```
I_D = ε₀(dΦ_E/dt) = ε₀·d(EA)/dt

Maxwell's correction to Ampere's law: includes displacement current
This predicted electromagnetic waves!
```

## 8.2 EM Waves

```
Speed in vacuum: c = 1/√(μ₀ε₀) = 3 × 10⁸ m/s

In medium: v = 1/√(με) = c/n

Refractive index: n = c/v = √(εᵣμᵣ) ≈ √εᵣ (for non-magnetic)

E⃗ and B⃗ are perpendicular to each other and to direction of propagation
E/B = c
```

### Properties:
- Transverse waves (E and B ⊥ to propagation)
- Travel at c in vacuum
- Not deflected by E or B fields
- Can travel through vacuum
- Carry energy and momentum
- Obey superposition

### EM Wave Equations:
```
E = E₀·sin(kx − ωt)
B = B₀·sin(kx − ωt)
E₀/B₀ = c
```

### Energy and Intensity:
```
Energy density: u = ½ε₀E² + B²/(2μ₀) = ε₀E²  (E and B contribute equally)

Intensity: I = u × c = ε₀cE₀²/2 = cB₀²/(2μ₀) = E₀B₀/(2μ₀)

Radiation pressure: P_rad = I/c  (for perfect absorption)
                   P_rad = 2I/c (for perfect reflection)
```

## 8.3 Electromagnetic Spectrum

| Name | Wavelength | Frequency | Source/Use |
|------|-----------|-----------|-----------|
| Radio waves | > 0.1 m | < 3 GHz | AM/FM radio, TV |
| Microwaves | 1mm–0.1m | 3GHz–300GHz | Radar, microwave oven, satellite |
| Infrared | 700nm–1mm | 3×10¹¹–4.3×10¹⁴ Hz | Heat, remote controls, thermal imaging |
| Visible | 400–700 nm | 4.3×10¹⁴–7.5×10¹⁴ Hz | Human vision |
| Ultraviolet | 10–400 nm | 7.5×10¹⁴–3×10¹⁶ Hz | Sterilization, vitamin D, ozone |
| X-rays | 0.01–10 nm | 3×10¹⁶–3×10¹⁹ Hz | Medical imaging, crystallography |
| Gamma rays | < 0.01 nm | > 3×10¹⁹ Hz | Nuclear reactions, cancer treatment |

---

# 9. RAY OPTICS & OPTICAL INSTRUMENTS

## 9.1 Reflection

```
Laws of Reflection:
1. Angle of incidence = Angle of reflection (i = r)
2. Incident ray, reflected ray, and normal are coplanar
```

### Plane Mirror:
- Image is virtual, erect, same size
- Image is laterally inverted
- Image distance = Object distance (behind mirror)
- Mirror moves by x → image moves by 2x

### Spherical Mirrors:

**Sign Convention (New Cartesian):**
- All distances from pole
- Along incident ray direction: positive
- Against incident ray: negative

**Mirror Formula:**
```
1/v + 1/u = 1/f = 2/R

f = R/2

Magnification: m = −v/u = h_i/h_o

m > 0: erect image (virtual)
m < 0: inverted image (real)
|m| > 1: magnified
|m| < 1: diminished
```

| Object position | Image (Concave) | Image (Convex) |
|----------------|----------------|----------------|
| At infinity | F, real, inverted, point | F, virtual, erect, diminished |
| Beyond C | Between F and C, real, inverted, diminished | Behind mirror, virtual, erect, diminished |
| At C | At C, real, inverted, same size | — |
| Between F and C | Beyond C, real, inverted, magnified | Behind mirror, virtual, erect, diminished |
| At F | At infinity | Behind mirror, virtual, erect, diminished |
| Between P and F | Behind mirror, virtual, erect, magnified | Behind mirror, virtual, erect, diminished |

## 9.2 Refraction

```
Snell's Law: n₁·sinθ₁ = n₂·sinθ₂
            μ₁sinθ₁ = μ₂sinθ₂

n = c/v = absolute refractive index
n₂₁ = n₂/n₁ = sinθ₁/sinθ₂ = v₁/v₂ = λ₁/λ₂
```

### Critical Angle & TIR:
```
At critical angle: θ₂ = 90°
sinC = n₂/n₁ = 1/n  (for n₁ > n₂, going from denser to rarer)

Total Internal Reflection: θ₁ > C

Applications: Optical fiber, diamond sparkle, mirage, prism instruments
```

### Optical Fiber:
```
Acceptance angle: sinθ_max = √(n₁² − n₂²)
NA (Numerical Aperture) = sinθ_max
```

## 9.3 Refraction at Spherical Surface

```
n₂/v − n₁/u = (n₂ − n₁)/R

Power of surface: P = (n₂ − n₁)/R
```

## 9.4 Lens Formula & Magnification

```
1/v − 1/u = 1/f  [Lens formula]

m = v/u = h_i/h_o

For lens: m = v/u (unlike mirror, no negative sign)
m > 0: same side as object → virtual, erect
m < 0: other side → real, inverted
```

### Lens Maker's Equation:
```
1/f = (n−1)[1/R₁ − 1/R₂]

n = refractive index of lens material
R₁, R₂ = radii of curvature (sign convention applies)

Power: P = 1/f  [f in metres → P in Diopters (D)]
```

### Combination of Lenses:
```
In contact: 1/f_eq = 1/f₁ + 1/f₂ + ...
            P_eq = P₁ + P₂ + ...

Separated by distance d: 1/f_eq = 1/f₁ + 1/f₂ − d/(f₁f₂)
```

### Displacement Method (to find f):
```
f = (D² − d²)/(4D)

where D = distance between object and screen
      d = distance between two positions of lens
```

## 9.5 Prism

```
Deviation: δ = (i₁ + i₂) − A   (A = prism angle)

At minimum deviation: i₁ = i₂ = i, r₁ = r₂ = r = A/2

n = sin[(A + δ_m)/2] / sin(A/2)

For small angle prism:
δ = (n − 1)A
```

### Dispersion:
```
Angular dispersion: δ_V − δ_R = (n_V − n_R)A

Dispersive power: ω = (n_V − n_R)/(n_y − 1) = (δ_V − δ_R)/δ_y

where subscripts V, R, y = violet, red, yellow
```

## 9.6 Optical Instruments

### Simple Microscope (Magnifying Glass):
```
M = 1 + D/f  (for image at near point D = 25 cm)
M = D/f  (for image at infinity, relaxed eye)
```

### Compound Microscope:
```
M = m_o × m_e

m_o = −v_o/u_o  (magnification of objective, real image)
m_e = 1 + D/f_e  (magnification of eyepiece)

Approximate: M = L × D/(f_o × f_e)

where L = tube length (distance between lenses minus focal lengths)
```

### Astronomical Telescope (Normal adjustment):
```
M = −f_o/f_e  (negative = inverted image)

Tube length = f_o + f_e
```

### Terrestrial Telescope:
Same as astronomical but with erecting lens → image is erect.

### Resolving Power:
```
Telescope: RP = D/(1.22λ)
Microscope: RP = 2n·sinα/λ  (Abbe criterion)

Limit of resolution (telescope): θ_min = 1.22λ/D
```

---

# 10. WAVE OPTICS

## 10.1 Huygens' Principle

1. Every point on a wavefront acts as a source of secondary spherical wavelets
2. The new wavefront is the common tangent to all secondary wavelets

### Laws of Reflection and Refraction from Huygens' Principle:
```
Refraction: sinθ₁/sinθ₂ = v₁/v₂ = n₂/n₁
```

## 10.2 Young's Double Slit Experiment (YDSE)

```
Setup: Two slits S₁ and S₂, separation d, screen at distance D

Path difference: Δ = d·sinθ ≈ dy/D  (for small θ)

Fringe width: β = λD/d

Condition for bright fringe: Δ = nλ → y_n = nλD/d
Condition for dark fringe: Δ = (2n−1)λ/2 → y_n = (2n−1)λD/2d
```

### Intensity in YDSE:
```
I = 4I₀·cos²(δ/2)  (if both slits have equal intensity I₀)

where δ = phase difference = (2π/λ) × path difference

I_max = 4I₀ (constructive, δ = 0, 2π, 4π...)
I_min = 0  (destructive, δ = π, 3π, 5π...)
```

### With initial phase difference (or path difference):
```
For unequal intensities I₁ and I₂:
I = I₁ + I₂ + 2√(I₁I₂)·cosδ

I_max = (√I₁ + √I₂)²
I_min = (√I₁ − √I₂)²

I_max/I_min = [(√I₁ + √I₂)/(√I₁ − √I₂)]²
```

### Effect of Immersing in Medium:
```
λ_medium = λ/n → β_medium = λD/(nd)  (fringe width decreases)
```

### Effect of Moving Source:
```
Extra path difference introduced at S
If source moves by y₀: Fringe shift = (y₀/D_s) × (D/d) where D_s = source to slit dist.
```

## 10.3 Single Slit Diffraction

```
Condition for minima: a·sinθ = nλ  (n = ±1, ±2, ...)
y_n = nλD/a

Width of central maximum: 2λD/a = 2y₁

Angular half-width of central max: θ = λ/a

Secondary maxima: a·sinθ = (2n+1)λ/2  (approximate)
```

### Intensity Pattern:
```
I = I₀[sin(α)/α]²  where α = πa·sinθ/λ

Central max: I₀ at θ = 0
First secondary max: I₀/22 at α = 3π/2
```

## 10.4 Diffraction Grating

```
d(sinθ + sinα) = mλ  (general grating equation)

For normal incidence (α = 0):
d·sinθ = mλ  (m = 0, ±1, ±2, ...)

Resolving power: RP = λ/dλ = mN

where N = total number of slits, m = order
```

## 10.5 Polarization

### Malus's Law:
```
I = I₀·cos²θ

where θ = angle between polarizer and analyzer
I₀ = intensity after first polarizer = I_unpolarized/2
```

### Brewster's Law:
```
At polarizing angle (Brewster's angle) i_B:
n = tan(i_B)

Reflected ray is completely polarized (perpendicular to plane of incidence)
i_B + r_B = 90°
```

## 10.6 Thin Film Interference

```
For reflected rays (thin film of thickness t, refractive index n):

Constructive (if one reflection has phase change):
2nt = (2m+1)λ/2 = (m + ½)λ

Destructive:
2nt = mλ

(Phase change of π on reflection from denser medium)
```

---

# 11. DUAL NATURE OF RADIATION & MATTER

## 11.1 Photoelectric Effect

**Observations:**
1. Instantaneous emission of electrons
2. Minimum frequency (threshold) required
3. Max KE ∝ frequency (not intensity)
4. Photocurrent ∝ intensity
5. Stopping potential independent of intensity

### Einstein's Photoelectric Equation:
```
KE_max = hν − φ = h(ν − ν₀)

φ = hν₀ = work function (minimum energy to eject electron)
ν₀ = threshold frequency
λ₀ = c/ν₀ = threshold wavelength

eV₀ = KE_max = hν − φ

V₀ = stopping potential
```

### Work Functions of Common Metals:
| Metal | φ (eV) |
|-------|--------|
| Cs | 2.0 |
| Na | 2.3 |
| Ag | 4.3 |
| Pt | 5.65 |

```
h = 6.626 × 10⁻³⁴ J·s = 4.136 × 10⁻¹⁵ eV·s
hc = 1240 eV·nm = 12400 eV·Å
```

## 11.2 Photon Properties

```
Energy: E = hν = hc/λ

Momentum: p = h/λ = E/c = hν/c

Mass: m = E/c² = h/(λc)  [equivalent mass, photon has zero rest mass]

Rest mass of photon = 0

Speed in vacuum = c always
```

## 11.3 de Broglie Hypothesis (Wave-Particle Duality)

```
de Broglie wavelength: λ = h/p = h/(mv)

For particle accelerated through voltage V:
λ = h/√(2mqV)   [non-relativistic]

For electron: λ = 12.27/√V  Å  (V in volts)

For thermal particles (kinetic energy = 3kT/2):
λ = h/√(3mkT)
```

### Davisson-Germer Experiment:
Experimentally confirmed wave nature of electrons through electron diffraction.

```
nλ = d·sinφ  (for diffraction peaks)
```

## 11.4 Heisenberg Uncertainty Principle

```
Δx · Δpₓ ≥ h/(4π) = ℏ/2  (ℏ = h/2π = 1.055 × 10⁻³⁴ J·s)

ΔE · Δt ≥ ℏ/2

ΔL · Δθ ≥ ℏ/2
```

> This is fundamental (not due to measurement limitations) — particles do NOT have definite position AND momentum simultaneously.

---

# 12. ATOMS

## 12.1 Rutherford's Nuclear Model

- Most of atom is empty space
- All positive charge concentrated in tiny nucleus
- Electrons orbit nucleus

**Failure:** Could not explain stability (accelerating electrons should radiate and spiral in), nor discrete spectral lines.

## 12.2 Bohr's Model of Hydrogen Atom

### Bohr's Postulates:
1. Electrons move in fixed circular orbits without radiating
2. Only orbits where angular momentum = nh/(2π) are allowed
3. Radiation emitted/absorbed when electron changes orbit

### Quantization of Angular Momentum:
```
L = mvr = nℏ = nh/(2π)  (n = 1, 2, 3, ...)
```

### Radius of nth Orbit (Bohr radius):
```
rₙ = n²a₀/Z

a₀ = 0.529 Å = 0.0529 nm  (Bohr radius for n=1, Z=1)
rₙ = n² × 0.529/Z  Å
```

### Velocity of Electron:
```
vₙ = Ze²/(2ε₀hn) = (e²/4πε₀ℏ) × Z/n = αc × Z/n

α = fine structure constant = 1/137
v₁ = 2.18 × 10⁶ m/s for hydrogen
```

### Total Energy:
```
KE = Ze²/(8πε₀rₙ) = 13.6Z²/n²  eV
PE = −Ze²/(4πε₀rₙ) = −27.2Z²/n²  eV
E_n = −13.6Z²/n²  eV

E₁ = −13.6 eV  (ground state of H)
E_n = E₁/n²

Ionization energy = |E₁| = 13.6 eV (for H)
```

### Frequency & Wavelength of Emitted Photon:
```
hν = E_n₂ − E_n₁  (transition from n₂ to n₁, n₂ > n₁)

Rydberg formula:
1/λ = RH × Z²(1/n₁² − 1/n₂²)

RH = 1.097 × 10⁷ m⁻¹  (Rydberg constant)
```

## 12.3 Spectral Series of Hydrogen

| Series | n₁ | n₂ | Region |
|--------|-----|-----|--------|
| Lyman | 1 | 2,3,4,... | UV |
| Balmer | 2 | 3,4,5,... | Visible (first 4 lines) |
| Paschen | 3 | 4,5,6,... | Near IR |
| Brackett | 4 | 5,6,7,... | IR |
| Pfund | 5 | 6,7,8,... | Far IR |

```
For Balmer series (visible):
Hα: 3→2, λ = 656.3 nm (red)
Hβ: 4→2, λ = 486.1 nm (blue-green)
Hγ: 5→2, λ = 434.0 nm (violet)
Hδ: 6→2, λ = 410.2 nm (violet)
```

## 12.4 Limitations of Bohr Model

- Cannot explain spectra of multi-electron atoms
- Cannot explain intensity of spectral lines
- Cannot explain fine structure (splitting of lines)
- Cannot explain chemical bonding
- Violates Heisenberg uncertainty principle (assumes fixed orbits)

---

# 13. NUCLEI

## 13.1 Nuclear Properties

```
Atomic number: Z = number of protons
Mass number: A = number of protons + neutrons (nucleons)
Neutron number: N = A − Z

Nuclear radius: R = R₀A^(1/3)
R₀ = 1.2 × 10⁻¹⁵ m = 1.2 fm

Nuclear volume ∝ A
Nuclear density ≈ 2.3 × 10¹⁷ kg/m³  [constant for all nuclei!]
```

### Isotopes, Isobars, Isotones:
| Term | Same | Different |
|------|------|-----------|
| Isotopes | Z | A, N |
| Isobars | A | Z, N |
| Isotones | N | Z, A |

## 13.2 Mass Defect & Binding Energy

```
Mass defect: Δm = Zmp + Nmn − M_nucleus
(M_nucleus < Zmp + Nmn — Einstein's mass-energy relation!)

Binding Energy: BE = Δm × c²
               BE = Δm × 931.5 MeV/u

Binding Energy per nucleon: BE/A

1 u (atomic mass unit) = 1.66 × 10⁻²⁷ kg = 931.5 MeV/c²
```

### BE/A Curve:
- Rises steeply for light nuclei (fusion releases energy)
- Peaks at Fe-56 (~8.8 MeV/nucleon) — most stable
- Slowly decreases for heavy nuclei (fission releases energy)

## 13.3 Radioactive Decay

### Types:

**α-decay:**
```
ᴬ_Z X → ᴬ⁻⁴_(Z−2) Y + ⁴_₂He (α particle)

Alpha = ⁴He nucleus (2 protons + 2 neutrons)
Stopped by paper or few cm of air
```

**β⁻-decay:**
```
ᴬ_Z X → ᴬ_(Z+1) Y + e⁻ + ν̄_e

Neutron → Proton + electron + antineutrino
Stopped by few mm of aluminum
```

**β⁺-decay (Positron emission):**
```
ᴬ_Z X → ᴬ_(Z−1) Y + e⁺ + ν_e

Proton → Neutron + positron + neutrino
```

**Electron Capture:**
```
p + e⁻ → n + ν_e
```

**γ-decay:**
```
No change in Z or A — nucleus goes from excited to ground state
Stopped by thick lead or concrete
```

### Radioactive Decay Law:
```
N(t) = N₀·e^(−λt)

Activity: A = −dN/dt = λN = A₀e^(−λt)

Half-life: T₁/₂ = ln2/λ = 0.693/λ

Mean life: τ = 1/λ = T₁/₂/ln2 = 1.44T₁/₂

After n half-lives: N = N₀/2ⁿ, A = A₀/2ⁿ

Unit of Activity: Becquerel (Bq) = 1 decay/s
                  1 Curie (Ci) = 3.7 × 10¹⁰ Bq
```

## 13.4 Nuclear Reactions

```
Q-value = (Mass of reactants − Mass of products) × c²
        = (KE of products − KE of reactants)

Q > 0: Exothermic (energy released)
Q < 0: Endothermic (energy absorbed)
```

### Fission:
```
²³⁵_₉₂U + n → ⁹⁶_₃₆Kr + ¹³⁷_₅₆Ba + 3n + Q

Q ≈ 200 MeV per fission

Chain reaction: k = number of neutrons causing further fission
k < 1: Subcritical (reaction dies)
k = 1: Critical (steady reaction) — nuclear reactor
k > 1: Supercritical — nuclear bomb
```

### Fusion:
```
²_₁H + ³_₁H → ⁴_₂He + n + 17.6 MeV

Requires very high temperature (10⁷ K) — thermonuclear reaction
Sun's energy source, hydrogen bomb
```

---

# 14. SEMICONDUCTOR ELECTRONICS

## 14.1 Energy Bands in Solids

```
Valence band: Filled with valence electrons
Conduction band: Empty or partially filled
Band gap (E_g): Energy gap between them

Conductors: E_g = 0 (bands overlap)
Semiconductors: E_g small (Si: 1.1 eV, Ge: 0.67 eV)
Insulators: E_g large (Diamond: 5.5 eV)
```

## 14.2 Intrinsic Semiconductors

- Pure semiconductor (Si or Ge)
- At 0K: acts as insulator (all electrons in valence band)
- At room temp: thermal energy breaks some bonds → electron-hole pairs
- n = p = nᵢ (intrinsic carrier concentration)
- Conductivity increases with temperature (opposite to metals!)

## 14.3 Extrinsic Semiconductors

### n-type (donor impurity):
```
Add pentavalent atoms (P, As, Sb) to Si
Extra electron → majority carriers are electrons
nₑ >> nₕ
Fermi level moves toward conduction band
```

### p-type (acceptor impurity):
```
Add trivalent atoms (B, Al, Ga, In) to Si
Hole created → majority carriers are holes
nₕ >> nₑ
Fermi level moves toward valence band
```

### Mass Action Law:
```
nₑ × nₕ = nᵢ²  (always valid in thermal equilibrium)
```

## 14.4 p-n Junction Diode

### Formation:
- p-n junction formed at interface
- Diffusion of holes to n-side, electrons to p-side
- Depletion layer (no free carriers) forms
- Built-in electric field (n→p) developed
- Contact potential (barrier potential) ≈ 0.3V (Ge), 0.7V (Si)

### Forward Bias (p to +, n to −):
```
Barrier reduces, current flows easily
I = I₀(e^(eV/kT) − 1)  (Shockley diode equation)

I₀ = reverse saturation current
Cut-in voltage: 0.3V (Ge), 0.7V (Si)
```

### Reverse Bias (p to −, n to +):
```
Barrier increases, only leakage current (~μA)
At breakdown voltage: large reverse current flows
```

## 14.5 Diode Circuits

### Half-Wave Rectifier:
```
Output frequency = Input frequency (f)
Ripple factor r = 1.21
Efficiency η = 40.6%
V_dc = V_m/π ≈ 0.318V_m
I_dc = I_m/π
```

### Full-Wave Rectifier (Centre-tap):
```
Output frequency = 2f
Ripple factor r = 0.48
Efficiency η = 81.2%
V_dc = 2V_m/π ≈ 0.636V_m
I_dc = 2I_m/π
```

### Bridge Rectifier:
```
Output frequency = 2f
Same as full-wave but no centre tap needed
Uses 4 diodes instead of 2
```

### Filter Capacitor:
```
V_ripple = I_dc/(fC)  (full-wave)
Ripple factor = 1/(4√3 fCR_L)
```

## 14.6 Special Purpose Diodes

### Zener Diode:
```
Works in reverse breakdown (Zener breakdown or avalanche)
Used as voltage regulator

For voltage regulation:
V_out = V_Z (constant)
I_Z = (V_in − V_Z)/R_s − I_L

Condition: I_Z(min) < I_Z < I_Z(max)
```

### LED (Light Emitting Diode):
```
Emits photon when electron-hole recombination occurs:
hν ≈ E_g  (photon energy ≈ band gap)

Different band gaps → different colors
GaAs: infrared
GaP: green/red
GaN: blue/UV
InGaN: white
```

### Photodiode:
- Operated in reverse bias
- Light creates electron-hole pairs → increases reverse current
- Photocurrent ∝ Light intensity
- Used in light detectors, solar cells

### Solar Cell:
```
P-V characteristics: similar to diode
Fill Factor FF = P_max/(V_oc × I_sc)
Efficiency η = P_max/P_incident
```

## 14.7 Bipolar Junction Transistor (BJT)

### Structure:
- Three regions: Emitter (E), Base (B), Collector (C)
- Two types: npn and pnp
- Emitter is heavily doped, collector is lightly doped, base is very thin

### Current Relations:
```
I_E = I_B + I_C

α = I_C/I_E  (common base current gain, < 1, ≈ 0.95–0.99)
β = I_C/I_B  (common emitter current gain, ≈ 20–200)

β = α/(1 − α)
α = β/(β + 1)
```

### Operating Regions:
| Region | E-B junction | C-B junction | Use |
|--------|-------------|-------------|-----|
| Active | Forward | Reverse | Amplifier |
| Saturation | Forward | Forward | Switch ON |
| Cutoff | Reverse | Reverse | Switch OFF |

### Common Emitter Amplifier:
```
Voltage gain: A_v = −β × R_C/r_be

Input resistance: R_in = β × r_e ≈ βr_e
where r_e = 26mV/I_E (at room temp)

Power gain: A_p = β² × R_C/r_be

Phase shift: 180° (inverting amplifier)
```

## 14.8 Logic Gates

### Basic Gates:

**AND gate:**
```
Y = A · B
Output HIGH only when both inputs HIGH
```

**OR gate:**
```
Y = A + B
Output HIGH when at least one input HIGH
```

**NOT gate (Inverter):**
```
Y = Ā
Output is complement of input
```

**NAND gate (Universal):**
```
Y = A̅·̅B̅ = ̄(AB)
Can implement all other gates
```

**NOR gate (Universal):**
```
Y = A̅+̅B̅ = ̄(A+B)
Can implement all other gates
```

**XOR gate:**
```
Y = A ⊕ B = AB̄ + ĀB
Output HIGH when inputs are DIFFERENT
```

**XNOR gate:**
```
Y = A ⊙ B = AB + ĀB̄
Output HIGH when inputs are SAME
```

### Boolean Algebra Theorems:
```
De Morgan's Laws:
̄(A + B) = Ā · B̄   (NOT-OR = NAND-like)
̄(A · B) = Ā + B̄   (NOT-AND = NOR-like)

Identity laws: A+0=A, A·1=A
Complement: A+Ā=1, A·Ā=0
Idempotent: A+A=A, A·A=A
Absorption: A+AB=A, A(A+B)=A
```

## 14.9 Operational Amplifier (Op-Amp Basics)

```
Ideal Op-Amp:
- Infinite open-loop gain (A → ∞)
- Infinite input impedance (R_in → ∞)
- Zero output impedance (R_out = 0)
- Infinite bandwidth

Inverting amplifier: A_v = −R_f/R_in
Non-inverting amplifier: A_v = 1 + R_f/R_in
```

---

# 15. COMMUNICATION SYSTEMS

## 15.1 Basic Elements

```
Signal → Transmitter → Channel → Receiver → Output

Analog: continuous variation (music, voice)
Digital: discrete values (0 and 1)
```

## 15.2 Bandwidth

```
Audio signal: 20 Hz to 20 kHz (bandwidth ≈ 20 kHz)
Video signal: bandwidth ≈ 4.2 MHz
AM broadcast: 540 kHz to 1600 kHz
FM broadcast: 88 MHz to 108 MHz
```

## 15.3 Modulation

**Need for modulation:**
- Audio frequencies have short range
- Multiple signals would mix (need carrier differentiation)
- Antennas would be impractically large

### Amplitude Modulation (AM):
```
c(t) = A_c·sin(ω_c t)  [carrier]
m(t) = A_m·sin(ω_m t)  [message]

AM signal: s(t) = A_c[1 + m_a·sin(ω_m t)]·sin(ω_c t)

Modulation index: m_a = A_m/A_c  (0 ≤ m_a ≤ 1)

AM contains:
- Carrier: frequency f_c, amplitude A_c
- USB (Upper Sideband): frequency f_c + f_m
- LSB (Lower Sideband): frequency f_c − f_m

Bandwidth of AM = 2 × f_m(max)
```

### Frequency Modulation (FM):
```
Frequency of carrier varies with message signal

Modulation index: β = Δf/f_m

Advantages of FM over AM:
- Less noise susceptibility
- Better audio quality
- No change in amplitude → less interference
```

## 15.4 Range of Communication

```
Ground wave: follows Earth's curvature
Range = √(2Rh)  where R = Earth's radius, h = antenna height

For two antennas of heights h_t and h_r:
d_max = √(2Rh_t) + √(2Rh_r)

Sky wave: reflects from ionosphere (F layer, ≈ 250 km)
Used for HF (3–30 MHz) international communication

Space wave (line of sight): above 40 MHz, satellite communication
```

---

# 📊 QUICK REFERENCE — IMPORTANT CONSTANTS (Class 12)

| Constant | Value |
|----------|-------|
| ε₀ (permittivity of free space) | 8.85 × 10⁻¹² C²/(N·m²) |
| μ₀ (permeability of free space) | 4π × 10⁻⁷ T·m/A |
| k = 1/(4πε₀) | 9 × 10⁹ N·m²/C² |
| c (speed of light) | 3 × 10⁸ m/s |
| e (electron charge) | 1.6 × 10⁻¹⁹ C |
| m_e (electron mass) | 9.11 × 10⁻³¹ kg |
| m_p (proton mass) | 1.67 × 10⁻²⁷ kg |
| m_n (neutron mass) | 1.675 × 10⁻²⁷ kg |
| h (Planck's constant) | 6.626 × 10⁻³⁴ J·s |
| ℏ = h/2π | 1.055 × 10⁻³⁴ J·s |
| hc | 1240 eV·nm |
| k_B (Boltzmann constant) | 1.38 × 10⁻²³ J/K |
| N_A (Avogadro's number) | 6.022 × 10²³ mol⁻¹ |
| 1 eV | 1.6 × 10⁻¹⁹ J |
| 1 u (atomic mass unit) | 1.66 × 10⁻²⁷ kg = 931.5 MeV/c² |
| R_H (Rydberg constant) | 1.097 × 10⁷ m⁻¹ |
| a₀ (Bohr radius) | 0.529 Å |
| σ (Stefan's constant) | 5.67 × 10⁻⁸ W/(m²K⁴) |

---

# 🎯 JEE-SPECIFIC TIPS & TRICKS

## High-Weightage Topics (Class 12, based on trends):
1. **Electrostatics + Capacitors** — 3–4 questions every year
2. **Current Electricity** — Kirchhoff's + Wheatstone
3. **Electromagnetic Induction + AC Circuits** — frequently combined
4. **Ray Optics + Wave Optics** — both important
5. **Modern Physics** — photoelectric, Bohr model, nuclei
6. **Semiconductors** — diode, transistor, logic gates

## Critical Formulas to Memorize Instantly:

### Electric Field (must know all cases):
```
Point charge: E = kq/r²
Line charge: E = λ/2πε₀r
Sheet: E = σ/2ε₀
Inside sphere (uniform): E = kQr/R³
Outside sphere: E = kQ/r²
Inside conducting shell: E = 0
```

### Magnetic Field (must know all cases):
```
Infinite wire: B = μ₀I/2πr
Center of loop: B = μ₀I/2R
Solenoid: B = μ₀nI
Toroid: B = μ₀NI/2πr
Moving charge: B = μ₀qv sinθ/4πr²
```

### Optics Quick Checks:
```
Mirror: 1/v + 1/u = 1/f
Lens: 1/v − 1/u = 1/f
Lens maker's: 1/f = (n−1)(1/R₁ − 1/R₂)
Prism min dev: n = sin[(A+δ)/2]/sin(A/2)
TIR: sinC = 1/n
YDSE fringe: β = λD/d
```

## Common JEE Traps:
- Sign convention: **different** for mirrors (1/v + 1/u = 1/f) and lenses (1/v − 1/u = 1/f)
- Magnetic force does **no work** — KE doesn't change in pure magnetic field
- At resonance: Z = R (minimum), I is maximum — V_L and V_C can be >> V_source!
- Zener diode works in **reverse bias** (unlike normal diode)
- Transistor: common emitter has 180° phase shift, common base doesn't
- In YDSE: extra path difference from optical path length (nL), not geometrical
- Binding energy per nucleon: **Iron is most stable** (peak at Fe-56)
- Half-life: After n half-lives, N = N₀/2ⁿ (don't use N₀/n!)

---

# 📝 FORMULA SHEET — ONE-PAGE SUMMARY (Class 12)

```
ELECTROSTATICS
F = kq₁q₂/r² | E = kQ/r² | V = kQ/r | U = kq₁q₂/r
E = −dV/dr | C = ε₀A/d | U_cap = ½CV²
ε = −N(dΦ/dt) | F = q(E + v×B)

CURRENT ELECTRICITY
V = IR | R = ρL/A | I = nAve | P = VI = I²R
KCL: ΣI = 0 | KVL: ΣV = 0 | Bridge: P/Q = R/S
Potentiometer: ε₁/ε₂ = l₁/l₂

MAGNETISM
F = qvBsinθ | F = BILsinθ | τ = NIAB sinθ
B_wire = μ₀I/2πr | B_loop-center = μ₀I/2R | B_solenoid = μ₀nI
r = mv/qB | T = 2πm/qB | F/L = μ₀I₁I₂/2πd

EMI & AC
ε = −dΦ/dt | ε = BvL | L = NΦ/I | U_L = ½LI²
X_L = ωL | X_C = 1/ωC | Z = √(R²+(X_L−X_C)²)
ω₀ = 1/√LC | Q = ω₀L/R | P = V_rms·I_rms·cosφ
Transformer: N₁/N₂ = V₁/V₂ = I₂/I₁

OPTICS
Mirror: 1/v + 1/u = 1/f | m = −v/u
Lens: 1/v − 1/u = 1/f | m = v/u | P = 1/f(m)
Snell: n₁sinθ₁ = n₂sinθ₂ | TIR: sinC = n₂/n₁
YDSE: β = λD/d | I = 4I₀cos²(δ/2)
Diffraction: a sinθ = nλ | Malus: I = I₀cos²θ

MODERN PHYSICS
E = hν = hc/λ | p = h/λ | KE_max = hν − φ = eV₀
λ_dB = h/mv | Δx·Δp ≥ ℏ/2
E_n = −13.6Z²/n² eV | rₙ = n²a₀/Z

NUCLEAR
R = R₀A^(1/3) | BE = Δmc² | N = N₀e^(−λt)
T₁/₂ = 0.693/λ | τ = 1/λ | A = λN

SEMICONDUCTORS
Diode: I = I₀(e^(eV/kT)−1) | β = I_C/I_B | α = β/(1+β)
A_v(CE) = −βR_C/r_be | NAND/NOR are universal gates
```

---

# 🧪 IIT JEE Class 11 Chemistry — Complete Study Guide
### Every Concept | Every Formula | Every Reaction

> **Covers:** NCERT + JEE Advanced Level | Chapters 1–14 (Class 11)

---

## 📋 TABLE OF CONTENTS

1. [Some Basic Concepts of Chemistry](#1-some-basic-concepts-of-chemistry)
2. [Structure of Atom](#2-structure-of-atom)
3. [Classification of Elements & Periodicity](#3-classification-of-elements--periodicity-in-properties)
4. [Chemical Bonding & Molecular Structure](#4-chemical-bonding--molecular-structure)
5. [States of Matter](#5-states-of-matter-gases--liquids)
6. [Thermodynamics](#6-thermodynamics)
7. [Equilibrium](#7-equilibrium)
8. [Redox Reactions](#8-redox-reactions)
9. [Hydrogen](#9-hydrogen)
10. [s-Block Elements](#10-s-block-elements)
11. [p-Block Elements (Group 13 & 14)](#11-p-block-elements-group-13--14)
12. [Organic Chemistry — Basic Principles](#12-organic-chemistry--basic-principles--techniques)
13. [Hydrocarbons](#13-hydrocarbons)
14. [Environmental Chemistry](#14-environmental-chemistry)

---

---

# 1. SOME BASIC CONCEPTS OF CHEMISTRY

## 1.1 Matter and Its Classification

```
Matter
├── Pure Substances
│   ├── Elements (H, O, Fe...)
│   └── Compounds (H₂O, NaCl...)
└── Mixtures
    ├── Homogeneous (solutions)
    └── Heterogeneous (suspensions, colloids)
```

## 1.2 SI Units (Fundamental)

| Physical Quantity | SI Unit | Symbol |
|---|---|---|
| Mass | Kilogram | kg |
| Length | Metre | m |
| Time | Second | s |
| Temperature | Kelvin | K |
| Amount of substance | Mole | mol |
| Electric current | Ampere | A |
| Luminous intensity | Candela | cd |

### Derived Units

- **Pressure:** Pa = N/m² = kg·m⁻¹·s⁻²
- **Energy:** J = kg·m²·s⁻²
- **Density:** kg·m⁻³

### Temperature Conversions

```
K = °C + 273.15
°F = (9/5)°C + 32
°C = (°F − 32) × 5/9
```

## 1.3 Significant Figures Rules

1. All non-zero digits are significant
2. Zeros between non-zero digits are significant (e.g., 1007 → 4 sig figs)
3. Leading zeros are NOT significant (e.g., 0.0045 → 2 sig figs)
4. Trailing zeros after decimal ARE significant (e.g., 3.600 → 4 sig figs)
5. Trailing zeros in a whole number are ambiguous → use scientific notation

**Arithmetic Rules:**
- Addition/Subtraction → Answer has fewest decimal places
- Multiplication/Division → Answer has fewest significant figures

## 1.4 Laws of Chemical Combination

### Law of Conservation of Mass (Lavoisier, 1774)
> *Mass of reactants = Mass of products in a chemical reaction*

### Law of Definite Proportions (Proust, 1799)
> *A pure compound always contains the same elements in the same proportion by mass*

### Law of Multiple Proportions (Dalton, 1803)
> *When two elements form more than one compound, the masses of one element that combine with a fixed mass of the other are in a small whole number ratio*

**Example:** CO and CO₂
- In CO: mass of O per 12g C = 16g
- In CO₂: mass of O per 12g C = 32g
- Ratio = 1 : 2 ✓

### Gay-Lussac's Law of Gaseous Volumes (1808)
> *Gases combine in simple whole number ratios by volume at constant T and P*

### Avogadro's Law
> *Equal volumes of all gases at same T and P contain equal number of molecules*

## 1.5 Atomic and Molecular Masses

- **Atomic Mass Unit (amu or u):** 1 amu = 1/12 × mass of ¹²C = 1.66056 × 10⁻²⁷ kg
- **Atomic mass** = average mass relative to 1/12 of ¹²C

### Molecular Mass
```
Molecular Mass = Σ (atomic mass × number of atoms)

Example: H₂SO₄
= 2(1) + 32 + 4(16) = 98 u
```

### Formula Mass (for ionic compounds)
```
NaCl = 23 + 35.5 = 58.5 u
```

## 1.6 Mole Concept ⭐ (Most Important for JEE)

### Mole Definition
> *1 mole = 6.022 × 10²³ particles (Avogadro's number, Nₐ)*

### Key Formulas

```
                  Given mass (g)
Number of moles = ──────────────────
                  Molar mass (g/mol)

Number of particles = n × Nₐ

                Volume at STP (L)
For gases: n = ──────────────────
                    22.4 L/mol
```

> **STP (Standard Temperature & Pressure):**
> - Old STP: 0°C (273.15 K), 1 atm → Molar volume = 22.4 L/mol
> - New IUPAC STP: 0°C, 1 bar → Molar volume = 22.7 L/mol
> *(JEE uses 22.4 L/mol — old STP)*

### Molar Mass
- Equal to atomic/molecular mass in g/mol
- H₂O = 18 g/mol, NaCl = 58.5 g/mol

## 1.7 Percentage Composition

```
               Mass of element in 1 mol of compound
% by mass = ─────────────────────────────────────── × 100
                    Molar mass of compound
```

**Example:** % of H in H₂O = (2/18) × 100 = 11.11%

## 1.8 Empirical and Molecular Formula

### Steps to find Empirical Formula:
1. Find % composition of each element
2. Divide by atomic mass → mole ratio
3. Divide by smallest mole ratio → simplest whole number ratio
4. That gives Empirical Formula

### Molecular Formula from Empirical Formula:
```
Molecular Formula = n × Empirical Formula

        Molecular mass
n = ───────────────────
      Empirical Formula mass
```

## 1.9 Stoichiometry and Limiting Reagent

### Steps for Stoichiometry Problems:
1. Write balanced chemical equation
2. Convert masses to moles
3. Use mole ratio from equation
4. Convert back to mass/volume

### Limiting Reagent
> *The reagent that is completely consumed first, limiting the amount of product formed*

**To find:** Divide moles of each reactant by its stoichiometric coefficient → smallest ratio is limiting reagent

### Percent Yield
```
           Actual yield
% Yield = ─────────────── × 100
          Theoretical yield
```

## 1.10 Concentration Terms (Solutions)

### Molarity (M)
```
         Moles of solute
M = ──────────────────────
    Volume of solution (L)

     W × 1000
M = ──────────
     M.M × V(mL)
```

### Molality (m)
```
         Moles of solute
m = ──────────────────────────────
    Mass of solvent (kg)

     W_solute × 1000
m = ─────────────────────────
    M.M_solute × W_solvent(g)
```

### Mole Fraction (χ)
```
         n_A
χ_A = ─────────
       n_A + n_B

χ_A + χ_B = 1
```

### Mass Percent (w/w)
```
           Mass of solute
w/w % = ─────────────────── × 100
         Mass of solution
```

### Parts per million (ppm)
```
         Mass of solute
ppm = ─────────────────── × 10⁶
      Mass of solution
```

### Normality (N)
```
N = M × n-factor

         Equivalents of solute
N = ─────────────────────────────
    Volume of solution (L)
```

---

---

# 2. STRUCTURE OF ATOM

## 2.1 Subatomic Particles

| Particle | Symbol | Charge | Mass (amu) | Discovered by |
|---|---|---|---|---|
| Electron | e⁻ | −1 | 1/1836 ≈ 0.00055 | J.J. Thomson (1897) |
| Proton | p⁺ | +1 | 1.00728 | Rutherford (1919) |
| Neutron | n⁰ | 0 | 1.00867 | Chadwick (1932) |

## 2.2 Thomson's Model (Plum Pudding, 1904)
- Atom = sphere of positive charge with electrons embedded
- **Failed:** Could not explain Rutherford's α-scattering experiment

## 2.3 Rutherford's Nuclear Model (1911)

### α-Particle Scattering Experiment:
- Most α-particles passed through (atom is mostly empty space)
- Few deflected at large angles (positive nucleus exists)
- Very few bounced back (nucleus is very small and dense)

### Rutherford's Conclusions:
- Atom has a tiny, dense, positively charged **nucleus**
- Electrons revolve around nucleus in circular orbits
- Most of atom's volume is empty space

### Atomic Number (Z) = Number of protons
### Mass Number (A) = Protons + Neutrons
```
Number of neutrons = A − Z
```

### Isotopes, Isobars, Isotones

| Term | Same | Different | Example |
|---|---|---|---|
| Isotopes | Z | A, n | ¹H, ²H, ³H |
| Isobars | A | Z | ¹⁴C, ¹⁴N |
| Isotones | n | Z, A | ¹⁴C (n=8), ¹⁵N (n=8) |
| Isoelectronic | e⁻ | Z | Na⁺, Mg²⁺, Al³⁺ |

### Rutherford Model Failure:
- Accelerating electron should radiate energy → spiral into nucleus
- Cannot explain atomic spectra (line spectrum)

## 2.4 Developments Leading to Bohr's Model

### Electromagnetic Radiation
```
c = νλ
```
- c = 3 × 10⁸ m/s (speed of light)
- ν = frequency (Hz = s⁻¹)
- λ = wavelength (m)

```
      c
ν = ─────
      λ

E = hν = hc/λ
```
- h = Planck's constant = 6.626 × 10⁻³⁴ J·s

### Wave Number (ν̃)
```
ν̃ = 1/λ (in cm⁻¹ or m⁻¹)
```

### Electromagnetic Spectrum (Increasing wavelength)
```
γ-rays < X-rays < UV < Visible < IR < Microwaves < Radio waves
```

**Visible Light (VIBGYOR):**
```
Violet (400 nm) → Indigo → Blue → Green → Yellow → Orange → Red (700 nm)
```

## 2.5 Planck's Quantum Theory (1900)

> *Energy is not continuous but emitted/absorbed in discrete packets called **quanta** (photons)*

```
E = nhν   (n = 1, 2, 3...)
```

### Photoelectric Effect (Einstein, 1905)
> *When light of sufficient frequency falls on a metal, electrons are ejected*

```
KE_max = hν − hν₀ = hν − W

W = hν₀ = work function (minimum energy to remove electron)
ν₀ = threshold frequency
```

**Key Points:**
- KE depends only on frequency, NOT intensity
- Number of electrons depends on intensity
- If ν < ν₀, no electron emission regardless of intensity

## 2.6 Atomic Spectra

### Line Spectrum of Hydrogen
- Only specific wavelengths → atom has discrete energy levels

### Spectral Series of Hydrogen

| Series | Region | n₁ | n₂ |
|---|---|---|---|
| Lyman | UV | 1 | 2, 3, 4... |
| Balmer | Visible | 2 | 3, 4, 5... |
| Paschen | Near-IR | 3 | 4, 5, 6... |
| Brackett | IR | 4 | 5, 6, 7... |
| Pfund | Far-IR | 5 | 6, 7, 8... |

### Rydberg Formula ⭐
```
      1         1     1
ν̃ = ─── = RH(─── − ───)
      λ        n₁²   n₂²
```
- RH = Rydberg constant = 1.097 × 10⁷ m⁻¹ = 109677 cm⁻¹
- n₂ > n₁

## 2.7 Bohr's Model of Hydrogen Atom (1913) ⭐⭐

### Postulates:
1. Electrons revolve in fixed circular orbits (stationary states) without radiating energy
2. Only those orbits are allowed where angular momentum = nh/2π
3. Energy is emitted/absorbed when electron jumps between orbits

### Quantization of Angular Momentum
```
      nh
mvr = ────
      2π
```

### Bohr's Equations for Hydrogen-like Atoms (Z = atomic number):

```
              n²a₀         n²(0.529 Å)
Radius: rₙ = ────── = ─────────────────
               Z               Z

             -13.6 eV × Z²
Energy: Eₙ = ─────────────────
                  n²

           2.18 × 10⁻¹⁸ × Z²
Eₙ = − ─────────────────────── J
                 n²
```

where a₀ = Bohr radius = 0.529 Å = 52.9 pm

```
Velocity: vₙ = (2.18 × 10⁶ × Z)/n  m/s

Frequency of revolution: νₙ = vₙ/2πrₙ
```

### Energy of Photon Emitted
```
          1     1
ΔE = RH(─── − ───)hc
         n₁²   n₂²

ΔE = 13.6 eV × Z² (1/n₁² − 1/n₂²)
```

### Limitations of Bohr's Model:
1. Cannot explain spectra of multi-electron atoms
2. Cannot explain splitting of spectral lines (Zeeman & Stark effect)
3. Cannot explain chemical bonding
4. Violates Heisenberg's Uncertainty Principle (fixed orbit = known position AND momentum)

## 2.8 de Broglie's Wave-Particle Duality

> *Every moving particle has an associated wave*

```
      h        h
λ = ───── = ──────
      mv       p

      h
λ = ───────────────
    √(2mKE)

       h
λ = ─────────────
    √(2meV)    (for accelerated electron through potential V)
```

## 2.9 Heisenberg's Uncertainty Principle ⭐

> *It is impossible to simultaneously determine the exact position and exact momentum of a microscopic particle*

```
Δx × Δp ≥ h/4π

Δx × mΔv ≥ h/4π

ΔE × Δt ≥ h/4π
```

**Important:** This is NOT due to experimental limitations — it's a fundamental property of nature.

## 2.10 Quantum Mechanical Model of Atom

### Schrödinger Wave Equation
```
∂²ψ   ∂²ψ   ∂²ψ   8π²m
─── + ─── + ─── + ─────(E − V)ψ = 0
∂x²   ∂y²   ∂z²    h²
```
- ψ = wave function (orbital)
- ψ² = probability of finding electron (electron density)

### Quantum Numbers ⭐⭐

**1. Principal Quantum Number (n)**
- n = 1, 2, 3, 4... (K, L, M, N shells)
- Determines energy and size of orbital
- Max electrons in shell = 2n²

**2. Azimuthal/Angular Momentum Quantum Number (l)**
- l = 0, 1, 2, ..., (n−1)
- Determines shape of orbital

| l | Subshell | Shape |
|---|---|---|
| 0 | s | Sphere |
| 1 | p | Dumbbell |
| 2 | d | Double dumbbell / cloverleaf |
| 3 | f | Complex |

- Orbital angular momentum = √(l(l+1)) × h/2π

**3. Magnetic Quantum Number (mₗ)**
- mₗ = −l, ..., 0, ..., +l → (2l+1) values
- Determines orientation of orbital in space

| Subshell | l | mₗ values | # Orbitals |
|---|---|---|---|
| s | 0 | 0 | 1 |
| p | 1 | −1, 0, +1 | 3 |
| d | 2 | −2,−1,0,+1,+2 | 5 |
| f | 3 | −3,...,+3 | 7 |

**4. Spin Quantum Number (mₛ)**
- mₛ = +1/2 (spin up ↑) or −1/2 (spin down ↓)
- Spin angular momentum = √(s(s+1)) × h/2π = √3/2 × h/2π

## 2.11 Shapes of Orbitals

### s-orbital: Spherical, non-directional
- 1s: 1 node (at nucleus only conceptually)
- 2s: 1 radial node, larger sphere
- ns has (n−1) radial nodes

### p-orbital: Dumbbell shape
- Three degenerate orbitals: px, py, pz
- 1 nodal plane (the plane perpendicular to the axis)
- 2p has 0 radial nodes, 1 angular node

### d-orbital: 5 degenerate orbitals
- dxy, dyz, dxz, dx²-y², dz²
- dz² has a donut (torus) around the middle

### Number of Nodes
```
Radial nodes = n − l − 1
Angular nodes = l
Total nodes = n − 1
```

## 2.12 Electronic Configuration

### Rules:

**Aufbau Principle:**
> Fill orbitals in order of increasing energy

**Energy order (use n+l rule):**
```
1s < 2s < 2p < 3s < 3p < 4s < 3d < 4p < 5s < 4d < 5p < 6s < 4f < 5d < 6p...
```

**Pauli Exclusion Principle:**
> No two electrons in an atom can have all four quantum numbers identical → max 2 electrons per orbital (with opposite spins)

**Hund's Rule of Maximum Multiplicity:**
> Electrons in degenerate orbitals occupy separate orbitals first with parallel spins, then pair up

### Exceptional Configurations ⭐
```
Cr: [Ar] 3d⁵ 4s¹  (not 3d⁴ 4s²) — half-filled d is extra stable
Cu: [Ar] 3d¹⁰ 4s¹ (not 3d⁹ 4s²) — fully-filled d is extra stable
```

**Reason:** Half-filled and fully-filled subshells have:
1. Symmetrical electron distribution → extra stability
2. Maximum exchange energy → lower energy

### Magnetic Properties
```
Number of unpaired electrons (n) →

Magnetic moment μ = √(n(n+2)) BM
```
(BM = Bohr Magneton)

- Paramagnetic: has unpaired electrons (attracted to magnetic field)
- Diamagnetic: all electrons paired (repelled by magnetic field)

---

---

# 3. CLASSIFICATION OF ELEMENTS & PERIODICITY IN PROPERTIES

## 3.1 Historical Development

| Contribution | Scientist | Year |
|---|---|---|
| Law of Triads | Döbereiner | 1817 |
| Newlands' Octaves | Newlands | 1864 |
| Periodic Law (by atomic mass) | Mendeleev | 1869 |
| Modern Periodic Law (by Z) | Moseley | 1913 |

### Mendeleev's Periodic Law
> *Properties of elements are periodic functions of their atomic masses*

**Merits:** Predicted existence of missing elements (Eka-boron=Sc, Eka-Al=Ga, Eka-Si=Ge)
**Defects:** Wrong atomic mass order (Ar/K, Co/Ni), no position for isotopes, H placement unclear

### Modern Periodic Law
> *Properties of elements are periodic functions of their atomic numbers (Z)*

## 3.2 Modern Periodic Table

### Structure:
- **Periods:** 7 horizontal rows (Period 1: 2 elements, Period 2&3: 8 each, Period 4&5: 18 each, Period 6&7: 32 each)
- **Groups:** 18 vertical columns (1–18)

### Blocks of Periodic Table

| Block | Elements | Filling orbital |
|---|---|---|
| s-block | Groups 1, 2 | ns¹ or ns² |
| p-block | Groups 13–18 | np¹ to np⁶ |
| d-block | Groups 3–12 | (n−1)d¹⁻¹⁰ ns¹⁻² |
| f-block | Lanthanides, Actinides | (n−2)f¹⁻¹⁴ |

## 3.3 Periodic Trends ⭐⭐

### Atomic Radius

**Covalent Radius** = half the distance between two bonded atoms of same element
**Van der Waals Radius** > Covalent Radius

**Trends:**
```
Across period (left → right): DECREASES
     (Z increases → more nuclear attraction → electrons pulled in)

Down group (top → bottom): INCREASES
     (new shells added → electron-electron repulsion increases)
```

**Exception:** Noble gases have largest Van der Waals radii in their period

### Ionic Radius

```
Cation (M⁺): smaller than neutral atom (lost electrons, same Z, less repulsion)
Anion (X⁻): larger than neutral atom (gained electrons, more repulsion)
```

**Isoelectronic species:** Same electrons, different Z
- As Z increases → smaller radius
- Example: N³⁻ > O²⁻ > F⁻ > Ne > Na⁺ > Mg²⁺ > Al³⁺

### Ionization Enthalpy (IE) ⭐

> *Energy required to remove the most loosely bound electron from isolated gaseous atom*

```
M(g) → M⁺(g) + e⁻    ΔH = IE₁

M⁺(g) → M²⁺(g) + e⁻  ΔH = IE₂

Always: IE₁ < IE₂ < IE₃...
```

**Trends:**
```
Across period: Generally INCREASES
     (Z increases, radius decreases → electrons held tighter)

Down group: DECREASES
     (radius increases → outermost electrons farther, more shielded)
```

**Exceptions (Lower IE than expected):**
- Be > B: 2s² is more stable than 2p¹ (B has lower IE than Be)
- N > O: N has half-filled 2p (extra stable), O pairs electrons (easier to remove paired e⁻)
- Mg > Al: similar reason (3s² > 3p¹)
- P > S: half-filled 3p in P

**Factors affecting IE:**
1. Nuclear charge (Z) — increases IE
2. Atomic radius — increases IE (as r decreases)
3. Shielding effect — decreases IE
4. Penetration effect — increases IE
5. Orbital type — s > p > d > f (s-orbital has more penetration)

### Electron Gain Enthalpy (Electron Affinity)

> *Enthalpy change when an electron is added to neutral gaseous atom*

```
X(g) + e⁻ → X⁻(g)    ΔegH

More negative ΔegH → greater tendency to accept electron
```

**Trends:** Similar to IE (increases across period, decreases down group)

**Exceptions:**
- Cl has higher EA than F (F is too small → high electron-electron repulsion in small 2p orbitals)
- N has lower EA than C and O (half-filled 2p = extra stable → less tendency to accept e⁻)
- Be, Mg have very low EA (stable ns² configuration)
- Noble gases have positive EA (no tendency)

**Successive Electron Affinities:**
- EA₁ is usually exothermic (−ΔH)
- EA₂ is always endothermic (energy needed to force e⁻ into negative ion)

### Electronegativity ⭐

> *Tendency of an atom in a molecule to attract shared electrons towards itself*

**Scales:**
- Pauling scale (most common): F = 4.0 (highest)
- Mulliken scale: EN = (IE + EA)/2
- Allred-Rochow scale: based on electrostatic force

**Trends:**
```
Across period: INCREASES (F is most electronegative)
Down group: DECREASES
```

**Order:** F > O > N ≈ Cl > Br > C ≈ S > I > H > metals

**Uses:**
1. Predict polarity of bonds
2. Estimate ionic character:
   - ΔEN > 1.7 → mostly ionic
   - ΔEN < 0.4 → mostly covalent
3. Determine oxidation states

### Valence / Valency

- s & p block: Valence = Group number (or 8 − Group for high groups)
- Transition metals: Multiple valences

## 3.4 Periodic Trends in Chemical Properties

### Metallic and Non-metallic Character
```
Metallic character: DECREASES across period, INCREASES down group
Non-metallic character: INCREASES across period, DECREASES down group
```

### Oxides
```
Left side: Basic oxides (Na₂O, MgO, CaO)
Middle: Amphoteric oxides (Al₂O₃, ZnO, Cr₂O₃)
Right side: Acidic oxides (SO₃, P₄O₁₀, Cl₂O₇)
```

### Hydrides
```
Left side: Ionic hydrides (NaH, CaH₂) — reducing agents
Right side: Covalent hydrides (HF, HCl, NH₃, H₂O)
Acid strength of hydrides: HF < HCl < HBr < HI (down group)
Base strength: NH₃ > PH₃ > AsH₃ > SbH₃ (down group)
```

---

---

# 4. CHEMICAL BONDING & MOLECULAR STRUCTURE

## 4.1 Kossel-Lewis Theory

### Octet Rule
> *Atoms tend to gain, lose, or share electrons to achieve 8 electrons in their outermost shell (like noble gases)*

**Exceptions to Octet Rule:**
1. **Incomplete octet:** BF₃ (6e⁻ around B), BeCl₂ (4e⁻ around Be), AlCl₃
2. **Expanded octet:** PCl₅ (10e⁻ around P), SF₆ (12e⁻ around S) — possible only for 3rd period and beyond (d-orbitals)
3. **Odd-electron molecules:** NO, NO₂, ClO₂

### Lewis Structures — Rules for Drawing:
1. Count total valence electrons
2. Connect atoms with single bonds
3. Complete octets of terminal atoms first
4. Remaining electrons → lone pairs on central atom
5. If central atom lacks octet → form multiple bonds

### Formal Charge
```
Formal Charge = Valence electrons − Non-bonding electrons − (1/2 × Bonding electrons)

FC = V − L − B/2
```
**Best Lewis structure has lowest formal charges (preferably zero)**

### Resonance
> *When a molecule can be represented by two or more equivalent Lewis structures, it is called resonance; actual structure is a hybrid (average)*

**Examples:**
- O₃: Two equivalent structures, bond order = 1.5
- CO₃²⁻: Three equivalent structures, bond order = 4/3
- Benzene: C₆H₆, bond order = 1.5

**Resonance Stabilization:** Resonance hybrid is more stable than any single structure

## 4.2 Ionic Bonding

> *Complete transfer of electrons from metal to non-metal → electrostatic attraction between ions*

### Conditions Favoring Ionic Bond Formation:
- Low IE of cation-forming element
- High EA of anion-forming element
- High lattice energy

### Lattice Energy (U)
> *Energy released when 1 mole of ionic compound is formed from its gaseous ions*

**Born-Haber Cycle (for NaCl):**
```
Na(s) + ½Cl₂(g) → NaCl(s)    ΔHf°

ΔHf° = ΔHsub(Na) + ½ΔHdiss(Cl₂) + IE(Na) + EA(Cl) + U(NaCl)
```

**Lattice Energy (Born-Landé Equation):**
```
U = -NAMz⁺z⁻e²/4πε₀r₀ × (1 - 1/n)
```
- M = Madelung constant (depends on structure)
- z⁺, z⁻ = charges on ions
- r₀ = interionic distance
- n = Born exponent

**Factors:**
- U increases as charge increases (CaCl₂ > NaCl)
- U increases as ionic radius decreases (LiF > NaF > KF)

### Properties of Ionic Compounds:
- High melting/boiling points
- Conduct electricity in molten state or in solution (not solid state)
- Soluble in polar solvents
- Hard but brittle

## 4.3 Covalent Bonding

> *Sharing of electron pairs between atoms*

### Types of Covalent Bonds:
- Single bond: 1 shared pair (σ bond only)
- Double bond: 1 σ + 1 π bond
- Triple bond: 1 σ + 2 π bonds

### Bond Parameters ⭐

**Bond Length:** Distance between nuclei of bonded atoms
```
Single > Double > Triple (bond length decreases)
Single < Double < Triple (bond strength increases)
```

**Bond Enthalpy (Bond Energy):**
> Energy needed to break 1 mole of bonds in gaseous state

```
ΔHrxn = Σ(bonds broken) − Σ(bonds formed)
      = Σ BE(reactants) − Σ BE(products)
```

**Bond Order:**
```
         Bonding e⁻ − Antibonding e⁻
BO = ─────────────────────────────────
                    2

Higher BO → shorter bond length, higher bond energy
```

## 4.4 VSEPR Theory ⭐⭐ (Valence Shell Electron Pair Repulsion)

**Principle:** Electron pairs around central atom arrange to minimize repulsion

**Repulsion order:**
```
Lone pair–Lone pair > Lone pair–Bond pair > Bond pair–Bond pair
```

### VSEPR Table

| Formula | BP | LP | Shape | Example | Bond Angle |
|---|---|---|---|---|---|
| AX₂ | 2 | 0 | Linear | BeCl₂, CO₂ | 180° |
| AX₃ | 3 | 0 | Trigonal planar | BF₃, SO₃ | 120° |
| AX₂E | 2 | 1 | Bent/Angular | SO₂, SnCl₂ | <120° |
| AX₄ | 4 | 0 | Tetrahedral | CH₄, SiCl₄ | 109.5° |
| AX₃E | 3 | 1 | Trigonal pyramidal | NH₃, PCl₃ | <109.5° |
| AX₂E₂ | 2 | 2 | Bent/V-shape | H₂O, H₂S | <109.5° |
| AX₅ | 5 | 0 | Trigonal bipyramidal | PCl₅ | 90°, 120° |
| AX₄E | 4 | 1 | See-saw | SF₄ | |
| AX₃E₂ | 3 | 2 | T-shaped | ClF₃ | |
| AX₂E₃ | 2 | 3 | Linear | XeF₂, I₃⁻ | 180° |
| AX₆ | 6 | 0 | Octahedral | SF₆ | 90° |
| AX₅E | 5 | 1 | Square pyramidal | BrF₅ | |
| AX₄E₂ | 4 | 2 | Square planar | XeF₄, [PtCl₄]²⁻ | 90° |

**Bond angle order:** CH₄ (109.5°) > NH₃ (107°) > H₂O (104.5°)
(Lone pairs compress bond angles)

## 4.5 Valence Bond Theory (VBT)

> *Covalent bond forms by overlap of atomic orbitals; maximum overlap = strongest bond*

### Types of Orbital Overlap:

**σ (sigma) bond:** Head-on (axial) overlap
- s-s, s-p, p-p head-on overlap
- Cylindrically symmetric about internuclear axis
- Free rotation possible

**π (pi) bond:** Lateral (sideways) overlap
- p-p sideways overlap
- Has a nodal plane containing bond axis
- No free rotation (restricted)

### Hybridization ⭐⭐

> *Mixing of atomic orbitals of similar energy to form new hybrid orbitals of equivalent energy*

| Hybridization | Orbitals Mixed | Shape | Bond Angle | Examples |
|---|---|---|---|---|
| sp | s + p | Linear | 180° | BeCl₂, C₂H₂, CO₂ |
| sp² | s + 2p | Trigonal Planar | 120° | BF₃, C₂H₄, benzene |
| sp³ | s + 3p | Tetrahedral | 109.5° | CH₄, NH₃, H₂O, CCl₄ |
| sp³d | s+3p+d | Trigonal Bipyramidal | 90°,120° | PCl₅, SF₄ |
| sp³d² | s+3p+2d | Octahedral | 90° | SF₆, [CrF₆]³⁻ |
| dsp² | d+s+2p | Square Planar | 90° | [Ni(CN)₄]²⁻, [PtCl₄]²⁻ |

**Quick method for finding hybridization:**
```
Hybridization number = (Bond pairs + Lone pairs on central atom)
= 2 → sp
= 3 → sp²
= 4 → sp³
= 5 → sp³d
= 6 → sp³d²
```

## 4.6 Molecular Orbital Theory (MOT) ⭐

### Linear Combination of Atomic Orbitals (LCAO):
```
Bonding MO (σ) : ψ_b = ψ_A + ψ_B  (lower energy)
Antibonding MO (σ*): ψ_a = ψ_A − ψ_B  (higher energy)
```

### MO Energy Level Diagram for O₂, F₂, Ne₂:
```
σ1s < σ*1s < σ2s < σ*2s < σ2p < π2p = π2p < π*2p = π*2p < σ*2p
```

### MO Energy Level for B₂, C₂, N₂ (π before σ in 2p):
```
σ1s < σ*1s < σ2s < σ*2s < π2p = π2p < σ2p < π*2p = π*2p < σ*2p
```

### Bond Order (MO):
```
         Nb − Na
BO = ─────────────
           2
```
Nb = bonding electrons, Na = antibonding electrons

### MO Properties Table:

| Molecule | Config | BO | Magnetic |
|---|---|---|---|
| H₂ | (σ1s)² | 1 | Diamagnetic |
| He₂ | (σ1s)²(σ*1s)² | 0 | Doesn't exist |
| Li₂ | ....(σ2s)² | 1 | Diamagnetic |
| B₂ | ....(π2p)¹(π2p)¹ | 1 | Paramagnetic |
| C₂ | ....(π2p)²(π2p)² | 2 | Diamagnetic |
| N₂ | ...(σ2p)²(π2p)⁴ | 3 | Diamagnetic |
| O₂ | ...(σ2p)²(π2p)⁴(π*2p)¹(π*2p)¹ | 2 | Paramagnetic |
| F₂ | ...(π*2p)⁴ | 1 | Diamagnetic |
| Ne₂ | ...(σ*2p)² | 0 | Doesn't exist |

## 4.7 Hydrogen Bonding ⭐

> *Electrostatic attraction between H bonded to highly electronegative atom (F, O, N) and lone pair on another electronegative atom*

**Condition:** H must be bonded to F, O, or N (very high EN + small size)

### Types:

**Intermolecular H-bond:** Between different molecules (HF, H₂O, NH₃, alcohols, carboxylic acids)

**Intramolecular H-bond:** Within same molecule (o-nitrophenol, salicylaldehyde)

### Effects of H-bonding:
- Higher boiling/melting points (H₂O > H₂S, HF > HCl)
- Higher viscosity and surface tension
- Lower vapor pressure
- Anomalous expansion of water below 4°C

### Hydrogen Bond Strength: F–H···F > O–H···O > N–H···N

## 4.8 Polarity of Molecules

**Dipole Moment (μ):**
```
μ = q × d

SI unit: Coulomb-metre (C·m)
Common unit: Debye (D)  [1 D = 3.336 × 10⁻³⁰ C·m]
```

**For polyatomic molecules:** Vector sum of all bond dipoles

**Examples:**
- CO₂ (linear) → μ = 0 (symmetric, dipoles cancel)
- H₂O (bent) → μ ≠ 0
- BF₃ (trigonal planar) → μ = 0
- NH₃ (pyramidal) → μ ≠ 0
- CCl₄ (tetrahedral) → μ = 0
- CHCl₃ → μ ≠ 0

---

---

# 5. STATES OF MATTER: GASES & LIQUIDS

## 5.1 The Gas Laws ⭐⭐

### Boyle's Law (1662) — Isothermal
> *At constant T and n, V ∝ 1/P*

```
PV = constant

P₁V₁ = P₂V₂  (at constant T, n)
```

### Charles' Law (1787) — Isobaric
> *At constant P and n, V ∝ T*

```
V/T = constant

V₁/T₁ = V₂/T₂  (at constant P, n)
```

### Gay-Lussac's Law — Isochoric
> *At constant V and n, P ∝ T*

```
P/T = constant

P₁/T₁ = P₂/T₂  (at constant V, n)
```

### Avogadro's Law
> *At constant T and P, V ∝ n*

```
V/n = constant
```

## 5.2 Ideal Gas Equation ⭐

```
PV = nRT

P = pressure (Pa or atm)
V = volume (m³ or L)
n = moles
R = universal gas constant
T = temperature (K) — ALWAYS Kelvin!
```

### Values of R:
```
R = 8.314 J/(mol·K) = 8.314 Pa·m³/(mol·K)
R = 0.0821 L·atm/(mol·K)
R = 1.987 cal/(mol·K)
R = 62.36 L·mmHg/(mol·K)
```

### Combined Gas Law:
```
P₁V₁/T₁ = P₂V₂/T₂  (n constant)

PV/nT = R
```

### Molar Mass from Ideal Gas Law:
```
        mRT         dRT
M = ─────── = ──────
        PV          P

(d = density = m/V)
```

## 5.3 Dalton's Law of Partial Pressures

> *Total pressure of mixture of non-reacting gases = sum of partial pressures*

```
P_total = P₁ + P₂ + P₃ + ...

Partial pressure: Pᵢ = χᵢ × P_total

         nᵢ
χᵢ = ─────────
      n_total
```

**Pressure of dry gas collected over water:**
```
P_dry gas = P_total − P_water vapour (aqueous tension)
```

## 5.4 Kinetic Theory of Gases ⭐⭐

### Postulates:
1. Gas molecules are point masses (negligible volume)
2. No intermolecular forces
3. Molecules in continuous, random motion
4. Elastic collisions
5. Average KE ∝ absolute temperature

### Kinetic Gas Equation:
```
PV = (1/3)mNu²rms

P = (1/3)ρu²rms
```
(m = mass of one molecule, N = number of molecules, u_rms = root mean square speed)

### Molecular Speeds ⭐

```
                    3RT          3PV
u_rms = √─────── = √─────
                     M            m

                  8RT
u_avg = √─────── = 0.9213 u_rms
                  πM

u_mp (most probable) = √(2RT/M) = 0.8165 u_rms
```

**Relationship:**
```
u_mp : u_avg : u_rms = 1 : 1.128 : 1.225 = √2 : √(8/π) : √3
```

### Kinetic Energy

```
Average KE per molecule = (3/2)kT    (k = Boltzmann constant = 1.38 × 10⁻²³ J/K)

Average KE per mole = (3/2)RT

Total KE = (3/2)nRT
```

### Degrees of Freedom and Energy

```
Monatomic gas: f = 3 (translational)  → KE = (3/2)RT per mole
Diatomic gas: f = 5 (3 trans + 2 rot) → KE = (5/2)RT per mole
Polyatomic: f = 6 (3 trans + 3 rot)   → KE = 3RT per mole
```

### Equipartition of Energy
> *Average KE associated with each degree of freedom = (1/2)kT per molecule or (1/2)RT per mole*

## 5.5 Real Gases and Deviation from Ideal Behavior

### Compressibility Factor (Z):
```
        PV
Z = ────────
       nRT

Z = 1 → Ideal gas
Z < 1 → Attractive forces dominate (at moderate P)
Z > 1 → Repulsive forces dominate (at very high P)
```

### Van der Waals Equation ⭐

```
[P + a(n/V)²][V − nb] = nRT

For 1 mole:
(P + a/V²)(V − b) = RT
```
- **'a'** = intermolecular attraction constant (pressure correction)
- **'b'** = excluded volume / co-volume (volume correction), b = 4 × actual volume of molecules

### Boyle Temperature (T_B):
> *Temperature at which real gas behaves like ideal gas over a wide pressure range*

```
T_B = a/(Rb)
```

### Van der Waals Constants for Common Gases:

| Gas | a (L²·atm/mol²) | b (L/mol) |
|---|---|---|
| H₂ | 0.244 | 0.0266 |
| N₂ | 1.39 | 0.0391 |
| O₂ | 1.36 | 0.0318 |
| CO₂ | 3.59 | 0.0427 |
| NH₃ | 4.17 | 0.0371 |

### Critical Constants:
```
Tc = 8a/27Rb
Pc = a/27b²
Vc = 3b

Zc = PcVc/RTc = 3/8 = 0.375 (for Van der Waals gas)
```

## 5.6 Mean Free Path (λ)

```
           1
λ = ────────────────
    √2 π d² N/V

where d = diameter of molecule, N/V = number density
```

## 5.7 Liquefaction of Gases

### Joule-Thomson Effect:
> *Real gases cool down on expansion through a porous plug (throttling) if T < inversion temperature*

### Inversion Temperature:
```
Tᵢ = 2a/Rb = 2T_B
```
- H₂ and He have very low Tᵢ → must be pre-cooled before throttling
- CO₂, N₂, O₂: Tᵢ > room temperature → cool on expansion

## 5.8 Liquid State

### Vapour Pressure:
- Liquid in equilibrium with its vapour → vapour pressure
- Increases with temperature
- Independent of amount of liquid

### Boiling Point:
> *Temperature at which vapour pressure = external pressure*

**Clausius-Clapeyron Equation:**
```
     ln(P₂/P₁) = ΔHvap/R × (1/T₁ − 1/T₂)
```

### Surface Tension (γ):
> *Force per unit length acting along the surface, tending to minimize surface area*

Units: N/m or J/m²
- Decreases with increasing temperature
- Causes capillary rise: h = 2γcosθ/rρg

### Viscosity (η):
> *Resistance to flow; measure of internal friction between layers of fluid*

Units: Poise (P) = g/(cm·s) = 0.1 Pa·s

**Stokes' Law:** F = 6πηrv

- Decreases with increasing temperature (liquids)
- Increases with temperature (gases)

---

---

# 6. THERMODYNAMICS

## 6.1 Basic Terminology

- **System:** Part under study
- **Surroundings:** Rest of universe
- **Open system:** Exchange of mass and energy
- **Closed system:** Only energy exchange
- **Isolated system:** No exchange

### Types of Processes:
- **Isothermal:** T = constant
- **Adiabatic:** q = 0 (no heat exchange)
- **Isobaric:** P = constant
- **Isochoric:** V = constant (ΔV = 0)
- **Reversible:** Infinitely slow, at each step system in equilibrium
- **Irreversible:** Real, spontaneous, faster

## 6.2 Zeroth Law of Thermodynamics
> *If A is in thermal equilibrium with B, and B with C, then A is in equilibrium with C*
> → Defines temperature

## 6.3 First Law of Thermodynamics ⭐

> *Energy cannot be created or destroyed; total energy of universe is constant*

```
ΔU = q + w      [IUPAC convention]
ΔU = q − w      [older convention — JEE often uses this]
```
- ΔU = change in internal energy
- q = heat absorbed by system (+ve if absorbed, −ve if released)
- w = work done ON system (+ve if compressed)

### Work

**For expansion/compression:**
```
w = −P_ext × ΔV  (work done BY system against constant external pressure)

For reversible process:
w_rev = −nRT ln(V₂/V₁) = −nRT ln(P₁/P₂)

For irreversible process:
w_irrev = −P_ext(V₂ − V₁)
```

### For Ideal Gas:

**Isothermal:**
```
ΔU = 0 (internal energy depends only on T)
q = −w = nRT ln(V₂/V₁)
```

**Adiabatic:**
```
q = 0
ΔU = w = nCᵥΔT
```

**Isochoric:**
```
w = 0 (no volume change)
ΔU = qᵥ = nCᵥΔT
```

**Isobaric:**
```
w = −PΔV = −nRΔT
ΔH = qₚ = nCₚΔT
```

## 6.4 Enthalpy (H) ⭐

```
H = U + PV

ΔH = ΔU + Δ(PV) = ΔU + PΔV (at constant P)
ΔH = ΔU + ΔnᵍRT   (Δnᵍ = moles of gaseous products − moles of gaseous reactants)

ΔH = qₚ (heat at constant pressure)
ΔU = qᵥ (heat at constant volume)
```

### Relationship:
```
ΔH = ΔU + ΔnᵍRT
```

### Heat Capacity ⭐

```
         q
C = ────────
       ΔT

Cᵥ = (∂U/∂T)ᵥ    (at constant volume)
Cₚ = (∂H/∂T)ₚ    (at constant pressure)

For ideal gas: Cₚ − Cᵥ = R

         Cₚ
γ = ──────── (adiabatic index / heat capacity ratio)
         Cᵥ

Monatomic: Cᵥ = 3R/2, Cₚ = 5R/2, γ = 5/3
Diatomic: Cᵥ = 5R/2, Cₚ = 7R/2, γ = 7/5
Polyatomic: Cᵥ = 3R, Cₚ = 4R, γ = 4/3
```

### Adiabatic Process Equations:
```
TV^(γ−1) = constant
TP^(1−γ)/γ = constant (or T/P^((γ−1)/γ) = constant)
PV^γ = constant

Work in reversible adiabatic:
w = nCᵥ(T₂ − T₁) = (P₁V₁ − P₂V₂)/(γ − 1)
```

## 6.5 Standard Enthalpy Changes ⭐⭐

### Standard Conditions: 298 K, 1 bar (100 kPa), 1 M solutions

**Standard Enthalpy of Formation (ΔHf°):**
> Enthalpy change when 1 mole of compound forms from elements in standard state

- ΔHf° of any element in standard state = 0

**Hess's Law:**
> *Enthalpy change of a reaction is independent of the path taken*

```
ΔHrxn = ΣΔHf°(products) − ΣΔHf°(reactants)
```

### Types of Enthalpy Changes:

| Type | Definition |
|---|---|
| ΔH_combustion | Burning 1 mole completely in O₂ |
| ΔH_neutralization | Neutralization of 1 mole of H⁺ with OH⁻ → −57.1 kJ/mol (strong acid + strong base) |
| ΔH_hydration | Hydration of 1 mole of gaseous ions |
| ΔH_solution | Dissolving 1 mole of solute in large excess solvent |
| ΔH_atomization | 1 mole of atoms from element in standard state |
| ΔH_ionization | Removing electron from 1 mole gaseous atoms |
| ΔH_sublimation | Converting 1 mole solid to gas |
| ΔH_fusion | Melting 1 mole of solid |
| ΔH_vaporization | Vaporizing 1 mole of liquid |

**Bond Enthalpy Method:**
```
ΔHrxn = Σ(bond enthalpies of bonds broken) − Σ(bond enthalpies of bonds formed)
```

### Kirchhoff's Equation:
```
ΔH(T₂) = ΔH(T₁) + ΔCₚ(T₂ − T₁)

where ΔCₚ = Σ(Cₚ of products) − Σ(Cₚ of reactants)
```

## 6.6 Entropy (S) ⭐⭐

> *Measure of randomness/disorder in a system*

```
ΔS = qrev/T  (for reversible process)

ΔS > qirrev/T  (for irreversible process)
```

### Third Law of Thermodynamics:
> *Entropy of a perfectly crystalline solid at 0 K is zero (S = 0 at 0 K)*

### Standard Entropy Change:
```
ΔS°rxn = ΣS°(products) − ΣS°(reactants)
```

**Entropy changes:**
- Solid < Liquid < Gas
- ΔS > 0: Gas produced, mixing, dissolution of most solids
- ΔS < 0: Gas consumed, ordering

## 6.7 Second Law of Thermodynamics

> *For a spontaneous process, entropy of universe increases*

```
ΔS_universe = ΔS_system + ΔS_surroundings > 0  (spontaneous)
ΔS_universe = 0  (reversible/equilibrium)
ΔS_universe < 0  (non-spontaneous)
```

## 6.8 Gibbs Free Energy (G) ⭐⭐⭐

```
G = H − TS

ΔG = ΔH − TΔS   (at constant T and P)

ΔG°rxn = ΣΔGf°(products) − ΣΔGf°(reactants)
```

### Spontaneity Criteria:

| ΔH | ΔS | ΔG = ΔH − TΔS | Spontaneity |
|---|---|---|---|
| − | + | Always − | Always spontaneous |
| + | − | Always + | Never spontaneous |
| − | − | − at low T | Spontaneous at low T |
| + | + | − at high T | Spontaneous at high T |

### Relationship with Equilibrium:
```
ΔG = ΔG° + RT ln Q

At equilibrium (Q = K): ΔG = 0
ΔG° = −RT ln Kp = −RT ln Kc (approximately)

ΔG° = −nFE°cell (for electrochemical cells)
```

**Work from Gibbs Energy:**
```
Maximum non-PV work = −ΔG
```

---

---

# 7. EQUILIBRIUM

## 7.1 Dynamic Equilibrium

> *Forward and reverse reaction rates are equal; concentrations remain constant*

**Physical equilibrium:** Phase changes, dissolution
**Chemical equilibrium:** Reversible chemical reactions

## 7.2 Law of Mass Action & Equilibrium Constant ⭐⭐

For: **aA + bB ⇌ cC + dD**

```
         [C]^c [D]^d
Kc = ─────────────────
         [A]^a [B]^b

         (Pc)^c (Pd)^d
Kp = ──────────────────
         (Pa)^a (Pb)^b
```

### Relationship between Kp and Kc:
```
Kp = Kc (RT)^Δnᵍ

Δnᵍ = (c + d) − (a + b) = moles of gaseous products − moles of gaseous reactants
```

### Properties of K:
- Dimensionless (activities, not concentrations)
- Depends only on temperature
- Large K → products favored; Small K → reactants favored
- K > 10³ → forward reaction nearly complete
- K < 10⁻³ → reverse reaction predominates

### Manipulating K:
```
If reaction is reversed: K' = 1/K
If equation is multiplied by n: K' = K^n
If equations are added: K' = K₁ × K₂
```

## 7.3 Reaction Quotient (Q) and Predicting Direction

```
Q < K → Reaction proceeds forward (products form)
Q > K → Reaction proceeds backward (reactants form)
Q = K → System at equilibrium
```

## 7.4 Le Chatelier's Principle ⭐

> *If a system at equilibrium is disturbed, it will shift to counteract the disturbance*

| Disturbance | System Response |
|---|---|
| Add reactant | Shift right (forward) |
| Remove reactant | Shift left (backward) |
| Add product | Shift left |
| Remove product | Shift right |
| Increase pressure (compress) | Shift toward fewer moles of gas |
| Decrease pressure (expand) | Shift toward more moles of gas |
| Increase temperature | Shift toward endothermic side |
| Decrease temperature | Shift toward exothermic side |
| Add inert gas (constant V) | No effect |
| Add catalyst | No effect on K or equilibrium position; only speeds up reaching equilibrium |

## 7.5 Haber Process (Industrial Application)
```
N₂(g) + 3H₂(g) ⇌ 2NH₃(g)    ΔH = −92 kJ/mol

Conditions: 400–500°C, 200 atm, Fe catalyst
```
**Le Chatelier analysis:**
- High pressure favors NH₃ (fewer gas moles on product side)
- Low temperature favors NH₃ (exothermic), but rate is slow → compromise at 400–500°C
- Catalyst speeds equilibrium without affecting K

## 7.6 Ionic Equilibrium ⭐⭐

### Arrhenius Definition:
- Acid: produces H⁺ in water
- Base: produces OH⁻ in water

### Brønsted-Lowry Definition:
- Acid: proton (H⁺) donor
- Base: proton acceptor
- Conjugate acid-base pairs differ by H⁺

### Lewis Definition:
- Acid: electron pair acceptor
- Base: electron pair donor

### Ionization of Water (Kw):
```
H₂O ⇌ H⁺ + OH⁻

Kw = [H⁺][OH⁻] = 1 × 10⁻¹⁴ at 25°C (increases with temperature)

At 25°C: pKw = 14
Neutral: [H⁺] = [OH⁻] = 10⁻⁷ M
```

### pH Scale:
```
pH = −log[H⁺]
pOH = −log[OH⁻]
pH + pOH = pKw = 14 (at 25°C)

Acidic: pH < 7
Neutral: pH = 7
Basic: pH > 7
```

### Weak Acid Ionization:
```
HA ⇌ H⁺ + A⁻

         [H⁺][A⁻]
Ka = ─────────────
           [HA]

[H⁺] = √(Ka × C)     (when α << 1)

Degree of ionization: α = √(Ka/C)

pH = ½(pKa − log C)
```

### Weak Base Ionization:
```
B + H₂O ⇌ BH⁺ + OH⁻

         [BH⁺][OH⁻]
Kb = ─────────────────
            [B]

[OH⁻] = √(Kb × C)

pH = 14 − ½(pKb − log C) = 14 − pOH
```

### Ka × Kb = Kw (for conjugate acid-base pair)
```
pKa + pKb = pKw = 14
```

### Buffer Solutions ⭐

> *Resist changes in pH on addition of acid or base*

**Henderson-Hasselbalch Equation:**
```
pH = pKa + log([A⁻]/[HA])     (acidic buffer)
pOH = pKb + log([BH⁺]/[B])    (basic buffer)
```

**Buffer capacity:** Maximum when [A⁻] = [HA] → pH = pKa (buffer range: pKa ± 1)

### Hydrolysis of Salts:

| Salt | Reaction | pH |
|---|---|---|
| Strong acid + Strong base (NaCl) | No hydrolysis | = 7 |
| Weak acid + Strong base (CH₃COONa) | A⁻ + H₂O ⇌ HA + OH⁻ | > 7 |
| Strong acid + Weak base (NH₄Cl) | BH⁺ + H₂O ⇌ B + H₃O⁺ | < 7 |
| Weak acid + Weak base (CH₃COONH₄) | Both hydrolyze | ≈7 (depends on Ka, Kb) |

**pH of salt of weak acid + strong base:**
```
pH = 7 + ½(pKa + log C)
```
**pH of salt of strong acid + weak base:**
```
pH = 7 − ½(pKb + log C)
```

### Solubility Product (Ksp) ⭐

```
For MₓXy ⇌ xMⁿ⁺(aq) + yXᵐ⁻(aq)

Ksp = [Mⁿ⁺]ˣ[Xᵐ⁻]ʸ
```

**Relationship between Ksp and molar solubility (s):**
- AB type: Ksp = s² → s = √Ksp
- AB₂ type: Ksp = 4s³ → s = ∛(Ksp/4)
- A₂B₃ type: Ksp = 108s⁵ → s = (Ksp/108)^(1/5)

**Common Ion Effect:**
> *Solubility decreases when a common ion is added (Ksp shifts left)*

**Precipitation:**
```
If ionic product (IP) > Ksp → precipitation occurs
If IP < Ksp → no precipitation (solution unsaturated)
If IP = Ksp → solution just saturated
```

---

---

# 8. REDOX REACTIONS

## 8.1 Oxidation States ⭐

### Rules (in order of priority):
1. Free element: OS = 0 (Na, Cl₂, S₈)
2. Monoatomic ion: OS = charge (Na⁺ = +1, Cl⁻ = −1)
3. Sum of OS in compound = 0; in polyatomic ion = ionic charge
4. Fluorine always −1
5. H: +1 (usually), −1 in metal hydrides (NaH)
6. O: −2 (usually), −1 in peroxides (H₂O₂, Na₂O₂), −½ in superoxides, +2 in OF₂
7. Alkali metals: always +1; Alkaline earth: always +2

### Balancing Redox Reactions:

**Ion-Electron Method:**
1. Split into half-reactions (oxidation and reduction)
2. Balance atoms (except H and O)
3. Balance O by adding H₂O
4. Balance H by adding H⁺ (acidic) or OH⁻ (basic)
5. Balance charge by adding electrons
6. Multiply half-reactions so electrons cancel
7. Add half-reactions

**Oxidation Number Method:**
1. Assign OS to all atoms
2. Identify atoms changing OS
3. Calculate change in OS
4. Multiply by appropriate factor to equalize electron loss/gain
5. Balance remaining atoms

## 8.2 Disproportionation

> *When an element in one oxidation state simultaneously gets oxidized and reduced*

Examples:
```
Cl₂ + 2NaOH → NaCl + NaOCl + H₂O
P₄ + 3NaOH + 3H₂O → 3NaH₂PO₂ + PH₃
```

---

---

# 9. HYDROGEN

## 9.1 Properties of Hydrogen

- Most abundant element in universe
- Lightest element, Z = 1
- Isotopes: Protium (¹H), Deuterium (²H or D), Tritium (³H or T, radioactive)

## 9.2 Preparation of Hydrogen

```
Industrial (Steam Reforming):
CH₄ + H₂O → CO + 3H₂    (900°C, Ni catalyst — Water gas shift reaction)
CO + H₂O → CO₂ + H₂     (400°C, Fe₂O₃ catalyst)

Electrolysis of water:
2H₂O → 2H₂ + O₂

Lab (Zn + dil. H₂SO₄):
Zn + H₂SO₄ → ZnSO₄ + H₂↑
```

## 9.3 Hydrides

| Type | Examples | Properties |
|---|---|---|
| Ionic/Saline | NaH, CaH₂, LiH | Metal hydrides, strong reducing agents |
| Covalent | CH₄, NH₃, HCl, H₂O | Molecular |
| Metallic/Interstitial | PdH₀.₈₉, TiH₁.₇₃ | Non-stoichiometric, metallic appearance |

## 9.4 Water (H₂O) ⭐

**Structure:** Bent, sp³ hybridized O, bond angle 104.5°, μ = 1.85 D

**Anomalous Properties (due to H-bonding):**
- High BP (100°C) vs H₂S (−60°C)
- Maximum density at 4°C
- High specific heat capacity (4.18 J/g·K)
- Ice less dense than liquid water (floats)

### Hard Water:
- **Temporary hardness:** Ca(HCO₃)₂, Mg(HCO₃)₂ → removed by boiling
- **Permanent hardness:** CaSO₄, MgSO₄, CaCl₂ → removed by Na₂CO₃ (Soda ash), or ion exchange

## 9.5 Hydrogen Peroxide (H₂O₂) ⭐

**Structure:** Non-planar, dihedral angle 111.5°, O-O bond, H-O-O angle 96.87°

**Preparation:**
```
BaO₂ + H₂SO₄ → BaSO₄ + H₂O₂   (Merck's method)
2F₂ + 2NaOH → 2NaF + H₂O₂     (at low temperature)
Electrolysis of H₂SO₄: then hydrolysis of peroxodisulfate
```

**Properties:**
- Oxidizing agent: H₂O₂ + 2H⁺ + 2e⁻ → 2H₂O (usually)
- Reducing agent: H₂O₂ → O₂ + 2H⁺ + 2e⁻ (with strong oxidizers like KMnO₄)
- Bleaching agent (oxidative bleaching)
- 100 volume H₂O₂: 1 mL gives 100 mL O₂ at STP (≈ 30% w/v)

---

---

# 10. s-BLOCK ELEMENTS

## 10.1 Group 1 (Alkali Metals): Li, Na, K, Rb, Cs, Fr

### Electronic Configuration: [Noble gas] ns¹

### Physical Properties:
- Silvery-white, soft metals
- Low density (Li, Na, K float on water)
- Low melting/boiling points (decrease down group)
- Large atomic radii, largest in their period

### Chemical Properties:

**Reaction with O₂:**
```
4Li + O₂ → 2Li₂O    (oxide)
2Na + O₂ → Na₂O₂    (peroxide, excess O₂) → 4Na + O₂ → 2Na₂O (limited O₂)
K, Rb, Cs + O₂ → Superoxides (MO₂)
```

**Reaction with H₂O:**
```
2M + 2H₂O → 2MOH + H₂
(Reactivity: Li < Na < K < Rb < Cs)
```

**Reaction with H₂:**
```
2M + H₂ → 2MH (ionic hydrides)
```

**Reaction with Halogens:**
```
2M + X₂ → 2MX (halides)
```

### Anomalous Behavior of Li:
Li resembles Mg (diagonal relationship):
- Both form nitrides (Li₃N, Mg₃N₂)
- Both have high charge/size ratio
- Li₂CO₃ decomposes on heating
- LiOH is not very stable thermally

### Important Compounds:

**NaOH (Caustic Soda):**
- Made by Chlor-alkali process (electrolysis of brine): 2NaCl + 2H₂O → Cl₂ + H₂ + 2NaOH

**Na₂CO₃ (Washing Soda, Solvay Process):**
```
NaCl + NH₃ + CO₂ + H₂O → NaHCO₃↓ + NH₄Cl
2NaHCO₃ → Na₂CO₃ + H₂O + CO₂
```

**NaHCO₃ (Baking Soda):** Mild antacid, in baking powder (with tartaric acid)

## 10.2 Group 2 (Alkaline Earth Metals): Be, Mg, Ca, Sr, Ba, Ra

### Electronic Configuration: [Noble gas] ns²

### General Properties:
- Harder and denser than Group 1
- Higher melting points than Group 1
- IE₂ much higher than IE₁ (but both are removed in reactions → +2 oxidation state)

### Anomalous Behavior of Be:
Be resembles Al (diagonal relationship):
- Both are amphoteric (react with NaOH and HCl)
- Both form covalent halides
- Both form layer lattice hydroxides
- Be doesn't react with water; Al forms oxide layer

### Important Reactions:

**Mg with hot water/steam:**
```
Mg + H₂O → MgO + H₂ (Ca reacts with cold water)
2Mg + O₂ → 2MgO  (burns brilliantly in O₂)
3Mg + N₂ → Mg₃N₂ (burns in N₂)
```

**Ca with CO₂:**
```
Ca(OH)₂ + CO₂ → CaCO₃↓ + H₂O (milky)
CaCO₃ + CO₂ + H₂O → Ca(HCO₃)₂  (excess CO₂ → clear again)
```

### Important Compounds:

**CaO (Quicklime):**
```
CaCO₃ →(Δ)→ CaO + CO₂  (∼825°C)
CaO + H₂O → Ca(OH)₂ + heat  (slaking)
```

**Ca(OH)₂ (Slaked Lime):**
- Limewater: dilute Ca(OH)₂ solution
- Used in whitewashing, mortar, Solvay process

**CaSO₄ (Gypsum: CaSO₄·2H₂O):**
```
CaSO₄·2H₂O →(120°C)→ CaSO₄·½H₂O (Plaster of Paris)
Plaster of Paris + H₂O → CaSO₄·2H₂O (sets/hardens)
Dead burnt plaster: CaSO₄ (>200°C) — doesn't set
```

**CaCO₃:** Limestone, marble, chalk

**Mg(OH)₂:** Milk of magnesia (antacid)

---

---

# 11. p-BLOCK ELEMENTS (GROUP 13 & 14)

## 11.1 Group 13 (Boron Family): B, Al, Ga, In, Tl

### Electronic Configuration: [Noble gas] ns² np¹

### Boron (B):
- Non-metal, very high melting point (2573 K), hard
- Covalent compounds only (small size, high charge density)
- Electron-deficient: forms Lewis acid

**Borax (Na₂B₄O₇·10H₂O):**
```
Na₂B₄O₇·10H₂O → Na₂B₄O₇ + 10H₂O
Na₂B₄O₇ → 2NaBO₂ + B₂O₃  (borax bead test)
```
Structure: [B₄O₅(OH)₄]²⁻ with 2 sp³ and 2 sp² boron atoms

**Boric Acid (H₃BO₃):**
- Weak monobasic acid (not Brønsted acid; Lewis acid)
- H₃BO₃ + H₂O ⇌ [B(OH)₄]⁻ + H⁺  (accepts OH⁻)
- Layered structure with H-bonding
- On heating: H₃BO₃ → HBO₂ → B₂O₃

### Aluminium (Al):
- Most abundant metal in earth's crust (after O and Si, Al is 3rd most abundant element)
- Amphoteric metal:

```
Al + NaOH(dil) + H₂O → NaAl(OH)₄ (tetrahydroxoaluminate) + H₂↑
Al + 3HCl → AlCl₃ + 3/2 H₂↑
```

**Alumina (Al₂O₃):** α-Al₂O₃ (corundum) very hard; γ-Al₂O₃ = active catalyst support

**Alum (KAl(SO₄)₂·12H₂O):** Used in water purification (coagulation of colloidal particles)

**AlCl₃:** Covalent, Lewis acid, used in Friedel-Crafts reactions, dimerizes to Al₂Cl₆

## 11.2 Group 14 (Carbon Family): C, Si, Ge, Sn, Pb

### Electronic Configuration: [Noble gas] ns² np²

### Carbon (C):
**Allotropes:**

| Form | Structure | Properties |
|---|---|---|
| Diamond | sp³, tetrahedral, 3D network | Hardest, insulator, high density |
| Graphite | sp², layers, delocalized π-e⁻ | Soft, conductor, lubricant, low density |
| Fullerene (C₆₀) | sp², closed cage | Semiconductor, cage structure |

**Oxides:**
- CO: reducing agent, toxic (binds hemoglobin), neutral oxide
- CO₂: acidic oxide, greenhouse gas; forms H₂CO₃ with water

**Silicon:**
- Giant covalent structure (like diamond)
- SiO₂ (quartz): acidic oxide; used in glass, optical fibers
- Silicates: basic unit = SiO₄⁴⁻ tetrahedra
- Silicones: (–SiR₂–O–)ₙ synthetic polymers, water-repellent

### Trends in Group 14:
- **Stability of +2 state:** Increases down the group (Inert pair effect: ns² electrons become inert)
  - C, Si: +4 dominant
  - Ge: +4 > +2
  - Sn: +4 and +2 both stable
  - Pb: +2 dominant (Pb⁴⁺ is strong oxidizer)

**Inert Pair Effect:** ns² electrons in heavier elements are more stable (increased nuclear attraction, poor shielding by d and f electrons) → less likely to participate in bonding

---

---

# 12. ORGANIC CHEMISTRY — BASIC PRINCIPLES & TECHNIQUES

## 12.1 Tetravalency of Carbon & Catenation

- Carbon forms 4 covalent bonds (sp, sp², sp³)
- Catenation: ability to bond with itself → chains, rings, branched structures
- Organic compounds: contain C-H bonds (broadly)

## 12.2 Classification of Organic Compounds

```
Organic Compounds
├── Acyclic (open chain)
│   ├── Straight chain
│   └── Branched chain
└── Cyclic
    ├── Carbocyclic
    │   ├── Alicyclic (cycloalkanes)
    │   └── Aromatic (benzene and derivatives)
    └── Heterocyclic (N, O, S in ring)
```

## 12.3 Functional Groups ⭐

| Functional Group | Name | Example |
|---|---|---|
| -OH | Hydroxyl | CH₃OH (methanol) |
| -CHO | Aldehyde | CH₃CHO (ethanal) |
| -CO- | Ketone | CH₃COCH₃ (propanone) |
| -COOH | Carboxyl | CH₃COOH (acetic acid) |
| -COO- | Ester | CH₃COOC₂H₅ |
| -NH₂ | Amino | CH₃NH₂ (methylamine) |
| -X (F,Cl,Br,I) | Halo | CH₃Cl (chloromethane) |
| -CN | Nitrile | CH₃CN |
| -NO₂ | Nitro | C₆H₅NO₂ |
| C=C | Alkene | CH₂=CH₂ |
| C≡C | Alkyne | HC≡CH |

## 12.4 IUPAC Nomenclature ⭐⭐

### Prefix for Chain Length:

| # C | Prefix | | # C | Prefix |
|---|---|---|---|---|
| 1 | Meth- | | 6 | Hex- |
| 2 | Eth- | | 7 | Hept- |
| 3 | Prop- | | 8 | Oct- |
| 4 | But- | | 9 | Non- |
| 5 | Pent- | | 10 | Dec- |

### Suffix by Functional Group (Priority Order):
```
COOH > SO₃H > COOR > COX > CONH₂ > CHO > C=O > OH > NH₂ > C≡C > C=C
```

**Steps for IUPAC naming:**
1. Identify longest C chain containing principal functional group
2. Number from end closer to principal group
3. Name substituents alphabetically with position numbers
4. Combine: prefix-substituents + parent chain + suffix

### Common Substituent Names:
- -CH₃: methyl, -C₂H₅: ethyl, -C₃H₇: propyl
- -CH₂-: methylene, -CH=: methylidene
- -(CH₃)₂CH-: isopropyl (1-methylethyl)
- (CH₃)₃C-: tert-butyl (1,1-dimethylethyl)

## 12.5 Isomerism ⭐⭐

### Structural Isomerism:
1. **Chain isomerism:** Different carbon skeletons (n-butane vs isobutane)
2. **Position isomerism:** Same group at different positions (1-propanol vs 2-propanol)
3. **Functional group isomerism:** Same formula, different groups (CH₃CHO vs CH₂=CHOH)
4. **Metamerism:** Different alkyl groups on same functional group (diethyl ether vs methyl propyl ether)
5. **Tautomerism:** Interconversion, usually keto-enol

### Stereoisomerism:
1. **Geometrical (cis-trans / E-Z) isomerism:**
   - Requires restricted rotation (C=C, ring) and two different groups on each carbon

   ```
   E (entgegen): Higher priority groups on opposite sides
   Z (zusammen): Higher priority groups on same side
   
   Priority by Cahn-Ingold-Prelog (CIP) rules: Higher atomic number = higher priority
   ```

2. **Optical isomerism:**
   - Chiral carbon = C bonded to 4 different groups (sp3, asymmetric center)
   - Enantiomers: non-superimposable mirror images; identical physical properties but rotate plane-polarized light in opposite directions
   - R-S configuration by CIP rules

   ```
   Maximum optical isomers = 2ⁿ (n = number of chiral centers, if no meso form)
   ```
   - **Meso compounds:** Has chiral centers but has internal plane of symmetry → optically inactive
   - **Racemic mixture:** 50:50 mixture of enantiomers → no net optical rotation ([α] = 0)
   - **Diastereomers:** Stereoisomers that are NOT mirror images; have different physical properties

## 12.6 Electronic Effects ⭐⭐

### Inductive Effect (I Effect):
> *Permanent polarization of σ bond due to electronegativity difference; transmitted through chain (decreases with distance)*

- **−I effect** (electron withdrawing): −NO₂, −CN, −COOH, −CHO, −F, −Cl, −Br, −I, −OH, −OR, −NH₂
- **+I effect** (electron donating): alkyl groups (CH₃, C₂H₅... in order of increasing +I), negative charges

### Resonance Effect (Mesomeric Effect, M Effect):
> *Delocalization of π electrons or lone pairs through conjugated system*

- **−M effect** (electron withdrawing): −NO₂, −CN, −COOH, −CHO, −CO− (withdraws e⁻ from ring/system)
- **+M effect** (electron donating): −NH₂, −OH, −OR, −X (donates lone pair into system)

### Hyperconjugation:
> *Delocalization of σ (C-H) bonding electrons with adjacent π system or empty orbital*
> Baker-Nathan Effect

**Condition:** C-H bond adjacent to C=C or C⁺ or C radical

```
Number of hyperconjugative structures = number of α-H atoms
More α-H → more hyperconjugation → more stability
```

**Stability of Carbocations:**
```
3° > 2° > 1° > CH₃⁺
(due to +I effect and hyperconjugation of alkyl groups)
```

**Stability of Radicals:**
```
3° > 2° > 1° > CH₃•
```

**Stability of Carbanions:**
```
CH₃⁻ > 1° > 2° > 3°
(alkyl groups destabilize by +I effect)
```

### Electromeric Effect (E Effect):
> *Temporary effect; complete transfer of π electrons to one atom when attacking reagent approaches*

- **+E effect:** π electrons toward attacking reagent
- **−E effect:** π electrons away from attacking reagent

## 12.7 Reaction Intermediates ⭐

### Carbocations (Carbonium Ions):
- sp² hybridized, trigonal planar, empty p-orbital
- Stability: 3° > 2° > 1° > CH₃⁺
- Benzylic and allylic carbocations stabilized by resonance

### Carbanions:
- sp³ hybridized, pyramidal, lone pair
- Stability: CH₃⁻ > 1° > 2° > 3°
- Stabilized by −I and −M groups adjacent

### Free Radicals:
- sp² hybridized (usually), one unpaired electron
- Stability: 3° > 2° > 1° > CH₃•
- Stabilized by resonance, hyperconjugation

### Carbenes (:CR₂):
- Neutral, divalent carbon (two bonds, two nonbonding electrons)
- Singlet (paired) or triplet (unpaired) state
- Example: :CH₂ (methylene)

### Nitrene (:NR):
- Neutral, monovalent nitrogen with lone pair

## 12.8 Types of Organic Reactions

### By Bond Cleavage:

**Homolytic Fission:**
```
A:B → A• + •B  (equal sharing → free radicals; favored by nonpolar bonds, UV light, heat)
```

**Heterolytic Fission:**
```
A:B → A⁺ + B⁻  or  A⁻ + B⁺  (unequal sharing → ions; favored by polar bonds, polar solvents)
```

### By Reagent Type:

| Reagent Type | Description | Example |
|---|---|---|
| Electrophile (E⁺) | Electron-pair acceptor | H⁺, NO₂⁺, Br⁺, BF₃ |
| Nucleophile (Nu⁻) | Electron-pair donor | OH⁻, CN⁻, NH₃, H₂O, Cl⁻ |
| Free radical | Unpaired electron | Cl•, Br• |

### Reaction Types:

| Type | Mechanism | Example |
|---|---|---|
| Substitution (S) | One group replaces another | CH₄ + Cl₂ → CH₃Cl + HCl |
| Addition (A) | Two reactants → one product | CH₂=CH₂ + Br₂ → CH₂BrCH₂Br |
| Elimination (E) | One reactant → two products | CH₃CH₂Br + KOH → CH₂=CH₂ + KBr + H₂O |
| Rearrangement (R) | Restructuring of carbon skeleton | 1,2-hydride or 1,2-alkyl shift |

---

---

# 13. HYDROCARBONS

## 13.1 Alkanes (CₙH₂ₙ₊₂) ⭐

### Nomenclature: Suffix = -ane
Methane, Ethane, Propane, Butane, Pentane, Hexane, Heptane, Octane, Nonane, Decane

### Properties of Methane:
- Colorless, odorless, less dense than air
- Nearly insoluble in water
- Chief constituent of natural gas, biogas

### Reactions:

**1. Free Radical Halogenation (SR — Substitution Radical):**
```
CH₄ + Cl₂ → CH₃Cl + HCl   (sunlight/UV, hν)

Mechanism:
Initiation:   Cl₂ →(hν)→ 2Cl•
Propagation:  Cl• + CH₄ → HCl + CH₃•
              CH₃• + Cl₂ → CH₃Cl + Cl•
Termination:  Cl• + Cl• → Cl₂
              CH₃• + CH₃• → C₂H₆
              CH₃• + Cl• → CH₃Cl
```

**Reactivity order:** F₂ > Cl₂ > Br₂ > I₂ (iodination doesn't occur practically)
**Selectivity order:** I₂ > Br₂ > Cl₂ > F₂ (Br₂ most selective in practice)

**2. Combustion:**
```
CₙH₂ₙ₊₂ + (3n+1)/2 O₂ → nCO₂ + (n+1)H₂O
CH₄ + 2O₂ → CO₂ + 2H₂O  (complete combustion)
Incomplete: CO + soot (C) formed
```

**3. Cracking:**
- Thermal cracking: high temperature, breaks C-C bonds
- Catalytic cracking: zeolite catalysts

**4. Isomerization:**
- n-butane → iso-butane (AlCl₃/HCl, heat)

**5. Reforming:**
- Straight chain → branched/aromatic (Pt catalyst)

**Conformations of Ethane:**
```
Staggered (gauche or anti) vs Eclipsed
Newman projection analysis:
Staggered (anti): lowest energy, dihedral angle = 60° between H atoms
Eclipsed: highest energy (torsional strain)
```

## 13.2 Alkenes (CₙH₂ₙ) ⭐⭐

### Preparation:

**1. Dehydrohalogenation (Elimination, E2):**
```
CH₃CH₂Cl + KOH(alc.) → CH₂=CH₂ + KCl + H₂O

Zaitsev's Rule: Predominant product is more substituted alkene
```

**2. Dehydration of alcohols:**
```
CH₃CH₂OH →(H₃PO₄/heat or H₂SO₄/170°C)→ CH₂=CH₂ + H₂O

At 140°C: Ether (ethoxyethane) formed — intermolecular dehydration
At 170°C: Alkene — intramolecular dehydration
```

**3. Reduction of alkynes:**
```
HC≡CH + H₂ →(Lindlar's catalyst: Pd/BaSO₄/quinoline)→ cis-CH₂=CH₂
HC≡CH + Na/liq. NH₃ → trans-alkene (Birch reduction)
```

### Reactions of Alkenes ⭐⭐

**1. Electrophilic Addition:**

**Hydrohalogenation (Markovnikov's Rule):**
```
CH₃-CH=CH₂ + HBr → CH₃-CHBr-CH₃  (Markovnikov: H adds to C with more H)

Markovnikov's Rule: "In addition of HX to an unsymmetrical alkene, H adds to the carbon bearing more H atoms (or the more stable carbocation forms)"

Anti-Markovnikov (Peroxide effect/Kharasch effect):
CH₃-CH=CH₂ + HBr →(ROOR)→ CH₃-CH₂-CH₂Br  (free radical mechanism)
```

**Halogenation (Addition of X₂):**
```
CH₂=CH₂ + Br₂(CCl₄) → CH₂Br-CH₂Br  (anti addition)
Br₂ solution decolorized → test for alkene
```

**Hydration:**
```
CH₂=CH₂ + H₂O →(H₃PO₄ or H₂SO₄)→ CH₃CH₂OH
```

**Oxymercuration-Demercuration:**
```
Alkene + Hg(OAc)₂/H₂O → (demercurate with NaBH₄) → Markovnikov alcohol
(syn addition, no rearrangement)
```

**Hydroboration-Oxidation (Anti-Markovnikov):**
```
Alkene + BH₃ → trialkylborane →(H₂O₂/OH⁻)→ Anti-Markovnikov alcohol
(syn addition)
```

**2. Ozonolysis:**
```
Reductive ozonolysis: R-CH=CH-R' + O₃, then Zn/H₂O → R-CHO + R'-CHO
Oxidative ozonolysis: + H₂O₂ → R-COOH + R'-COOH
```

**3. Epoxidation:**
```
Alkene + mCPBA (meta-chloroperoxybenzoic acid) → epoxide (oxirane)
```

**4. Polymerization:**
```
nCH₂=CH₂ →(high P, T, catalyst)→ (-CH₂-CH₂-)ₙ  (polyethylene)
```

### Stability of Alkenes:
```
More substituted = more stable (hyperconjugation, +I effect of alkyl groups)
Trans > Cis (less steric strain)
```

## 13.3 Alkynes (CₙH₂ₙ₋₂) ⭐

### Preparation:
**1. Dehydrohalogenation (double):**
```
CH₃CHBr₂ + 2KOH(alc.) → CH≡CH + 2KBr + 2H₂O
```

**2. From calcium carbide:**
```
CaC₂ + H₂O → Ca(OH)₂ + HC≡CH↑
```

### Properties:

**Acidity of Terminal Alkynes:**
```
RC≡CH + NaNH₂ → RC≡C⁻Na⁺ + NH₃  (pKa ~ 25)
HC≡CH + AgNO₃(aq) → HC≡CAg↓ (silver acetylide, cream ppt)
HC≡CH + CuCl(amm.) → HC≡CCu↓ (red ppt)

Acidity: HC≡CH > H₂C=CH₂ > CH₃CH₃
(sp > sp² > sp³ C-H bonds; more s character = stronger acid)
```

### Reactions:

**1. Hydrogenation:**
```
HC≡CH + H₂ →(Pd-C)→ CH₂=CH₂ →(Pd-C)→ CH₃CH₃
Partial: Lindlar → cis-alkene; Na/NH₃(l) → trans-alkene
```

**2. Halogenation:**
```
HC≡CH + Br₂(CCl₄) → CHBr=CHBr (dibromoalkene)
                  + Br₂ → CHBr₂-CHBr₂ (tetrabromoethane)
```

**3. Hydration (Markovnikov):**
```
HC≡CH + H₂O →(HgSO₄/H₂SO₄, 60°C)→ CH₃CHO (vinyl alcohol → tautomerizes to acetaldehyde)
```

**4. Hydrohalogenation:**
```
HC≡CH + HCl →(HgCl₂/C)→ CH₂=CHCl (vinyl chloride → PVC)
```

## 13.4 Aromatic Hydrocarbons (Benzene) ⭐⭐

### Benzene (C₆H₆):
- Cyclic, planar, all C-C bonds equivalent (1.40 Å, between single 1.54 and double 1.34)
- Resonance stabilization energy ≈ 150 kJ/mol (delocalization of 6 π electrons)
- Hückel's Rule: Aromatic if 4n + 2 π electrons (n = 0,1,2...) in cyclic, planar, conjugated system

### Hückel's Rule:
```
Aromatic: 4n+2 π electrons → C₆H₆ (6e⁻), C₁₀H₈ naphthalene (10e⁻)
Antiaromatic: 4n π electrons → cyclobutadiene (4e⁻), cyclooctatetraene (8e⁻)
Non-aromatic: not all p-orbitals continuous
```

### Electrophilic Aromatic Substitution (EAS) ⭐⭐

**General Mechanism:**
```
Step 1: Generation of electrophile (E⁺)
Step 2: Attack of E⁺ on benzene ring → arenium ion (σ-complex/Wheland intermediate)
Step 3: Loss of H⁺ → restore aromaticity
```

**Key Reactions:**

**1. Nitration:**
```
C₆H₆ + HNO₃ →(conc.H₂SO₄, 50°C)→ C₆H₅NO₂ + H₂O
Electrophile: NO₂⁺ (nitronium ion)
HNO₃ + H₂SO₄ → NO₂⁺ + HSO₄⁻ + H₂O
```

**2. Halogenation:**
```
C₆H₆ + Cl₂ →(FeCl₃, Lewis acid)→ C₆H₅Cl + HCl
Electrophile: Cl⁺ (from Cl₂-FeCl₃ complex)
```

**3. Sulfonation:**
```
C₆H₆ + H₂SO₄(fuming) → C₆H₅SO₃H + H₂O  (reversible at high T)
Electrophile: SO₃
```

**4. Friedel-Crafts Alkylation:**
```
C₆H₆ + RCl →(AlCl₃)→ C₆H₅R + HCl
Electrophile: R⁺ (carbocation)
Problem: polyalkylation, carbocation rearrangement
```

**5. Friedel-Crafts Acylation:**
```
C₆H₆ + RCOCl →(AlCl₃)→ C₆H₅COR + HCl
Electrophile: RCO⁺ (acylium ion)
No rearrangement (acylium is stabilized by resonance)
```

### Directing Effects of Substituents ⭐⭐

**ortho/para-directing groups (+M or +I effect):**
```
–OH, –OR, –NH₂, –NR₂, –NHCOR, –X (halogens activate o/p but are deactivators overall)
–CH₃, –C₂H₅ (alkyl groups: +I, hyperconjugation)
```

**meta-directing groups (−M or −I effect):**
```
–NO₂, –CN, –COOH, –CHO, –COR, –SO₃H
(electron withdrawing groups → deactivate ring, direct to meta)
```

**Rules:**
- EDG (electron donating): activate ring → faster EAS → ortho/para
- EWG (electron withdrawing): deactivate ring → slower EAS → meta
- For mixed substituents: more powerful group dominates

### Addition Reactions of Benzene (rare):

**Hydrogenation:**
```
C₆H₆ + 3H₂ →(Ni/Pt, high P)→ C₆H₁₂ (cyclohexane)
```

**Addition of Cl₂ (photochemical):**
```
C₆H₆ + 3Cl₂ →(hν)→ C₆H₆Cl₆ (BHC, benzene hexachloride = lindane)
```

---

---

# 14. ENVIRONMENTAL CHEMISTRY

## 14.1 Environmental Segments

- **Troposphere:** 0–12 km; weather, photochemical reactions
- **Stratosphere:** 12–50 km; ozone layer at 20-30 km
- **Mesosphere:** 50–80 km
- **Thermosphere/Ionosphere:** 80–400 km; ionized by solar radiation

## 14.2 Atmospheric Pollution

### Tropospheric Pollutants:

**Oxides of Sulfur (SO₂):**
```
Fossil fuel combustion: S + O₂ → SO₂ →(O₂/cat.)→ SO₃
SO₃ + H₂O → H₂SO₄ (acid rain, pH < 5.6)
```

**Oxides of Nitrogen:**
```
N₂ + O₂ →(high T)→ 2NO (in car engines, lightning)
2NO + O₂ → 2NO₂ (brown, toxic)
NO₂ + H₂O → HNO₃ (acid rain)
```

**Acid Rain:**
- pH < 5.6 (normal rain pH = 5.6 due to CO₂)
- Causes: corrosion of metals, damage to limestone/marble, harm to aquatic life, plant damage
- H₂SO₄ and HNO₃ are main acid rain constituents

**Carbon Monoxide (CO):**
- Incomplete combustion of fossil fuels
- Toxic: binds hemoglobin (250× affinity than O₂) → carboxyhemoglobin → asphyxiation

**Particulate Pollutants:**
- Aerosols, dust, soot, pollen, asbestos
- Smog = smoke + fog

**Photochemical Smog:**
```
O₃, PAN (peroxyacetyl nitrate = CH₃CO-OO-NO₂), NO₂, RCHO, RCHO
Formed by: NO₂ →(hν)→ NO + O•
O• + O₂ → O₃
O₃ + hydrocarbons → PAN (eye irritant)
```

### Stratospheric Pollution — Ozone Depletion ⭐

**Ozone Formation/Destruction (Natural):**
```
O₂ →(hν, UV)→ 2O•
O• + O₂ → O₃  (formation)
O₃ →(hν, UV)→ O₂ + O•  (destruction = O₃ shields UV)
```

**CFC (Chlorofluorocarbons, Freons) — Ozone Depleters:**
```
CCl₂F₂ →(UV)→ •CCl F₂ + Cl•
Cl• + O₃ → ClO• + O₂
ClO• + O• → Cl• + O₂  (Cl• regenerated — chain reaction!)
```
One Cl• atom can destroy 10⁵ O₃ molecules

**Other Ozone Depleters:** Halons (CBrF₃), N₂O, CH₄ (indirectly)

**Montreal Protocol (1987):** International agreement to phase out CFCs

## 14.3 Water Pollution

### Biochemical Oxygen Demand (BOD):
> *Amount of O₂ (mg/L) required by microorganisms to oxidize organic matter in water at 20°C for 5 days*
- Clean water: BOD < 5 mg/L
- Polluted water: BOD > 17 mg/L

### Dissolved Oxygen (DO):
- Healthy water: DO = 6–8 mg/L
- Depleted DO → death of fish

### Eutrophication:
> *Excessive growth of algae in water body due to excess nutrients (NO₃⁻, PO₄³⁻) from agricultural runoff*
- Algal bloom → depletes O₂ (algae die, bacteria decompose them using O₂)

### Heavy Metal Pollution:
- Lead (Pb): from leaded gasoline, old paints
- Mercury (Hg): from industrial effluents → methylmercury (Minamata disease, Japan)
- Cadmium (Cd): Itai-itai disease (Japan)
- Arsenic: groundwater contamination

## 14.4 Soil Pollution

**Causes:** Pesticides, industrial waste, heavy metals, acid rain

**Persistent Organic Pollutants (POPs):** DDT, PCBs, dioxins — bioaccumulate in food chain

**Biomagnification:** Concentration of pollutant increases at higher trophic levels

**Green Chemistry Principles:** Minimize waste, use renewable feedstocks, avoid toxic reagents, improve atom economy

---

---

# 📊 QUICK REFERENCE: IMPORTANT CONSTANTS

| Constant | Symbol | Value |
|---|---|---|
| Avogadro's number | Nₐ | 6.022 × 10²³ mol⁻¹ |
| Planck's constant | h | 6.626 × 10⁻³⁴ J·s |
| Boltzmann constant | k | 1.38 × 10⁻²³ J/K |
| Gas constant | R | 8.314 J/(mol·K) |
| Speed of light | c | 3 × 10⁸ m/s |
| Faraday constant | F | 96485 C/mol ≈ 96500 C/mol |
| Bohr radius | a₀ | 0.529 Å |
| Electron mass | mₑ | 9.11 × 10⁻³¹ kg |
| Proton mass | mₚ | 1.67 × 10⁻²⁷ kg |
| 1 eV | | 1.6 × 10⁻¹⁹ J |
| 1 atm | | 101325 Pa = 1.01325 bar |
| 1 cal | | 4.184 J |

---

---

# 🎯 JEE IMPORTANT TIPS & HIGH-WEIGHTAGE TOPICS

## Must-Master Topics (High JEE Weightage):

1. **Mole Concept & Stoichiometry** — Always in JEE, highly conceptual
2. **Quantum Numbers & Electronic Configuration** — Direct questions + indirect applications
3. **Chemical Bonding** — VSEPR, hybridization, polarity — Very frequent
4. **Thermodynamics** — ΔG, ΔH, ΔS, Hess's Law — Numerical problems
5. **Equilibrium** — Kc, Kp, pH, buffers, Ksp — Massive chapter, always tested
6. **Bohr's Model** — Direct formula application + energy calculations
7. **Organic Mechanisms** — Reaction types, intermediates, directing effects
8. **Kinetic Theory** — Speed calculations, PV=nRT applications

## Common Mistakes to Avoid:

- Using Celsius instead of Kelvin in gas law calculations
- Forgetting Δn_g when converting Kp ↔ Kc
- Mixing up +I/−I and +M/−M effects in organic
- Confusing EA with ΔegH sign conventions
- Using 22.4 L/mol at non-STP conditions
- Forgetting that bond order and bond length are inversely related

## Dimensional Analysis Reminders:

```
Pressure: 1 atm = 760 mmHg = 101.325 kPa = 101325 Pa
Energy: 1 kJ/mol = 1000 J/mol; 1 eV = 96.5 kJ/mol
Wavelength: 1 Å = 10⁻¹⁰ m = 100 pm; 1 nm = 10⁻⁹ m
```

---

