**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/03_BCC/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../RefCV.ec3U4r.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../RefCV.2.11.0-dev.so ../../RefCV.cpp

[pkrvmq0rgcvqdmg:11078] *** Process received signal ***
[pkrvmq0rgcvqdmg:11078] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:11078] Signal code:  (-6)
[pkrvmq0rgcvqdmg:11078] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7faca3445330]
[pkrvmq0rgcvqdmg:11078] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7faca349eb2c]
[pkrvmq0rgcvqdmg:11078] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7faca344527e]
[pkrvmq0rgcvqdmg:11078] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7faca34288ff]
[pkrvmq0rgcvqdmg:11078] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7faca38a5ff5]
[pkrvmq0rgcvqdmg:11078] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7faca38bb0da]
[pkrvmq0rgcvqdmg:11078] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7faca38a5a55]
[pkrvmq0rgcvqdmg:11078] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7faca38a5a6f]
[pkrvmq0rgcvqdmg:11078] [ 8] plumed_master(+0x146dd)[0x56386c3116dd]
[pkrvmq0rgcvqdmg:11078] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7faca342a1ca]
[pkrvmq0rgcvqdmg:11078] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7faca342a28b]
[pkrvmq0rgcvqdmg:11078] [11] plumed_master(+0x15365)[0x56386c312365]
[pkrvmq0rgcvqdmg:11078] *** End of error message ***
</pre>
{% endraw %}
