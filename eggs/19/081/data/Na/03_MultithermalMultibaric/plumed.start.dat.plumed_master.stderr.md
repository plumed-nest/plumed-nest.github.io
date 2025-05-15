**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/03_MultithermalMultibaric/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../RefCV.h8Sdvj.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../RefCV.2.11.0-dev.so ../../RefCV.cpp

[pkrvmberfyhpb9w:12511] *** Process received signal ***
[pkrvmberfyhpb9w:12511] Signal: Aborted (6)
[pkrvmberfyhpb9w:12511] Signal code:  (-6)
[pkrvmberfyhpb9w:12511] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbfeec45330]
[pkrvmberfyhpb9w:12511] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbfeec9eb2c]
[pkrvmberfyhpb9w:12511] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbfeec4527e]
[pkrvmberfyhpb9w:12511] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbfeec288ff]
[pkrvmberfyhpb9w:12511] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbfef0a5ff5]
[pkrvmberfyhpb9w:12511] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbfef0bb0da]
[pkrvmberfyhpb9w:12511] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbfef0a5a55]
[pkrvmberfyhpb9w:12511] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbfef0a5a6f]
[pkrvmberfyhpb9w:12511] [ 8] plumed_master(+0x146dd)[0x5576fcd756dd]
[pkrvmberfyhpb9w:12511] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbfeec2a1ca]
[pkrvmberfyhpb9w:12511] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbfeec2a28b]
[pkrvmberfyhpb9w:12511] [11] plumed_master(+0x15365)[0x5576fcd76365]
[pkrvmberfyhpb9w:12511] *** End of error message ***
</pre>
{% endraw %}
