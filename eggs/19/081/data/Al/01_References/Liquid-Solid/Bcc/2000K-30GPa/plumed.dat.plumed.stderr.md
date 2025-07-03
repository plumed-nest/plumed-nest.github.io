**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/01_References/Liquid-Solid/Bcc/2000K-30GPa/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../../../RefCV.763PrZ.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../../../../RefCV.2.10b.so ../../../../../RefCV.cpp

[pkrvmbietmlfzoi:12573] *** Process received signal ***
[pkrvmbietmlfzoi:12573] Signal: Aborted (6)
[pkrvmbietmlfzoi:12573] Signal code:  (-6)
[pkrvmbietmlfzoi:12573] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9266c45330]
[pkrvmbietmlfzoi:12573] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9266c9eb2c]
[pkrvmbietmlfzoi:12573] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9266c4527e]
[pkrvmbietmlfzoi:12573] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9266c288ff]
[pkrvmbietmlfzoi:12573] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f92670a5ff5]
[pkrvmbietmlfzoi:12573] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f92670bb0da]
[pkrvmbietmlfzoi:12573] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f92670a5a55]
[pkrvmbietmlfzoi:12573] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f92670a5a6f]
[pkrvmbietmlfzoi:12573] [ 8] plumed(+0x146dd)[0x55c7fcdfd6dd]
[pkrvmbietmlfzoi:12573] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9266c2a1ca]
[pkrvmbietmlfzoi:12573] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9266c2a28b]
[pkrvmbietmlfzoi:12573] [11] plumed(+0x15365)[0x55c7fcdfe365]
[pkrvmbietmlfzoi:12573] *** End of error message ***
</pre>
{% endraw %}
