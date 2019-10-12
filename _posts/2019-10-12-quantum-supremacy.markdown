---
layout: post
title: "Quantum Supremacy And A New Era In Computing"
date: 2019-10-11
description: "Understanding quantum computers and the future that lies ahead"
image: assets/images/quantum-1.jpg
author: anand
tags: [Qunatum Computing, Quantum Supremacy, Algorithms, Future, Cryptography]
featured: true
hidden: false
categories: [ Computing ]
---
Recently, a paper by Google's researchers was briefly posted on the NASA website. It claimed that their processor (a Quantum Computer) was able to perform a calculation in 3 minutes and 20 seconds that would take today's most advanced classical computer, Summit, approximately 10,000 years. The paper was, however, taken down later.

Whether the said feat has been achieved or not, it is no harm to understand the concept of Quantum Supremacy and what it may have in store for us.

The term 'Quantum Supremacy' was coined in 2012 by John Preskill who is a professor of theoretical physics at CalTech. Before we talk about Quantum Supremacy, let's first delve a bit into quantum mechanics and quantum computers.

### **Quantum mechanics - the principles at play**
At the scale of atoms and electrons, many of the equations of classical mechanics, which describe how things move at everyday sizes and speeds, cease to be useful. In classical mechanics, objects exist in a specific place at a specific time. However, in quantum mechanics, objects instead exist in a haze of probability.

Multiple scientists contributed to a foundation of three revolutionary principles that gradually gained acceptance and experimental verification between 1900 and 1930 and ultimately paved way to the foundation of quantum theory or quantum mechanics. The three principles being -

**Quantized properties** - Through physical experiments, Planck demonstrated that energy, in certain situations, can exhibit characteristics of physical matter. According to theories of classical physics, energy is solely a continuous wave-like phenomenon, independent of the characteristics of physical matter. Planck's theory held that radiant energy is made up of particle-like components, known as **"quanta"**.

**Wave-Particle duality** - Is the concept in quantum mechanics that every particle or quantum entity may be described as either a particle or a wave. It expresses the inability of the classical concepts "particle" or "wave" to fully describe the behaviour of quantum-scale objects. As Albert Einstein wrote -

>> It seems as though we must use sometimes the one theory and sometimes the other, while at times we may use either. We are faced with a new kind of difficulty. We have two contradictory pictures of reality; separately neither of them fully explains the phenomena of light, but together they do.

**Heisenberg's uncertainty principle** - In 1927, Heisenberg made another major contribution to quantum physics. He reasoned that since matter acts as waves, some properties, such as an electron's position and speed, are "complementary," meaning there's a limit (related to Planck's constant) to how well the precision of each property can be known. Under what would come to be called []"Heisenberg's uncertainty principle,"](https://www.livescience.com/18567-wacky-physics-heisenberg-uncertainty-principle.html) it was reasoned that the more precisely an electron's position is known, the less precisely its speed can be known, and vice versa.

**Schrödinger's equation** - In classical mechanics, Newton's laws of motion govern the relation between a body and the forces acting upon it. In quantum mechanics, the analogue of Newton's law is Schrödinger's equation. It is a linear partial differential equation that describes the wave function or state function of a quantum-mechanical system.

In 1980, Paul Benioff described the first quantum mechanical model of a computer. In this work, Benioff showed that a computer could operate under the laws of quantum mechanics by describing a Schrödinger's equation based description of Turing machines, laying a foundation for further work in quantum computing.

### **Quantum Computers**
Quantum computers work differently from the classical computers we work on today. Exploiting the principles of quantum mechanics, they can easily tackle computational problems that may be tough for the classical computer as the size of the numbers and number of inputs involved grows bigger.

Conventional computers process information in 'bits' or 1s and 0s, following classical physics under which our computers can process a '1' or a '0' at a time. The world's most powerful super computer today can juggle 148,000 trillion operations in a second and requires about 9000 IBM CPUs connected in a particular combination to achieve this feat.

Quantum computers compute in **'qubits'** (or quantum bits). They exploit the properties of quantum mechanics, the science that governs how matter behaves on the atomic scale. In this scheme of things, processors can be a 1 and a 0 simultaneously, a state achieved by quantum superposition. While this accelerates the speed of computation, a machine with less than a 100 qubits can solve problems with a lot of data that are even theoretically beyond the capabilities of the most powerful supercomputers.

![The Bloch sphere is a geometrical representation of the pure state space of a two-level quantum mechanical system (qubit). Photo Credits - Wikimedia Commons](../assets/images/bloch-sphere.png?raw=true)

Because of [quantum superposition](https://en.wikipedia.org/wiki/Quantum_superposition), a quantum computer - if it works to plan - can mimic several classical computers working in parallel. The ideas governing quantum computers have been around since the 1990s but actual machines have been around since 2011, most notably built by Canadian company D-Wave Systems.

---

### **Quantum supremacy**
In theory, a quantum computer can solve complex problems that are beyond the scope of a classical computer. The basic advantage is speed as it is able to simulate several classical computers working in parallel. Several encryption systems used in banking and security applications are premised on computers being unable to handle mathematical problems that are computationally demanding beyond a limit. Quantum computers, in theory, can surpass those limits.

Quantum supremacy refers to quantum computers being able to solve a problem that a classical computers cannot.

The paper (published and taken down, allegedly) describes how Google's quantum processor tackled a random sampling problem - that is, **checking that a set of numbers has a truly random distribution**. This is very difficult for a traditional computer when there are a lot of numbers involved.

![Google's Sycamore. Credits - Google Images](../assets/images/sycamore.jpeg?raw=true)

Google is said to have used a 54-qubit processor, *Sycamore*. Although one of its qubits didn't work, the remaining 53 were [quantum entangled](https://en.wikipedia.org/wiki/Quantum_entanglement) with one another and used to generate a set of binary digits and check their distribution was truly random. The paper calculates the task would have taken Summit, the world's best supercomputer, 10,000 years - but Sycamore did it in 3 minutes and 20 seconds.

---

### **What lies ahead?**
The quantum supremacy milestone allegedly achieved by Google is a pivotal step in the quest for practical quantum computers. As explained by John Preskill recently -

>> I thought it would be useful to have a word for the era that is now dawning, so [I recently made one up](https://arxiv.org/pdf/1801.00862.pdf): NISQ. (It rhymes with risk.) This stands for "noisy intermediate-scale quantum." Here "intermediate-scale" refers to the size of quantum computers that are now becoming available: potentially large enough to perform certain highly specialized tasks beyond the reach of today's supercomputers. "Noisy" emphasizes that we have imperfect control over the qubits, resulting in small errors that accumulate over time; if we attempt too long a computation, we're not likely to get the right answer.

The recent achievement by the Google team bolsters our confidence that quantum computing is merely really, really hard. If that's true, a plethora of quantum technologies are likely to blossom in the decades ahead.

---

### **A possible application in Cryptography**
A question critics raise is how the use of quantum computing and its ability to break encryption codes will impact online banking. Breaking banking grade encryption is far away. Scott Aaronson, a theoretical computer scientist who has written on Google's feat, opines that current encryption standards would require a quantum computer to have "several thousand logical qubits" working in tandem perfectly.

It requires millions of qubits of the kind that powers Sycamore to make 'logical qubits' and the 53 at Sycamore's disposal does not quite cut the ice. However, there are other approaches to designing quantum computers and with it there may be cleverer ways to solve problems using them. Moreover, if technological breakthroughs were to pose a real threat to banking or financial operations, it is likely that banks will harness quantum computers themselves.

Theoretically, quantum computers can successfully sift through the near-infinite combinations of public key cryptography, a system which uses two keys for decryption. Data encryption algorithms, such as RSA that is used in payment gateways, have been theoretically shown to be broken by tests involving [Shor's algorithm](https://anandsoni.in/shor/) running on quantum computers.

While the intractability of modern cryptography is a cause of great civilisational triumph, could the dawn of quantum supremacy be the undoing of society since almost all facets of life, from communication to commerce, are now conducted online?

This also calls for developing quantum-resistant (or post-quantum) crypto-algorithms which is an ongoing and futuristic area of mathematical research.

---

*Credits-*
1. https://www.quantamagazine.org/john-preskill-explains-quantum-supremacy-20191002/
2. https://www.thehindu.com/sci-tech/technology/what-quantum-computing-means-for-your-bank-accounts-and-smartphones/article23791602.ece
3. https://www.thehindu.com/sci-tech/technology/what-is-quantum-supremacy/article29543857.ece
4. https://theconversation.com/how-quantum-mechanics-can-change-computing-80995
5. https://www.history.com/this-day-in-history/the-birth-of-quantum-theory
6. https://www.livescience.com/33816-quantum-mechanics-explanation.html
7. https://www.wikipedia.org/
