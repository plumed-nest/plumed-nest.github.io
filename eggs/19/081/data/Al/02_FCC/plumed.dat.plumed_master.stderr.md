**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/02_FCC/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../RefCV.UujvCf.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../RefCV.2.11.0-dev.so ../../RefCV.cpp

[pkrvmberfyhpb9w:11661] *** Process received signal ***
[pkrvmberfyhpb9w:11661] Signal: Aborted (6)
[pkrvmberfyhpb9w:11661] Signal code:  (-6)
[pkrvmberfyhpb9w:11661] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4591c45330]
[pkrvmberfyhpb9w:11661] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4591c9eb2c]
[pkrvmberfyhpb9w:11661] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4591c4527e]
[pkrvmberfyhpb9w:11661] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4591c288ff]
[pkrvmberfyhpb9w:11661] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f45920a5ff5]
[pkrvmberfyhpb9w:11661] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f45920bb0da]
[pkrvmberfyhpb9w:11661] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f45920a5a55]
[pkrvmberfyhpb9w:11661] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f45920a5a6f]
[pkrvmberfyhpb9w:11661] [ 8] plumed_master(+0x146dd)[0x5621e6c566dd]
[pkrvmberfyhpb9w:11661] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4591c2a1ca]
[pkrvmberfyhpb9w:11661] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4591c2a28b]
[pkrvmberfyhpb9w:11661] [11] plumed_master(+0x15365)[0x5621e6c57365]
[pkrvmberfyhpb9w:11661] *** End of error message ***
</pre>
{% endraw %}
