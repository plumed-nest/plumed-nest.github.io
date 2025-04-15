**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/01_References/Liquid-Solid/Fcc/2000K-30GPa/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../../../RefCV.K2Bi92.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../../../../RefCV.2.10b.so ../../../../../RefCV.cpp

[fv-az1277-646:68333] *** Process received signal ***
[fv-az1277-646:68333] Signal: Aborted (6)
[fv-az1277-646:68333] Signal code:  (-6)
[fv-az1277-646:68333] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5591045330]
[fv-az1277-646:68333] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f559109eb2c]
[fv-az1277-646:68333] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f559104527e]
[fv-az1277-646:68333] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f55910288ff]
[fv-az1277-646:68333] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f55914a5ff5]
[fv-az1277-646:68333] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f55914bb0da]
[fv-az1277-646:68333] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f55914a5a55]
[fv-az1277-646:68333] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f55914a5a6f]
[fv-az1277-646:68333] [ 8] plumed(+0x146dd)[0x5578c7cff6dd]
[fv-az1277-646:68333] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f559102a1ca]
[fv-az1277-646:68333] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f559102a28b]
[fv-az1277-646:68333] [11] plumed(+0x15365)[0x5578c7d00365]
[fv-az1277-646:68333] *** End of error message ***
</pre>
{% endraw %}
