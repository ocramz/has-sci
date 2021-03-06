# Has-Sci

A collection of computational methods in science.

The aim of this libary is to utilise the powerful type system of haskell and its awesome expressivity to keep the underlying mathematics visible, while making extensive use of typeclasses to allow easy plugging of external objects, methods and numerical libraries.

Build and run using [stack](https://docs.haskellstack.org/en/stable/README/#how-to-install):
```
stack build
stack exec has-sci-physics-examples-exe [simulator]
```

## Simulators
* classical_electric_potential: (Default) Classical electric potential simulator.
* quantum_oscillation: Quantum oscillation simulator.
* classical_gravity: Classical gravity simulator.

For some simulators the initial simulation window may be tiny depending on the configuration. You can resize the window and use Ctrl + Drag-Down to zoom in or Ctrl + Drag-Up to zoom out.

You can change configuration of a simulator from its source module.