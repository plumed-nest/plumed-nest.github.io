**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/02_References/Example/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../RefCV.bwujF5.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../../RefCV.2.11.0-dev.so ../../../RefCV.cpp

[runnervmkj6or:10904] *** Process received signal ***
[runnervmkj6or:10904] Signal: Aborted (6)
[runnervmkj6or:10904] Signal code:  (-6)
[runnervmkj6or:10904] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5065445330]
[runnervmkj6or:10904] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f506549eb2c]
[runnervmkj6or:10904] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f506544527e]
[runnervmkj6or:10904] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f50654288ff]
[runnervmkj6or:10904] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f50658a5ff5]
[runnervmkj6or:10904] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f50658bb0da]
[runnervmkj6or:10904] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f50658a5a55]
[runnervmkj6or:10904] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f50658a5a6f]
[runnervmkj6or:10904] [ 8] plumed_master(+0x146dd)[0x56509f5ca6dd]
[runnervmkj6or:10904] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f506542a1ca]
[runnervmkj6or:10904] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f506542a28b]
[runnervmkj6or:10904] [11] plumed_master(+0x15365)[0x56509f5cb365]
[runnervmkj6or:10904] *** End of error message ***
</pre>
{% endraw %}
