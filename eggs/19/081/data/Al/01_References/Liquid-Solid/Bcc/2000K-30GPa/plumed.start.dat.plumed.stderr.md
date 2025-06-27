**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/01_References/Liquid-Solid/Bcc/2000K-30GPa/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../../../RefCV.s1q5VG.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../../../../RefCV.2.10b.so ../../../../../RefCV.cpp

[pkrvmbietmlfzoi:66785] *** Process received signal ***
[pkrvmbietmlfzoi:66785] Signal: Aborted (6)
[pkrvmbietmlfzoi:66785] Signal code:  (-6)
[pkrvmbietmlfzoi:66785] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3defe45330]
[pkrvmbietmlfzoi:66785] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3defe9eb2c]
[pkrvmbietmlfzoi:66785] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3defe4527e]
[pkrvmbietmlfzoi:66785] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3defe288ff]
[pkrvmbietmlfzoi:66785] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3df02a5ff5]
[pkrvmbietmlfzoi:66785] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3df02bb0da]
[pkrvmbietmlfzoi:66785] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3df02a5a55]
[pkrvmbietmlfzoi:66785] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3df02a5a6f]
[pkrvmbietmlfzoi:66785] [ 8] plumed(+0x146dd)[0x56106d89e6dd]
[pkrvmbietmlfzoi:66785] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3defe2a1ca]
[pkrvmbietmlfzoi:66785] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3defe2a28b]
[pkrvmbietmlfzoi:66785] [11] plumed(+0x15365)[0x56106d89f365]
[pkrvmbietmlfzoi:66785] *** End of error message ***
</pre>
{% endraw %}
