# gmsh-tools
Package is build around the Python SDK for the GMSH 4.x. It provides high level interface,
dealing with several inconveniences of the gmsh-sdk:

- The geometric entities are Python objects not just IDs.
- Automatic synchronisation between geometry and gmsh module.
- Grouping of geometric entities.
- Assignment of the physical groups to the entities and propagation of this through the intersecton operations.
- Better interface to the Fields.
- Unified interface to GMSH options.

In addition to this form of GMSH geometry API we provide:

- heal_mesh - an agressive mesh optimizer (WIP)
- gmsh_io - simple interface to GMSH files
