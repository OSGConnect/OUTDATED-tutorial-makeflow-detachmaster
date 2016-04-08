
[TOC]
 
## Overview
It is okay to run Makeflow on the terminal when jobs complete in few minutes.  What if you want to run many jobs
that may run for several days and weeks. If you log out from the submit node, the master process will be killed.
Since the master process keeps track of the workers that are distributed on OSG machines, you need to re-submit
Makeflow.




