# Minimal Message Passing Network

A repository to demonstrate fitting a minimal message-passing network.
Intended as a teaching example more than a high-quality implemetnation.

The code in these libraries is close to what is used in early versions of [nfp](https://github.com/NREL/nfp).
If you are looking to do more state-of-the art deep learning on molecules, I would recommend learning a package
like [nfp](https://github.com/NREL/nfp), [megnet](https://github.com/materialsvirtuallab/megnet),
[schnetpack](https://schnetpack.readthedocs.io/en/stable/), or [deepchem](https://deepchem.io/).

## Installation

The module requirements are described in [environment.yml](./environment.yml) and can be installed with:

```bash
conda env create --file environment.yml --force
```

## Layout

The first notebook must be run to save the data in a protobuf format accessible by later notebooks.

Then you can either run the "small neural network" to get a minimal (117-parameter) MPNN for comparison,
or the "large model" to compare models on different material properties.
