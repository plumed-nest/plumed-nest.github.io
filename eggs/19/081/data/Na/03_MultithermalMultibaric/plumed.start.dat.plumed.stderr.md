**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/03_MultithermalMultibaric/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../RefCV.g91oQX.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../RefCV.2.10.0.so ../../RefCV.cpp

[runnervmw9dnm:10803] *** Process received signal ***
[runnervmw9dnm:10803] Signal: Aborted (6)
[runnervmw9dnm:10803] Signal code:  (-6)
[runnervmw9dnm:10803] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0d06445330]
[runnervmw9dnm:10803] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0d0649eb2c]
[runnervmw9dnm:10803] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0d0644527e]
[runnervmw9dnm:10803] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0d064288ff]
[runnervmw9dnm:10803] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0d068a5ff5]
[runnervmw9dnm:10803] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0d068bb0da]
[runnervmw9dnm:10803] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0d068a5a55]
[runnervmw9dnm:10803] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0d068a5a6f]
[runnervmw9dnm:10803] [ 8] plumed(+0x146dd)[0x5591409ee6dd]
[runnervmw9dnm:10803] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0d0642a1ca]
[runnervmw9dnm:10803] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0d0642a28b]
[runnervmw9dnm:10803] [11] plumed(+0x15365)[0x5591409ef365]
[runnervmw9dnm:10803] *** End of error message ***
</pre>
{% endraw %}
