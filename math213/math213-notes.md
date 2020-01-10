## 1.2 Dot Product -- 01-09-2020

### Dot Product:
- Dot Product: 
  - <span style="color:yellow">**u** * **v** = **u1v1** + **u2v2** + ... + **uNvN**</span>
- Why use Dot Product? 
  - takes as its input two vectors and outputs a scalar <span style="color:darkred">(**NOT VECTOR MULTIPLICATION,** there is no such thing)</span>
  - Not correct to say "u *times* v" but rather "dot product of u and v"
- Properties of Dot Product: 
  1. Commutative ---> **u** * **v** = **v** * **u** 
  2. Distributive ---> **u** * (**v** + **w**) = **u** * **v** + **u** * **w**
  3. (**c** * **u**) * **v** = **c**(**u** * **v**) = **u**(**c** * **v**)

### Length of Vector:

- Length of a vector **u** is given by <span style="color:yellow">||**u**|| = sqrt(**u** * **u**)</span>
  - length is denoted by the two vertical lines on either side of the vector
  - length is also called "Magnitude" or "Norm" of a vector

- Properties of Magnitude (length) 
  1. ||**v**|| = 0 if and only if **v** = 0
  2. ||c **v**|| = |c| ||**v**|| -> 'c' is a constant and the vector is stretched by the value of 'c'
  3. ||**u** + **v**|| <= ||**u**|| + ||**v**|| (triangle inequality)

- A vector over its own magnitude will always have a length of 1

### Distance between two Vectors:

- distance is just the two vectors subtracted
  - <span style="color:yellow"> distance of (**u** , **v**) = ||**v** - **u**||</span>

### Finding angles with Dot Product

- If **u** * **v** = 0 (dot product is zero), then we say they are "orthogonal"(perpendicular)

### Projection of a vector onto another Vector

- Idea is when you have a vector **u** and some other vector **v**, think of shining a light perpendicular to you, the vector **v** will cast a shadow on **u**, that length or "shadow" is the projection of **v** on **u**
- <span style="color:yellow">projection of **v** on **u** = {(**u** * **v**) / (**u** * **u**)} * u