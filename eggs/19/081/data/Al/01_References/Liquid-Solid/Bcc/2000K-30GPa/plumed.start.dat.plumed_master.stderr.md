**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/01_References/Liquid-Solid/Bcc/2000K-30GPa/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../../../RefCV.W3YtO0.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../../../../RefCV.2.11.0-dev.so ../../../../../RefCV.cpp

[runnervmmtnos:37790] *** Process received signal ***
[runnervmmtnos:37790] Signal: Aborted (6)
[runnervmmtnos:37790] Signal code:  (-6)
[runnervmmtnos:37790] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f179f645330]
[runnervmmtnos:37790] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f179f69eb2c]
[runnervmmtnos:37790] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f179f64527e]
[runnervmmtnos:37790] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f179f6288ff]
[runnervmmtnos:37790] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f179faa5ff5]
[runnervmmtnos:37790] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f179fabb0da]
[runnervmmtnos:37790] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f179faa5a55]
[runnervmmtnos:37790] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f179faa5a6f]
[runnervmmtnos:37790] [ 8] plumed_master(+0x146dd)[0x55c72e6336dd]
[runnervmmtnos:37790] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f179f62a1ca]
[runnervmmtnos:37790] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f179f62a28b]
[runnervmmtnos:37790] [11] plumed_master(+0x15365)[0x55c72e634365]
[runnervmmtnos:37790] *** End of error message ***
</pre>
{% endraw %}
