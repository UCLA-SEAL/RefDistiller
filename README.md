# RefDistiller
Refactoring Inspection Support for Manual Refactoring Edits (TSE 2017)
https://sites.google.com/site/refdistiller/


## Summary

Manual refactoring edits are error prone, as refactoring requires developers to coordinate related transformations and understand the complex inter-relationship between affected files, variables, and methods. We propose RefDistiller, an approach for improving detection of manual refactoring anomalies by two combined strategies. First, it uses a predefined template to identify potential missed refactoring edits---omission anomalies. Second, it leverages an automated refactoring engine to separate behavior-preserving edits from behavior-modifying edits---commission anomalies. We evaluate its effectiveness on a data set with one hundred manual refactoring bugs. These bugs are hard to detect because they do not produce any compilation errors nor are caught by the pre- and post-condition checking of many existing refactoring engines. RefDistiller is able to identify 97% of the erroneous edits, of which 24% are not detected by the given test suites.

## Team 
This project is developed by Professor [Miryung Kim](http://web.cs.ucla.edu/~miryung/)'s group. 
If you encounter any problems, please open an issue or feel free to contact us:

[Everton](https://scholar.google.com/citations?user=K3EKWwoAAAAJ&hl=pt-BR): Researcher at Federal University of Campina Grande, everton@computacao.ufcg.edu.br;

[Myoungkyu](https://sites.google.com/site/mksongprofile): Assistant Professor at UNO, myoungkyu@unomaha.edu;

## How to cite 
Please refer to our TSE'17 paper, [Refactoring Inspection Support for Manual Refactoring Edits](https://ieeexplore.ieee.org/document/7874212) for more details. 
### Bibtex  

@ARTICLE{RefDistiller,
  author={Alves, Everton L. G. and Song, Myoungkyu and Massoni, Tiago and Machado, Patrícia D. L. and Kim, Miryung},
  journal={IEEE Transactions on Software Engineering}, 
  title={Refactoring Inspection Support for Manual Refactoring Edits}, 
  year={2018},
  volume={44},
  number={4},
  pages={365-383},
  doi={10.1109/TSE.2017.2679742}}


## How to use this tool

Pls visit our [website](https://sites.google.com/site/refdistiller/) for detail

## Video

https://www.youtube.com/watch?v=0Iseoc5HRpU

## FAQ 
