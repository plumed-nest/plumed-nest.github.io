**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/02_References/Example/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../RefCV.jqHXRS.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1497) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.1' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../../RefCV.2.10.1.so ../../../RefCV.cpp

[runnervmvrwv9:10744] *** Process received signal ***
[runnervmvrwv9:10744] Signal: Aborted (6)
[runnervmvrwv9:10744] Signal code:  (-6)
[runnervmvrwv9:10744] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0162445330]
[runnervmvrwv9:10744] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f016249eb2c]
[runnervmvrwv9:10744] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f016244527e]
[runnervmvrwv9:10744] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f01624288ff]
[runnervmvrwv9:10744] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f01628a5ff5]
[runnervmvrwv9:10744] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f01628bb0da]
[runnervmvrwv9:10744] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f01628a5a55]
[runnervmvrwv9:10744] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f01628a5a6f]
[runnervmvrwv9:10744] [ 8] plumed(+0x146dd)[0x56095f03f6dd]
[runnervmvrwv9:10744] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f016242a1ca]
[runnervmvrwv9:10744] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f016242a28b]
[runnervmvrwv9:10744] [11] plumed(+0x15365)[0x56095f040365]
[runnervmvrwv9:10744] *** End of error message ***
</pre>
{% endraw %}
