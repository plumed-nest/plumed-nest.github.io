**Project ID:** [plumID:20.003]({{ '/' | absolute_url }}eggs/20/003/)  
Stderr for source:  plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
TD_TS-target-plumed2.6.ACqxlO.cpp:23:10: fatal error: TargetDistribution.h: No such file or directory
23 | #include "TargetDistribution.h"
|          ^~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./TD_TS-target-plumed2.6.2.11.0-dev.so TD_TS-target-plumed2.6.cpp

[pkrvmberfyhpb9w:11373] *** Process received signal ***
[pkrvmberfyhpb9w:11373] Signal: Aborted (6)
[pkrvmberfyhpb9w:11373] Signal code:  (-6)
[pkrvmberfyhpb9w:11373] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f558f645330]
[pkrvmberfyhpb9w:11373] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f558f69eb2c]
[pkrvmberfyhpb9w:11373] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f558f64527e]
[pkrvmberfyhpb9w:11373] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f558f6288ff]
[pkrvmberfyhpb9w:11373] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f558faa5ff5]
[pkrvmberfyhpb9w:11373] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f558fabb0da]
[pkrvmberfyhpb9w:11373] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f558faa5a55]
[pkrvmberfyhpb9w:11373] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f558faa5a6f]
[pkrvmberfyhpb9w:11373] [ 8] plumed_master(+0x146dd)[0x563581b5c6dd]
[pkrvmberfyhpb9w:11373] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f558f62a1ca]
[pkrvmberfyhpb9w:11373] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f558f62a28b]
[pkrvmberfyhpb9w:11373] [11] plumed_master(+0x15365)[0x563581b5d365]
[pkrvmberfyhpb9w:11373] *** End of error message ***
</pre>
{% endraw %}
