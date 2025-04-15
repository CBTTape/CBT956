# CBT956
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. 
Due to amazing work by Alison Zhang and Jake Choi repos are no longer deleted.

```
//***FILE 956 is from Steve Myers, and contains several of his      *   FILE 956
//*           programs.  Currently included are programs:           *   FILE 956
//*           DSREF, ICOPY, DASDSUM and SCAN118.                    *   FILE 956
//*                                                                 *   FILE 956
//*       SCAN118 was modified by Fred Camp and Paul Lemons to      *   FILE 956
//*       add the port numbers that the users are connecting to.    *   FILE 956
//*       This was needed because their installation had been       *   FILE 956
//*       migrating from non-secured to secured ports, and they     *   FILE 956
//*       needed to check which users hadn't been migrated yet.     *   FILE 956
//*       (See member $$NOTE01)                                     *   FILE 956
//*                                                                 *   FILE 956
//*           email:  Paul.Lemons@Vericast.com                      *   FILE 956
//*                                                                 *   FILE 956
//*           email:  Fred.Camp@vericast.com                        *   FILE 956
//*                                                                 *   FILE 956
//*       The DSREF program produces reports showing dataset        *   FILE 956
//*       access by userid, using SMF 14, 15 and 30 records.        *   FILE 956
//*                                                                 *   FILE 956
//*           email:  mvsprog@yahoo.com  (possibly deceased)        *   FILE 956
//*                                                                 *   FILE 956
//*       DSREF produces three reports:                             *   FILE 956
//*                                                                 *   FILE 956
//*        - Data set to userid                                     *   FILE 956
//*                                                                 *   FILE 956
//*          data set name                                          *   FILE 956
//*           user user ... user                                    *   FILE 956
//*                                                                 *   FILE 956
//*        - User to data set                                       *   FILE 956
//*                                                                 *   FILE 956
//*          user                                                   *   FILE 956
//*           data set  data set ... data set                       *   FILE 956
//*                                                                 *   FILE 956
//*        - Optional list of jobs in the data                      *   FILE 956
//*                                                                 *   FILE 956
//*       For additional information, see member $DOC.              *   FILE 956
//*                                                                 *   FILE 956
//*       DISKLST is another VTOC mapping program, which can        *   FILE 956
//*       also map multiple volumes very quickly.                   *   FILE 956
//*                                                                 *   FILE 956
//*       The ICOPY program, copies disk datasets using EXCP,       *   FILE 956
//*       and copies the tracks of the dataset.  ICOPY, and         *   FILE 956
//*       instructions for its use, are included here.  ICOPY is    *   FILE 956
//*       especially handy in copying partitioned datasets.         *   FILE 956
//*       ICOPY DOES A "TRACK COPY", AS OPPOSED TO A "MEMBER        *   FILE 956
//*       COPY", which IEBCOPY does.  Sometimes this approach       *   FILE 956
//*       is useful, AS IT PRESERVES DELETED PDS MEMBERS.           *   FILE 956
//*                                                                 *   FILE 956
//*       The DASDSUM program takes a PARM prefix of the partial    *   FILE 956
//*       volser (a group of volsers in your configuration),        *   FILE 956
//*       and tells you how many datasets are on them, by dataset   *   FILE 956
//*       prefix.  So, for example, you can know what kind of       *   FILE 956
//*       datasets are on your work packs.                          *   FILE 956
//*                                                                 *   FILE 956
//*       The SCAN118 program is a batch program which shows TSO    *   FILE 956
//*       and TCPIP sessions for TSO, in great detail.  The info    *   FILE 956
//*       is derived from SMF Type 118 records, which you have to   *   FILE 956
//*       capture.  But the reward is worth it.!!  This member is   *   FILE 956
//*       in TSO XMIT format, and contains all the materials to     *   FILE 956
//*       install and test the program (except for capturing the    *   FILE 956
//*       SMF 118 records).                                         *   FILE 956
//*                                                                 *   FILE 956
```
