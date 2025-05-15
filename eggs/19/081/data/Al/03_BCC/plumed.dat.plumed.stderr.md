**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/03_BCC/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../RefCV.YiyztM.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../RefCV.2.10b.so ../../RefCV.cpp

[pkrvmberfyhpb9w:11799] *** Process received signal ***
[pkrvmberfyhpb9w:11799] Signal: Aborted (6)
[pkrvmberfyhpb9w:11799] Signal code:  (-6)
[pkrvmberfyhpb9w:11799] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fac34245330]
[pkrvmberfyhpb9w:11799] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fac3429eb2c]
[pkrvmberfyhpb9w:11799] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fac3424527e]
[pkrvmberfyhpb9w:11799] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fac342288ff]
[pkrvmberfyhpb9w:11799] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fac346a5ff5]
[pkrvmberfyhpb9w:11799] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fac346bb0da]
[pkrvmberfyhpb9w:11799] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fac346a5a55]
[pkrvmberfyhpb9w:11799] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fac346a5a6f]
[pkrvmberfyhpb9w:11799] [ 8] plumed(+0x146dd)[0x55871d6b06dd]
[pkrvmberfyhpb9w:11799] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fac3422a1ca]
[pkrvmberfyhpb9w:11799] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fac3422a28b]
[pkrvmberfyhpb9w:11799] [11] plumed(+0x15365)[0x55871d6b1365]
[pkrvmberfyhpb9w:11799] *** End of error message ***
</pre>
{% endraw %}
