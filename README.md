# CBT498
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. 
Due to amazing work by Alison Zhang and Jake Choi repos are no longer deleted.

```
//***FILE 498 is from Craig Schneiderwent and contains a match      *   FILE 498
//*           merge program in Assembler, to combine two sequential *   FILE 498
//*           files.                                                *   FILE 498
//*                                                                 *   FILE 498
//*           email:  cschneidpublic@yahoo.com                      *   FILE 498
//*                   include MTCHMRG in Subject: line              *   FILE 498
//*                                                                 *   FILE 498
//*  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  *   FILE 498
//*                                                                 *   FILE 498
//*        $DOC     Documentation for MTCHMRG utility               *   FILE 498
//*        $README  This member                                     *   FILE 498
//*        JRETURND Standard exit logic macro                       *   FILE 498
//*        JSAVED   Standard entry logic macro                      *   FILE 498
//*        MTCHMRG  Source code to the MTCHMRG utility              *   FILE 498
//*        REGISTER Standard register equates macro                 *   FILE 498
//*        TESTDATA Test materials pds in TSO XMIT format           *   FILE 498
//*                                                                 *   FILE 498
//*  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  *   FILE 498
//*                                                                 *   FILE 498
//*           PROGRAM NAME: MTCHMRG                                 *   FILE 498
//*           AUTHOR: CRAIG SCHNEIDERWENT                           *   FILE 498
//*           Date:      16-DEC-1999                                *   FILE 498
//*           Updated:   06-Jan-2009                                *   FILE 498
//*           PURPOSE: MATCH MERGE TWO FILES                        *   FILE 498
//*                                                                 *   FILE 498
//*           KEY COMPARISON IS A CLC INSTRUCTION                   *   FILE 498
//*                                                                 *   FILE 498
//*           EXEC PGM=MTCHMRG,PARM='000120002300042'               *   FILE 498
//*                                  LLLLL1111122222                *   FILE 498
//*                                                                 *   FILE 498
//*           LLLLL = LENGTH OF KEY                                 *   FILE 498
//*           11111 = OFFSET OF KEY IN SYSUT1                       *   FILE 498
//*           22222 = OFFSET OF KEY IN SYSUT2                       *   FILE 498
//*                                                                 *   FILE 498
//*           ABOVE PARAMETER CAN ALSO BE SPECIFIED ON SYSIN        *   FILE 498
//*                                                                 *   FILE 498
//*           SYSUT3 WILL CONTAIN CONCATENATED MATCHING             *   FILE 498
//*                  SYSUT1 AND SYSUT2 RECORDS                      *   FILE 498
//*           SYSUT4 WILL CONTAIN UNMATCHED SYSUT1 RECORDS          *   FILE 498
//*           SYSUT5 WILL CONTAIN UNMATCHED SYSUT2 RECORDS          *   FILE 498
//*           SYSUT6 WILL CONTAIN MATCHED SYSUT1 RECORDS            *   FILE 498
//*           SYSUT7 WILL CONTAIN MATCHED SYSUT2 RECORDS            *   FILE 498
//*                                                                 *   FILE 498
```
