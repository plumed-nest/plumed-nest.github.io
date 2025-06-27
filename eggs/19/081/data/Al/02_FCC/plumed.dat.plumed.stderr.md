**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/02_FCC/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../RefCV.hrlU35.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../RefCV.2.10b.so ../../RefCV.cpp

[pkrvmbietmlfzoi:67044] *** Process received signal ***
[pkrvmbietmlfzoi:67044] Signal: Aborted (6)
[pkrvmbietmlfzoi:67044] Signal code:  (-6)
[pkrvmbietmlfzoi:67044] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0bd6645330]
[pkrvmbietmlfzoi:67044] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0bd669eb2c]
[pkrvmbietmlfzoi:67044] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0bd664527e]
[pkrvmbietmlfzoi:67044] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0bd66288ff]
[pkrvmbietmlfzoi:67044] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0bd6aa5ff5]
[pkrvmbietmlfzoi:67044] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0bd6abb0da]
[pkrvmbietmlfzoi:67044] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0bd6aa5a55]
[pkrvmbietmlfzoi:67044] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0bd6aa5a6f]
[pkrvmbietmlfzoi:67044] [ 8] plumed(+0x146dd)[0x55a4b4d9c6dd]
[pkrvmbietmlfzoi:67044] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0bd662a1ca]
[pkrvmbietmlfzoi:67044] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0bd662a28b]
[pkrvmbietmlfzoi:67044] [11] plumed(+0x15365)[0x55a4b4d9d365]
[pkrvmbietmlfzoi:67044] *** End of error message ***
</pre>
{% endraw %}
