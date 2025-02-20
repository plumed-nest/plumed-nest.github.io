**Project ID:** [plumID:20.003]({{ '/' | absolute_url }}eggs/20/003/)  
Stderr for source:  plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
TD_TS-target-plumed2.6.kx1phl.cpp:23:10: fatal error: TargetDistribution.h: No such file or directory
23 | #include "TargetDistribution.h"
|          ^~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1499) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed_master' PLUMED_VERSION='2.11.0-dev' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed_master' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed_master' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed_master"/scripts/mklib.sh -n -o ./TD_TS-target-plumed2.6.2.11.0-dev.so TD_TS-target-plumed2.6.cpp

[fv-az1444-322:11660] *** Process received signal ***
[fv-az1444-322:11660] Signal: Aborted (6)
[fv-az1444-322:11660] Signal code:  (-6)
[fv-az1444-322:11660] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f610de45330]
[fv-az1444-322:11660] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f610de9eb2c]
[fv-az1444-322:11660] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f610de4527e]
[fv-az1444-322:11660] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f610de288ff]
[fv-az1444-322:11660] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f610e2a5ff5]
[fv-az1444-322:11660] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f610e2bb0da]
[fv-az1444-322:11660] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f610e2a5a55]
[fv-az1444-322:11660] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f610e2a5a6f]
[fv-az1444-322:11660] [ 8] plumed_master(+0x146dd)[0x55781aab16dd]
[fv-az1444-322:11660] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f610de2a1ca]
[fv-az1444-322:11660] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f610de2a28b]
[fv-az1444-322:11660] [11] plumed_master(+0x15365)[0x55781aab2365]
[fv-az1444-322:11660] *** End of error message ***
</pre>
{% endraw %}
