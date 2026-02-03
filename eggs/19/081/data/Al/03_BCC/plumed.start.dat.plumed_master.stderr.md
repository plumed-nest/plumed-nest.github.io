**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/03_BCC/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../RefCV.kIWLru.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../RefCV.2.11.0-dev.so ../../RefCV.cpp

[runnervmkj6or:10525] *** Process received signal ***
[runnervmkj6or:10525] Signal: Aborted (6)
[runnervmkj6or:10525] Signal code:  (-6)
[runnervmkj6or:10525] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa36c045330]
[runnervmkj6or:10525] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa36c09eb2c]
[runnervmkj6or:10525] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa36c04527e]
[runnervmkj6or:10525] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa36c0288ff]
[runnervmkj6or:10525] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa36c4a5ff5]
[runnervmkj6or:10525] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa36c4bb0da]
[runnervmkj6or:10525] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa36c4a5a55]
[runnervmkj6or:10525] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa36c4a5a6f]
[runnervmkj6or:10525] [ 8] plumed_master(+0x146dd)[0x55a52d10b6dd]
[runnervmkj6or:10525] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa36c02a1ca]
[runnervmkj6or:10525] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa36c02a28b]
[runnervmkj6or:10525] [11] plumed_master(+0x15365)[0x55a52d10c365]
[runnervmkj6or:10525] *** End of error message ***
</pre>
{% endraw %}
