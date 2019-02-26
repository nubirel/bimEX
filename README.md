# bimEX
## *bim*etric 3+1 *E*xact *C*omputation*s*
### citation to paper

bimEX is a [Mathematica](https://www.wolfram.com/mathematica/) package making use of [xAct](http://www.xact.es/). Its goal is to provide a ready-to-use working framework in which one can manipulate the abstract bimetric equations in the 3+1 formalism, and compute them in any desired ansatz.

### Getting started

To use bimEX, download the file bimEX.m and load it into a Mathematica notebook as,

`<<"<path>/bimEX.m"`

This repository also includes

- The source file bimEX.nb
- The working example bimEX_Working_Example.nb
- Two notebooks bimEX_Decomposition_Lists_Loader.nb and bimEX_Decomposition_xAct_Loader, which are complementary to the working example
- Two packages Decomposition_Lists.m and Decomposition_xAct.m, generated by bimEX_Working_Example.nb.
- The file LICENSE.md
- The file contributing.md

The notebook bimEX_Decomposition_Lists_Loader.nb loads the file Decomposition_Lists.m, whereas the notebook bimEX_Decomposition_xAct_Loader loads the file Decomposition_xAct.m.

### Prerequisites

To run bimEX, you need to install Mathematica and the xAct bundle.

### Documentation

The documentation is provided in the form of **Usage messages** in Mathematica. They are accessible by typing

`?<name_of_function_or_option>`

in the Mathematica notebook. We refer to the associated paper.

### Testing the package

To test the package, follows the following instructions,

- Put the files bimEX.m and the notebooks bimEX_Working_Example.nb, bimEX_Decomposition_Lists_Loader.nb and bimEX_Decomposition_xAct_Loader in the same folder
- Open bimEX_Working_Example.nb and evaluate the notebook. This generates the two .m files Decomposition_Lists.m and Decomposition_xAct.m
- Open bimEX_Decomposition_Lists_Loader.nb and bimEX_Decomposition_xAct_Loader in separate Mathematica's kernels, and evaluate them.

### Contributing

Please see the file contributing.md.

### Author

- Francesco Torsello

### License

GNU GPL-3.0

A copy of this license is included in the file LICENSE.md.

### Acknowledgments

It is a pleasure to thank Mikica Kocic for all the support and help he gave me during the development of bimEX.
