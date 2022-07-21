# Outline

## First hour

  * Introductions [5 minutes]
    * Ask participants to say two sentences about themselves and two sentences about
      their level of Python experience and any previous experience with quantum
      physics.
  * Overview [5 minutes]
    * What we are going to cover during the tutorial
  * Short meditation [2 minutes]
    * Letting going of all the other things happening.
    * Thinking about why you are here and what you'd like to get out of the tutorial.
  * Overview of real neutral atom devices [15 minutes]
    * What components make up the apparatus?
    * How are the atoms held in place?
    * How are the atoms moved into place?
    * How are the atoms controlled?
    * How are the states of the atoms measured?
  * Opening Python and importing QuTiP [5 minutes]
    * What is QuTiP?
  * Describing a single neutral atom [15 minutes]
    * Look at the relevant energy states
    * Linking the physical state with its simulate representation
    * Building a description of the atom in QuTiP
    * Visualizing the state of the atom on the Bloch sphere
    * Playing with a single atom in QuTiP
  * Break

## Second hour

  * Describing multiple neutral atoms [20 minutes]
    * Tensor products in QuTiP
    * Comparison to composition of classical systems
    * Partial traces and density matrices using QuTiP
    * Visualizing multi-atom states
    * Visualizing entanglement
  * Understanding the evolution of quantum systems [20 minutes]
    * Understanding the Schrödinger equation
    * Understanding the role of the Hamiltonian and the energy of a system
    * Understanding the role of the phase in the system evolution
    * Using QuTiP to evolve a quantum system in time
  * Playing with different Hamiltonians [10 minutes]
    * Eigenvalues of the Hamiltonian
    * Scaling the energy
    * Changing the differences between energies
  * Break

## Third hour

  * Recap of where we are [5 minutes]
    * Can code multi-atom states
    * Can can evolve states in time
    * All the ingredients we need to start controlling the states
  * Controlling a quantum system [20 minutes]
    * Time-dependent Hamiltonians
    * Adding driving to the Hamiltonian
    * Visualising the evolution of time-dependent systems with QuTiP
  * Rotating the state of a single atom [15 minutes]
    * Defining the control pulse
    * Solving for the state of the atom as a function of time
    * Visualising the evolution of the state
  * Understanding the Rydberg blockade [10 minutes]
    * Describing the mechanism of interaction between neighbouring atoms
    * Demonstrating how this can be used to implement a two-atom logic gate
  * Break

## Fourth hour

  * CNOT gate [15 minutes]
    * Implementing a CNOT gate using control pulses and the Rydberg blockade
    * Visualising the evolution of the states of the atoms
  * Coupling the system to the environment [15 minutes]
    * Describing the environment
    * Visualising the evolution including decoherence
  * Bringing everything together [15 minutes]
    * Tying the building blocks we've built into a simulator of 4 neutral atoms
  * Wrapping up [15 minutes]
    * Questions
    * Discussion
