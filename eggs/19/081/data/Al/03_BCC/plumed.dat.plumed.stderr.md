**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/03_BCC/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../RefCV.NEKWur.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../RefCV.2.10.0.so ../../RefCV.cpp

[runnervmeorf1:10650] *** Process received signal ***
[runnervmeorf1:10650] Signal: Aborted (6)
[runnervmeorf1:10650] Signal code:  (-6)
[runnervmeorf1:10650] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f34e1e45330]
[runnervmeorf1:10650] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f34e1e9eb2c]
[runnervmeorf1:10650] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f34e1e4527e]
[runnervmeorf1:10650] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f34e1e288ff]
[runnervmeorf1:10650] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f34e22a5ff5]
[runnervmeorf1:10650] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f34e22bb0da]
[runnervmeorf1:10650] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f34e22a5a55]
[runnervmeorf1:10650] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f34e22a5a6f]
[runnervmeorf1:10650] [ 8] plumed(+0x146dd)[0x5591f86616dd]
[runnervmeorf1:10650] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f34e1e2a1ca]
[runnervmeorf1:10650] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f34e1e2a28b]
[runnervmeorf1:10650] [11] plumed(+0x15365)[0x5591f8662365]
[runnervmeorf1:10650] *** End of error message ***
</pre>
{% endraw %}
