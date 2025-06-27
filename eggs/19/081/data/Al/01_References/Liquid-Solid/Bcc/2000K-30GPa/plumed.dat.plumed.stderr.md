**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/01_References/Liquid-Solid/Bcc/2000K-30GPa/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../../../RefCV.R3Vc4d.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../../../../RefCV.2.10b.so ../../../../../RefCV.cpp

[pkrvmbietmlfzoi:66700] *** Process received signal ***
[pkrvmbietmlfzoi:66700] Signal: Aborted (6)
[pkrvmbietmlfzoi:66700] Signal code:  (-6)
[pkrvmbietmlfzoi:66700] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3ea6c45330]
[pkrvmbietmlfzoi:66700] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3ea6c9eb2c]
[pkrvmbietmlfzoi:66700] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3ea6c4527e]
[pkrvmbietmlfzoi:66700] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3ea6c288ff]
[pkrvmbietmlfzoi:66700] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3ea70a5ff5]
[pkrvmbietmlfzoi:66700] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3ea70bb0da]
[pkrvmbietmlfzoi:66700] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3ea70a5a55]
[pkrvmbietmlfzoi:66700] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3ea70a5a6f]
[pkrvmbietmlfzoi:66700] [ 8] plumed(+0x146dd)[0x56447fb8a6dd]
[pkrvmbietmlfzoi:66700] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3ea6c2a1ca]
[pkrvmbietmlfzoi:66700] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3ea6c2a28b]
[pkrvmbietmlfzoi:66700] [11] plumed(+0x15365)[0x56447fb8b365]
[pkrvmbietmlfzoi:66700] *** End of error message ***
</pre>
{% endraw %}
