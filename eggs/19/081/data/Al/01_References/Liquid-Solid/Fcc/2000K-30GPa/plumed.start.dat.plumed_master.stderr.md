**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/01_References/Liquid-Solid/Fcc/2000K-30GPa/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../../../RefCV.EWhWLX.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1497) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../../../../RefCV.2.11.0-dev.so ../../../../../RefCV.cpp

[runnervmvrwv9:10128] *** Process received signal ***
[runnervmvrwv9:10128] Signal: Aborted (6)
[runnervmvrwv9:10128] Signal code:  (-6)
[runnervmvrwv9:10128] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd42e645330]
[runnervmvrwv9:10128] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd42e69eb2c]
[runnervmvrwv9:10128] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd42e64527e]
[runnervmvrwv9:10128] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd42e6288ff]
[runnervmvrwv9:10128] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd42eaa5ff5]
[runnervmvrwv9:10128] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd42eabb0da]
[runnervmvrwv9:10128] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd42eaa5a55]
[runnervmvrwv9:10128] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd42eaa5a6f]
[runnervmvrwv9:10128] [ 8] plumed_master(+0x146dd)[0x55efbf2236dd]
[runnervmvrwv9:10128] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd42e62a1ca]
[runnervmvrwv9:10128] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd42e62a28b]
[runnervmvrwv9:10128] [11] plumed_master(+0x15365)[0x55efbf224365]
[runnervmvrwv9:10128] *** End of error message ***
</pre>
{% endraw %}
