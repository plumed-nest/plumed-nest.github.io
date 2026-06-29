**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/03_MultithermalMultibaric/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../RefCV.9BBi4a.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1494) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../RefCV.2.11.0-dev.so ../../RefCV.cpp

[runnervmmklqx:12043] *** Process received signal ***
[runnervmmklqx:12043] Signal: Aborted (6)
[runnervmmklqx:12043] Signal code:  (-6)
[runnervmmklqx:12043] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5181a45330]
[runnervmmklqx:12043] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5181a9eb2c]
[runnervmmklqx:12043] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5181a4527e]
[runnervmmklqx:12043] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5181a288ff]
[runnervmmklqx:12043] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5181ea5ff5]
[runnervmmklqx:12043] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5181ebb0da]
[runnervmmklqx:12043] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5181ea5a55]
[runnervmmklqx:12043] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5181ea5a6f]
[runnervmmklqx:12043] [ 8] plumed_master(+0x146dd)[0x5637ed2066dd]
[runnervmmklqx:12043] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5181a2a1ca]
[runnervmmklqx:12043] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5181a2a28b]
[runnervmmklqx:12043] [11] plumed_master(+0x15365)[0x5637ed207365]
[runnervmmklqx:12043] *** End of error message ***
</pre>
{% endraw %}
