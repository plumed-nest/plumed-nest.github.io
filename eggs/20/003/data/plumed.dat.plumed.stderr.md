**Project ID:** [plumID:20.003]({{ '/' | absolute_url }}eggs/20/003/)  
Stderr for source:  plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
TD_TS-target-plumed2.6.cpp:23:10: fatal error: TargetDistribution.h: No such file or directory
23 | #include "TargetDistribution.h"
|          ^~~~~~~~~~~~~~~~~~~~~~
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:1071) void PLMD::PlumedMain::load(const string&)
An error happened while executing command env PLUMED_ROOT='/home/runner/opt/lib/plumed' PLUMED_VERSION='2.9.1' PLUMED_HTMLDIR='/home/runner/opt/share/doc/plumed' PLUMED_INCLUDEDIR='/home/runner/opt/include' PLUMED_PROGRAM_NAME='plumed' PLUMED_IS_INSTALLED='yes' "/home/runner/opt/lib/plumed"/scripts/mklib.sh TD_TS-target-plumed2.6.cpp

[fv-az768-943:09053] *** Process received signal ***
[fv-az768-943:09053] Signal: Aborted (6)
[fv-az768-943:09053] Signal code:  (-6)
[fv-az768-943:09053] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f5be4842520]
[fv-az768-943:09053] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f5be48969fc]
[fv-az768-943:09053] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f5be4842476]
[fv-az768-943:09053] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f5be48287f3]
[fv-az768-943:09053] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f5be4ca2b9e]
[fv-az768-943:09053] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f5be4cae20c]
[fv-az768-943:09053] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f5be4cae277]
[fv-az768-943:09053] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f5be4cae52b]
[fv-az768-943:09053] [ 8] plumed(+0x12f48)[0x55da76100f48]
[fv-az768-943:09053] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f5be4829d90]
[fv-az768-943:09053] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f5be4829e40]
[fv-az768-943:09053] [11] plumed(+0x131e5)[0x55da761011e5]
[fv-az768-943:09053] *** End of error message ***
</pre>
{% endraw %}
