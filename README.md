# CBT436
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. GitHub repos will be deleted and created during this period...

```
//***FILE 436 from Glenn Jones of Aramco in Saudi Arabia, and       *   FILE 436
//*           contains a version of the COMPCODE program, which     *   FILE 436
//*           notifies users of completion code information for     *   FILE 436
//*           jobs.  This version has been modified to even send    *   FILE 436
//*           emails to notify a user located elsewhere, of a job   *   FILE 436
//*           completion on the MVS system.                         *   FILE 436
//*                                                                 *   FILE 436
//*           Glenn Jones                                           *   FILE 436
//*           Saudi Aramco, Dhahran, Saudi Arabia                   *   FILE 436
//*           email: jonesgk@aramco.com.sa                          *   FILE 436
//*                  g_k_j@yahoo.com                                *   FILE 436
//*                                                                 *   FILE 436
//*      I have modified some code which may be of interest to      *   FILE 436
//*      you or others.  Whenever I'm on the computer, I            *   FILE 436
//*      generally have an email session going (either work or      *   FILE 436
//*      home). Sometimes my tasks do not require mainframe         *   FILE 436
//*      access.                                                    *   FILE 436
//*                                                                 *   FILE 436
//*      Rather than continually logging on/swapping to a           *   FILE 436
//*      mainframe session, I modified a copy of the public         *   FILE 436
//*      COMPCODE program to optionally do e-mail notifications.    *   FILE 436
//*      This COMPCODE program is in production jobs, started       *   FILE 436
//*      tasks, as well as batch work that is important enough      *   FILE 436
//*      for me to know about if a problem occurs.                  *   FILE 436
//*                                                                 *   FILE 436
//*      Another neat feature is when I go out of town, I make a    *   FILE 436
//*      simple update to the notify dataset for the person who     *   FILE 436
//*      will be handling the problems in my absence. Since all     *   FILE 436
//*      my jobs & STC's have this notify step, one simple          *   FILE 436
//*      update is immediately in effect for everything.            *   FILE 436
//*                                                                 *   FILE 436
//*      I also made the code Y2K friendly, and changed it to       *   FILE 436
//*      print out the steps real termination code, not just the    *   FILE 436
//*      highest recorded in the JCT.  This code is currently       *   FILE 436
//*      running on OS/390 V2R5 without any problems. The email     *   FILE 436
//*      portion uses IBM's MVS SMTP, and the program requires      *   FILE 436
//*      simple modifications for use at your installation.         *   FILE 436
//*                                                                 *   FILE 436
```
