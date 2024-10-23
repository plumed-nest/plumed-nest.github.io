**Project ID:** [plumID:20.003]({{ '/' | absolute_url }}eggs/20/003/)  
Stderr for source:  plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
TD_TS-target-plumed2.6.KYmBP7.cpp:23:10: fatal error: TargetDistribution.h: No such file or directory
23 | #include "TargetDistribution.h"
|          ^~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1292) void PLMD::PlumedMain::load(const string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./TD_TS-target-plumed2.6.2.11.0-dev.so TD_TS-target-plumed2.6.cpp

[fv-az585-767:09210] *** Process received signal ***
[fv-az585-767:09210] Signal: Aborted (6)
[fv-az585-767:09210] Signal code:  (-6)
[fv-az585-767:09210] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f3d00642520]
[fv-az585-767:09210] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f3d006969fc]
[fv-az585-767:09210] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f3d00642476]
[fv-az585-767:09210] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f3d006287f3]
[fv-az585-767:09210] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f3d00aa2b9e]
[fv-az585-767:09210] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f3d00aae20c]
[fv-az585-767:09210] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f3d00aae277]
[fv-az585-767:09210] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f3d00aae52b]
[fv-az585-767:09210] [ 8] plumed_master(+0x14254)[0x55a7800b5254]
[fv-az585-767:09210] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f3d00629d90]
[fv-az585-767:09210] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f3d00629e40]
[fv-az585-767:09210] [11] plumed_master(+0x14eb5)[0x55a7800b5eb5]
[fv-az585-767:09210] *** End of error message ***
</pre>
{% endraw %}
