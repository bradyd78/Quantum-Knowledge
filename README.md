# Quantum Knowledge

This repo contains different resources that helped me learn quantum topics. I also include my own personal way of explaining concepts. Feel free to add or edit the content.

---

## Table of Contents

1. 📚 [Quantum Vocab Cheat Sheet](cheatsheet/vocab.md)
2. [Linear Algebra](#linear-algebra)
3. [Dirac Notation](#dirac-notation)
4. [Quantum Physics](#quantum-physics)
5. [Quantum Mechanics Basics](#quantum-mechanics-basics)
6. [Quantum Computing](#quantum-computing)
7. [Useful Resources](#useful-resources)
8. [How to Contribute](#how-to-contribute)

---

## 1. Dirac Notation
<a name="dirac-notation"></a>

📦 **Dirac Notation — In Juice Box Terms**

Dirac notation uses “kets” and “bras” to describe quantum states:

- **Ket (|ψ⟩)** → “Should be” — like labeling a juice box, e.g. “This is supposed to be apple juice.”
- **Bra (⟨ψ|)** → “Seems like” — tasting it to check, e.g. “Does this act like apple juice?”
- **Bra–ket (⟨ψ|ψ⟩)** → “I’m this sure” — measuring how likely it actually is apple juice.

It’s a way to represent and compare quantum states using inner products.  
Succinctly: **Ket = identity, Bra = evaluation, Bra–ket = confidence.**

**Useful Links:**
- [Wikipedia: Bra–ket notation](https://en.wikipedia.org/wiki/Bra%E2%80%93ket_notation)
- [YouTube: Dirac Notation Explained](https://www.youtube.com/results?search_query=dirac+notation)
- [Quantum Country: Dirac Notation](https://quantum.country/qcvc)

**Documentation:**
- [Understanding Quantum Information and Computation](https://youtube.com/playlist?list=PLOFEBzvs-VvqKKMXX4vbi4EB1uaErFMSO&si=4IolgqQDrtsA9oAf)
- [MIT OpenCourseWare Lecture Notes](https://ocw.mit.edu/courses/physics/8-04-quantum-physics-i-spring-2016/lecture-notes/)
- [Qiskit Textbook: Dirac Notation](https://qiskit.org/textbook/ch-states/dirac-notation.html)

---

## 2. Linear Algebra
<a name="linear-algebra"></a>

### 🧠 Introduction to Linear Algebra (Quantum Computing Focus)

Linear algebra is the mathematical foundation of quantum computing. It deals with vectors, matrices, and transformations — all of which are essential for understanding quantum states, gates, and measurements.

---

### 📚 Why Learn Linear Algebra?

Quantum computing uses:
- **Vectors** → to represent quantum states (`|ψ⟩`)
- **Matrices** → to represent quantum gates
- **Inner products** → to calculate probabilities
- **Tensor products** → to combine qubits
- **Eigenvalues/eigenvectors** → to understand quantum measurements

---

### 🧩 Key Concepts

| Concept                  | Description                                         | Quantum Relevance                        |
|--------------------------|-----------------------------------------------------|------------------------------------------|
| **Vector**               | A list of numbers (e.g., `[1, 0]`)                  | Represents quantum states like `|0⟩`     |
| **Matrix**               | A grid of numbers that transforms vectors           | Quantum gates are matrices               |
| **Matrix Multiplication**| Applying a transformation to a vector               | Simulates quantum circuits               |
| **Inner Product**        | Measures similarity between vectors                 | Determines probabilities of outcomes     |
| **Eigenvalues/Eigenvectors** | Special vectors that don’t change direction     | Key to quantum measurements              |
| **Complex Numbers**      | Numbers with real and imaginary parts               | Quantum amplitudes are complex           |
| **Unitary/Hermitian Matrices** | Preserve length and have real eigenvalues   | Describe quantum gates and observables   |

---

### 🧠 Geometric Interpretations

- **Scale**: make all inputs bigger/smaller
- **Skew**: make certain inputs bigger/smaller
- **Flip**: make inputs negative
- **Rotate**: change coordinates based on old ones (East becomes North, etc.)

These are ways to warp a vector space. Just remember: vectors are examples of data to modify.

---

### 🎓 Recommended Resources

#### 📘 Courses
- [Better Explained – Linear Algebra](https://betterexplained.com/articles/linear-algebra-guide/)
- [Khan Academy – Linear Algebra](https://www.khanacademy.org/math/linear-algebra)
- [MIT OpenCourseWare – Linear Algebra](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/)
- [Alison – Free Online Course](https://alison.com/course/introduction-to-linear-algebra)

#### 📗 Books

##### 1. [Linear Algebra for Beginners: The Ultimate Step-by-Step Guide](https://www.amazon.com/Linear-Algebra-Beginners-Ultimate-Guide/dp/B0DW4FCDBT)
- Clear explanations, practice problems, and full-length tests

##### 2. [The Linear Algebra a Beginning Graduate Student Ought to Know](https://www.walmart.com/ip/The-Linear-Algebra-a-Beginning-Graduate-Student-Ought-to-Know-Paperback-9789400726352/19508112)
- Deeper dive into theory and computation

##### 3. [Linear Algebra: For Beginners (Solved Problem-Based)](https://www.amazon.com/dp/B096TRVB4F)
- Problem-focused approach with examples

##### 4. [Linear Algebra Essentials: A Crash Course for Beginners](https://www.amazon.com/dp/B0CCLN7MQ6)
- Concise and practical introduction

##### 5. [A First Course in Linear Algebra – Open Textbook](https://open.umn.edu/opentextbooks/textbooks/5)
- Free and comprehensive resource

> 📘 Tip: Start with a book that matches your comfort level. If you're new to math, go for #1 or #4. If you're ready to dive deeper, #2 or #5 are excellent choices.

#### 📺 Videos
- [Essence of Linear Algebra – 3Blue1Brown](https://www.youtube.com/playlist?list=PLZHQObOWTQDMsr9K-rj53DwVRMYO3t5Yr)

---

### 🧠 Pro Tip

As you learn linear algebra, try to connect each concept to quantum computing:
- **Unitary matrices** → quantum gates
- **Eigenvectors** → measurement outcomes
- **Tensor products** → entanglement

> “Linear algebra is the language of quantum mechanics. Master it, and you’ll unlock the quantum world.”

---

## 3. Quantum Physics
<a name="quantum-physics"></a>

Quantum physics is the broad field that studies the behavior of matter and energy at the smallest scales. It includes quantum mechanics, quantum field theory, and quantum technologies.

### 📺 Lectures
- [MIT Quantum Physics I – Video Lectures](https://ocw.mit.edu/courses/8-04-quantum-physics-i-spring-2016/pages/video-lectures/part-1/)

---

## 4. Quantum Mechanics Basics
<a name="quantum-mechanics-basics"></a>

Quantum mechanics is the mathematical framework that describes quantum phenomena. It includes principles like:

- **Superposition**: particles can exist in multiple states at once
- **Entanglement**: particles can be correlated across space
- **Measurement**: observing a quantum system affects its state
- **Uncertainty Principle**: limits how precisely we can know certain properties

_Add your explanations, links, and documentation as you learn new concepts._

---

## 5. Quantum Computing
<a name="quantum-computing"></a>

Quantum computing uses quantum mechanics to perform computations. It relies on:

- **Qubits**: quantum bits that can be in superpositions
- **Quantum gates**: operations that manipulate qubits
- **Quantum circuits**: sequences of gates to perform algorithms
- **Quantum algorithms**: like Grover’s and Shor’s

_Add your explanations, links, and documentation as you learn new concepts._

---

## 6. Useful Resources
<a name="useful-resources"></a>

- [Quantum Country](https://quantum.country/)
- [Qiskit Textbook](https://qiskit.org/textbook/)
- [Quantum Computing Playground (IBM)](https://quantum-computing.ibm.com/)

---

## 7. How to Contribute
<a name="how-to-contribute"></a>

- Add new sections with explanations, links, and documentation as you learn.
- Update the Table of Contents.
- Format new entries like the examples above.
