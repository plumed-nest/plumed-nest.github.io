**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/02_References/Example/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../RefCV.GLldO6.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../../RefCV.2.10.0.so ../../../RefCV.cpp

[runnervmkj6or:10786] *** Process received signal ***
[runnervmkj6or:10786] Signal: Aborted (6)
[runnervmkj6or:10786] Signal code:  (-6)
[runnervmkj6or:10786] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4c07a45330]
[runnervmkj6or:10786] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4c07a9eb2c]
[runnervmkj6or:10786] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4c07a4527e]
[runnervmkj6or:10786] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4c07a288ff]
[runnervmkj6or:10786] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4c07ea5ff5]
[runnervmkj6or:10786] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4c07ebb0da]
[runnervmkj6or:10786] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4c07ea5a55]
[runnervmkj6or:10786] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4c07ea5a6f]
[runnervmkj6or:10786] [ 8] plumed(+0x146dd)[0x5622497186dd]
[runnervmkj6or:10786] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4c07a2a1ca]
[runnervmkj6or:10786] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4c07a2a28b]
[runnervmkj6or:10786] [11] plumed(+0x15365)[0x562249719365]
[runnervmkj6or:10786] *** End of error message ***
</pre>
{% endraw %}
