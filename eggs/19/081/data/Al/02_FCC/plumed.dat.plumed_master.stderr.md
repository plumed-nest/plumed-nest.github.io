**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/02_FCC/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../RefCV.XqJbeA.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1494) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../RefCV.2.11.0-dev.so ../../RefCV.cpp

[runnervmmklqx:11181] *** Process received signal ***
[runnervmmklqx:11181] Signal: Aborted (6)
[runnervmmklqx:11181] Signal code:  (-6)
[runnervmmklqx:11181] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3434445330]
[runnervmmklqx:11181] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f343449eb2c]
[runnervmmklqx:11181] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f343444527e]
[runnervmmklqx:11181] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f34344288ff]
[runnervmmklqx:11181] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f34348a5ff5]
[runnervmmklqx:11181] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f34348bb0da]
[runnervmmklqx:11181] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f34348a5a55]
[runnervmmklqx:11181] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f34348a5a6f]
[runnervmmklqx:11181] [ 8] plumed_master(+0x146dd)[0x5635485456dd]
[runnervmmklqx:11181] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f343442a1ca]
[runnervmmklqx:11181] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f343442a28b]
[runnervmmklqx:11181] [11] plumed_master(+0x15365)[0x563548546365]
[runnervmmklqx:11181] *** End of error message ***
</pre>
{% endraw %}
