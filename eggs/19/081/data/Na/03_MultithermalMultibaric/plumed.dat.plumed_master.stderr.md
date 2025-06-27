**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/03_MultithermalMultibaric/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../RefCV.mZh4Jy.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../RefCV.2.11.0-dev.so ../../RefCV.cpp

[pkrvmbietmlfzoi:67838] *** Process received signal ***
[pkrvmbietmlfzoi:67838] Signal: Aborted (6)
[pkrvmbietmlfzoi:67838] Signal code:  (-6)
[pkrvmbietmlfzoi:67838] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7430e45330]
[pkrvmbietmlfzoi:67838] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7430e9eb2c]
[pkrvmbietmlfzoi:67838] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7430e4527e]
[pkrvmbietmlfzoi:67838] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7430e288ff]
[pkrvmbietmlfzoi:67838] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f74312a5ff5]
[pkrvmbietmlfzoi:67838] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f74312bb0da]
[pkrvmbietmlfzoi:67838] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f74312a5a55]
[pkrvmbietmlfzoi:67838] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f74312a5a6f]
[pkrvmbietmlfzoi:67838] [ 8] plumed_master(+0x146dd)[0x558e1344c6dd]
[pkrvmbietmlfzoi:67838] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7430e2a1ca]
[pkrvmbietmlfzoi:67838] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7430e2a28b]
[pkrvmbietmlfzoi:67838] [11] plumed_master(+0x15365)[0x558e1344d365]
[pkrvmbietmlfzoi:67838] *** End of error message ***
</pre>
{% endraw %}
