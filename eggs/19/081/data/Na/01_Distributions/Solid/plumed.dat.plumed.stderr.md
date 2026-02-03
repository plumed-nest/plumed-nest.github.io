**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/01_Distributions/Solid/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../RefCV.bVkLKj.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../../RefCV.2.10.0.so ../../../RefCV.cpp

[runnervmkj6or:10663] *** Process received signal ***
[runnervmkj6or:10663] Signal: Aborted (6)
[runnervmkj6or:10663] Signal code:  (-6)
[runnervmkj6or:10663] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fed80c45330]
[runnervmkj6or:10663] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fed80c9eb2c]
[runnervmkj6or:10663] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fed80c4527e]
[runnervmkj6or:10663] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fed80c288ff]
[runnervmkj6or:10663] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fed810a5ff5]
[runnervmkj6or:10663] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fed810bb0da]
[runnervmkj6or:10663] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fed810a5a55]
[runnervmkj6or:10663] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fed810a5a6f]
[runnervmkj6or:10663] [ 8] plumed(+0x146dd)[0x5609542aa6dd]
[runnervmkj6or:10663] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fed80c2a1ca]
[runnervmkj6or:10663] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fed80c2a28b]
[runnervmkj6or:10663] [11] plumed(+0x15365)[0x5609542ab365]
[runnervmkj6or:10663] *** End of error message ***
</pre>
{% endraw %}
