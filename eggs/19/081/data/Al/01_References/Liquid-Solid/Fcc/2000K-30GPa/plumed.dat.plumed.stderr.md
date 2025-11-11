**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/01_References/Liquid-Solid/Fcc/2000K-30GPa/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../../../RefCV.V5vMuf.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../../../../RefCV.2.10.0.so ../../../../../RefCV.cpp

[runnervmw9dnm:09790] *** Process received signal ***
[runnervmw9dnm:09790] Signal: Aborted (6)
[runnervmw9dnm:09790] Signal code:  (-6)
[runnervmw9dnm:09790] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc395c45330]
[runnervmw9dnm:09790] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc395c9eb2c]
[runnervmw9dnm:09790] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc395c4527e]
[runnervmw9dnm:09790] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc395c288ff]
[runnervmw9dnm:09790] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc3960a5ff5]
[runnervmw9dnm:09790] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc3960bb0da]
[runnervmw9dnm:09790] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc3960a5a55]
[runnervmw9dnm:09790] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc3960a5a6f]
[runnervmw9dnm:09790] [ 8] plumed(+0x146dd)[0x559e0e3c36dd]
[runnervmw9dnm:09790] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc395c2a1ca]
[runnervmw9dnm:09790] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc395c2a28b]
[runnervmw9dnm:09790] [11] plumed(+0x15365)[0x559e0e3c4365]
[runnervmw9dnm:09790] *** End of error message ***
</pre>
{% endraw %}
