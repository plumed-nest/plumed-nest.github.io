**Project ID:** [plumID:20.003]({{ '/' | absolute_url }}eggs/20/003/)  
Stderr for source:  plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
TD_TS-target-plumed2.6.exMlvl.cpp:23:10: fatal error: TargetDistribution.h: No such file or directory
23 | #include "TargetDistribution.h"
|          ^~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1502) void PLMD::PlumedMain::load(const std::string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.10b' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh -n -o ./TD_TS-target-plumed2.6.2.10b.so TD_TS-target-plumed2.6.cpp

[fv-az1444-322:11627] *** Process received signal ***
[fv-az1444-322:11627] Signal: Aborted (6)
[fv-az1444-322:11627] Signal code:  (-6)
[fv-az1444-322:11627] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0a06e45330]
[fv-az1444-322:11627] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0a06e9eb2c]
[fv-az1444-322:11627] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0a06e4527e]
[fv-az1444-322:11627] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0a06e288ff]
[fv-az1444-322:11627] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0a072a5ff5]
[fv-az1444-322:11627] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0a072bb0da]
[fv-az1444-322:11627] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0a072a5a55]
[fv-az1444-322:11627] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0a072a5a6f]
[fv-az1444-322:11627] [ 8] plumed(+0x146dd)[0x55cd767986dd]
[fv-az1444-322:11627] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0a06e2a1ca]
[fv-az1444-322:11627] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0a06e2a28b]
[fv-az1444-322:11627] [11] plumed(+0x15365)[0x55cd76799365]
[fv-az1444-322:11627] *** End of error message ***
</pre>
{% endraw %}
