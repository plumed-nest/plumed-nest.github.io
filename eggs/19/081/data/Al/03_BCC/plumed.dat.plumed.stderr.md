**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/03_BCC/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../RefCV.s4O7Kk.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../RefCV.2.10.0.so ../../RefCV.cpp

[runnervmkj6or:10404] *** Process received signal ***
[runnervmkj6or:10404] Signal: Aborted (6)
[runnervmkj6or:10404] Signal code:  (-6)
[runnervmkj6or:10404] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fed01645330]
[runnervmkj6or:10404] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fed0169eb2c]
[runnervmkj6or:10404] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fed0164527e]
[runnervmkj6or:10404] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fed016288ff]
[runnervmkj6or:10404] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fed01aa5ff5]
[runnervmkj6or:10404] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fed01abb0da]
[runnervmkj6or:10404] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fed01aa5a55]
[runnervmkj6or:10404] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fed01aa5a6f]
[runnervmkj6or:10404] [ 8] plumed(+0x146dd)[0x55facd17f6dd]
[runnervmkj6or:10404] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fed0162a1ca]
[runnervmkj6or:10404] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fed0162a28b]
[runnervmkj6or:10404] [11] plumed(+0x15365)[0x55facd180365]
[runnervmkj6or:10404] *** End of error message ***
</pre>
{% endraw %}
