**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/01_Distributions/Liquid/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../../RefCV.WJ3jXg.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10.0' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./../../../RefCV.2.10.0.so ../../../RefCV.cpp

[runnervmeorf1:10822] *** Process received signal ***
[runnervmeorf1:10822] Signal: Aborted (6)
[runnervmeorf1:10822] Signal code:  (-6)
[runnervmeorf1:10822] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa7a3845330]
[runnervmeorf1:10822] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa7a389eb2c]
[runnervmeorf1:10822] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa7a384527e]
[runnervmeorf1:10822] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa7a38288ff]
[runnervmeorf1:10822] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa7a3ca5ff5]
[runnervmeorf1:10822] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa7a3cbb0da]
[runnervmeorf1:10822] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa7a3ca5a55]
[runnervmeorf1:10822] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa7a3ca5a6f]
[runnervmeorf1:10822] [ 8] plumed(+0x146dd)[0x5619202826dd]
[runnervmeorf1:10822] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa7a382a1ca]
[runnervmeorf1:10822] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa7a382a28b]
[runnervmeorf1:10822] [11] plumed(+0x15365)[0x561920283365]
[runnervmeorf1:10822] *** End of error message ***
</pre>
{% endraw %}
