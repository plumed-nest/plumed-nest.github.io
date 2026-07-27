**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/01_Distributions/Solid/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../RefCV.3AxT0y.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1497) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../../RefCV.2.11.0-dev.so ../../../RefCV.cpp

[runnervmvrwv9:10641] *** Process received signal ***
[runnervmvrwv9:10641] Signal: Aborted (6)
[runnervmvrwv9:10641] Signal code:  (-6)
[runnervmvrwv9:10641] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff4f9045330]
[runnervmvrwv9:10641] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff4f909eb2c]
[runnervmvrwv9:10641] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff4f904527e]
[runnervmvrwv9:10641] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff4f90288ff]
[runnervmvrwv9:10641] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff4f94a5ff5]
[runnervmvrwv9:10641] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff4f94bb0da]
[runnervmvrwv9:10641] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff4f94a5a55]
[runnervmvrwv9:10641] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff4f94a5a6f]
[runnervmvrwv9:10641] [ 8] plumed_master(+0x146dd)[0x55e9d1de06dd]
[runnervmvrwv9:10641] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff4f902a1ca]
[runnervmvrwv9:10641] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff4f902a28b]
[runnervmvrwv9:10641] [11] plumed_master(+0x15365)[0x55e9d1de1365]
[runnervmvrwv9:10641] *** End of error message ***
</pre>
{% endraw %}
