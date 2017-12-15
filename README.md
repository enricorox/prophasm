# ProPhyle Assembler

[![Build Status](https://travis-ci.org/prophyle/prophyle_assembler.svg?branch=master)](https://travis-ci.org/prophyle/prophyle_assembler)


## Prerequisities

* GCC 4.8+ or equivalent
* ZLib


## Getting started

```
git clone https://github.com/prophyle/prophyle_assembler
cd prophyle_assembler && make -j
./prophyle_assembler -k 15 -i tests/test1.fa -i tests/test2.fa -o _out1.fa -o _out2.fa -x _intersect.fa -s _stats.tsv
```

## Algorithm


<img alt="Greedy assembly" src="figures/greedy_assembly.png" height="150px" width="540px" /><img alt="Subtraction of k-mer sets" src="figures/subtraction.png" height="180px" width="355px" />


## Issues

Please use [Github issues](https://github.com/prophyle/prophyle_assembler/issues).


## Changelog

See [Releases](https://github.com/prophyle/prophyle_assembler/releases).


## Licence

[MIT](https://github.com/prophyle/prophyle_assembler/blob/master/LICENSE)


## Author

Karel Brinda \<kbrinda@hsph.harvard.edu\>
