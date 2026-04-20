**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/02_FCC/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../RefCV.VEgOnE.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../RefCV.2.11.0-dev.so ../../RefCV.cpp

[runnervmeorf1:10510] *** Process received signal ***
[runnervmeorf1:10510] Signal: Aborted (6)
[runnervmeorf1:10510] Signal code:  (-6)
[runnervmeorf1:10510] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f91bd445330]
[runnervmeorf1:10510] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f91bd49eb2c]
[runnervmeorf1:10510] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f91bd44527e]
[runnervmeorf1:10510] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f91bd4288ff]
[runnervmeorf1:10510] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f91bd8a5ff5]
[runnervmeorf1:10510] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f91bd8bb0da]
[runnervmeorf1:10510] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f91bd8a5a55]
[runnervmeorf1:10510] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f91bd8a5a6f]
[runnervmeorf1:10510] [ 8] plumed_master(+0x146dd)[0x55d8df1cd6dd]
[runnervmeorf1:10510] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f91bd42a1ca]
[runnervmeorf1:10510] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f91bd42a28b]
[runnervmeorf1:10510] [11] plumed_master(+0x15365)[0x55d8df1ce365]
[runnervmeorf1:10510] *** End of error message ***
</pre>
{% endraw %}
