**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/01_References/Liquid-Solid/Bcc/2000K-30GPa/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../../../RefCV.AQSlsN.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../../../../RefCV.2.11.0-dev.so ../../../../../RefCV.cpp

[runnervmeorf1:10170] *** Process received signal ***
[runnervmeorf1:10170] Signal: Aborted (6)
[runnervmeorf1:10170] Signal code:  (-6)
[runnervmeorf1:10170] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb551e45330]
[runnervmeorf1:10170] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb551e9eb2c]
[runnervmeorf1:10170] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb551e4527e]
[runnervmeorf1:10170] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb551e288ff]
[runnervmeorf1:10170] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb5522a5ff5]
[runnervmeorf1:10170] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb5522bb0da]
[runnervmeorf1:10170] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb5522a5a55]
[runnervmeorf1:10170] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb5522a5a6f]
[runnervmeorf1:10170] [ 8] plumed_master(+0x146dd)[0x56365af996dd]
[runnervmeorf1:10170] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb551e2a1ca]
[runnervmeorf1:10170] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb551e2a28b]
[runnervmeorf1:10170] [11] plumed_master(+0x15365)[0x56365af9a365]
[runnervmeorf1:10170] *** End of error message ***
</pre>
{% endraw %}
