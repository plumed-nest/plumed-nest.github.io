**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/02_FCC/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../RefCV.z0nd0O.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1497) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../RefCV.2.11.0-dev.so ../../RefCV.cpp

[runnervmvrwv9:10213] *** Process received signal ***
[runnervmvrwv9:10213] Signal: Aborted (6)
[runnervmvrwv9:10213] Signal code:  (-6)
[runnervmvrwv9:10213] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd9a2845330]
[runnervmvrwv9:10213] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd9a289eb2c]
[runnervmvrwv9:10213] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd9a284527e]
[runnervmvrwv9:10213] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd9a28288ff]
[runnervmvrwv9:10213] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd9a2ca5ff5]
[runnervmvrwv9:10213] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd9a2cbb0da]
[runnervmvrwv9:10213] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd9a2ca5a55]
[runnervmvrwv9:10213] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd9a2ca5a6f]
[runnervmvrwv9:10213] [ 8] plumed_master(+0x146dd)[0x564a34c196dd]
[runnervmvrwv9:10213] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd9a282a1ca]
[runnervmvrwv9:10213] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd9a282a28b]
[runnervmvrwv9:10213] [11] plumed_master(+0x15365)[0x564a34c1a365]
[runnervmvrwv9:10213] *** End of error message ***
</pre>
{% endraw %}
