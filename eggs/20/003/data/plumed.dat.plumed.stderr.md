**Project ID:** [plumID:20.003]({{ '/' | absolute_url }}eggs/20/003/)  
Stderr for source:  plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
TD_TS-target-plumed2.6.HJ7a6I.cpp:23:10: fatal error: TargetDistribution.h: No such file or directory
23 | #include "TargetDistribution.h"
|          ^~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1292) void PLMD::PlumedMain::load(const string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./TD_TS-target-plumed2.6.2.10b.so TD_TS-target-plumed2.6.cpp

[fv-az585-767:09185] *** Process received signal ***
[fv-az585-767:09185] Signal: Aborted (6)
[fv-az585-767:09185] Signal code:  (-6)
[fv-az585-767:09185] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f7859442520]
[fv-az585-767:09185] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f78594969fc]
[fv-az585-767:09185] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f7859442476]
[fv-az585-767:09185] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f78594287f3]
[fv-az585-767:09185] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f78598a2b9e]
[fv-az585-767:09185] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f78598ae20c]
[fv-az585-767:09185] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f78598ae277]
[fv-az585-767:09185] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f78598ae52b]
[fv-az585-767:09185] [ 8] plumed(+0x14254)[0x562bc382f254]
[fv-az585-767:09185] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f7859429d90]
[fv-az585-767:09185] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f7859429e40]
[fv-az585-767:09185] [11] plumed(+0x14eb5)[0x562bc382feb5]
[fv-az585-767:09185] *** End of error message ***
</pre>
{% endraw %}
