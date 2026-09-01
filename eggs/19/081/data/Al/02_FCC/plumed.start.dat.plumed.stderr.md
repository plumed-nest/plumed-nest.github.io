**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/02_FCC/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../RefCV.UO6zdO.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1497) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.1' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../RefCV.2.10.1.so ../../RefCV.cpp

[runnervmgx7h7:11265] *** Process received signal ***
[runnervmgx7h7:11265] Signal: Aborted (6)
[runnervmgx7h7:11265] Signal code:  (-6)
[runnervmgx7h7:11265] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8f94245330]
[runnervmgx7h7:11265] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8f9429ec0c]
[runnervmgx7h7:11265] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8f9424527e]
[runnervmgx7h7:11265] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8f942288ff]
[runnervmgx7h7:11265] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8f946a5ff5]
[runnervmgx7h7:11265] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8f946bb0da]
[runnervmgx7h7:11265] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8f946a5a55]
[runnervmgx7h7:11265] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8f946a5a6f]
[runnervmgx7h7:11265] [ 8] plumed(+0x146dd)[0x55fdb299d6dd]
[runnervmgx7h7:11265] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8f9422a1ca]
[runnervmgx7h7:11265] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8f9422a28b]
[runnervmgx7h7:11265] [11] plumed(+0x15365)[0x55fdb299e365]
[runnervmgx7h7:11265] *** End of error message ***
</pre>
{% endraw %}
