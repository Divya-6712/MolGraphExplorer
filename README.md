# MolGraphExplorer

MolGraphExplorer is a Julia-based chemoinformatics tool for analyzing molecular structures using graph theory.

The software represents molecules as graphs where atoms are nodes and chemical bonds are edges.

## Features

* Molecular graph construction
* Graph traversal algorithms

  * Breadth-First Search (BFS)
  * Depth-First Search (DFS)
* Graph visualization of molecules
* Computation of molecular graph properties

## Example Molecules

The demo supports several example molecules:

* Methane
* Ethane
* Benzene
* Ethanol

The program computes graph statistics such as number of atoms, bonds, atom degree distribution, and connected components. 

## Implementation

The software is implemented in Julia and uses adjacency lists to represent molecular graphs, allowing efficient traversal and connectivity analysis. 

## Usage

Run the demo program:

julia --project=. examples/demo.jl
