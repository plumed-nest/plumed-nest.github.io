**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/02_References/Example/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../RefCV.S1mxyp.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../../RefCV.2.11.0-dev.so ../../../RefCV.cpp

[pkrvmxyh4eaekms:14101] *** Process received signal ***
[pkrvmxyh4eaekms:14101] Signal: Aborted (6)
[pkrvmxyh4eaekms:14101] Signal code:  (-6)
[pkrvmxyh4eaekms:14101] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0526645330]
[pkrvmxyh4eaekms:14101] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f052669eb2c]
[pkrvmxyh4eaekms:14101] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f052664527e]
[pkrvmxyh4eaekms:14101] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f05266288ff]
[pkrvmxyh4eaekms:14101] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0526aa5ff5]
[pkrvmxyh4eaekms:14101] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0526abb0da]
[pkrvmxyh4eaekms:14101] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0526aa5a55]
[pkrvmxyh4eaekms:14101] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0526aa5a6f]
[pkrvmxyh4eaekms:14101] [ 8] plumed_master(+0x146dd)[0x5587432f16dd]
[pkrvmxyh4eaekms:14101] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f052662a1ca]
[pkrvmxyh4eaekms:14101] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f052662a28b]
[pkrvmxyh4eaekms:14101] [11] plumed_master(+0x15365)[0x5587432f2365]
[pkrvmxyh4eaekms:14101] *** End of error message ***
</pre>
{% endraw %}
