**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Al/02_FCC/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../RefCV.tXZ0MI.cpp:22:10: fatal error: multicolvar/MultiColvarBase.h: No such file or directory
22 | #include "multicolvar/MultiColvarBase.h"
|          ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1499) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./../../RefCV.2.11.0-dev.so ../../RefCV.cpp

[fv-az1046-619:10335] *** Process received signal ***
[fv-az1046-619:10335] Signal: Aborted (6)
[fv-az1046-619:10335] Signal code:  (-6)
[fv-az1046-619:10335] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb10e445330]
[fv-az1046-619:10335] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb10e49eb2c]
[fv-az1046-619:10335] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb10e44527e]
[fv-az1046-619:10335] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb10e4288ff]
[fv-az1046-619:10335] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb10e8a5ff5]
[fv-az1046-619:10335] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb10e8bb0da]
[fv-az1046-619:10335] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb10e8a5a55]
[fv-az1046-619:10335] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb10e8a5a6f]
[fv-az1046-619:10335] [ 8] plumed_master(+0x146dd)[0x55c5f82266dd]
[fv-az1046-619:10335] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb10e42a1ca]
[fv-az1046-619:10335] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb10e42a28b]
[fv-az1046-619:10335] [11] plumed_master(+0x15365)[0x55c5f8227365]
[fv-az1046-619:10335] *** End of error message ***
</pre>
{% endraw %}
