**Project ID:** [plumID:20.003]({{ '/' | absolute_url }}eggs/20/003/)  
Stderr for source:  plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
TD_TS-target-plumed2.6.0BtGjE.cpp:23:10: fatal error: TargetDistribution.h: No such file or directory
23 | #include "TargetDistribution.h"
|          ^~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./TD_TS-target-plumed2.6.2.11.0-dev.so TD_TS-target-plumed2.6.cpp

[pkrvmxyh4eaekms:13065] *** Process received signal ***
[pkrvmxyh4eaekms:13065] Signal: Aborted (6)
[pkrvmxyh4eaekms:13065] Signal code:  (-6)
[pkrvmxyh4eaekms:13065] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbf17e45330]
[pkrvmxyh4eaekms:13065] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbf17e9eb2c]
[pkrvmxyh4eaekms:13065] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbf17e4527e]
[pkrvmxyh4eaekms:13065] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbf17e288ff]
[pkrvmxyh4eaekms:13065] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbf182a5ff5]
[pkrvmxyh4eaekms:13065] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbf182bb0da]
[pkrvmxyh4eaekms:13065] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbf182a5a55]
[pkrvmxyh4eaekms:13065] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbf182a5a6f]
[pkrvmxyh4eaekms:13065] [ 8] plumed_master(+0x146dd)[0x556ff57dd6dd]
[pkrvmxyh4eaekms:13065] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbf17e2a1ca]
[pkrvmxyh4eaekms:13065] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbf17e2a28b]
[pkrvmxyh4eaekms:13065] [11] plumed_master(+0x15365)[0x556ff57de365]
[pkrvmxyh4eaekms:13065] *** End of error message ***
</pre>
{% endraw %}
