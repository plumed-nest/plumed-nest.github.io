**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/02_References/Example/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../RefCV.Hr5TRm.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../../RefCV.2.10b.so ../../../RefCV.cpp

[pkrvmbietmlfzoi:13554] *** Process received signal ***
[pkrvmbietmlfzoi:13554] Signal: Aborted (6)
[pkrvmbietmlfzoi:13554] Signal code:  (-6)
[pkrvmbietmlfzoi:13554] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f302ea45330]
[pkrvmbietmlfzoi:13554] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f302ea9eb2c]
[pkrvmbietmlfzoi:13554] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f302ea4527e]
[pkrvmbietmlfzoi:13554] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f302ea288ff]
[pkrvmbietmlfzoi:13554] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f302eea5ff5]
[pkrvmbietmlfzoi:13554] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f302eebb0da]
[pkrvmbietmlfzoi:13554] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f302eea5a55]
[pkrvmbietmlfzoi:13554] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f302eea5a6f]
[pkrvmbietmlfzoi:13554] [ 8] plumed(+0x146dd)[0x56055eea56dd]
[pkrvmbietmlfzoi:13554] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f302ea2a1ca]
[pkrvmbietmlfzoi:13554] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f302ea2a28b]
[pkrvmbietmlfzoi:13554] [11] plumed(+0x15365)[0x56055eea6365]
[pkrvmbietmlfzoi:13554] *** End of error message ***
</pre>
{% endraw %}
