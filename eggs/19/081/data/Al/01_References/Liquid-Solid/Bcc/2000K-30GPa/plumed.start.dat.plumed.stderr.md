**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/01_References/Liquid-Solid/Bcc/2000K-30GPa/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../../../RefCV.edgTzH.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../../../../RefCV.2.10.0.so ../../../../../RefCV.cpp

[runnervmw9dnm:09705] *** Process received signal ***
[runnervmw9dnm:09705] Signal: Aborted (6)
[runnervmw9dnm:09705] Signal code:  (-6)
[runnervmw9dnm:09705] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5961645330]
[runnervmw9dnm:09705] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f596169eb2c]
[runnervmw9dnm:09705] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f596164527e]
[runnervmw9dnm:09705] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f59616288ff]
[runnervmw9dnm:09705] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5961aa5ff5]
[runnervmw9dnm:09705] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5961abb0da]
[runnervmw9dnm:09705] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5961aa5a55]
[runnervmw9dnm:09705] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5961aa5a6f]
[runnervmw9dnm:09705] [ 8] plumed(+0x146dd)[0x55c3122ae6dd]
[runnervmw9dnm:09705] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f596162a1ca]
[runnervmw9dnm:09705] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f596162a28b]
[runnervmw9dnm:09705] [11] plumed(+0x15365)[0x55c3122af365]
[runnervmw9dnm:09705] *** End of error message ***
</pre>
{% endraw %}
