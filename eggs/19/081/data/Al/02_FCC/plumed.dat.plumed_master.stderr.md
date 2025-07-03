**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/02_FCC/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../RefCV.c44FTy.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../RefCV.2.11.0-dev.so ../../RefCV.cpp

[pkrvmbietmlfzoi:12952] *** Process received signal ***
[pkrvmbietmlfzoi:12952] Signal: Aborted (6)
[pkrvmbietmlfzoi:12952] Signal code:  (-6)
[pkrvmbietmlfzoi:12952] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0442e45330]
[pkrvmbietmlfzoi:12952] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0442e9eb2c]
[pkrvmbietmlfzoi:12952] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0442e4527e]
[pkrvmbietmlfzoi:12952] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0442e288ff]
[pkrvmbietmlfzoi:12952] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f04432a5ff5]
[pkrvmbietmlfzoi:12952] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f04432bb0da]
[pkrvmbietmlfzoi:12952] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f04432a5a55]
[pkrvmbietmlfzoi:12952] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f04432a5a6f]
[pkrvmbietmlfzoi:12952] [ 8] plumed_master(+0x146dd)[0x556b970506dd]
[pkrvmbietmlfzoi:12952] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0442e2a1ca]
[pkrvmbietmlfzoi:12952] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0442e2a28b]
[pkrvmbietmlfzoi:12952] [11] plumed_master(+0x15365)[0x556b97051365]
[pkrvmbietmlfzoi:12952] *** End of error message ***
</pre>
{% endraw %}
