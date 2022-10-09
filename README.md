# generate-flow-shop-instances
 Program to generate the 120 flow shop instances proposed by
 Taillard, E.D.: "Benchmarks for basic scheduling problems",
 EJOR vol. 64, pp. 278-285, 1993
 
 Originaly written by Taillard in PASCAL, re-written in C by
 Dirk C. Mattfeld, University of Bremen <dirk@uni-bremen.de> and
 Rob J.M. Vaessens, Eindhoven University of Technology <robv@win.tue.nl
 Last update : 2/7/1996.

 UNIX compile: cc -o fsp_gen fsp_gen.c -lm

 Tested on the machines/systems/compilers listed below.
 DEC 5000    Ultrix 4.2    cc
 SUN 10      Solaris 2     cc
 IBM 6000    AIX 3.x       xlc
 Atari ST    TOS           pure c
 IBM-PC      DOS 6.2       MS-C 
 IBM-PC      Linux         gcc 

 Care should be taken on 64 bit machines (e.g. Cray). There, 
 'long' and 'double' contain 128 bit. In this case replace all 
 'long' and 'double' with the appropriate 64 bit type. 
  
     Verification file 'ta001' (if VERIFY == 1 and FIRMACIND == 1)

     20 5
     1 54 2 79 3 16 4 66 5 58 
     1 83 2 3 3 89 4 58 5 56 
     1 15 2 11 3 49 4 31 5 20 
     1 71 2 99 3 15 4 68 5 85 
     1 77 2 56 3 89 4 78 5 53 
     1 36 2 70 3 45 4 91 5 35 
     1 53 2 99 3 60 4 13 5 53 
     1 38 2 60 3 23 4 59 5 41 
     1 27 2 5 3 57 4 49 5 69 
     1 87 2 56 3 64 4 85 5 13 
     1 76 2 3 3 7 4 85 5 86 
     1 91 2 61 3 1 4 9 5 72 
     1 14 2 73 3 63 4 39 5 8 
     1 29 2 75 3 41 4 41 5 49 
     1 12 2 47 3 63 4 56 5 47 
     1 77 2 14 3 47 4 40 5 87 
     1 32 2 21 3 26 4 54 5 58 
     1 87 2 86 3 75 4 77 5 18 
     1 68 2 5 3 77 4 51 5 68 
     1 94 2 77 3 40 4 31 5 28 