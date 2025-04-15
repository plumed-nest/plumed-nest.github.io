**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/01_References/Liquid-Solid/Bcc/2000K-30GPa/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../../../RefCV.W0EV2R.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../../../../RefCV.2.10b.so ../../../../../RefCV.cpp

[fv-az1277-646:68248] *** Process received signal ***
[fv-az1277-646:68248] Signal: Aborted (6)
[fv-az1277-646:68248] Signal code:  (-6)
[fv-az1277-646:68248] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3b9fa45330]
[fv-az1277-646:68248] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3b9fa9eb2c]
[fv-az1277-646:68248] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3b9fa4527e]
[fv-az1277-646:68248] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3b9fa288ff]
[fv-az1277-646:68248] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3b9fea5ff5]
[fv-az1277-646:68248] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3b9febb0da]
[fv-az1277-646:68248] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3b9fea5a55]
[fv-az1277-646:68248] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3b9fea5a6f]
[fv-az1277-646:68248] [ 8] plumed(+0x146dd)[0x557c89d166dd]
[fv-az1277-646:68248] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3b9fa2a1ca]
[fv-az1277-646:68248] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3b9fa2a28b]
[fv-az1277-646:68248] [11] plumed(+0x15365)[0x557c89d17365]
[fv-az1277-646:68248] *** End of error message ***
</pre>
{% endraw %}
