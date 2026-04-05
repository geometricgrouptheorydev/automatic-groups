# Automatic Groups and Biautomatic Structures of Geometrizable 3 and 4-Manifolds

This repository contains my prize-winning research monograph on the intersection of **Geometric Group Theory**, **Formal Language Theory**, and **Differential Topology**. In particular,
this research investigates the existence of biautomatic structures within the fundamental groups of geometrizable 3-manifolds. Automatic groups are algebraic groups equipped with finite state automata for equality recognition and the group operation. Any group that satisfies a particular fellow travelling property is also automatic. Biautomaticity is a strengthening of automaticity that takes into account the inversion operation.

## Abstract

Automatic groups were introduced in the late eighties, as a generalization of group tables for finite groups to discrete infinite groups, forever linking the theory of regular languages to group theory. Automatic and biautomatic structures of a group are of various interest from an algorithmic and computational viewpoint; they provide methods for carrying computations to a wide class of interesting groups, including hyperbolic groups. Indeed, every automatic group has a solvable word problem and satisfies a quadratic Dehn function while every biautomatic group furthermore has a solvable conjugacy problem.

The first aim of this dissertation is to introduce the theory of regular languages, automatic, and biautomatic groups, including important closure properties. The second aim of this dissertation has to do with 3-manifold fundamental groups, the study of which is of great interest, as 3-manifolds are largely determined by their fundamental groups; in fact, every closed, irreducible, non-spherical 3-manifold is indeed uniquely determined by its fundamental group. Thurston's conjecture, proven by Perelman in 2003, permits us to decompose every closed 3-manifold into pieces admitting one of 8 maximal geometries. Similarly, there are 19 classes of maximal 4-dimensional geometries, and we shall determine which of these geometries admit biautomatic structures, though there are some open problems in the 4-dimensional case.

## Why This Matters?

Beyond the theoretical results, this work explores the bounds of computational decidability. Algorithmic problems such as the word and conjugacy problems are famously unsolvable in general. By proving a group is biautomatic, we provide a mathematical guarantee that the conjugacy problem is algorithmically solvable in polynomial time, which is a foundational requirement for robust system design. Establishing a relationship between abstract mathematical branches such as Differential Topology and the more readily applicable Formal Language Theory is also of importance, allowing systems to be designed to determine properties of geometric spaces computationally.

## Technical Communication

- **Cross-Domain Synthesis:** Bridging disparate fields into a cohesive 40-page technical document.
- **Information Hierarchy:** Utilizing a structured approach to define all the complex theoretical concepts and tools required to connect these fields together, including topics such as regular languages, automatic structures, group presentations, word metrics, group cohomology, hyperbolic geometry, geometrizable manifolds, and orbifolds. 
- **Visual Communication:** Diagrams of automata and commutative diagrams.

## Tools & Workflow

I wrote this monograph in LaTeX, the standard markup language for typesetting mathematics. When I add LaTeX support to my static site generator, this monograph will be hosted directly on the web and be part of the sample pages for that project.
