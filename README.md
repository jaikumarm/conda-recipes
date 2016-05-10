# conda-recipes
build and test recipes for conda

# usage
Example recipes for the conda build system.  Use

Build the local custom package:

    conda build theano

Install and use the local package

    conda install --use-local theano

Upload package to anaconda cloud

    anaconda login
    anaconda upload linux-64/theano-0.9.0.dev0-py35_0.tar.bz2

Install package from anaconda.org

    conda install -c jaikumarm theano=0.9.0.dev0


This is a personal repository.  For much more comprehensive list of recipes from the community look at  [conda/conda-recipes](https://github.com/conda/conda-recipes).

See http://conda.pydata.org/docs/building/build.html for information on how to make a recipe, or just look at the examples here.

This project (`conda-recipes`) is in the public domain.   Note that this statement does not reflect in any way, shape or form the licenses of the projects which are being built from these recipes.  For example, even though a project `foo` might have an MIT, Apache, or any other license, the recipe for project `foo` (within this repository) is public domain.
