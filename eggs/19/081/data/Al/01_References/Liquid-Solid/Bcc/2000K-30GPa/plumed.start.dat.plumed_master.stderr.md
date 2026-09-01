**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/01_References/Liquid-Solid/Bcc/2000K-30GPa/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../../../RefCV.FQmtak.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1497) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../../../../RefCV.2.11.0-dev.so ../../../../../RefCV.cpp

[runnervmgx7h7:10957] *** Process received signal ***
[runnervmgx7h7:10957] Signal: Aborted (6)
[runnervmgx7h7:10957] Signal code:  (-6)
[runnervmgx7h7:10957] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f021c045330]
[runnervmgx7h7:10957] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f021c09ec0c]
[runnervmgx7h7:10957] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f021c04527e]
[runnervmgx7h7:10957] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f021c0288ff]
[runnervmgx7h7:10957] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f021c4a5ff5]
[runnervmgx7h7:10957] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f021c4bb0da]
[runnervmgx7h7:10957] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f021c4a5a55]
[runnervmgx7h7:10957] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f021c4a5a6f]
[runnervmgx7h7:10957] [ 8] plumed_master(+0x146dd)[0x5649d65496dd]
[runnervmgx7h7:10957] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f021c02a1ca]
[runnervmgx7h7:10957] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f021c02a28b]
[runnervmgx7h7:10957] [11] plumed_master(+0x15365)[0x5649d654a365]
[runnervmgx7h7:10957] *** End of error message ***
</pre>
{% endraw %}
