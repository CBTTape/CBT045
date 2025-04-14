# CBT045
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. 
Due to amazing work by Alison Zhang and Jake Choi repos are no longer deleted.

```
//***FILE 045 IS AN ENHANCEMENT TO THE YALE COMPARE PROGRAM THAT IS *   FILE 045
//*       IN FILE 226 OF THIS TAPE.  THE PURPOSE OF THIS CODE IT TO *   FILE 045
//*       ALLOW THE COMPARE PGM TO PROCESS TWO PDS FILES RATHER     *   FILE 045
//*       THAN TWO SEQUENTIAL FILES. THE PROGRAM IS SELF CONTAINED. *   FILE 045
//*       SIMPLY ASSEMBLE AND LINK AND IT'S READY TO USE.           *   FILE 045
//*       ADDITIONAL INFORMATION ON HOW TO USE THE PROGRAM IS       *   FILE 045
//*       CONTAINED AS COMMENTS AT THE BEGINNING OF THE CODE        *   FILE 045
//*       ITSELF.  ALSO INCLUDED IS THE JES2 SOURCE COMPARE SYSTEM. *   FILE 045
//*                                                                 *   FILE 045
//*        COMPONENTS OF THIS FILE :                                *   FILE 045
//*             $$DOC    - DOCUMENTATION OF THE JES2 COMPARE SYSTEM *   FILE 045
//*             PDSCMPR  - ORIGINAL PDS COMPARE PROGRAM             *   FILE 045
//*                                                                 *   FILE 045
//*        JES2 SOURCE COMPARE SYSTEM                               *   FILE 045
//*             JES2CMPR - AN ASSEMBLY LANGUAGE PROGRAM THAT        *   FILE 045
//*                        IS A MODIFICATION OF THE PDSCMPR         *   FILE 045
//*                        PROGRAM.  THIS PROGRAM CREATES A         *   FILE 045
//*                        PDS THAT CONTAINS ALL OF THE             *   FILE 045
//*                        CHANGES BETWEEN TWO RELEASES.            *   FILE 045
//*             JES2LIST - AN ASSEMBLY LANGUAGE PROGRAM THAT        *   FILE 045
//*                        READS THE ABOVE PDS,  THE SYSPRINT       *   FILE 045
//*                        OUTPUT FROM THE ASSEMBLER AND            *   FILE 045
//*                        PRINTS A NEW ASSEMBLY LISTING            *   FILE 045
//*                        SHOWING WERE CHANGES HAVE                *   FILE 045
//*                        OCCURRED                                 *   FILE 045
//*             CMPRPDS  - A JCL STREAM THAT EXECUTES JES2CMPR      *   FILE 045
//*             JES2ASM2 - A PROC THAT EXECUTES                     *   FILE 045
//*                        THE ASSEMBLER AND THEN JES2LIST TO       *   FILE 045
//*                        CREATE THE POST ASSEMBLY LISTING         *   FILE 045
//*             ASM88888 - A JCL STREAM THAT ASSEMBLES ALL OF       *   FILE 045
//*                        THE JES2 MODULES                         *   FILE 045
//*           THIS FILE IN IS IEBUPDTE SYSIN FORMAT                 *   FILE 045
//*                                                                 *   FILE 045
```
