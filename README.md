# nmonchart

This program is a perl version of the most excellent shell [scripted implementation](http://nmon.sourceforge.net/pmwiki.php?n=Site.Nmonchart) written by Nigel Griffiths. The rewrite was just to address performance. The original implementation became quite consumptive for large files. As I was running it every 5 minutes through the day to give a semi-real-time view of performance, I needed something that would do so more efficiently. 

Syntax is ``nmonchart.pl < /nmondata/`hostname`_`date +\%y\%m\%d`*.nmon > `date +\%Y-\%m-\%d`.html``
