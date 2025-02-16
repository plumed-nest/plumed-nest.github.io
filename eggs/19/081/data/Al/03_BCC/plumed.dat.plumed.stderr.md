**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/03_BCC/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../RefCV.s0yEos.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1499) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../RefCV.2.10b.so ../../RefCV.cpp

[fv-az1112-175:68816] *** Process received signal ***
[fv-az1112-175:68816] Signal: Aborted (6)
[fv-az1112-175:68816] Signal code:  (-6)
[fv-az1112-175:68816] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4205c45330]
[fv-az1112-175:68816] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4205c9eb2c]
[fv-az1112-175:68816] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4205c4527e]
[fv-az1112-175:68816] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4205c288ff]
[fv-az1112-175:68816] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f42060a5ff5]
[fv-az1112-175:68816] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f42060bb0da]
[fv-az1112-175:68816] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f42060a5a55]
[fv-az1112-175:68816] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f42060a5a6f]
[fv-az1112-175:68816] [ 8] plumed(+0x146dd)[0x558d255a66dd]
[fv-az1112-175:68816] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4205c2a1ca]
[fv-az1112-175:68816] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4205c2a28b]
[fv-az1112-175:68816] [11] plumed(+0x15365)[0x558d255a7365]
[fv-az1112-175:68816] *** End of error message ***
</pre>
{% endraw %}
