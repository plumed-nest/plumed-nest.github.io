**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/03_BCC/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../RefCV.vPJaVT.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1497) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../RefCV.2.11.0-dev.so ../../RefCV.cpp

[runnervmvrwv9:10384] *** Process received signal ***
[runnervmvrwv9:10384] Signal: Aborted (6)
[runnervmvrwv9:10384] Signal code:  (-6)
[runnervmvrwv9:10384] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f72a3845330]
[runnervmvrwv9:10384] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f72a389eb2c]
[runnervmvrwv9:10384] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f72a384527e]
[runnervmvrwv9:10384] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f72a38288ff]
[runnervmvrwv9:10384] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f72a3ca5ff5]
[runnervmvrwv9:10384] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f72a3cbb0da]
[runnervmvrwv9:10384] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f72a3ca5a55]
[runnervmvrwv9:10384] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f72a3ca5a6f]
[runnervmvrwv9:10384] [ 8] plumed_master(+0x146dd)[0x561df290f6dd]
[runnervmvrwv9:10384] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f72a382a1ca]
[runnervmvrwv9:10384] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f72a382a28b]
[runnervmvrwv9:10384] [11] plumed_master(+0x15365)[0x561df2910365]
[runnervmvrwv9:10384] *** End of error message ***
</pre>
{% endraw %}
