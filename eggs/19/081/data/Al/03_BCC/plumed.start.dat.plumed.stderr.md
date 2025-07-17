**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/03_BCC/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../RefCV.arjoIV.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../RefCV.2.10b.so ../../RefCV.cpp

[pkrvmq0rgcvqdmg:11131] *** Process received signal ***
[pkrvmq0rgcvqdmg:11131] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:11131] Signal code:  (-6)
[pkrvmq0rgcvqdmg:11131] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd7bd245330]
[pkrvmq0rgcvqdmg:11131] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd7bd29eb2c]
[pkrvmq0rgcvqdmg:11131] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd7bd24527e]
[pkrvmq0rgcvqdmg:11131] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd7bd2288ff]
[pkrvmq0rgcvqdmg:11131] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd7bd6a5ff5]
[pkrvmq0rgcvqdmg:11131] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd7bd6bb0da]
[pkrvmq0rgcvqdmg:11131] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd7bd6a5a55]
[pkrvmq0rgcvqdmg:11131] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd7bd6a5a6f]
[pkrvmq0rgcvqdmg:11131] [ 8] plumed(+0x146dd)[0x55ce8debf6dd]
[pkrvmq0rgcvqdmg:11131] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd7bd22a1ca]
[pkrvmq0rgcvqdmg:11131] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd7bd22a28b]
[pkrvmq0rgcvqdmg:11131] [11] plumed(+0x15365)[0x55ce8dec0365]
[pkrvmq0rgcvqdmg:11131] *** End of error message ***
</pre>
{% endraw %}
