# JoinFACETS2maf_example

Usage:

    ./facets_and_ccf_to_maf_md.R example.maf facets_files.txt

Alternatively, use the cmo python package:

    cmo_facets --version default maf -m example.maf -f facets_files.txt

1. download CMO package with maf annotation eg. https://github.com/mskcc/cmo
2. install for your user with `setup.py install --user`
1. add `~/.local/bin` to your path if you haven't already done this for a previous cmo install
1. you should now have `cmo_facets` available at the command line
2. at the moment use the default version of the facets wrapping code

Output:

Creates annotated maf file example.ann.maf
