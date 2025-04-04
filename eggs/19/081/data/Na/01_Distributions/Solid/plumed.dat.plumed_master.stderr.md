**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/01_Distributions/Solid/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../RefCV.mGiyYV.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../../RefCV.2.11.0-dev.so ../../../RefCV.cpp

[fv-az805-507:10041] *** Process received signal ***
[fv-az805-507:10041] Signal: Aborted (6)
[fv-az805-507:10041] Signal code:  (-6)
[fv-az805-507:10041] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc44e445330]
[fv-az805-507:10041] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc44e49eb2c]
[fv-az805-507:10041] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc44e44527e]
[fv-az805-507:10041] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc44e4288ff]
[fv-az805-507:10041] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc44e8a5ff5]
[fv-az805-507:10041] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc44e8bb0da]
[fv-az805-507:10041] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc44e8a5a55]
[fv-az805-507:10041] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc44e8a5a6f]
[fv-az805-507:10041] [ 8] plumed_master(+0x146dd)[0x555b7fc666dd]
[fv-az805-507:10041] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc44e42a1ca]
[fv-az805-507:10041] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc44e42a28b]
[fv-az805-507:10041] [11] plumed_master(+0x15365)[0x555b7fc67365]
[fv-az805-507:10041] *** End of error message ***
</pre>
{% endraw %}
