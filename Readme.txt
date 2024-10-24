/******************************************************************
        Accelerated Re-visit CU-coding (ARC) Software Manual
******************************************************************/
1. Macro Description
2. Modified source code files
3. Configuration files

****************************************************************
1. Macro Description
ARC                           //0 : hpm15.4, 1 : hpm15.4 with Accelerated Re-visit CU-coding (ARC) integrated
ARC_IBC                  //0 : ARC for IBC off, 1 : ARC for IBC on
ARC_SP                    //0 : ARC for SP off, 1 : ARC for SP on
ARC_Intra                 //0 : ARC for Intra off, 1 : ARC for Intra on
ARC_ANAL             //0 : SCC search space analysis (S and Ssimd) off, 1 : SCC search space analysis (S and Ssimd) on
ARC_PLUS             //0 : Additional speedup (ARC+) off, 1 : Additional speedup (ARC+) on 

*******************************************************************
2. Modified source code files
2.1  ARC
// The following source code files have been modified for ARC:
enc_pibc.c
enc_ibc_hashmap.cpp
enc_def.h
com_usp.h
enc_sp.h
enc_sp.cpp
enc_pintra.c
enc.c
enc_mode.c

2.2  ARC_ANAL
// The following source code files have been modified for SCC search space analysis:
app_encoder.c
enc.c
enc_pibc.c
com_usp.h
enc_sp.cpp
enc_pintra.c

*******************************************************************
3. Configuration files

   The default configuration files to run the reference software are provided in the directory "cfg".
   These cfg files contain explanatory comments for each parameter.
   
 *******************************************************************  
 
Notes: Please contact the author at 1950970404@qq.com for the password to access the source code, executable files, etc.

The AVS datasets (test sequences) can be downloaded from https://pan.baidu.com/s/19I9t1SyQhG6JtzcLVdNuBg?pwd=6789 
The HEVC datasets (test sequences) can be downloaded from https://pan.baidu.com/s/1CJ_uS6v6t8v4H74bAbj6SA?pwd=6789  
The extraction code for the above dataset download is 6789

  
