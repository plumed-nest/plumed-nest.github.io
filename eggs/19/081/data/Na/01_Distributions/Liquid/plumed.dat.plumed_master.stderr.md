**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/01_Distributions/Liquid/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../RefCV.P2ziQA.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1497) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../../RefCV.2.11.0-dev.so ../../../RefCV.cpp

[runnervmgx7h7:11555] *** Process received signal ***
[runnervmgx7h7:11555] Signal: Aborted (6)
[runnervmgx7h7:11555] Signal code:  (-6)
[runnervmgx7h7:11555] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f01dc445330]
[runnervmgx7h7:11555] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f01dc49ec0c]
[runnervmgx7h7:11555] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f01dc44527e]
[runnervmgx7h7:11555] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f01dc4288ff]
[runnervmgx7h7:11555] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f01dc8a5ff5]
[runnervmgx7h7:11555] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f01dc8bb0da]
[runnervmgx7h7:11555] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f01dc8a5a55]
[runnervmgx7h7:11555] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f01dc8a5a6f]
[runnervmgx7h7:11555] [ 8] plumed_master(+0x146dd)[0x55dadfe106dd]
[runnervmgx7h7:11555] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f01dc42a1ca]
[runnervmgx7h7:11555] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f01dc42a28b]
[runnervmgx7h7:11555] [11] plumed_master(+0x15365)[0x55dadfe11365]
[runnervmgx7h7:11555] *** End of error message ***
</pre>
{% endraw %}
