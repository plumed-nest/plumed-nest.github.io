**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/01_Distributions/Liquid/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../RefCV.aCA2Br.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../../RefCV.2.10.0.so ../../../RefCV.cpp

[runnervmw9dnm:10300] *** Process received signal ***
[runnervmw9dnm:10300] Signal: Aborted (6)
[runnervmw9dnm:10300] Signal code:  (-6)
[runnervmw9dnm:10300] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbe32245330]
[runnervmw9dnm:10300] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbe3229eb2c]
[runnervmw9dnm:10300] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbe3224527e]
[runnervmw9dnm:10300] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbe322288ff]
[runnervmw9dnm:10300] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbe326a5ff5]
[runnervmw9dnm:10300] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbe326bb0da]
[runnervmw9dnm:10300] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbe326a5a55]
[runnervmw9dnm:10300] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbe326a5a6f]
[runnervmw9dnm:10300] [ 8] plumed(+0x146dd)[0x5562fca846dd]
[runnervmw9dnm:10300] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbe3222a1ca]
[runnervmw9dnm:10300] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbe3222a28b]
[runnervmw9dnm:10300] [11] plumed(+0x15365)[0x5562fca85365]
[runnervmw9dnm:10300] *** End of error message ***
</pre>
{% endraw %}
