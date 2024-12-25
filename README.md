# CHStone

A Suite of Benchmark Programs for C-based High-Level Synthesis

## Introduction

The CHStone benchmark suite has been developed for C-based high-level synthesis (HLS). The CHStone benchmark suite selected programs of various application domains, some of which originally belong to other benchmark suites. CHStone has several key features described as follows:

    - CHStone consists of 12 programs which are selected from various application domains such as arithmetic, media processing, security and microprocessor.
    - The programs in CHStone are relatively large compared with the ones which have been widely used in the past literature on HLS.
    - The CHStone benchmark programs are written in the standard C language, and can be compiled and executed on a host computer.
    - In our experimental environment, we used GCC 3.4.4 on Windows XP.
    - All the programs in CHStone have been confirmed to be synthesizable by a state-of-the-art HLS tool.
    - In our experimental environment, we used eXCite from YXI.
    - CHStone is very easy to use since test vectors are self-contained and no external library is necessary.

## List of Benchmark Programs

The CHStone suite includes the following programs. Source-level characteristics and synthesis results can be found in [our paper](https://doi.org/10.2197/ipsjjip.17.242). 

| **Program**  | **Design Description** | **Source** |
| ------------- | ------------- | ------------- |
| DFADD  | Double-precision floating-point addition  | SoftFloat (Ref 1) |
| DFMUL  | Double-precision floating-point multiplication  | SoftFloat (Ref 1) |
| DFDIV  | Double-precision floating-point division  | SoftFloat (Ref 1) |
| DFSIN  | Sine function for double-precision floating-point numbers  | CHStone group, SoftFloat (Ref 1) |
| MIPS 	 | Simplified MIPS processor | CHStone group |
| ADPCM  | Adaptive differential pulse code modulation decoder and encoder | SNU (Ref 2) |
| GSM    | Linear predictive coding analysis of global system for mobile communications | MediaBench (Ref 3) |
| JPEG   | JPEG image decompression | The Portable Video Research Group (Ref 4), CHStone group |
| MOTION | Motion vector decoding of the MPEG-2 | MediaBench (Ref 3) |
| AES    | Advanced encryption standard | AILab (Ref 5) |
| BLOWFISH | Data encryption standard | MiBench (Ref 6) |
| SHA    | Secure hash algorithm | MiBench (Ref 6) |

Ref 1.) [SoftFloat](http://www.jhauser.us/arithmetic/SoftFloat.html)  
Ref 2.) [SNU Real-time Benchmarks](http://archi.snu.ac.kr/realtime/benchmark/)  
Ref 3.) C. Lee, M. Potkonjak, and W. H. Mangione-Smith, "MediaBench: A tool for evaluating and synthesizing multimedia and communicatons systems," MICRO, 1997.  
Ref 4.) A. C. Hung, "PVRG-JPEG CODEC 1.1," Technical Report, Stanford University, 1993.  
Ref 5.) [AILab](http://www-ailab.elcom.nitech.ac.jp/)  
Re6 6.) M. R. Guthaus, J. S. Ringenberg, and D. Ernst, "MiBench: A free, commercially representative embedded benchmark suite," WWC, 2001.  

##Publication

Please cite the following paper when you publish a paper where CHStone is used.

Yuko Hara, Hiroyuki Tomiyama, Shinya Honda and Hiroaki Takada,   
["Proposal and Quantitative Analysis of the CHStone Benchmark Program Suite for Practical C-based High-level Synthesis"](https://doi.org/10.2197/ipsjjip.17.242)  
Journal of Information Processing, Vol. 17, pp.242-254, (2009).  

## Links

Interesting, usefull high-level synthesis tools.

- [C-to-verilog.com](http://www.c-to-verilog.com/index.html) - a free on-line C to Verilog compiler
- [LegUp](http://www.legup.org/) - an open source high-level synthesis framework
- [PandA](http://panda.dei.polimi.it/) - an open source HW-SW codesign framework, including high-level synthesis and so on

