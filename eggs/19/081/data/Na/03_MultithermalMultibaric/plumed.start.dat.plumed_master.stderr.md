**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/03_MultithermalMultibaric/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../RefCV.nmQG7u.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../RefCV.2.11.0-dev.so ../../RefCV.cpp

[runnervmeorf1:11362] *** Process received signal ***
[runnervmeorf1:11362] Signal: Aborted (6)
[runnervmeorf1:11362] Signal code:  (-6)
[runnervmeorf1:11362] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f26e6445330]
[runnervmeorf1:11362] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f26e649eb2c]
[runnervmeorf1:11362] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f26e644527e]
[runnervmeorf1:11362] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f26e64288ff]
[runnervmeorf1:11362] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f26e68a5ff5]
[runnervmeorf1:11362] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f26e68bb0da]
[runnervmeorf1:11362] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f26e68a5a55]
[runnervmeorf1:11362] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f26e68a5a6f]
[runnervmeorf1:11362] [ 8] plumed_master(+0x146dd)[0x55fbbe8076dd]
[runnervmeorf1:11362] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f26e642a1ca]
[runnervmeorf1:11362] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f26e642a28b]
[runnervmeorf1:11362] [11] plumed_master(+0x15365)[0x55fbbe808365]
[runnervmeorf1:11362] *** End of error message ***
</pre>
{% endraw %}
