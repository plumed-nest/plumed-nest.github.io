**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/03_BCC/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../RefCV.9s1hDY.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../RefCV.2.10b.so ../../RefCV.cpp

[pkrvmbietmlfzoi:67214] *** Process received signal ***
[pkrvmbietmlfzoi:67214] Signal: Aborted (6)
[pkrvmbietmlfzoi:67214] Signal code:  (-6)
[pkrvmbietmlfzoi:67214] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd659445330]
[pkrvmbietmlfzoi:67214] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd65949eb2c]
[pkrvmbietmlfzoi:67214] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd65944527e]
[pkrvmbietmlfzoi:67214] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd6594288ff]
[pkrvmbietmlfzoi:67214] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd6598a5ff5]
[pkrvmbietmlfzoi:67214] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd6598bb0da]
[pkrvmbietmlfzoi:67214] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd6598a5a55]
[pkrvmbietmlfzoi:67214] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd6598a5a6f]
[pkrvmbietmlfzoi:67214] [ 8] plumed(+0x146dd)[0x55817f0e76dd]
[pkrvmbietmlfzoi:67214] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd65942a1ca]
[pkrvmbietmlfzoi:67214] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd65942a28b]
[pkrvmbietmlfzoi:67214] [11] plumed(+0x15365)[0x55817f0e8365]
[pkrvmbietmlfzoi:67214] *** End of error message ***
</pre>
{% endraw %}
