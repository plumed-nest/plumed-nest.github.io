**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/01_References/Liquid-Solid/Fcc/2000K-30GPa/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../../../RefCV.DeRtwP.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../../../../RefCV.2.10b.so ../../../../../RefCV.cpp

[fv-az805-507:09404] *** Process received signal ***
[fv-az805-507:09404] Signal: Aborted (6)
[fv-az805-507:09404] Signal code:  (-6)
[fv-az805-507:09404] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2bf1845330]
[fv-az805-507:09404] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2bf189eb2c]
[fv-az805-507:09404] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2bf184527e]
[fv-az805-507:09404] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2bf18288ff]
[fv-az805-507:09404] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2bf1ca5ff5]
[fv-az805-507:09404] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2bf1cbb0da]
[fv-az805-507:09404] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2bf1ca5a55]
[fv-az805-507:09404] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2bf1ca5a6f]
[fv-az805-507:09404] [ 8] plumed(+0x146dd)[0x55bf6c6c76dd]
[fv-az805-507:09404] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2bf182a1ca]
[fv-az805-507:09404] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2bf182a28b]
[fv-az805-507:09404] [11] plumed(+0x15365)[0x55bf6c6c8365]
[fv-az805-507:09404] *** End of error message ***
</pre>
{% endraw %}
