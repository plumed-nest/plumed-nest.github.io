**Project ID:** [plumID:20.003]({{ '/' | absolute_url }}eggs/20/003/)  
Stderr for source:  plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
TD_TS-target-plumed2.6.Ayq2ij.cpp:23:10: fatal error: TargetDistribution.h: No such file or directory
23 | #include "TargetDistribution.h"
|          ^~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./TD_TS-target-plumed2.6.2.10b.so TD_TS-target-plumed2.6.cpp

[fv-az1696-883:67004] *** Process received signal ***
[fv-az1696-883:67004] Signal: Aborted (6)
[fv-az1696-883:67004] Signal code:  (-6)
[fv-az1696-883:67004] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc108a45330]
[fv-az1696-883:67004] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc108a9eb2c]
[fv-az1696-883:67004] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc108a4527e]
[fv-az1696-883:67004] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc108a288ff]
[fv-az1696-883:67004] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc108ea5ff5]
[fv-az1696-883:67004] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc108ebb0da]
[fv-az1696-883:67004] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc108ea5a55]
[fv-az1696-883:67004] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc108ea5a6f]
[fv-az1696-883:67004] [ 8] plumed(+0x146dd)[0x55ccf54e16dd]
[fv-az1696-883:67004] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc108a2a1ca]
[fv-az1696-883:67004] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc108a2a28b]
[fv-az1696-883:67004] [11] plumed(+0x15365)[0x55ccf54e2365]
[fv-az1696-883:67004] *** End of error message ***
</pre>
{% endraw %}
