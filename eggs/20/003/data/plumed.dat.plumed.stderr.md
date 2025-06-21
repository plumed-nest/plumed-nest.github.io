**Project ID:** [plumID:20.003]({{ '/' | absolute_url }}eggs/20/003/)  
Stderr for source:  plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
TD_TS-target-plumed2.6.9hzEZy.cpp:23:10: fatal error: TargetDistribution.h: No such file or directory
23 | #include "TargetDistribution.h"
|          ^~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./TD_TS-target-plumed2.6.2.10b.so TD_TS-target-plumed2.6.cpp

[pkrvmxyh4eaekms:13032] *** Process received signal ***
[pkrvmxyh4eaekms:13032] Signal: Aborted (6)
[pkrvmxyh4eaekms:13032] Signal code:  (-6)
[pkrvmxyh4eaekms:13032] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fdbc8445330]
[pkrvmxyh4eaekms:13032] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fdbc849eb2c]
[pkrvmxyh4eaekms:13032] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fdbc844527e]
[pkrvmxyh4eaekms:13032] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fdbc84288ff]
[pkrvmxyh4eaekms:13032] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fdbc88a5ff5]
[pkrvmxyh4eaekms:13032] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fdbc88bb0da]
[pkrvmxyh4eaekms:13032] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fdbc88a5a55]
[pkrvmxyh4eaekms:13032] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fdbc88a5a6f]
[pkrvmxyh4eaekms:13032] [ 8] plumed(+0x146dd)[0x564b862196dd]
[pkrvmxyh4eaekms:13032] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fdbc842a1ca]
[pkrvmxyh4eaekms:13032] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fdbc842a28b]
[pkrvmxyh4eaekms:13032] [11] plumed(+0x15365)[0x564b8621a365]
[pkrvmxyh4eaekms:13032] *** End of error message ***
</pre>
{% endraw %}
