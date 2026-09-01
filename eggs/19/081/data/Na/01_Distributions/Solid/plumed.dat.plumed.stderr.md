**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/01_Distributions/Solid/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../RefCV.LEd4uZ.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1497) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.1' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../../RefCV.2.10.1.so ../../../RefCV.cpp

[runnervmgx7h7:11609] *** Process received signal ***
[runnervmgx7h7:11609] Signal: Aborted (6)
[runnervmgx7h7:11609] Signal code:  (-6)
[runnervmgx7h7:11609] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1aea845330]
[runnervmgx7h7:11609] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1aea89ec0c]
[runnervmgx7h7:11609] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1aea84527e]
[runnervmgx7h7:11609] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1aea8288ff]
[runnervmgx7h7:11609] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1aeaca5ff5]
[runnervmgx7h7:11609] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1aeacbb0da]
[runnervmgx7h7:11609] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1aeaca5a55]
[runnervmgx7h7:11609] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1aeaca5a6f]
[runnervmgx7h7:11609] [ 8] plumed(+0x146dd)[0x55587bfe96dd]
[runnervmgx7h7:11609] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1aea82a1ca]
[runnervmgx7h7:11609] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1aea82a28b]
[runnervmgx7h7:11609] [11] plumed(+0x15365)[0x55587bfea365]
[runnervmgx7h7:11609] *** End of error message ***
</pre>
{% endraw %}
