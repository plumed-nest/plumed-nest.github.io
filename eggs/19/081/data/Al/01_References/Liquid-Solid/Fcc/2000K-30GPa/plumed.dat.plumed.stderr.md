**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/01_References/Liquid-Solid/Fcc/2000K-30GPa/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../../../RefCV.wgW47R.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../../../../RefCV.2.10b.so ../../../../../RefCV.cpp

[fv-az790-36:68242] *** Process received signal ***
[fv-az790-36:68242] Signal: Aborted (6)
[fv-az790-36:68242] Signal code:  (-6)
[fv-az790-36:68242] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc052645330]
[fv-az790-36:68242] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc05269eb2c]
[fv-az790-36:68242] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc05264527e]
[fv-az790-36:68242] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc0526288ff]
[fv-az790-36:68242] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc052aa5ff5]
[fv-az790-36:68242] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc052abb0da]
[fv-az790-36:68242] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc052aa5a55]
[fv-az790-36:68242] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc052aa5a6f]
[fv-az790-36:68242] [ 8] plumed(+0x146dd)[0x564a75dc06dd]
[fv-az790-36:68242] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc05262a1ca]
[fv-az790-36:68242] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc05262a28b]
[fv-az790-36:68242] [11] plumed(+0x15365)[0x564a75dc1365]
[fv-az790-36:68242] *** End of error message ***
</pre>
{% endraw %}
